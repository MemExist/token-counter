# Global AI Token Counter  
## 全球 AI Token 计数器

> Count tokens. Estimate costs. Analyze text. Across global languages.  
> 统计 Token，估算成本，分析文本，支持全球语言。

---

## Overview / 项目简介

**Global AI Token Counter** 是一个轻量级、纯前端的 AI Token 计数与文本分析工具。

它可以帮助用户快速估算文本的 Token 数量、字符数、词数、行数、模型上下文窗口占用比例，以及不同 AI 模型的大致输入 / 输出费用。

**Global AI Token Counter** is a lightweight, frontend-only AI token counter and text analysis tool.

It helps users estimate token usage, character count, word count, line count, context window usage, and approximate input/output costs for different AI models.

无需后端。无需数据库。无需复杂部署。  
No backend. No database. No complex deployment.

---

## Features / 功能亮点

| 功能 | Description |
|---|---|
| Token 计数 | Estimate token usage for AI prompts |
| 字符统计 | Count characters |
| 词汇统计 | Count words |
| 行数统计 | Count lines |
| 模型费用预估 | Estimate input, output, and total cost |
| 上下文窗口用量 | Show context window usage percentage |
| 全球模型列表 | Load global AI model information |
| AI 文本分析 | Generate short AI-powered text analysis |
| 深色 / 浅色主题 | Support dark and light themes |
| 单文件部署 | Deploy as a single static HTML file |

---

## Supported Languages / 支持语言

This tool can be used with text from many languages around the world.

本工具可用于分析多种全球语言文本，包括但不限于：

| Region | Languages |
|---|---|
| East Asia | 中文, 日本語, 한국어 |
| Europe | English, Français, Deutsch, Italiano, Español, Português |
| Eastern Europe | Русский, Українська, Polski |
| Middle East | العربية, فارسی, עברית |
| South Asia | हिन्दी, বাংলা, தமிழ், తెలుగు |
| Southeast Asia | Tiếng Việt, ไทย, Bahasa Indonesia, Bahasa Melayu |
| Others | Türkçe, Nederlands, Ελληνικά, Svenska |

---

## Use Cases / 使用场景

- 估算 AI 提示词 Token 数量
- 计算不同模型的大致使用成本
- 检查文本是否接近模型上下文限制
- 分析多语言文本长度和复杂度
- 对比不同 AI 模型的输入输出费用
- 写 Prompt、文章、翻译内容、代码说明前进行预估
- 了解文本在 AI 模型中的大致消耗

---

## How It Works / 工作原理

本项目主要由浏览器前端完成运行。

The project mainly runs in the browser.

基础文本统计会在本地完成，例如：

- 字符数
- 词数
- 行数
- Token 数量
- 上下文窗口占用
- 费用预估

部分高级功能会请求第三方公共服务，例如模型列表加载和 AI 文本分析。

Some advanced features may request public third-party services, such as model list loading and AI-powered text analysis.

---

## Tech Stack / 技术栈

- HTML
- CSS
- JavaScript
- GitHub Pages
- Browser local execution
- Public model data API
- Public AI text analysis endpoint

This project is designed as a static web app.  
It can run directly in a browser without any build step.

---

## Deployment / 部署方式

You can deploy this project directly with **GitHub Pages**.

你可以直接使用 **GitHub Pages** 部署本项目。

### Steps / 步骤

1. Rename the main HTML file to:

```text
index.html

---

## Privacy Notice / 隐私声明

This project includes a dedicated privacy policy file.

本项目已提供单独的隐私声明文件。

Please read the [Privacy Policy](./PRIVACY.md) before using or deploying this project.

在使用或部署本项目之前，请阅读 [隐私声明](./PRIVACY.md)。

The privacy policy explains how this project handles local processing, third-party requests, AI text analysis, browser local storage, and GitHub Pages hosting.

该隐私声明说明了本项目如何处理本地计算、第三方请求、AI 文本分析、浏览器本地存储以及 GitHub Pages 托管相关内容。

Users should avoid submitting passwords, API keys, identity information, private conversations, business secrets, unpublished code, or other sensitive content to public AI analysis features.

用户应避免向公共 AI 分析功能提交密码、API Key、身份信息、私人聊天记录、商业机密、未公开代码或其他敏感内容。