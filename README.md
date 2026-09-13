<p align="center">
  <img src="app-icon.png" width="150" alt="Post Folder Studio icon" />
</p>
<h1 align="center">Post Folder Studio</h1>
<p align="center">为影视后期建立清晰、可交接的项目目录。<br/>A macOS app for organizing post-production folders and bins.</p>
<p align="center">
  <a href="https://github.com/Sarahliu39/post-folder-studio/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Sarahliu39/post-folder-studio?style=flat-square&color=8b6ca8" /></a>
  <img alt="macOS 13 or later" src="https://img.shields.io/badge/macOS-13%2B-596579?style=flat-square" />
  <img alt="Apple Silicon" src="https://img.shields.io/badge/Apple-Silicon-596579?style=flat-square" />
</p>
<p align="center"><a href="https://github.com/Sarahliu39/post-folder-studio/releases/latest">下载 DMG · Download</a> · <a href="#features">功能 · Features</a> · <a href="#installation">安装 · Installation</a> · <a href="https://github.com/Sarahliu39/post-folder-studio/issues">反馈 · Feedback</a></p>

## 界面演示 · Interface Demo

![Post Folder Studio：项目设置与目录预览 / Project settings and folder preview](interface-demo.png)

*真实界面示例，来自早期版本截图；当前版本的文字和外观可能不同。*  
*Actual interface example from an earlier build; current labels and appearance may differ.*

<a id="features"></a>
## 功能 · Features

| 中文 | English |
| --- | --- |
| **项目目录模板**：适用于短片、纪录片、长片及剪辑部门等工作场景。 | **Project presets** for short films, documentaries, features and editorial departments. |
| **按项目组织**：根据拍摄天数、机位数及可选模块生成结构。 | **Project-based organization** using shooting days, camera counts and optional modules. |
| **可编辑预览**：新增、重命名、删除节点，确认后再生成文件夹。 | **Editable preview**: add, rename and remove nodes before creating folders. |
| **可复用模板**：保存个人模板，导入和导出 JSON。 | **Reusable templates**: save custom structures and import or export JSON. |
| **Bin 创建**：目前支持在已打开的 DaVinci Resolve 项目中创建媒体池 Bin。 | **Bin creation**: currently supports media-pool bins in an open DaVinci Resolve project. |
| **个性化外观**：中英文界面、日夜配色、玻璃／磨砂／纯色材质和透明度。 | **Personalized appearance**: Chinese/English UI, light/dark palettes, glass/frosted/solid materials and transparency. |
| **软件内更新**：检查、下载、验证签名、安装与重启。 | **In-app updates**: check, download, verify signatures, install and relaunch. |

<a id="installation"></a>
## 下载与安装 · Download & Installation

1. 在 [Releases](https://github.com/Sarahliu39/post-folder-studio/releases/latest) 下载 DMG。  
   Download the DMG from [Releases](https://github.com/Sarahliu39/post-folder-studio/releases/latest).
2. 打开 DMG，将 **Post Folder Studio.app** 拖入 **Applications**。  
   Open the DMG and drag **Post Folder Studio.app** into **Applications**.
3. 从“应用程序”启动软件。  
   Launch the app from **Applications**.

**系统要求 / Requirements:** Apple Silicon（M 系列）Mac · macOS 13+。暂无 Intel 或 Windows 安装包。 / No Intel or Windows build is currently provided.

> 当前安装包尚未经过 Apple Developer ID 签名与公证，首次启动可能提示无法验证开发者。  
> This build is not Developer ID-signed or notarized by Apple. macOS may warn that the developer cannot be verified.

## 快速开始 · Quick Start

**项目名称 → 模板 → 天数与机位 → 检查预览 → 生成文件夹**  
**Project name → Preset → Days & cameras → Review preview → Create folders**

创建 Resolve Bin 前，请打开目标项目并启用本地脚本访问。可用性取决于 Resolve 版本和配置。  
Before creating Resolve bins, open the target project and enable local scripting access. Availability depends on your Resolve version and configuration.

## 更新与订阅 · Updates & Subscriptions

从 **5.0.0** 起，在 **Settings → 软件更新 / Software Update** 中下载并安装新版，也可启用自动检查和自动下载。更新由 Sparkle 提供，安装包来自本仓库 Releases，安装前验证更新签名。需要重启时请先保存工作。

Starting with **5.0.0**, use **Settings → Software Update** to download and install new versions, with optional automatic checks and downloads. Sparkle retrieves packages from this repository and verifies update signatures before installation. Save your work before relaunching.

**旧版需要手动安装本版一次，之后即可使用内置更新。**  
**Older builds without the updater require one manual installation first.**

发布通知：**Watch → Custom → Releases**；Star 不等于订阅。  
Release notifications: **Watch → Custom → Releases**; starring does not subscribe you.

## 反馈 · Feedback

请在 [Issues](https://github.com/Sarahliu39/post-folder-studio/issues) 提交版本号、macOS 版本、芯片型号、复现步骤和截图，避免包含私人项目资料。  
Report issues with the app version, macOS version, chip model, reproduction steps and screenshots. Please exclude private project information.

## 关于仓库 · About This Repository

本仓库用于分发安装包、展示软件和发布更新，不公开应用源代码。  
This repository distributes application builds, documentation and update information. Application source code is not published here.
