# Privacy Policy
## 隐私声明

Last updated: 2026-04-27

This Privacy Policy explains how **Global AI Token Counter** handles user data.

本隐私声明说明 **Global AI Token Counter / 全球 AI Token 计数器** 如何处理用户数据。

---

## 1. Overview / 概述

**Global AI Token Counter** is a frontend-only static web tool.

**Global AI Token Counter / 全球 AI Token 计数器** 是一个纯前端静态网页工具。

This project is designed to help users count tokens, estimate AI model costs, check context window usage, and generate short text analysis reports.

本项目用于帮助用户统计 Token、估算 AI 模型费用、查看上下文窗口占用，并生成简短的文本分析报告。

The project itself does not require:

本项目本身不需要：

- Account registration / 注册账户
- Login / 登录
- Email address / 邮箱地址
- User profile / 用户资料
- Custom backend server / 自建后端服务器
- Custom database / 自建数据库

---

## 2. Local Processing / 本地处理

Most basic calculations are performed locally in the user's browser.

大多数基础计算会在用户自己的浏览器中本地完成。

Locally processed data may include:

本地处理的数据可能包括：

- Character count / 字符数统计
- Word count / 词汇数统计
- Line count / 行数统计
- Token count / Token 数量统计
- Context window usage / 上下文窗口占用比例
- Estimated input cost / 输入费用预估
- Estimated output cost / 输出费用预估
- Estimated total cost / 总费用预估
- Theme preference / 主题偏好

These calculations are not sent to the project author.

这些基础计算结果不会发送给项目作者。

---

## 3. User Input / 用户输入内容

Users may paste text into the input box for token counting and text analysis.

用户可以将文本粘贴到输入框中，用于 Token 统计和文本分析。

For local statistics, the text is processed in the browser.

对于本地统计功能，文本会在浏览器中处理。

However, if the user clicks the AI analysis button, part of the input text may be sent to a public third-party AI service to generate a short analysis report.

但是，如果用户点击 AI 分析按钮，部分输入文本可能会被发送到公共第三方 AI 服务，用于生成简短分析报告。

In the current implementation, the AI analysis feature may send a shortened version of the input text to a public AI endpoint.

在当前实现中，AI 分析功能可能会将输入文本的截取内容发送到公共 AI 接口。

---

## 4. Third-Party Services / 第三方服务

This project may request third-party services to provide some features.

本项目可能会请求第三方服务以实现部分功能。

| Service | Purpose |
|---|---|
| Google Fonts | Load web fonts / 加载网页字体 |
| jsDelivr CDN | Load tokenizer-related script / 加载 tokenizer 相关脚本 |
| OpenRouter API | Load public AI model list and pricing data / 获取公开 AI 模型列表和价格信息 |
| Pollinations AI | Generate short AI text analysis / 生成简短 AI 文本分析报告 |

These third-party services may receive standard browser request information, such as:

这些第三方服务可能会接收常规浏览器请求信息，例如：

- IP address / IP 地址
- Browser type / 浏览器类型
- User agent / 用户代理信息
- Request time / 请求时间
- Referrer / 来源页面
- Requested URL / 请求地址

The handling of this information is controlled by the privacy policies of those third-party services.

这些信息的处理方式由对应第三方服务自己的隐私政策决定。

---

## 5. AI Text Analysis / AI 文本分析

When AI text analysis is used, part of the user's input may be sent to a public AI endpoint.

当用户使用 AI 文本分析功能时，用户输入内容的一部分可能会被发送到公共 AI 接口。

This is used only to generate a short text analysis result.

该功能仅用于生成简短的文本分析结果。

Users should not submit sensitive or private information to the AI analysis feature.

用户不应向 AI 分析功能提交敏感或隐私内容。

Please do not submit:

请不要提交：

- Passwords / 密码
- API keys / API 密钥
- Access tokens / 访问令牌
- Private keys / 私钥
- Identity documents / 身份证件信息
- Bank card information / 银行卡信息
- Phone numbers / 手机号
- Personal addresses / 个人住址
- Private conversations / 私人聊天记录
- Business secrets / 商业机密
- Unpublished code / 未公开代码
- Confidential documents / 机密文档
- Any other sensitive information / 其他敏感信息

