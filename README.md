<div align="center">

<img src="pixora.ico" width="96" height="96" alt="Pixora Logo" />

# Pixora (皮克索拉)

### 🚀 下一代智能截图、置顶贴图与 AI 桌面协同工作站
**Next-Generation Intelligent Screenshot, Pin & AI Desktop Assistant**

[![Release](https://img.shields.io/github/v/release/tracy115-ops/pixora-release?style=flat-square&color=orange)](https://github.com/tracy115-ops/pixora-release/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2B%20(x64)-blue?style=flat-square&logo=windows)](https://github.com/tracy115-ops/pixora-release/releases)
[![Language](https://img.shields.io/badge/Language-C%2B%2B20%20%2F%20Qt%206-green?style=flat-square&logo=qt)](https://www.qt.io/)
[![Protocol](https://img.shields.io/badge/Protocol-MCP%20Enabled-purple?style=flat-square)](https://modelcontextprotocol.io/)
[![License](https://img.shields.io/badge/License-GPL%20v3-lightgrey?style=flat-square)](LICENSE)

[📥 下载最新版本 (Download)](#-下载与安装-download--installation) • 
[✨ 核心特性 (Features)](#-核心特性亮点-features) • 
[🤖 AI 赋能 (AI Capabilities)](#-ai-多模态深度集成-ai-integration) • 
[⌨️ 快捷键速查 (Hotkeys)](#️-常用快捷键速查-shortcuts)

</div>

---

## 📖 产品简介 (About Pixora)

**Pixora** 是一款基于 **C++20** 与 **Qt 6** 现代架构打造的专业级桌面效率工具。

它融合了经典截图工具（如 Snipaste / Flameshot）的极致纯粹体验与前沿 **多模态大模型 (AI)**、**MCP (Model Context Protocol)** 协议，不仅具备像素级精度的屏幕捕获、窗口层级检测、置顶贴图与专业标注，更让您的每一次截图都能直接化为 AI 的视觉感知入口！

无论是程序员日常代码审查、UI/UX 设计师像素级对比、办公族图表总结，还是技术博主编写教程说明，Pixora 都能带来行云流水般的桌面生产力跃升。

---

## ✨ 核心特性亮点 (Features)

### 📸 1. 极致精细的截屏体验
* **智能窗口与父/子元素穿透检测**：
  * 移动鼠标自动高亮吸附窗口与 UI 控件。
  * **滚轮向上滚动**：自动扩展选区至父级容器；**滚轮向下滚动**：向内聚焦子元素，复杂界面控件秒选！
* **多元截屏模式**：
  * 支持**自由矩形**、**全屏截图**、**活动窗口捕捉**、**延时截屏**。
  * **长截图 (滚动拼接截屏)**：平滑抓取长网页、长聊天记录与长代码文件。
  * **GIF 动态录屏**：内置高画质帧率与时长调节，一键录制动图。
* **超级像素级取色器**：
  * 悬停时光标附带高倍网格放大镜与 RGB / HEX 颜色值。
  * 按快捷键 `C` 复制当前像素颜色代码，按 `Shift` 切换 HEX/RGB 格式，按 `Alt` 锁定取色。
* **二维码 / 条形码自动检测**：
  * 截屏区域如包含二维码或条形码，底层算法毫秒级快速识别。

---

### 📌 2. 自由桌面贴图 (Pin to Desktop)
* **万物皆可贴图**：不仅支持将截图一键钉在桌面，还支持通过剪贴板直接将复制的文字、图像、本地文件钉为置顶便签。
* **快捷图像变换**：
  * 滚轮无级平滑缩放（10% ~ 500%）。
  * 快捷键 `R` 旋转 90°，`F` / `Shift+F` 水平与垂直镜像翻转。
* **贴图专业黑白与夜间反色模式**：
  * 按 **`5`**：一键切换黑白灰度模式（消除色彩干扰，精准比对线条与灰阶细节）。
  * 按 **`I`**：一键反转色彩（夜间模式，瞬间将刺眼的白底图像转化为柔和的黑底白字）。
* **鼠标穿透模式 (`F9`)**：
  * 一键开启无感知穿透模式，贴图悬浮在屏幕最上层，鼠标操作直接穿透至下方 IDE、设计软件或网页，对照临摹、写代码零遮挡。
* **无缝文件拖拽与系统剪贴板**：
  * 支持直接将浏览器中的网络图片拖拽为贴图。
  * 复制截图后，在微信/QQ 可直接粘贴图片，在 **Windows 资源管理器或桌面上按 `Ctrl + V` 可直接粘贴为 `.png` 文件**！

---

### ✏️ 3. 丰富的专业标注工具箱 (Annotations)
* **常用图形全覆盖**：矩形、椭圆、直线、自由画笔、荧光记号笔、双向箭头、个性图章。
* **隐私安全**：内置**马赛克**与**高斯模糊**画笔，敏感信息随手打码。
* **数字序号自动递增标注 (① ② ③)**：
  * 编写教程、指引与 Bug 反馈的杀手级工具，每点击一次自动生成序号圈并递增编号。
* **高对比度文字标注**：
  * 文字标注自动生成高对比圆角微底衬，在任何亮色/暗色复杂壁纸背景下都清晰醒目。
* **极速撤销与单步删除**：
  * 支持全套 `Ctrl+Z` 撤销 / `Ctrl+Y` 重做，直接按键盘 `Delete` 或 `Backspace` 即可单步删除上一标注。

---

### 🤖 4. AI 多模态深度集成 (AI Integration)
Pixora 内置先进的多模态大模型交互引擎，让截图不再是终点，而是智能分析的起点：

* **截图多模态对话**：
  * 选区后点击 AI 图标，直接将当前画面发送给大模型。
  * 随时进行多轮图文对话：“这段报错是什么原因？”、“根据这张原型图写出 Tailwind 样式”、“翻译并总结这张报表”。
* **AI 智能 OCR 文字提取**：
  * 毫秒级提取图片中的印刷体、代码、排版文本，支持一键复制到剪贴板。
* **AI 智能截图翻译**：
  * 一键识别外语截图，即时翻译成中文并生成清晰的原位译文对照。
* **AI 自动 UI 标注**：
  * 大模型智能解析界面中的按钮、输入框、导航栏，并自动在图上绘制高亮控件边框与元数据标签。
* **流式打字输出与随时停止 (⏹)**：
  * 支持打字机流式输出，对话过程中可随时点击停止生成按钮，及时中断请求。
* **全平台模型自由接入**：
  * 支持无缝配置 **OpenAI (GPT-4o)**、**Anthropic (Claude 3.5 Sonnet)** 以及本地离线模型 **Ollama**。

---

### 🔌 5. 原生 MCP (Model Context Protocol) 协议支持
Pixora 率先原生集成了 Anthropic 推出的 **MCP** 协议标准：
* 允许外部 AI 编程工具与 Agent 客户端（如 **Cursor**、**Claude Desktop**、**Windsurf**、**VS Code Copilot** 等）直接连接并远程驱动 Pixora。
* AI 助手可自主执行全屏/区域截图、OCR 读取、贴图管理、屏幕尺寸与控件探知，实现真正的桌面级 AI Agent 自动化闭环。

---

### 🗄 6. 本地截图历史库 (History Management)
* **本地轻量级 SQLite 存储**：自动安全记录截屏历史，保护隐私，不上云端。
* **瀑布流检索与二次编辑**：支持按时间排序、缩略图预览、全尺寸原图查看、二次复制或重新钉图。

---

## 📥 下载与安装 (Download & Installation)

请前往本仓库的 **[Releases 页面](https://github.com/tracy115-ops/pixora-release/releases/latest)** 下载最新发布版本：

| 安装方式 | 适用场景 | 说明 |
|:---|:---|:---|
| **`Pixora-Setup-vX.X.X-x64.exe`** | 推荐大多数用户 | 标准安装程序，支持快捷方式创建、开机自启、一键安装与卸载 |
| **`pixora-win64-vX.X.X.zip`** | 便携/免安装用户 | 解压即用，所有配置文件本地化存储，适合存放在 U 盘或随身携带 |

> 💡 **在线无感自动更新**：Pixora 客户端内置了防卡死智能多 CDN 镜像加速更新引擎，后续有新版本发布时，直接在客户端点击“检查更新”即可秒级完成在线升级！

---

## ⌨️ 常用快捷键速查 (Shortcuts)

| 场景 | 快捷键 | 功能描述 |
|:---|:---:|:---|
| **全局** | `F1` | 打开快捷键帮助速查卡 |
| | `F7` | 将剪贴板图片/文字/文件钉在屏幕上 |
| | `Ctrl + Alt + H` | 打开本地截图历史管理器 |
| **截屏中** | `滚轮向上 / 向下` | 自动穿透扩展/收缩检测父级或子级 UI 元素 |
| | `C` | 复制当前十字光标下的像素颜色值 (RGB/HEX) |
| | `Shift` | 切换取色格式为 HEX 或 RGB |
| | `Alt` | 保持/切换颜色拾取放大镜 |
| | `Delete` / `Backspace` | 删除/撤销上一个绘制的标注 |
| | `Ctrl + Z` / `Ctrl + Y` | 撤销 / 重做标注 |
| | `Esc` | 退出截图 / 取消当前绘制 |
| **贴图窗口** | `鼠标滚轮` | 无级平滑缩放贴图 (10% ~ 500%) |
| | `5` | **黑白/灰度模式切换** (消除颜色干扰) |
| | `I` | **颜色反色模式切换** (白底反转为夜间黑底) |
| | `R` | 顺时针旋转 90 度 |
| | `F` / `Shift + F` | 水平翻转 / 垂直翻转 |
| | `F9` | **鼠标穿透模式开关** (点击直接穿透至下层窗口) |
| | `双击贴图` | 复制图像并关闭当前贴图 |
| | `Esc` | 关闭当前贴图 |
| | `右键菜单` | 另存为、复制、灰度、反色、穿透设置 |

*(所有全局快捷键均可在「设置」面板中自由重新绑定)*

---

## ⚙️ 系统要求 (Requirements)

* **操作系统**：Windows 10 / Windows 11 (64-bit)
* **架构**：x86_64
* **显卡/图形**：支持 DirectX / Direct3D 硬件加速显示（亦支持自动软渲染回退）

---

## 🤝 反馈与共建 (Feedback & Issues)

如果您在使用过程中遇到任何问题，或对新功能有任何灵感与建议：
* 欢迎在 [GitHub Issues](https://github.com/tracy115-ops/pixora-release/issues) 提交反馈与讨论。
* 如果 Pixora 提升了您的桌面生产力，欢迎给本项目点一颗 ⭐️ **Star** 鼓励支持！

---

<div align="center">

Made with ❤️ by the Pixora Team.

</div>
