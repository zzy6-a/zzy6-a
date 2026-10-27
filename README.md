<div align="center">

# zzy6-a

**Android 开发者 · 本地优先的工具制造者**

`Kotlin` · `Jetpack Compose` · `TypeScript` · `Node.js` · `PowerShell`

写给自己的工具，顺手开源。

[博客](https://zzy6.dpdns.org/) · [文章归档](https://zzy6.dpdns.org/archives/) · [全部仓库](https://github.com/zzy6-a?tab=repositories)

</div>

---

## 🧩 DeepSeek Harness 插件

> 让 Agent 在自己的桌面上真正干活。

| 插件 | 一句话 | 状态 |
| :-- | :-- | :-- |
| **[vision-use](https://github.com/zzy6-a/vision-use)**<br><sub>DSH Computer Use</sub> | 看见屏幕、操作键鼠，并且**能按控件名定位**——UI Automation 的 pattern 点击不移动鼠标 | **`v0.3.0`** |
| **[dsh-prompt-enhance](https://github.com/zzy6-a/dsh-prompt-enhance)**<br><sub>提示词增强</sub> | 输入框旁一键把口语改写成目标明确的完整任务说明，可撤销 | `active` |
| dsh-upgrade-guard<br><sub>兼容卫士</sub> | 宿主升级后巡检插件兼容性，启动失败时由宿主外 supervisor 救援并回滚 | `archived` |

### vision-use · 0.3.0 有什么

| 能力 | 说明 |
| :-- | :-- |
| **按名字点，不算坐标** | `uia_find` 列出候选控件（名称 / 类型 / 中心点 / 可用 pattern），`uia_click` 优先走 invoke / toggle / select / expand —— **鼠标不动**，点完回传前后 UI 指纹，让你知道到底变了没有 |
| **近景确认** | `uia_locate` 只回一张以控件为中心的裁剪图，回执里不带坐标 —— 用眼睛核对，不用算术 |
| **一次调用做一串** | `computer_sequence` 把 `click → type → key → wait → shot` 合成一次进程、一次模型往返，通常省 30–60 秒 |
| **截被遮挡的窗口** | `view_screen` 的 `hwnd` 走 PrintWindow，窗口被别的窗口盖住也能截到真实内容；`grid` 画坐标标尺，`marker` 画红十字核对落点 |
| **中文能输入了** | `computer_type` 的 `method: auto`：ASCII 用真实按键；含中文或超长文本走剪贴板，**用完还原你原来的剪贴板** |
| **看得见它在动** | Codex 风格蓝色边框 + 顶部状态徽章 + 光标光环 + 点击涟漪，按 **Esc** 随时中止；回合结束后约 4 秒自动收 |

```powershell
dsh plugin --profile desktop add https://github.com/zzy6-a/vision-use/releases/latest/download/dsh-vision-0.3.0.tgz
```

<sub>[发布页](https://github.com/zzy6-a/vision-use/releases) · [中文说明](https://github.com/zzy6-a/vision-use#readme) · [English](https://github.com/zzy6-a/vision-use/blob/main/README_EN.md)</sub>

---

## 📱 应用与站点

| 项目 | 说明 |
| :-- | :-- |
| [fuyang · 滏阳没有海](https://github.com/zzy6-a/fuyang) | 纯静态网页解谜 / ARG · 零依赖、断网可玩 · [开始游戏](https://zzy6-a.github.io/fuyang/) |
| [zzy-blog](https://github.com/zzy6-a/zzy-blog) | 个人博客（Hexo + Redefine）· [zzy6.dpdns.org](https://zzy6.dpdns.org/) |
| [ai-radar](https://github.com/zzy6-a/ai-radar) | AI 实时态势 PWA：新模型 · 价格变动 · 社区热帖 · 开源趋势 |
| [ScyroxTray](https://github.com/zzy6-a/ScyroxTray) | SCYROX / Compx 无线鼠标电量托盘工具（旧款 V6/V8 也支持） |

## 📦 已归档

这些项目不再维护，代码和发布继续留在原处，只读可查。

| 项目 | 说明 |
| :-- | :-- |
| [pocket-books · 口袋记账](https://github.com/zzy6-a/pocket-books) | 轻量、智能、完全本地的 Android 记账应用 · [下载中心](https://zzy6-a.github.io/pocket-books/) |
| [dsh-upgrade-guard · 兼容卫士](https://github.com/zzy6-a/dsh-upgrade-guard) | DSH 宿主升级巡检与启动救援 |

---

## 🛠 我在做什么

- **Android**：Kotlin + Compose + Material 3 + Room，MVVM
- **DSH 生态**：TypeScript + Node.js 插件，PowerShell 绑 Windows 原生能力
- **偏爱**：本地优先、可离线、不收集数据；能跑在自己机器上的东西

## 联系

<div align="center">

[![Email](https://img.shields.io/badge/1982779986%40qq.com-c14438?style=flat-square&logo=maildotru&logoColor=white)](mailto:1982779986@qq.com)
[![GitHub](https://img.shields.io/badge/zzy6--a-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zzy6-a)

</div>
