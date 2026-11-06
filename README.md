# 浏览器本地 AI（多引擎 · 多模型）

一个**单文件**网页（`index.html`），把主流的浏览器端 AI 引擎合并在一起：选择引擎和模型，点一下就从网络下载模型到你的浏览器里运行。没有后端服务器，没有 API Key，对话内容不会离开你的设备。

可直接托管在 GitHub Pages 上。

## 功能

- **两个引擎，一个页面**
  - **WebLLM**：基于 WebGPU，专为聊天优化，直接使用库自带的完整预编译模型列表（Llama、Qwen、Gemma、Phi、SmolLM 等，数量随库版本变化）。
  - **Transformers.js**：基于 ONNX Runtime Web，优先 WebGPU，没有 GPU 时自动退到 WebAssembly（CPU）。
- **模型选择表**：点击表格中的一行即可选中模型。支持关键词实时过滤，每行显示显存需求（WebLLM）或下载量（Transformers.js）。
- **联网搜索 Hugging Face**（Transformers.js 引擎）：实时查询适用于浏览器的 ONNX 文本生成模型，按下载量排序。也可以手动填写任意模型 ID，格式为 `作者/模型名`。
- **下载进度与缓存**：带进度条；模型缓存在浏览器里，再次加载很快。
- **流式输出**：边生成边显示，可随时停止，支持多轮对话。
- **HF 镜像开关**：勾选后改用 `hf-mirror.com`，方便直连 huggingface.co 困难的网络环境。
- **自动容错**
  - 引擎库从多个 CDN、多个版本依次尝试加载，失败时列出每个地址的错误。
  - Transformers.js 自动依次尝试 `webgpu/q4f16 → webgpu/q4 → webgpu/fp16 → wasm/q8 → wasm/q4`。
  - 缓存 API 不可用时，WebLLM 自动改用 IndexedDB 缓存。
  - 启动时检测环境（协议、存储、WebGPU、是否支持 f16），并把不兼容的模型标注 ⚠ 排到后面。
- **诊断面板**：加载失败时显示原因、对策和一段可复制的诊断信息。

## 快速开始

### 方式一：部署到 GitHub Pages（推荐）

1. 新建一个仓库，把 `index.html` 放在根目录。
2. 进入 **Settings → Pages**，Source 选择分支（如 `main`）和根目录 `/`，保存。
3. 等待一两分钟，用页面给出的 `https://用户名.github.io/仓库名/` 地址访问。

### 方式二：本地运行

在 `index.html` 所在目录执行：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

> **不要**直接双击用 `file://` 打开，也不要放进内嵌预览或沙盒环境里（协议显示为 `about:` 的那种）：这些环境里浏览器缓存常被禁用，模型无法保存，会导致加载失败。

## 使用方法

1. 选择**引擎**。
2. 在表格里选一个**模型**（可用搜索框过滤；Transformers.js 下还可以点「联网搜索 HF」）。
3. 如果直连 Hugging Face 很慢或失败，勾选「使用 HF 镜像」。
4. 点「下载并加载」，等待进度条走完。
5. 在底部输入框提问，Enter 发送，Shift+Enter 换行。

建议第一次先选小模型（约 0.4B–1B 参数）验证流程，再尝试更大的。

## 运行要求

| 项目 | 要求 |
|---|---|
| 浏览器 | 较新的 Chrome / Edge / Safari；WebLLM 需要 WebGPU |
| 页面来源 | HTTPS 或 `localhost`（WebGPU 只在安全上下文可用） |
| 存储 | 需要 Cache API 或 IndexedDB 可用，且有足够磁盘空间 |
| 内存 | 小模型约需几百 MB 到约 1 GB；7B 以上通常需要数 GB 显存 |
| 网络 | 首次需要下载模型；下载完成后可离线使用已缓存的模型（引擎库本身仍从 CDN 加载） |

没有 WebGPU 时，WebLLM 不可用，请改用 Transformers.js（CPU 模式，速度较慢）。

## 常见问题

**显示「加载失败」？** 先展开状态栏下方的「诊断信息」，对照下面几种常见原因：

| 现象 / 原因 | 处理办法 |
|---|---|
| 协议是 `file:` 或 `about:` | 改用 GitHub Pages 或 `http://localhost` 打开 |
| 内存 / 显存不足（有时只显示一个数字） | 换更小的模型，关闭其它占内存的标签页 |
| 网络错误 / Failed to fetch | 勾选「HF 镜像」；WebLLM 还需访问 GitHub raw，必要时使用代理 |
| 404 / Could not locate file | 该仓库没有浏览器可用的 ONNX 文件，换一个模型 |
| WebGPU 适配器获取失败 | 使用最新版 Chrome / Edge，或改用 Transformers.js |
| 模型被标 ⚠ | 设备不支持 `shader-f16`，或在 iPad/iPhone 上显存需求偏高，建议选 `q4f32` 的小模型 |

**为什么 WebLLM 的模型不能随便搜？** WebLLM 只能运行 MLC 团队预编译好的模型，所以直接使用库内置的列表。想用更多模型，请用 Transformers.js 引擎。

**聊天内容会上传吗？** 不会。推理完全在本地浏览器中进行。网络请求只用于下载引擎库和模型文件。

**iPad / iPhone 能用吗？** 取决于系统是否开启 WebGPU 以及设备内存。iOS 上所有浏览器都基于 WebKit，内存限制较严，建议使用小模型。

## 技术说明

- 单文件，无构建步骤；脚本以 ES Module 方式按需动态加载引擎库。
- 引擎库的 CDN 候选（按顺序尝试）：jsDelivr、esm.sh、esm.run，版本依次尝试已知版本，最后回退到最新版。如需固定版本或自托管，修改 `index.html` 中的 `WEBLLM_URLS` 和 `TJS_URLS` 两个数组即可。
- 镜像地址在 `MIRROR` 常量中，默认是 `https://hf-mirror.com`。
- 切换引擎或点「卸载」会释放当前模型占用的显存。

## 已知限制

- 目前只做了文本对话；Transformers.js 支持的语音、视觉等任务尚未接入。
- 未接入 wllama（llama.cpp 的 WebAssembly 版）：它需要 `Cross-Origin-Opener-Policy` / `Cross-Origin-Embedder-Policy` 响应头，GitHub Pages 无法设置。
- 联网搜索到的模型不保证都能在浏览器里运行，个别可能因体积或格式不兼容而失败。
- 作者在开发时的沙箱无法联网，真实的模型下载与 GPU 推理没有在开发环境中实测；核心逻辑（模型筛选、容错链、错误解析、环境检测、界面交互）有自动化测试覆盖。

## 致谢

- [WebLLM](https://github.com/mlc-ai/web-llm)（MLC AI）
- [Transformers.js](https://github.com/huggingface/transformers.js)（Hugging Face）
- [hf-mirror](https://hf-mirror.com)（Hugging Face 社区镜像）

## Claude Sonnet 5.5 制作
