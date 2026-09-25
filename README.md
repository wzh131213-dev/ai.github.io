# 🔑 免费申请与使用 Google Gemini API Key 指南

Google 为开发者提供了非常慷慨的**免费 API 配额**（每分钟 15 次请求，每天数千次免费调用——足以满足个人开发和日常使用需求）。

### 📌 申请步骤

1. **访问 Google AI Studio**
打开官网：https://aistudio.google.com/

2. **使用 Google 账号登录**
使用您的 Gmail 或 Google 账号登录。

3. **创建 API Key**
* 进入控制台后，点击左侧菜单或页面顶部的 **"Get API key"** 按钮。 
* 点击 **"Create API key"**（可以在新项目中创建，也可以选择现有的 Google Cloud 项目）。

4. **复制 API Key**
* 系统会生成一个以 `AIzaSy...` 开头的密钥字符串。 
* 点击 **Copy** 复制密钥（请妥善保管，切勿公开分享）。

5. **在工具中填入**
* 返回我们的 **GamePrompt AI Studio** 页面。 
* 点击右上角的 **"Settings / API Configuration"** 按钮。 
* 选择 **🌐 Online API Generation** 模式，将刚才复制的密钥粘贴到输入框中，然后点击 **Save & Apply** —— 这样就完成了！

### 💡 注意事项与提示

* **网络要求**：受 Google 服务限制，访问 AI Studio 和调用 API 时，您需要处于支持 Google AI 服务的网络节点环境下（建议使用美国、日本、新加坡等地区的节点）。

* **完全免费**：只要您不主动绑定信用卡以开启付费方案（Paid Plan），Gemini 默认的免费层级（Free Tier）就不会产生任何费用。

* **隐私与安全**：在本工具中，API Key 仅存储在您浏览器的 `localStorage` 中，且所有 API 请求均直接与 Google 官方服务器通信——不会经过任何第三方中转服务器。 ---

# 🐱 喵星食堂：治愈之旅
*在星辰坠落的森林深处，经营一家专为疲惫灵魂开设的深夜猫咪食堂。*

> 注：原文档多次重复了相同的游戏设计内容。以下仅翻译一次独特内容；重复部分均为完全相同的副本。

## 游戏类型与平台
2D 横版卷轴经营类平台游戏

## 核心设计概述
玩家将扮演一只精通炼金烹饪技艺的猫咪，在梦幻般的 2D 横版森林中展开冒险。通过在平台间跳跃穿梭，玩家收集散落在各处的星光食材，并在经营模式下将其合成为具有深度治愈功效的猫咪美食。游戏结合了动作探索的灵活性与模拟经营的成就感，采用 16/32 位复古像素画风，为玩家营造一个宁静、温馨的避风港。

## 核心玩法机制
- **横版卷轴探索**：玩家操控小猫在多层森林关卡中跳跃攀爬，搜寻诸如“黄金猫草”和“月光浆果”等稀有食材。关卡设计侧重于节奏感而非高难度挑战，并包含影响食材生长的动态天气系统。
- **炼金烹饪合成**：在食堂厨房内，玩家利用网格合成系统将收集到的原材料进行组合。不同的食谱可制作出带有特殊增益效果的菜肴——例如，“闪耀布丁”能提升移动速度，而“宁静汤”则能吸引稀有顾客光临。
- **动态食堂经营**：随着菜肴等级的提升，食堂将吸引更多流浪猫 NPC。玩家需提供正确的菜肴以解锁每位 NPC 的专属故事，并赚取“猫咪币”来装饰食堂或升级厨具。

## 美术提示
- **环境提示**：像素艺术游戏背景，32 位美学风格，温馨的夜间森林，巨大的发光蘑菇，漂浮的星辰，温暖的木屋厨房内景，横版卷轴布局，柔和的环境光效，柔和色调，高分辨率像素细节，吉卜力风格氛围。 - **角色/精灵图提示词**：可爱的姜黄色虎斑猫角色精灵图（sprite sheet），16位像素画风格；包含行走、跳跃、坐下和烹饪动作的多帧动画；猫咪戴着迷你厨师帽和围裙，表情生动，轮廓清晰，配色鲜艳。
- **UI 提示词**：游戏 UI 设计，16位像素画风格；具有木质纹理的物品栏槽位，猫爪形状的按钮图标，鱼形生命值条，复古字体，暖黄与棕色调，半透明菜单遮罩层。

