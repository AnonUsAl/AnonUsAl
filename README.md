<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=7C3AED&center=true&vCenter=true&width=560&lines=Cross-platform+Developer;Flutter+%7C+Nuxt+%7C+.NET+%7C+Compose+%7C+C%2B%2B;Local-first+%7C+Privacy+%7C+Open+Source" alt="AnonUsAl" />

# AnonUsAl

**跨平台开发者** — Flutter · Nuxt · .NET · Kotlin/Compose · C++/MFC

云术工作室 [@ClouderyStudio](https://github.com/ClouderyStudio) 成员 · [mood-tab](https://github.com/ClouderyStudio/mood-tab) 作者

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Nuxt_4-00DC82?style=flat-square&logo=nuxt&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Tauri_2-24C8DB?style=flat-square&logo=tauri&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

</div>

---

## 关于我

我做的事情可以概括成一句：**把一件事从界面一直做到系统层。**

在跨平台方向，我主导开发了 [mood-tab](https://github.com/ClouderyStudio/mood-tab) —— 一款把数据完全留在本地的情绪记录 App。它用 Flutter 写成，SQLite 存储（桌面端走 FFI），带生物识别隐私锁、本地通知提醒、图表统计与 PDF 导出，Windows / macOS / iOS / Android 四端都已打包发版。做这件事的过程让我把「一份 Dart 代码跑通四种操作系统」的坑基本踩了一遍：CMake 与原生插件、CocoaPods、Gradle KTS、各平台的通知与权限模型。

在 Web 与后端方向，我参与团队的心理健康测评平台 [psychology](https://github.com/ClouderyStudio/psychology)（Nuxt 4 + Vue 3 + TypeScript + Tailwind），以及驱动整套生态的 .NET 10 统一后端（ASP.NET Core + EF Core，SQL Server / MySQL 双库，接入自建 Casdoor 做 OIDC 单点登录）。

我也喜欢往底层走。最近在改一个开源远控程序的主控端：把 MFC 界面统一成深色主题、处理高 DPI 缩放、梳理 MSBuild v142 的构建链路 —— 这类活儿让我对 Win32、GDI、多实例探测这些层面有实际手感。

除了写代码，我也关注心理健康议题，认为精神类疾病应该被更多人理解，而不是被标签化、回避或误解。上面那两款产品都源自这个想法。

---

## 代表项目

| 项目 | 说明 |
| --- | --- |
| **[mood-tab](https://github.com/ClouderyStudio/mood-tab)** | 跨平台情绪记录 App · Flutter · 四端发版 v3.0.16 · 本地优先，数据不出设备 |
| **[psychology](https://github.com/ClouderyStudio/psychology)** | 心理健康测评平台 · Nuxt 4 + Vue 3 + TypeScript · 团队主力项目 |
| **[can-i-run-ai](https://github.com/AnonUsAl/can-i-run-ai)** | 桌面工具：检测本机能跑得动哪些 AI 模型 · Tauri 2 + React 19 + Rust |
| **[Tb_Miner](https://github.com/AnonUsAl/Tb_Miner)** | 区块链挖矿模拟器 · Python · 钱包、交易签名、链数据持久化 |
| **[moodtracker](https://github.com/AnonUsAl/moodtracker)** | 情绪追踪工具 · 命令行 + Kivy / Buildozer 安卓端 |
| **[AnonUsAl.github.io](https://github.com/AnonUsAl/AnonUsAl.github.io)** | 个人主页 · GitHub Pages |

<details>
<summary><b>还有一些别的（点开）</b></summary>

<br>

- **[TBit](https://github.com/AnonUsAl/TBit)** / **[TiBit](https://github.com/AnonUsAl233/TiBit)** — Tcoin 链模拟器，挖矿与交易流程的练手项目
- **[docs](https://github.com/AnonUsAl/docs)** — 文档站（VitePress，自定义域名）
- **[allium-browser](https://github.com/AnonUsAl/allium-browser)** — I2P 匿名网络浏览器，fork 自 [umutcamliyurt/I2P-Browser](https://github.com/umutcamliyurt/I2P-Browser)，我给它提过 PR
- **[SimpleRemoter](https://github.com/AnonUsAl/SimpleRemoter)** — 开源远控程序 fork，我在 Beta 分支做 MFC 深色主题、高 DPI 适配与构建文档

</details>

---

## 技术栈

**跨平台 App**
`Flutter 3` · `Dart` · `provider` · `sqflite` / `sqflite_common_ffi` · `fl_chart` · `flutter_local_notifications` · `pdf` / `printing` · `local_auth` · `webview_flutter` · Kivy + Buildozer · Tauri 2

**Web 前端**
`Vue 3` · `Nuxt 4` · `React 19` · `TypeScript` · `Vite` · `Pinia` · `Tailwind CSS` · `shadcn-vue` · `Astro` · `VitePress` · Svelte 群岛

**后端与数据**
`C# / .NET 10` · `ASP.NET Core` · `EF Core` · `SQL Server` · `MySQL` · `SQLite` · `Go` · `Casdoor OIDC` · Express

**原生与系统层**
`C++` · `MFC` · `Win32 API` · `MSBuild v142` · `Direct3D / DXGI` · `FFmpeg` · `CMake` · `PyQt5 / PyQt6`

**移动端原生**
`Kotlin` · `Jetpack Compose` · `Room` · `Retrofit` · `Gradle KTS` · `Swift` · `CocoaPods` · `Android NDK`

**工具链**
`Git / GitHub Actions` · `VS Code` · `Neovim` · `CMake` · `pnpm` · Linux · Tor / I2P / 代理与隐私

---

## 团队

我是 **[ClouderyStudio（云术工作室）](https://github.com/ClouderyStudio)** 的成员，和团队一起维护心理健康测评平台、官网、文档站与统一后端。

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AnonUsAl&show_icons=true&hide_border=true&theme=dark&locale=cn&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnonUsAl&layout=compact&hide_border=true&theme=dark&locale=cn&langs_count=10" />

</div>

---

## 联系我

<div align="center">

**[anonusal.cldery.com](https://anonusal.cldery.com/)** &nbsp;·&nbsp; [GitHub](https://github.com/AnonUsAl) &nbsp;·&nbsp; [X](https://x.com/AnonUsAl4433) &nbsp;·&nbsp; [Telegram](https://t.me/AnonUsAl)

`QQ 3353739856` &nbsp;·&nbsp; `albusp486@gmail.com`

</div>

<details>
<summary><b>其它平台（点开）</b></summary>

<br>

- 站点：https://anonusal.cldery.com/
- X：https://x.com/AnonUsAl4433
- Telegram：@AnonUsAl
- LINE：@AnonUsAl
- WhatsApp：@AnonUsAl
- QQ空间：https://user.qzone.qq.com/3353739856/main
- 微博：https://weibo.com/u/8486027864
- 微博：https://weibo.com/u/5448978282

</details>

---

<div align="center">

> *"the quieter you become, the more you are able to hear"*

</div>