---

## 6. Local Storage / 本地存储

This project may use browser localStorage to save user preferences.

本项目可能会使用浏览器 localStorage 保存用户偏好设置。

Currently, this may include:

目前可能包括：

- Dark mode or light mode preference / 深色或浅色主题偏好

This data is stored only in the user's browser.

这些数据只保存在用户自己的浏览器中。

The project itself does not upload these preferences to the project author.

本项目本身不会将这些偏好设置上传给项目作者。

Users can clear this data by clearing browser site data.

用户可以通过清除浏览器网站数据来删除这些本地数据。

---

## 7. No Account System / 无账户系统

This project does not provide its own account system.

本项目不提供自己的账户系统。

The project itself does not collect:

本项目本身不会收集：

- Real names / 真实姓名
- Email addresses / 邮箱地址
- Account passwords / 账户密码
- User avatars / 用户头像
- User profiles / 用户资料

---

## 8. No Project-Owned Database / 无项目自建数据库

This project does not operate a custom backend database for storing user input.

本项目没有自建后端数据库用于保存用户输入内容。

The project author does not actively store user-submitted text through this project.

项目作者不会通过本项目主动保存用户提交的文本。

---

## 9. No Tracking by This Project / 本项目不主动追踪

This project itself does not actively:

本项目本身不会主动：

- Track users across websites / 跨网站追踪用户
- Create advertising profiles / 创建广告画像
- Sell user data / 出售用户数据
- Store user input on a project-owned server / 在项目自有服务器保存用户输入
- Collect real identity information / 收集真实身份信息
- Require login / 要求登录

However, third-party services used by the project may process standard technical request data according to their own policies.

但是，本项目使用的第三方服务可能会根据其自身政策处理常规技术请求数据。

---

## 10. GitHub Pages Hosting / GitHub Pages 托管

If this project is deployed on GitHub Pages, the website is hosted through GitHub's infrastructure.

如果本项目部署在 GitHub Pages 上，网站会通过 GitHub 的基础设施进行托管。

GitHub may process standard access logs and network request information according to its own policies.

GitHub 可能会根据其自身政策处理标准访问日志和网络请求信息。

The project author does not control GitHub's infrastructure-level logging.

项目作者无法控制 GitHub 基础设施层面的日志记录。

---

## 11. Security Notice / 安全提示

This tool is intended for normal text, public content, test prompts, and non-sensitive analysis.

本工具适合用于普通文本、公开内容、测试 Prompt 和非敏感分析。

For sensitive content, users should consider:

对于敏感内容，用户应考虑：

- Using a fully offline local tool / 使用完全离线的本地工具
- Removing private information before analysis / 分析前删除隐私信息
- Avoiding the AI analysis feature / 避免使用 AI 分析功能
- Reviewing the source code before deployment / 部署前自行检查源代码

---

## 12. Children's Privacy / 儿童隐私

This project is not specifically designed for children.

本项目并非专门面向儿童设计。

The project itself does not knowingly collect personal information from children.

本项目本身不会故意收集儿童个人信息。

---

## 13. Changes to This Policy / 政策变更

This Privacy Policy may be updated from time to time.

本隐私声明可能会不定期更新。

If the project adds new features that affect privacy, this document should be updated accordingly.

如果项目新增影响隐私的功能，应同步更新本文档。

---

## 14. Contact / 联系方式

If users have privacy-related questions, they can open an issue in this repository.

如果用户有隐私相关问题，可以在本仓库中提交 Issue。

---

## 15. Disclaimer / 免责声明

This Privacy Policy is provided for transparency and general information.

本隐私声明用于提高透明度并提供一般说明。

It is not legal advice.

本文档不构成法律建议。

Users and deployers should review the code and third-party services before using or deploying this project.

用户和部署者在使用或部署本项目之前，应自行检查代码和第三方服务。