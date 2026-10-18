<p align="center">
  <img src="https://raw.githubusercontent.com/vaxicy/oceanic-scale-theme/main/assets/icon.png" alt="Oceanic Scale Theme logo" width="128">
</p>

<h1 align="center">Oceanic Scale Theme</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=lilinhuang.oceanic-scale-theme"><img src="https://img.shields.io/badge/VS%20Code-Theme-71869B?logo=visual-studio-code" alt="VS Code Theme"></a>
  <img src="https://img.shields.io/badge/version-1.0.0-48515A?logo=visual-studio-code" alt="version 1.0.0">
  <img src="https://img.shields.io/badge/Variants-Light%20%26%20Dark-CEEAE8?logo=visual-studio-code" alt="Light and Dark variants">
  <a href="https://github.com/vaxicy/oceanic-scale-theme/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Non--Commercial-lightgrey" alt="License: Non-Commercial"></a>
</p>

<p align="center">
  <a href="#preview">Preview</a> ·
  <a href="#palette">Palette</a> ·
  <a href="#syntax">Syntax</a> ·
  <a href="#coverage">Coverage</a> ·
  <a href="#features">Features</a> ·
  <a href="#installation">Install</a> ·
  <a href="#development">Dev</a>
</p>

A garden seen through a sheet of sea glass, tuned for VS Code: **washed-aqua paper**, **slate-teal ink**, **sage leaves** and **a hint of pressed-flower mauve**. The light variant reads like a sunlit writing desk, the dark one like the same desk at dusk — both cut from one palette, so switching changes the light level rather than the character of the workspace.

一层海玻璃滤过的花园，为 VS Code 调色：**水洗青的纸面**、**灰青的墨迹**、**鼠尾草绿**，再点一抹**干花藕紫**。浅色版像日光下的书桌，深色版像同一张桌子的黄昏；两套变体共享同一套色板，切换时改变的是明暗而非气质。

<a name="preview"></a>

## Preview / 预览

