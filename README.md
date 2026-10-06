# Teams Meeting AI

**Microsoft Teams 实时 AI 会议助手 | Real-time AI Meeting Assistant for Microsoft Teams**

一个基于 Microsoft Teams 网页版实时字幕和 DeepSeek API 的 Windows 会议辅助工具。

A Windows meeting assistant that uses Microsoft Teams web captions and the DeepSeek API to provide real-time AI assistance during meetings.

## ⬇️ 下载最新版 / Download Latest Release

[**点击这里下载最新版本 / Click here to download the latest version**](https://github.com/MilkRabbit/Teams-Meeting-AI/releases/latest)

---

## 主要功能 / Features

- 实时读取 Microsoft Teams 网页版字幕  
  Read live captions from Microsoft Teams Web

- 自动区分自己与其他参会者  
  Distinguish between your speech and other participants

- AI 生成“回答对方”建议  
  Generate suggested replies to other participants

- AI 生成“接着往下说”内容  
  Generate natural continuations for your own speech

- AI 生成主动提问建议  
  Generate useful follow-up questions

- 支持用户背景信息  
  Use personal/professional background as AI context

- 支持 TXT、MD、PDF、DOCX、XLSX 等背景资料导入  
  Import background information from TXT, MD, PDF, DOCX, XLSX and other formats

- 支持中文 / English 输出  
  Supports Chinese and English output

---

## 下载 / Download

请前往本仓库的 **Releases** 页面下载最新版 Windows 安装程序。(https://github.com/MilkRabbit/Teams-Meeting-AI/releases/latest)

Download the latest Windows installer from the **Releases** section of this repository. (https://github.com/MilkRabbit/Teams-Meeting-AI/releases/latest)

文件名 / Installer:

`MeetingAI_Studio_Setup.exe`

---

## 使用方法 / Quick Start

### 1. 安装软件 / Install the application

下载并运行：

Download and run:

`MeetingAI_Studio_Setup.exe`

### 2. 安装 Tampermonkey

软件内点击：

**安装 Tampermonkey / Install Tampermonkey**

Install the Tampermonkey browser extension.

### 3. 安装 Teams 会议脚本 / Install the Teams userscript

软件会打开 Greasy Fork 页面：

The application will open the Greasy Fork userscript page:

https://greasyfork.org/zh-CN/scripts/598844-meeting-ai-teams

点击 **安装此脚本 / Install this script**，并在 Tampermonkey 中确认安装。

### 4. 配置 DeepSeek API

在软件中输入自己的 DeepSeek API Key。

Enter your own DeepSeek API Key in the application.

API Key 由用户自行申请，API 使用费用由 DeepSeek 收取。

Users need to provide their own DeepSeek API Key. API usage fees are charged by DeepSeek.

### 5. 打开 Teams 网页版 / Open Microsoft Teams Web

启动本地服务，然后打开 Teams 网页版并开启实时字幕。

Start the local service, open Microsoft Teams Web, and enable live captions.

---

## 隐私 / Privacy

- API Key 使用 Windows DPAPI 在本机加密保存。
- 用户背景资料保存在本机。
- 软件不会将你的 API Key 上传到开发者服务器。
- AI 请求直接使用用户自己的 DeepSeek API。

- The API Key is encrypted locally using Windows DPAPI.
- User background information is stored locally.
- The application does not upload your API Key to a developer-operated server.
- AI requests use the user's own DeepSeek API account.

---

## 系统要求 / Requirements

- Windows 10 / Windows 11
- Microsoft Teams Web
- Tampermonkey
- DeepSeek API Key
- Internet connection

---

## 当前版本 / Current Version

**v2.2**

首次公开发布版本。

First public release.

---

## 反馈 / Feedback

如果遇到问题或有功能建议，可以通过 GitHub Issues 提交。

If you encounter a problem or have a feature request, please open a GitHub Issue.

---

## Author

**MilkRabbit**

If this project is useful to you, consider giving it a ⭐ Star.
如果这个项目对你有帮助，欢迎点一个 ⭐ Star。
