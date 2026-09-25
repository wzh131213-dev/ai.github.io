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

#实例

# 《极界回响: # 《极界回响: #...》

> 在充满变数的无尽世界中，凭借独特的系统机制改写命运！

## 游戏概述
玩家将置身于以“# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 场景美术 Prompt
```
Masterpiece concept art of game environment for # 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。, stylized Pixel Art (16-bit / 32-bit), Isometric 2.5D Top-Down View, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
```

## 角色美术 Prompt
```
Character sheet concept art, protagonist inspired by # 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
```

## 代码 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。"

// Key Requirements:
1. Setup primary viewport using Isometric 2.5D Top-Down View camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with Isometric 2.5D Top-Down View, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。

// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."

# 《极界回响: # 喵语星空食堂：治...》
*在充满变数的无尽世界中，凭借独特的系统机制改写命运！*

## 游戏类型与平台
基于 Pixel 的 2D 玩法

## 核心设计概述
玩家将置身于以“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”为内核打造的虚构世界。游戏运用了独特的 Pixel Art (16-bit / 32-bit) 视角与视觉艺术风格，依托 Three.js / WebGL HTML5 引擎提供的强大实时物理与渲染特性，融合了高频策略对抗与深度的探索成长循环。

## 核心玩法机制
- **核心控制与能量循环**: 玩家可通过基础移动与特色技能（如时间延缓/重力转换/元素相克）影响环境，每次成功触发机制将积累能量值，用于释放高阶爆发。
- **程序化随机探索关卡**: 基于 2D Side-Scrolling Platformer 的地形模块化组合，关卡提供高度自由度的分叉路线选择，兼具高风险高回报的隐秘区域与精英挑战。
- **模块化构建与强化树**: 在战斗与探索间隙，玩家可自由组装核心构件，定制专属于自己的战斗流派与技能属性。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Masterpiece concept art of game environment for # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **角色/精灵 Prompt**: Character sheet concept art, protagonist inspired by # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。, full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **界面 UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI 编程 Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: # 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。."
```

## 世界观与剧情
在这个被遗忘的旧纪元废墟中，“# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
# 喵语星空食堂：治愈之旅 (Meow Star Canteen: Healing Journey)
*在繁星坠落的森林，经营一家为疲惫灵魂而开的猫咪深夜食堂。*

## 游戏类型与平台
2D Side-Scrolling Management Platformer

## 核心设计概述
玩家扮演一只拥有炼金厨艺的小猫，在梦幻的2D侧视角森林中穿梭冒险。通过跳跃平台收集散落在各处的星光食材，在经营模式中将食材合成极具疗愈力量的猫咪料理。游戏结合了动作探索的灵活性与模拟经营的成就感，采用16/32位复古像素画风，为玩家提供一个宁静、温馨的避风港。

## 核心玩法机制
- **横版平台食材搜寻 (Side-Scrolling Exploration)**: 玩家操控小猫在多层森林关卡中跳跃、攀爬，寻找隐藏的黄金猫草、月光浆果等稀有食材。关卡设计强调节奏感而非高难度，包含动态天气对食材生长的影响。
- **料理炼金合成 (Alchemical Cooking Synthesis)**: 在食堂后厨，玩家通过一个基于网格的合成系统将搜寻到的原料组合。不同的配方会产生具有特殊buff的料理，例如‘闪耀布丁’能增加移动速度，‘静谧浓汤’能吸引稀有顾客。
- **动态食堂经营 (Dynamic Canteen Management)**: 随着料理等级提升，食堂会吸引更多流浪猫NPC。玩家需要通过提供正确的料理来解锁NPC的个人故事，并赚取‘猫币’用于装饰食堂或升级厨具。

## 美术提示词 (Art Prompts)
- **场景环境 Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **角色/精灵 Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **界面 UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI 编程 Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## 世界观与剧情
在遥远的‘浮光之森’，传说每当流星划过，就会带走一个灵魂的疲惫。主角‘糯米’是一只掌握了古老料理术的猫咪，它在森林深处搭建了一个深夜食堂。这里的客人不仅仅是动物，还有那些从忙碌世界中短暂逃离的幻影。玩家通过经营食堂，不仅是在制作料理，更是在编织一个关于陪伴与归属感的故事。每一个深夜，灯火摇曳，热汤气腾，便是最治愈的时刻。”成了唯一破局的匙钥。玩家作为破晓守护者，不仅要在险象环生的荒域中求生，更要通过解开深埋在古老遗迹中的谜团，重构文明的法则。故事融合了深沉的宿命感与高燃的逆袭之旅。."
```