## AI 编程提示词
```
编写一个用于 2D 横版平台跳跃游戏的完整 Three.js 样板代码。要求：1. 使用 OrthographicCamera（正交相机）实现 2D 视角。 2. 实现一个 'Player' 类，使用 THREE.Sprite 或带有平面几何体（plane geometry）的 THREE.Mesh 来呈现像素画纹理。 3. 包含基于重力的物理引擎，支持跳跃及针对平台物体的碰撞检测。 4. 创建一个 'GameStates' 对象，用于处理“探索”（横版卷轴模式）与“烹饪”（基于 UI 的合成模式）两种模式之间的切换。 5. 使用 requestAnimationFrame 设置动画循环，并结合 delta time（时间增量）以实现平滑移动。 6. 处理 WASD/A
```

# 🔑 Guide to Applying for and Using a Free Google Gemini API Key

Google offers developers a very generous **free API quota** (15 requests per minute, thousands of free calls per day — more than enough for personal development and everyday use).

### 📌 Application Steps

1. **Visit Google AI Studio**
   Open the official website: https://aistudio.google.com/

2. **Sign in with your Google account**
   Log in using your Gmail or Google account.

3. **Create an API Key**
   * After entering the console, click the **"Get API key"** button in the left-hand menu or at the top.
   * Click **"Create API key"** (create it in a new project or select an existing Google Cloud project).

4. **Copy the API key**
   * The system generates a key string starting with `AIzaSy...`.
   * Click **Copy** to copy the key (please keep it safe and do not share it publicly).

5. **Enter it in the tool**
   * Return to our **GamePrompt AI Studio** page.
   * Click the **"Settings / API Configuration"** button in the top-right corner.
   * Select **🌐 Online API Generation** mode, paste the key you just copied into the input box, and click **Save & Apply** — that's it!

### 💡 Notes & Tips

* **Network requirements**: Due to Google service restrictions, you need to be on a network node that supports Google AI services when accessing AI Studio and calling the API (nodes in the US, Japan, Singapore, etc. are recommended).

* **Completely free**: As long as you don't voluntarily link a credit card to enable a Paid Plan, Gemini's default Free Tier will not incur any charges.

* **Privacy & security**: In this tool, the API key is stored only in your browser's `localStorage`, and all API requests communicate directly with Google's official servers — they do not pass through any third-party intermediate server.

---

# 🐱 Meow Star Canteen: Healing Journey
*In a forest where stars fall, run a late-night cat canteen for weary souls.*

> Note: The original document repeats the same game design content many times. The unique content is translated below once; the repeated blocks were identical copies.

## Game Type & Platform
2D Side-Scrolling Management Platformer

## Core Design Overview
The player takes on the role of a cat with alchemical cooking skills, adventuring through a dreamlike 2D side-view forest. By jumping across platforms, the player collects starlight ingredients scattered everywhere, then synthesizes them in the management mode into deeply healing cat cuisine. The game combines the flexibility of action exploration with the sense of accomplishment of simulation management, using a 16/32-bit retro pixel art style to provide players with a peaceful, cozy haven.

## Core Gameplay Mechanics
- **Side-Scrolling Exploration**: The player controls the kitten to jump and climb through multi-layered forest levels, searching for hidden rare ingredients such as Golden Catgrass and Moonlight Berries. Level design emphasizes rhythm rather than difficulty, and includes dynamic weather that affects ingredient growth.
- **Alchemical Cooking Synthesis**: In the canteen kitchen, the player combines gathered raw materials through a grid-based synthesis system. Different recipes produce dishes with special buffs — for example, "Shining Pudding" increases movement speed, while "Tranquil Soup" attracts rare customers.
- **Dynamic Canteen Management**: As dish levels increase, the canteen attracts more stray cat NPCs. The player must serve the right dishes to unlock each NPC's personal story, and earn "Cat Coins" to decorate the canteen or upgrade kitchenware.

## Art Prompts
- **Environment Prompt**: Pixel art game background, 32-bit aesthetic, cozy forest at night, giant glowing mushrooms, floating stars, warm interior of a wooden cabin kitchen, side-scrolling layout, soft ambient lighting, pastel colors, high resolution pixel details, Ghibli-inspired atmosphere.
- **Character/Sprite Prompt**: Character sprite sheet for a cute ginger tabby cat, 16-bit pixel art style, multiple frames of walking, jumping, sitting, and cooking animation, wearing a tiny chef hat and apron, expressive face, clear silhouettes, vibrant color palette.
- **UI Prompt**: Game UI design, 16-bit pixel art, inventory slots with wooden texture, cat paw icons for buttons, health bar shaped like a fish, vintage font, warm yellow and brown tones, translucent menu overlays.

