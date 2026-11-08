<div align="center">

# 你好，我是 Yongzhen Yang 👋

🧩 **仓颉工具链 · 开源** · 🔨 用华为 [仓颉语言](https://cangjie-lang.cn) 造开发者工具 · 📅 2014 年起在 GitHub 公开写码

**中文** · [English](https://github.com/yangyongzhen/yangyongzhen/blob/main/README.md)

![Cangjie](https://img.shields.io/badge/-Cangjie-0761D1?style=flat-square&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white)
![HarmonyOS](https://img.shields.io/badge/-HarmonyOS-000000?style=flat-square&logoColor=white)

[![Followers](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yangyongzhen)
[![CSDN](https://img.shields.io/badge/-blog.csdn.net%2Fqq8864-FC5531?style=flat-square&logoColor=white)](https://blog.csdn.net/qq8864)
[![AtomGit](https://img.shields.io/badge/-atomgit.com%2Fqq8864-0B8240?style=flat-square&logoColor=white)](https://atomgit.com/qq8864)
[![Email](https://img.shields.io/badge/-534117529%40qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:534117529@qq.com)

</div>

> **cj-tauri**、**cjh**、**cspub** 的作者——一个类 Tauri 的桌面应用框架、一个交互式编码 Agent、一个十平台发文 CLI。
> 三个项目都用仓颉写成，全部开源：合计约 7.6 万行代码、1,259 个单元测试。

**目前在做的事：** 补齐仓颉生态里缺的那几块——能直接放进真实工作流的工具，而不是演示程序。

## 主推项目

### ⚡ cj-tauri —— 仓颉版的类 Tauri 桌面框架

[![Stars](https://img.shields.io/github/stars/yangyongzhen/cj-tauri?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/cj-tauri)
[![Tag](https://img.shields.io/github/v/tag/yangyongzhen/cj-tauri?style=flat-square&label=latest%20tag)](https://github.com/yangyongzhen/cj-tauri/tags)
[![Docs](https://img.shields.io/badge/docs-yangyongzhen.github.io%2Fcj--tauri-ffb224?style=flat-square)](https://yangyongzhen.github.io/cj-tauri/)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/yangyongzhen/cj-tauri/blob/main/LICENSE)

静态编译的仓颉后端 + 系统 WebView（WebView2 / WebKitGTK / ArkWeb），双向 IPC 桥、能力白名单与插件系统。
产物只有几 MB，Windows、Linux、HarmonyOS 三端均实测通过。

`101 个源文件` · `25,431 行仓颉` · `350 个测试`

### 🤖 cjh —— 仓颉版编码 Agent 内核

[![Stars](https://img.shields.io/github/stars/yangyongzhen/cjh?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/cjh)
[![Tag](https://img.shields.io/github/v/tag/yangyongzhen/cjh?style=flat-square&label=latest%20tag)](https://github.com/yangyongzhen/cjh/tags)
[![Docs](https://img.shields.io/badge/docs-yangyongzhen.github.io%2Fcjh-ffb224?style=flat-square)](https://yangyongzhen.github.io/cjh/)

从零用仓颉写成的交互式编码 Agent：agent 循环、工具调用、skills、斜杠命令与终端 UI。
打成单个约 17 MB 的产物，便于嵌入。

`115 个源文件` · `41,528 行仓颉` · `810 个测试`

### 📤 cspub —— 一份 Markdown 进，十个平台出

[![Stars](https://img.shields.io/github/stars/yangyongzhen/cspub?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/cspub)
[![Tag](https://img.shields.io/github/v/tag/yangyongzhen/cspub?style=flat-square&label=latest%20tag)](https://github.com/yangyongzhen/cspub/tags)
[![Docs](https://img.shields.io/badge/docs-yangyongzhen.github.io%2Fcspub-ffb224?style=flat-square)](https://yangyongzhen.github.io/cspub/)

面向 CSDN / 知乎 / 掘金 / 开源中国 / 博客园 / 百家号 / 腾讯云 / 语雀 / 头条 / 思否的发文 CLI：
渲染 HTML、按平台转存图片、为网关请求签名、提交，并把 article id 打回来。
只依赖标准库与 stdx —— **零第三方依赖**。

`26 个源文件` · `9,369 行仓颉` · `99 个测试` · `10 个平台`

## 数字说话

| | |
| --- | --- |
| 上面三个项目的仓颉代码 | **约 7.6 万行** |
| 这些项目里的单元测试 | **1,259 个** |
| 原创仓库（连同 fork 共 95 个公开仓库） | **36 个** |
| 原创作品累计 star | **200** |
| 原创作品累计被 fork | **52** |
| 公开写码起始 | **2014 年** |

> 数据为 2026 年 11 月快照。下面的徽章是实时的，这些数字不是。

## 更早的作品

在做仓颉之前，我用十年时间折腾协议栈、嵌入式 GUI 绑定和后端服务——以 Go、Java、C、Rust 为主。

- 🐜 **[tinybg](https://github.com/yangyongzhen/tinybg)** —— 世界上最简单的博客系统：约 500 行 Go 后端撑起的完整个人博客 [![stars](https://img.shields.io/github/stars/yangyongzhen/tinybg?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/tinybg)
- 💳 **[Easy8583Ans](https://github.com/yangyongzhen/Easy8583Ans)** —— Java 版 ISO 8583 金融报文协议分析，我 fork 数最多的仓库 [![stars](https://img.shields.io/github/stars/yangyongzhen/Easy8583Ans?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/Easy8583Ans)
- 🖼️ **[golvgl](https://github.com/yangyongzhen/golvgl)** —— 开源嵌入式 GUI 库 LVGL 的 Go 绑定 [![stars](https://img.shields.io/github/stars/yangyongzhen/golvgl?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/golvgl)
- 🔌 **[gin-websocket](https://github.com/yangyongzhen/gin-websocket)** —— Gin Web 框架的 WebSocket 支持 [![stars](https://img.shields.io/github/stars/yangyongzhen/gin-websocket?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/gin-websocket)
- 🏭 **[powerlink-stm32](https://github.com/yangyongzhen/powerlink-stm32)** —— openPOWERLINK 工业以太网协议栈移植到 STM32 [![stars](https://img.shields.io/github/stars/yangyongzhen/powerlink-stm32?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/powerlink-stm32)
- 🏦 **[go8583](https://github.com/yangyongzhen/go8583)** —— 同样的 8583 协议工作，Go 版 [![stars](https://img.shields.io/github/stars/yangyongzhen/go8583?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/go8583)
- 🎙️ **[PodcastfyUI](https://github.com/yangyongzhen/PodcastfyUI)** —— 用纯 Rust 重写的 Podcastfy：把网页、PDF、纯文本变成双人对谈播客 [![stars](https://img.shields.io/github/stars/yangyongzhen/PodcastfyUI?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/PodcastfyUI)
- 📡 **[atomMqtt](https://github.com/yangyongzhen/atomMqtt)** —— 用 Rust 写的小巧 MQTT broker [![stars](https://img.shields.io/github/stars/yangyongzhen/atomMqtt?style=flat-square&label=%E2%98%85)](https://github.com/yangyongzhen/atomMqtt)

→ **[全部 95 个仓库](https://github.com/yangyongzhen?tab=repositories)**

## GitHub 活跃度

![Contribution graph](https://ghchart.rshah.org/yangyongzhen)

## 写作

我把平台 API 的逆向过程公开写出来，写的是证据而不是猜测：签名算法、错误码、图床行为、TLS 证书链。
大部分在 CSDN 上用中文写，可复用的踩坑记录就放在每个项目源码旁边的 `docs/开发文档与踩坑记录.md` 里。

[![CSDN](https://img.shields.io/badge/-blog.csdn.net%2Fqq8864-FC5531?style=flat-square&logoColor=white)](https://blog.csdn.net/qq8864)
[![AtomGit](https://img.shields.io/badge/-atomgit.com%2Fqq8864-0B8240?style=flat-square&logoColor=white)](https://atomgit.com/qq8864)
[![GitHub](https://img.shields.io/badge/-yangyongzhen-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yangyongzhen)
[![Email](https://img.shields.io/badge/-534117529%40qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:534117529@qq.com)
