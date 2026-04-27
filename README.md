# Global AI Token Counter
## 全球 AI Token 计数器

> Count tokens. Estimate costs. Analyze text. Across global languages.
> 统计 Token，估算成本，分析文本，支持全球语言。

---

## Overview / 项目简介

**Global AI Token Counter** 是一个轻量级、纯前端的 AI Token 计数与文本分析工具。

它可以帮助用户快速统计文本的 Token 数量、字符数、词数、行数，查看模型上下文窗口占用比例，并估算不同 AI 模型的大致输入 / 输出费用。

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
| 全球模型列表 | Load public AI model information |
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
- 计算不同 AI 模型的大致使用成本
- 检查文本是否接近模型上下文限制
- 分析多语言文本长度和复杂度
- 对比不同模型的输入 / 输出费用
- 写 Prompt、文章、翻译内容、代码说明前进行预估
- 了解文本在 AI 模型中的大致消耗
- 快速判断长文本是否适合直接提交给大模型

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
- 主题偏好保存

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

The privacy policy explains how this project handles:

隐私声明会说明本项目如何处理：

- Local processing / 本地计算
- Third-party requests / 第三方请求
- AI text analysis / AI 文本分析
- Browser local storage / 浏览器本地存储
- GitHub Pages hosting / GitHub Pages 托管

Users should avoid submitting sensitive content to public AI analysis features.

用户应避免向公共 AI 分析功能提交敏感内容，例如：

- Passwords / 密码
- API keys / API 密钥
- Identity information / 身份信息
- Bank card information / 银行卡信息
- Private conversations / 私人聊天记录
- Business secrets / 商业机密
- Unpublished code / 未公开代码
- Confidential documents / 机密文档
```

---

## Disclaimer / 免责声明

This project is provided for learning, testing, and general reference purposes only.

本项目仅用于学习、测试和一般参考用途。

The token count, context usage, and cost estimation results are provided as estimates. Actual results may vary depending on the specific AI model, tokenizer, provider pricing, API changes, and service rules.

Token 数量、上下文窗口占用和费用预估结果仅供参考。实际结果可能会因具体 AI 模型、分词器、服务商价格、API 变化和平台规则而不同。

This project does not guarantee the accuracy, completeness, availability, or reliability of any calculation result, model data, third-party API response, or AI-generated analysis.

本项目不保证任何计算结果、模型数据、第三方 API 响应或 AI 生成分析内容的准确性、完整性、可用性或可靠性。

Some features may depend on third-party services, including but not limited to font loading, CDN scripts, public model data APIs, and public AI analysis endpoints.

部分功能可能依赖第三方服务，包括但不限于字体加载、CDN 脚本、公开模型数据 API 和公共 AI 分析接口。

These services are controlled by their respective providers, not by this project.

这些服务由对应服务商控制，并不由本项目控制。

The project author is not responsible for any data loss, privacy risk, service interruption, inaccurate result, cost difference, or other damage caused by using, modifying, deploying, or relying on this project.

项目作者不对因使用、修改、部署或依赖本项目而导致的数据丢失、隐私风险、服务中断、结果不准确、费用差异或其他损失负责。

Users and deployers are responsible for reviewing the source code, third-party services, privacy policy, and legal requirements before using or deploying this project.

用户和部署者在使用或部署本项目之前，应自行检查源代码、第三方服务、隐私声明和相关法律要求。

This disclaimer is not legal advice.

本免责声明不构成法律建议。

---

## Project Structure / 项目结构

```text
.
├── index.html
├── README.md
├── PRIVACY.md
└── LICENSE

---

## Roadmap / 后续计划

- [ ] Add more tokenizer options
- [ ] Add local-only mode
- [ ] Add export results feature
- [ ] Add more model filters
- [ ] Improve mobile UI
- [ ] Add more language-specific analysis options
- [ ] Add optional offline privacy mode
- [ ] Add copy result button

---

## License / 开源协议

This project is licensed under the **GPL-3.0 License**.

本项目使用 **GPL-3.0** 开源协议。

---

## Support / 支持项目

If this project is useful to you, consider giving it a star.

如果这个项目对你有帮助，可以点一个 Star 支持一下。

---

## Short Description / 仓库简介


A lightweight global AI Token counter with model pricing, context usage, multilingual text analysis, and GitHub Pages deployment.

一个轻量级全球 AI Token 计数器，支持模型价格预估、上下文窗口用量分析、多语言文本分析，并可直接部署到 GitHub Pages。