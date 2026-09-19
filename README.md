# Pets 🐾

我的 Codex 小宠物收藏。

## 卡布

蓝金渐层小猫咪：圆圆的脸、蜜糖色眼睛、蓝灰色毛尖和奶金色底毛。

![卡布](pets/kabu/preview.gif)

包含 9 组常规动作和 16 个张望方向，使用透明背景的 v2 动画图集。

[查看卡布的文件与说明](pets/kabu/)

## 下载指南

### 下载完整宠物包（推荐）

1. 点击 **[下载 ZIP](https://github.com/Aaaaaant97/Pets/archive/refs/heads/main.zip)**，也可以在仓库首页选择 **Code → Download ZIP**。
2. 解压下载的文件，打开 `Pets-main/pets/kabu/` 文件夹。
3. 保留同一文件夹中的 `pet.json` 和 `spritesheet.webp`，两者共同组成卡布的宠物包。

| 文件 | 用途 | 是否必需 |
| --- | --- | --- |
| `pet.json` | 宠物名称、格式版本和图集路径等配置 | 必需 |
| `spritesheet.webp` | 小猫的完整动画图集 | 必需 |
| `preview.gif` | 待机动作预览 | 可选 |
| `README.md` | 宠物说明 | 可选 |

### 单独下载文件

也可以分别下载 **[pet.json](https://raw.githubusercontent.com/Aaaaaant97/Pets/main/pets/kabu/pet.json)** 和 **[spritesheet.webp](https://raw.githubusercontent.com/Aaaaaant97/Pets/main/pets/kabu/spritesheet.webp)**。如果浏览器直接显示内容，请使用“另存为”保存，并保留原文件名。

两个必需文件必须放在同一文件夹中；仅下载 `pet.json` 配置文件无法显示小猫。

## 安装到 Codex 桌面版

请使用支持 v2 自定义宠物的桌面版。以下以 macOS 为例：

1. 按照上面的下载指南解压文件。
2. 创建 `~/.codex/pets/lantang/` 文件夹，将下载的 `pet.json` 和 `spritesheet.webp` 复制进去，保持文件名不变：

   ```text
   ~/.codex/pets/lantang/
   ├── pet.json
   └── spritesheet.webp
   ```

   在访达中按 `Command + Shift + G`，可以前往 `~/.codex/`；不存在的子文件夹可自行新建。如果设置了自定义 `CODEX_HOME`，请改用该目录下的 `pets/lantang/`。

3. 打开 **设置 → Pets（宠物）**，点击 **Refresh（刷新）**，选择 **卡布**。
4. 在聊天输入框输入 `/pet`，或在命令菜单中选择 **Show pet（显示宠物）**，让小猫出现在桌面上。

文件夹名 `lantang` 与宠物的内部 ID 保持一致，界面显示的名字是「卡布」。这是本地宠物包，需要复制上述两个文件安装；仅将配置文件或 ZIP 发进聊天框不会自动安装。

宠物选择、刷新和显示操作可参考 [OpenAI 官方宠物说明](https://learn.chatgpt.com/docs/pets)。