| Light 浅色 | Dark 深色 |
| --- | --- |
| ![Oceanic Scale Theme Light](https://raw.githubusercontent.com/vaxicy/oceanic-scale-theme/main/store-assets/screenshots/en/screenshot-light.png) | ![Oceanic Scale Theme Dark](https://raw.githubusercontent.com/vaxicy/oceanic-scale-theme/main/store-assets/screenshots/en/screenshot-dark.png) |

> Both previews are captured from a real VS Code window running the theme — no mockups.
>
> 上方预览图取自真实运行该主题的 VS Code 窗口截图，非模拟图。

<a name="palette"></a>

## Palette / 色板

| Role | Light | Dark |
| --- | --- | --- |
| Editor background | `#F7FCFB` washed aqua paper | `#243638` deep sea glass |
| Foreground | `#3E5B5D` slate teal | `#E2E5DE` pale sage |
| Muted text / placeholders | `#7E8872` | `#8F9B7F` |
| Side bar | `#EAF7F5` with `#54604E` text | `#213537` with `#C3CEBD` text |
| Panel / terminal | `#F1F9F8` | `#203235` |
| Title bar | `#E3F1F0` with `#4D5968` text | `#1D2B2D` with `#CAD2DA` text |
| Tab bar / inactive tab | `#ECEFE8` | `#222A2C` |
| Active tab indicator | `#B38D9F` | `#DCF0EE` |
| Activity bar | `#D8EEEC` with `#5D7288` icons | `#192729` with `#C0E4E1` icons |
| Status bar | `#D5ECE9` with `#536348` text | `#2E4B4D` with `#DCE7CF` text |
| Selection | `#DCE5D0` sage wash | `#4D6047` deep sage |
| Current line | `#FBF2DF` | `#343D3F` |
| Borders / indent guides | `#D8DFD4` / `#E5E7DD` | `#414D43` / `#404B42` |
| Button | `#CEEAE8` with `#46553E` text (hover `#BFCEAD`) | `#CEEAE8` with `#2D3C27` text (hover `#DFE8D2`) |
| Badge | `#71869B` with `#FFFFFF` text | `#C0E4E1` with `#243638` text |
| Cursor | `#71869B` | `#F1F9F8` |
| Links | `#758C58` | `#CED8C2` |
| Errors / warnings | `#B05E65` / `#9C7B42` | `#E3A4AA` / `#E6CCA0` |
| Git added / modified / deleted | `#5D9A92` / `#A48657` / `#B3797E` | `#BCD2A8` / `#E0C59D` / `#DDA6AE` |

Brand palette: sea glass `#C0E4E1`, deep sea glass `#243638`, slate `#71869B`, sage `#BCD2A8`, mauve `#C4A7B7`, cream `#FBF2DF`.

品牌色板：海玻璃青 `#C0E4E1`、深海玻璃 `#243638`、灰蓝 `#71869B`、鼠尾草绿 `#BCD2A8`、藕紫 `#C4A7B7`、米白 `#FBF2DF`。

<a name="syntax"></a>

## Syntax mapping / 语法映射

| Syntax | Light | Dark |
| --- | --- | --- |
| Comments | `#929B87` italic | `#91A087` italic |
| Keywords / storage | `#4C8A87` | `#DCF0EE` pale aqua |
| Strings | `#4F9188` sea green | `#CEEAE8` light aqua |
| Regexp | `#89A26A` | `#D1DBC5` |
| Escapes | `#9B7954` | `#E8C79B` |
| Numbers / constants | `#A07845` amber ink | `#F1F9F8` |
| Types / classes / interfaces | `#847296` mauve | `#D4C3DF` |
| Functions / methods | `#43818A` teal | `#C0E4E1` bright aqua |
| Properties | `#54817B` | `#B6D2C7` |
| Variables | `#3E5B5D` | `#E2E5DE` |
| Parameters | `#81785D` | `#D4CDB5` |
| Operators | `#78816F` | `#BBC6B2` |
| Punctuation | `#91998A` | `#9FAE9B` |
| Tags | `#4C8A87` | `#EAF6F5` |
| Attributes | `#A07845` | `#F1F9F8` |
| Headings / bold / italic | `#4D5C3A` | `#ECF0E6` |
| Invalid | `#B65353` | `#E99B91` |

Keywords, tags and strings all belong to the sea-glass family, so code reads as one wash of aqua on both backgrounds; amber numbers, mauve types and warm escapes stay distinct to keep your eye anchored while scanning.

关键字、标签与字符串同属海玻璃一脉，在两种底色上都呈现为一片水青；数字保持琥珀、类型保持藕紫、转义字符保持暖色，扫读时才有落点。

<a name="coverage"></a>

## Coverage / 覆盖范围

Every surface below is themed in both variants (144 UI colors each):

- **Editor** — background, foreground, selection and inactive selection, current-line highlight, word and selection highlights, find match and find highlight, bracket-match background and border, cursor, line numbers (plus the active line number), indent guides, whitespace, ruler, errors, warnings and info.
- **Workbench chrome** — activity bar, badge and active border, title bar (active and inactive), side bar with section headers and border, status bar (normal, no-folder and debugging states), editor group header and tabs (active, inactive, hover, modified border and active top border).
- **Panels and overlays** — panel, editor widgets, hover widget, suggest widget, dropdowns, inputs and placeholder text, notifications, quick input, and the focus border.
- **Lists** — active, inactive and hover selection backgrounds, plus the highlight and focus-highlight colors, and tree indent guides.
- **Terminal** — background, foreground and the full 16-color ANSI palette, matched to the theme.
- **Details** — workbench borders, scrollbar sliders, git decoration colors (added / modified / deleted) with their gutter markers, buttons, badges, diff editor backgrounds, and semantic token colors for variable, parameter, property, function, method, type, class and interface.

以下区域在两套变体中均已配色（每套 144 个 UI 颜色）：编辑器本体（选区与失焦选区、当前行、词/选区高亮、查找匹配与高亮、括号匹配、光标、行号、标尺、缩进线、空白符、错误/警告/提示）；活动栏与角标、标题栏、侧边栏（含分节标题）、状态栏（含无文件夹与调试态）、标签栏；面板与各类浮窗（悬停、建议、通知、快速输入）、下拉与输入框、列表选中/悬停/高亮、树缩进线；终端 ANSI 全色；全部边框与滚动条、Git 装饰色与 gutter 标记、按钮与角标、差异编辑器底色，以及变量/参数/属性/函数/方法/类型/类/接口的语义高亮。完整的颜色清单见 `COLOR-SPEC.md`。

<a name="features"></a>

## Features / 功能

- **Two coordinated variants** — `Oceanic Scale Theme Light` and `Oceanic Scale Theme Dark` ship in one extension.
- **One sea-glass palette** — washed-aqua and deep sea-glass surfaces with slate-teal ink, sage green and a hint of mauve.
- **Readable syntax colors** — sea-glass keywords, teal strings, amber numbers and mauve types, tuned for contrast on both backgrounds.
- **Semantic highlighting** enabled, so language-aware tokens are colored beyond the classic TextMate scopes.
- **Terminal ANSI colors** taken from the same palette, so the integrated terminal sits inside the theme.

- **明暗两套协调变体**——同一扩展内含 `Oceanic Scale Theme Light` 与 `Oceanic Scale Theme Dark`。
- **一套海玻璃色板**——水洗青与深海玻璃的底色，配灰青墨迹、鼠尾草绿与一点藕紫。
- **可读的语法配色**——海玻璃青的关键字、青绿的字符串、琥珀色数字与藕紫的类型，在明暗底色上都保持对比。
- **启用语义高亮**，在传统 TextMate scope 之外为语言感知的 token 着色。
- **终端 ANSI 配色**取自同一色板，集成终端与主题融为一体。

<a name="installation"></a>

## Installation / 安装

Requires VS Code 1.80 or newer.

1. Search for **Oceanic Scale Theme** in the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`), or open the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=lilinhuang.oceanic-scale-theme).
2. Or install from a VSIX: download `oceanic-scale-theme-1.0.0.vsix`, open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **Extensions: Install from VSIX...**.

需要 VS Code 1.80 或更高版本。

1. 在扩展面板（`Ctrl+Shift+X` / `Cmd+Shift+X`）搜索 **Oceanic Scale Theme**，或打开 [Marketplace 页面](https://marketplace.visualstudio.com/items?itemName=lilinhuang.oceanic-scale-theme)。
2. 也可以从 VSIX 安装：下载 `oceanic-scale-theme-1.0.0.vsix`，打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Extensions: Install from VSIX...** 并选择该文件。

Or from the command line:

或使用命令行：

```
ext install lilinhuang.oceanic-scale-theme
```

<a name="activation"></a>

## Activation / 启用

Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme**, and choose **Oceanic Scale Theme Light** or **Oceanic Scale Theme Dark**.

To switch between the two variants quickly, use the keyboard shortcut `Ctrl+K Ctrl+T` at any time.

打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Preferences: Color Theme**，选择 **Oceanic Scale Theme Light** 或 **Oceanic Scale Theme Dark**。

随时可用快捷键 `Ctrl+K Ctrl+T` 在两套变体之间快速切换。

<a name="development"></a>

## Development / 开发

Open this folder in VS Code and press `F5` to launch an Extension Development Host with the theme loaded. Regenerate the real-window preview screenshots with:

在 VS Code 中打开本文件夹并按 `F5`，在扩展开发宿主中预览主题。重新生成真实窗口预览图：

```bash
# Windows
py -3 scripts/capture-real-screenshots.py
# macOS / Linux
python3 scripts/capture-real-screenshots.py
```

The script builds a throwaway VS Code profile, installs this theme into it, opens the sample project under `scripts/demo-project` and captures the window for both variants into `store-assets/screenshots/en/`.

脚本会临时创建一个独立的 VS Code 配置目录，把本主题装进去，打开 `scripts/demo-project` 示例工程，并把两套变体的窗口截图输出到 `store-assets/screenshots/en/`。

Check a build before publishing:

发布前自查：

```bash
# Windows
py -3 scripts/validate.py
# macOS / Linux
python3 scripts/validate.py
```

It refreshes `COLOR-SPEC.md` from the theme JSON files, verifies that every color value is a valid hex code, checks that the screenshot edges match `titleBar.activeBackground`, and — when a `.vsix` is present — verifies the manifest publisher, version and theme entries.

脚本会依据主题 JSON 重新生成 `COLOR-SPEC.md`，校验所有颜色值均为合法十六进制，检查截图首行/首列与 `titleBar.activeBackground` 一致，并在存在 `.vsix` 时校验清单里的发布者、版本与主题条目。

Package the extension with:

打包扩展：

```bash
vsce package
```

<a name="license"></a>

## License / 许可

Released under the **Non-Commercial License** — licensed for personal, educational and non-commercial use. See [LICENSE](LICENSE) for details.

基于 **Non-Commercial License（非商业使用许可）** 发布，可用于个人、教育及非商业用途，详见 [LICENSE](LICENSE)。

<a name="feedback"></a>

## Feedback / 反馈

Found an unthemed area or want a tweak? Open an issue at [github.com/vaxicy/oceanic-scale-theme/issues](https://github.com/vaxicy/oceanic-scale-theme/issues).

发现没有配色的区域或想调整某处颜色，欢迎在 [GitHub Issues](https://github.com/vaxicy/oceanic-scale-theme/issues) 反馈。

<a name="publisher"></a>

## Publisher / 发布者

Published by **lilinhuang** on the Visual Studio Code Marketplace.

由 **lilinhuang** 发布于 Visual Studio Code Marketplace.
