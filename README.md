# 阿努比斯的冒险 · Adventure of Anubis

使用 Unity 开发的 2D 横版动作冒险游戏。控制阿努比斯移动、跳跃与攻击，探索关卡并与敌人战斗。

## 在线游玩

**[在 itch.io 游玩《阿努比斯的冒险》](https://nonoking.itch.io/adventure-of-anubis)**

## 游戏内容

- 角色移动、跳跃和近战攻击。
- 敌人巡逻、追逐与生命值系统。
- 玩家生命值显示、死亡与重试。
- Tilemap 关卡、跟随镜头、音乐和音效。

## 本地运行

1. 安装 Unity **6000.6.3f1**。
2. 克隆项目：

   ```sh
   git clone https://github.com/NonoKing123456/AdventureOfAnubis.git
   cd AdventureOfAnubis
   ```

3. 在 Unity Hub 中添加项目目录，使用对应版本的编辑器打开。
4. 打开 `Assets/Scenes/MainMenu.unity`，点击 Play，从主菜单进入游戏。

## 项目结构

| 路径 | 内容 |
| --- | --- |
| `Assets/Scenes` | 主菜单和 Level1 关卡 |
| `Assets/Scripts/PlayerControl.cs` | 玩家移动、跳跃和攻击 |
| `Assets/Scripts/PlayerLife.cs` | 玩家生命值 |
| `Assets/Scripts/EnemyBrain.cs` | 敌人行为 |
| `Assets/Scripts/Game Managers` | 游戏流程和菜单 |
| `Assets/Scripts/UIs` | 生命值显示及选项面板 |
| `Assets/Settings/InputSystem_Actions.inputactions` | 操作绑定 |

## 构建

项目使用 URP 2D、Input System 和 Tilemap。在 Unity 的 Build Profiles 中选择目标平台，场景入口为 MainMenu，游戏关卡为 Level1。构建 Web 版本时需要安装对应的 Web Build Support 模块。
