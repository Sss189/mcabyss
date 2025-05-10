Mod Background
This mod is inspired by the anime Made in Abyss, focusing on replicating the "Abyss Curse" mechanics. Developed purely out of passion for the original work.

1. Usage Notice
Warnings:

Only tested on Minecraft 1.12.2 Forge (Singleplayer). No guarantees for other versions or multiplayer. 

Possible incompatibility with other mods:

Visual filters added for Layers 2-6 curses.

Layer 5 curse alters player movement logic.

Layer 6 curse modifies camera height, model rendering, GUI, and movement.

Star Compass item overrides vanilla item/drop rendering.

Star Compass transparent shell may glitch under shaders.

Star Compass changes movement and camera logic.

2. Mod Content
Three main components:

Abyss Layers & Curses

Items: Cartridge & Star Compass

Configuration

2.1 Abyss Layers & Curses
Layer Effects:
Six layers with escalating curses:

Layer 1: Nausea I (vanilla).

Layer 2: Hunger II, Slowness II, Mining Fatigue III, Weakness I + Ghosting filter.

Layer 3: Hunger III, Slowness III, Nausea I + Inverted color filter (stacked with nausea distortion).

Layer 4: Wither II + Red filter + Redstone/Magma particles (simulate bleeding).

Layer 5: Blindness + Inverted filter → White filter (lazy approach) + Forced random movement (prone to falling).

Layer 6:

Wither III + Strong red filter + Bleeding particles.

Replace player model with "Hollow", lock camera to Hollow's eyes, disable WASD/GUI, allow only forward jumps (no cooldown → funny glitches).

(Use /summon curseofabyss:hollow ~ ~ ~ to spawn the "Unfortunate Author Hollow".)

Curse Activation:

Triggers when ascending beyond a Y-axis threshold. Game tracks the lowest Y; exceeding the delta triggers curses.

Teleporting through multiple layers applies all eligible curses (Cartridge durability drains cumulatively).

HUD:

Displays current layer and curse trigger height on the top-left.

2.2 Items
Cartridge

Function: Blocks one curse, consuming durability. Appearance changes at 100%, 50%, 25% durability (lyrics from Forever Lost ED).

Recipe:

Row 1: Milk Bucket, Instant Health Potion (I/II), Redstone (any order)  
Row 2: Iron Ingot, Raw Mutton, Iron Ingot  
Row 3: Iron Ingot, Iron Ingot, Iron Ingot  
Grants Cooked Mutton when depleted.

Category: Creative-mode tool.

Star Compass

Function: Points to a set coordinate. Locks camera to target direction (XZ plane), disables backward movement. Shift+Right-click to reset. Random rotation if no target.

Drop Behavior: Hovers and rotates, pointer remains fixed.

Recipe:

Row 1: Glass, Glass, Glass  
Row 2: Gold Ingot, Nether Star, Gold Ingot  
Row 3: Glass, Glass, Glass  
Category: Creative-mode tool.

2.3 Configuration
Layer Settings: Custom Y-axis ranges (supports multiple ranges and Allow superposition , e.g., Layer 6: 10-20,50-60 Layer 5:0-100 ).Attention to the symbol

Curse Effects: Adjust duration and toggle particles.

Layer Toggle: Enable/disable specific curses.

HUD Settings: Customize colour and position.

Cartridge: Set durability cost per layer.

Star Compass: Toggle "no backward movement" and set initial coordinates.

3. Future Plan
???

模组背景
此模组的设定灵感来源于动漫《来自深渊》（Made in Abyss），主要还原了深渊诅咒的独特效果。开发初衷是出于对原作的热爱与兴趣。

1. 使用须知
注意事项：

此模组仅在 Minecraft 1.12.2 Forge 版本的单人模式 下测试通过，未适配其他版本或任何多人游戏。若因使用导致游戏崩溃，请自行承担风险。

可能的与其他模组的不兼容：

第二、三、四、五、六层诅咒添加了画面滤镜效果。

第五层诅咒修改了玩家的移动逻辑。

第六层诅咒调整了玩家视角高度、模型渲染、GUI显示及移动逻辑。

星之罗盘 物品修改了原版物品及其掉落物的渲染方式。

星之罗盘 的透明外壳在光影环境下可能产生未知效果。

星之罗盘 修改了玩家的移动与视角逻辑。

2. 模组内容
模组内容分为以下三部分：

深渊层与诅咒系统

物品：弹药包与星之罗盘

模组配置

2.1 深渊层与诅咒系统
诅咒层级与效果：
模组新增六个深渊层及其对应诅咒：

第一层：反胃 I（原版效果）。

第二层：饥饿 II、缓慢 II、挖掘疲劳 III、虚弱 I（原版效果） + 画面重影滤镜。

第三层：饥饿 III、缓慢 III、反胃 I（原版效果） + 画面反色滤镜（与反胃扭曲叠加）。

第四层：凋零 II（原版效果） + 红色滤镜 + 玩家周身红石与岩浆粒子（模拟流血）。

第五层：失明（原版效果） + 反色滤镜 → 白色滤镜（偷懒设计） + 强制随机移动（极易坠落）。

第六层：

凋零 III（原版效果） + 强红色滤镜 + 流血粒子效果。

替换玩家模型为“生骸”，锁定视角至生骸眼部，禁用 WASD 移动与 GUI，仅允许向视角方向跳跃（无冷却，可能产生有趣现象）。

(输入指令 /summon curseofabyss:hollow ~ ~ ~ 可召唤作者化身的“不幸生骸”)

诅咒触发逻辑：

玩家上升高度超过阈值时触发对应层诅咒。游戏记录玩家最低 Y 坐标，若当前 Y 与最低 Y 差值超过阈值，则触发诅咒。

若因传送等行为同时触发多层诅咒，所有符合条件的诅咒将一并生效（包括弹药包耐久消耗叠加）。

HUD 显示：

当前深渊层及诅咒触发高度信息显示于屏幕左上角。

2.2 物品系统
弹药包

功能：免疫一次诅咒并扣除耐久。耐久 100%、50%、25% 时外观与描述不同（灵感来自剧场版 ED《Forever Lost》歌词）。

配方：

第一行：牛奶桶、瞬间治疗药水（I 或 II）、红石（可乱序）  
第二行：铁锭、生羊肉、铁锭  
第三行：铁锭、铁锭、铁锭  
耐久耗尽后，玩家获得一块熟羊肉。

分类：创造模式工具。

星之罗盘

功能：指向设定坐标，强制锁定视角至目标方向（仅 XZ 平面），禁止后退。Shift+右键重置为当前位置。未设定坐标时随机旋转。

掉落物表现：悬浮自转，但指针始终指向目标。

配方：

第一行：玻璃、玻璃、玻璃  
第二行：金锭、下界之星、金锭  
第三行：玻璃、玻璃、玻璃  
分类：创造模式工具。

2.3 模组配置
层配置：自定义各层 Y 轴范围（支持多区间叠加，如第六层：10-20,50-60 同时第五层：0-100）。注意符号

诅咒效果配置：调整持续时间与粒子效果开关。

层诅咒开关：启用/禁用特定层诅咒。

HUD 设置：调整信息颜色与显示位置。

弹药包设置：自定义各层诅咒消耗的耐久值。

星之罗盘设置：启用/禁用“禁止后退”机制，设置初始坐标。

3. 画大饼
???
