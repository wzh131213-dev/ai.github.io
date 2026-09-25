# 🔑 Google Gemini 免费 API Key 申请与使用指南

Google 为开发者提供了非常丰厚的 **免费 API 调用额度**（每分钟支持 15 次请求，每日上千次免费调用，个人开发与日常使用完全足够）。

### 📌 申请步骤

1. **访问 Google AI Studio**
   打开官网：https://aistudio.google.com/

2. **登录 Google 账号**
   使用您的 Gmail 或 Google 账号进行登录。

3. **创建 API Key**

   * 进入控制台后，点击左侧菜单或顶部的 **"Get API key"** 按钮。

   * 点击 **"Create API key"**（在新建项目中创建或选择现有 Google Cloud 项目）。

4. **复制 API 密钥**

   * 系统生成一串以 `AIzaSy...` 开头的密钥字符串。

   * 点击 **Copy** 复制该密钥（请妥善保管，不要随意公开）。

5. **填入工具中使用**

   * 回到我们的 **GamePrompt AI Studio** 页面。

   * 点击右上角 **"设置 / API 配置"** 按钮。

   * 选择 **🌐 API 在线生成** 模式，将刚才复制的 Key 粘贴到输入框中并点击 **保存并应用** 即可！

### 💡 注意事项与提示

* **网络环境要求**：由于 Google 服务限制，访问 AI Studio 以及调用 API 时，需要确保处于支持 Google AI 服务的网络节点下（推荐使用美国、日本、新加坡等节点）。

* **完全免费**：只要不主动绑定信用卡开启 Paid Plan（付费计划），Gemini 默认的 Free Tier（免费层）不会产生任何费用。

* **隐私与安全**：本工具中的 API Key 仅保存在您本地浏览器的 `localStorage` 中，所有 API 请求均直接与 Google 官方服务器通信，不会经过任何第三方中间服务器。