## AI Programming Prompt
```
Write a complete Three.js boilerplate for a 2D side-scrolling platformer. Requirements: 1. Use OrthographicCamera for a 2D perspective. 2. Implement a 'Player' class using THREE.Sprite or THREE.Mesh with a plane geometry for pixel art textures. 3. Include a gravity-based physics engine with jumping and collision detection for platform objects. 4. Create a 'GameStates' object to handle switching between 'Exploration' (side-scroller) and 'Cooking' (UI-based synthesis) modes. 5. Set up an animation loop using requestAnimationFrame with delta time for smooth movement. 6. Handle WASD/Arrow keys for movement and 'E' for interaction. 7. Use THREE.TextureLoader to enable pixel-perfect rendering (minFilter/magFilter set to THREE.NearestFilter).
```

## Worldview & Story
In the distant "Floating Light Forest," legend says that whenever a shooting star streaks by, it carries away the weariness of a soul. The protagonist "Nuomi" (Sticky Rice) is a cat who has mastered the ancient culinary arts, and has built a late-night canteen deep in the forest. The guests here are not only animals, but also phantoms briefly escaping from the busy world. By running the canteen, the player is not just making dishes — they are weaving a story about companionship and belonging. Every late night, with flickering lamplight and steaming hot soup, is the most healing moment.

---

# 《极界回响: # 喵语星空食堂：治...》(Echoes of the Extreme Realm)
*In a world of endless variables, rewrite destiny with unique system mechanics!*

## Game Type & Platform
Pixel-based 2D gameplay

## Core Design Overview
The player is placed in a fictional world built around the "Meow Star Canteen: Healing Journey" concept described above. The game uses the distinctive visual art style of Pixel Art (16-bit / 32-bit), and relies on the powerful real-time physics and rendering features of the Three.js / WebGL HTML5 engine, blending high-frequency strategic confrontation with a deep exploration-and-growth loop.

## Core Gameplay Mechanics
- **Core Control & Energy Loop**: The player can affect the environment through basic movement and signature skills (such as time dilation / gravity switching / elemental countering). Each successful trigger of a mechanic accumulates energy value, which is used to unleash high-tier bursts.
- **Procedural Random Exploration Levels**: Based on modular terrain combinations of the 2D Side-Scrolling Platformer, levels offer highly free branching route choices, combining high-risk, high-reward hidden areas with elite challenges.
- **Modular Builds & Enhancement Trees**: Between combat and exploration, the player can freely assemble core components to customize their own combat style and skill attributes.

## Art Prompts
- **Environment Prompt**: Masterpiece concept art of game environment for "Meow Star Canteen: Healing Journey," stylized Pixel Art (16-bit / 32-bit), 2D Side-Scrolling Platformer, ambient lighting, Unreal Engine 5 render, cinematic lighting, volumetric fog, Octane render, highly detailed, 8k resolution --ar 16:9 --v 6.0
- **Character/Sprite Prompt**: Character sheet concept art, protagonist inspired by "Meow Star Canteen: Healing Journey," full body sprite design, Pixel Art (16-bit / 32-bit), multiple poses, expressive features, game-ready character design, clean background, high contrast --ar 16:9
- **UI Prompt**: Futuristic stylized Game UI HUD layout design, matching Pixel Art (16-bit / 32-bit), including health bar, skill cooldown icons, mini-map, inventory window, sleek modern vector graphics, game interface template --ar 16:9

## AI Programming Prompt
```
// AI Code Prompt for Three.js / WebGL HTML5
// Objective: Create a working prototype based on "Meow Star Canteen: Healing Journey"

// Key Requirements:
1. Setup primary viewport using 2D Side-Scrolling Platformer camera parameters.
2. Implement player controller for standard movement + core mechanic.
3. Create an interactive game object loop with collision handling.
4. Build a basic HUD displaying core metrics (Health/Energy/Score).
5. Render with stylized shaders matching Pixel Art (16-bit / 32-bit).

// Starter Boilerplate Instructions for Claude/ChatGPT:
"Please write a single runnable source code file using Three.js / WebGL HTML5 that sets up a 3D/2D scene with 2D Side-Scrolling Platformer, handles keyboard controls (WASD + Space), and demonstrates the mechanic: Meow Star Canteen: Healing Journey."
```

## Worldview & Story
In the forgotten ruins of an old era, "Meow Star Canteen: Healing Journey" became the only key to breaking the deadlock. The player, as a Dawn Guardian, must not only survive the perilous wastelands, but also reconstruct the laws of civilization byunraveling the mysteries buried deep within ancient ruins. The story blends a deep sense of destiny with a blazing journey of comeback.
