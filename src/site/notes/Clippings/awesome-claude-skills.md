---
{"dg-publish":true,"permalink":"/Clippings/awesome-claude-skills/","title":"awesome-claude-skills","tags":["clippings"],"dg-note-properties":{"title":"awesome-claude-skills","source":"https://github.com/ComposioHQ/awesome-claude-skills","author":null,"published":null,"created":"2026-10-12","description":null,"tags":["clippings"]}}
---

## Awesome Claude Skills克劳德的技能太棒了

[![Composio banner](https://private-user-images.githubusercontent.com/67639393/534448770-e91255af-e4ba-4d71-b1a8-bd081e8a234a.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTE3MzUzMDgsIm5iZiI6MTc5MTczNTAwOCwicGF0aCI6Ii82NzYzOTM5My81MzQ0NDg3NzAtZTkxMjU1YWYtZTRiYS00ZDcxLWIxYTgtYmQwODFlOGEyMzRhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjEwMTElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYxMDExVDE2MTAwOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWIyMTFkNDBmZTRjNjJiZDExMjM5M2Q5MDAzYTJjY2M4MTg1ODc5NTg3ZjJhM2NkNGYzNmNlY2JkZWYyNmEwZTMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.-qsknjAIpYz9U_D53dvCGWZ5vXUKuF4CRj7WTwA4sMQ)](https://dashboard.composio.dev/login?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills)

A comprehensive and curated list of 1000+ production ready and practical Claude Skills and Plugins for enhancing productivity across usecases on not just Claude.ai, Claude Code, but also across coding agents like Codex, Cursor, Gemini CLI, Antigravity and more.  
一份全面且精心挑选的列表，包含 1000 多个可用于生产环境且实用的 Claude 技能和插件，可提高各种用例的生产力，不仅适用于 Claude.ai、Claude Code，还适用于 Codex、Cursor、Gemini CLI、Antigravity 等编码代理。

## Give your skills real-world actions将你的技能应用于实际行动中

Skills tell your agent **how** to work. An MCP Gateway gives it secure access to the tools it needs.  
技能决定了代理 **如何** 工作。MCP 网关为其提供对所需工具的安全访问权限。

Composio [MCP Gateway](https://composio.dev/mcp-gateway) provides a single MCP endpoint for 1,000+ integrations with built-in authentication, team-based access controls, audit logs, and production-ready reliability.  
Composio [MCP Gateway](https://composio.dev/mcp-gateway) 为 1,000 多个集成提供了一个单一的 MCP 端点，并内置了身份验证、基于团队的访问控制、审计日志和生产就绪的可靠性。

---

## Quickstart: Connect Claude to 1000+ Apps快速入门：将 Claude 连接到 1000 多个应用程序

The **connect-apps** plugin lets Claude perform real actions - send emails, create issues, post to Slack. It handles auth and connects to 1000+ apps using Composio under the hood.  
**connect-apps** 插件让 Claude 可以执行实际操作——发送电子邮件、创建问题、发布到 Slack。它底层使用 Composio 处理身份验证并连接到 1000 多个应用程序。

### 1\. Install the Plugin1. 安装插件

```
claude --plugin-dir ./connect-apps-plugin
```

### 2\. Run Setup2. 运行安装程序

```
/connect-apps:setup
```

Paste your API key when asked. (Get a free key at [dashboard.composio.dev](https://dashboard.composio.dev/login?utm_source=Github&utm_content=AwesomeSkills))  
出现提示时，请粘贴您的 API 密钥。（您可以在 [dashboard.composio.dev](https://dashboard.composio.dev/login?utm_source=Github&utm_content=AwesomeSkills) 免费获取密钥）

### 3\. Restart & Try It3. 重新启动并尝试

```
exit
claude
```

> **Want skills that do more than generate text?** Claude can send emails, create issues, post to Slack, and take actions across 1000+ apps. [See how →](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/connect)  
> **想要功能更强大的技能，而不仅仅是生成文本？** Claude 可以发送电子邮件、创建问题、在 Slack 上发布内容，并在 1000 多个应用程序中执行操作。 [了解详情 →](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/connect)

If you receive the email, Claude is now connected to 1000+ apps.  
如果您收到此邮件，则表示 Claude 现在已连接到 1000 多个应用程序。

**[See all supported apps →  
查看所有支持的应用 →](https://composio.dev/toolkits)**

---

## Contents内容

## What Are Claude Skills?克劳德的技能有哪些？

Claude Skills are reusable instruction packages that teach an AI agent how to handle a specific class of tasks. Each skill is a folder containing a `SKILL.md` file with YAML frontmatter (name, description) and Markdown instructions, optionally bundled with scripts, references, and assets. Anthropic introduced the format in October 2025 and released it as an [open standard](https://github.com/anthropics/skills) in December 2025; it's now supported by Claude Code, Claude.ai, the Claude API, OpenAI Codex, Cursor, Gemini CLI, Antigravity, and Windsurf.  
Claude 技能是可重用的指令包，用于教导 AI 代理如何处理特定类型的任务。每个技能都是一个文件夹，其中包含一个 `SKILL.md` 文件，该文件包含 YAML 格式的前置信息（名称、描述）和 Markdown 格式的指令，还可以选择性地捆绑脚本、参考资料和资源。Anthropic 于 2025 年 10 月推出了该格式，并于 2025 年 12 月将其作为 [开放标准](https://github.com/anthropics/skills) 发布；目前，Claude Code、Claude.ai、Claude API、OpenAI Codex、Cursor、Gemini CLI、Antigravity 和 Windsurf 均支持该格式。

---

Skills load progressively. At session start, the agent sees only each skill's name and description — roughly 100 tokens per skill. The full SKILL.md body (typically under 5,000 tokens) loads only when the agent decides the skill is relevant to the current task.  
技能会逐步加载。会话开始时，智能体只能看到每个技能的名称和描述——每个技能大约 100 个标记。完整的 SKILL.md 文件内容（通常少于 5000 个标记）只有在智能体判断该技能与当前任务相关时才会加载。  
Auxiliary files in `scripts/` and `references/` load on demand. This is what lets a single agent host hundreds of skills without bloating its context window.  
`scripts/` 和 `references/` 中的辅助文件按需加载。这使得单个代理可以承载数百种技能，而不会使其上下文窗口变得臃肿。

---

Skills are not MCP servers and not tools. MCP defines how an agent connects to external systems — auth, transport, tool discovery. Tools are the individual functions an agent invokes.  
技能并非 MCP 服务器，也不是工具。MCP 定义了代理如何连接到外部系统——包括身份验证、传输和工具发现。工具则是代理调用的具体功能。  
Skills define the workflow — what to do, in what order, with what guardrails — once the agent has the connections and tools it needs. In production, all three layers run together: MCP for access, tools for actions, skills for behavior.  
技能定义了工作流程——代理拥有所需的连接和工具后，应该做什么、按什么顺序做、以及遵循哪些安全规则。在生产环境中，这三个层协同运行：MCP 用于访问控制，工具用于执行操作，技能用于行为控制。

---

## Skills技能

### Document Processing文档处理

- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - Create, edit, analyze Word docs with tracked changes, comments, formatting.  
	[docx](https://github.com/anthropics/skills/tree/main/skills/docx) - 创建、编辑、分析带有跟踪更改、注释和格式的 Word 文档。
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - Extract text, tables, metadata, merge & annotate PDFs.  
	[pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - 提取文本、表格、元数据，合并和注释 PDF。
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - Read, generate, and adjust slides, layouts, templates.  
	[pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - 读取、生成和调整幻灯片、布局、模板。
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - Spreadsheet manipulation: formulas, charts, data transformations.  
	[xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - 电子表格操作：公式、图表、数据转换。
- [Markdown to EPUB Converter](https://github.com/smerchek/claude-epub-skill) - Converts markdown documents and chat summaries into professional EPUB ebook files. *By [@smerchek](https://github.com/smerchek)*  
	[Markdown 转 EPUB 转换器](https://github.com/smerchek/claude-epub-skill) - 将 Markdown 文档和聊天记录摘要转换为专业的 EPUB 电子书文件。 *作者： [@smerchek](https://github.com/smerchek)*

---

- [Master Claude for Legal](https://github.com/sboghossian/master-claude-for-legal) - Skill pack for legal teams. NDA triage, multi-party version diff, citation verifier, meeting brief, and the Friday-newsletter status synthesis pattern. Includes 10 reference docs (privilege, verification, long documents, practice areas) and 3 firm templates.  
	[Master Claude for Legal——](https://github.com/sboghossian/master-claude-for-legal) 法律团队技能包。包含保密协议分类、多方版本差异分析、引文验证、会议简报撰写以及周五简报状态汇总模式。内含 10 份参考文档（特权、验证、长篇文档、业务领域）和 3 个律所模板。  
	Built from the public Anthropic Claude for Legal Teams webinar dataset.*By [@sboghossian](https://github.com/sboghossian)*  
	基于公开的 Anthropico Claude for Legal Teams 网络研讨会数据集构建。 *作者： [@sboghossian](https://github.com/sboghossian)*

---

### Development & Code Tools开发和代码工具

- [artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) - Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui).  
	[artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) - 一套使用现代前端 Web 技术（React、Tailwind CSS、shadcn/ui）创建复杂的多组件 claude.ai HTML 工件的工具。
- [aws-skills](https://github.com/zxkane/aws-skills) - AWS development with CDK best practices, cost optimization MCP servers, and serverless/event-driven architecture patterns.  
	[aws-skills](https://github.com/zxkane/aws-skills) - 使用 CDK 最佳实践、成本优化 MCP 服务器以及无服务器/事件驱动架构模式进行 AWS 开发。
- [building-blog](https://github.com/BuildShipGrowRepeat/nextjs-sanity-blog-skill) - Adds an SEO-first, i18n-ready blog to a Next.js + Sanity site via a 40-question intake, a one-page plan, and a 20-section spec. Includes a generator for AI hero images via Gemini 3 Pro Image (Nano Banana Pro). *By [@BuildShipGrowRepeat](https://github.com/BuildShipGrowRepeat)*  
	[building-blog](https://github.com/BuildShipGrowRepeat/nextjs-sanity-blog-skill) - 通过 40 个问题的问卷调查、一页纸的计划和 20 个章节的规范，为基于 Next.js + Sanity 的网站添加一个 SEO 优先、国际化 (i18n) 就绪的博客。包含一个使用 Gemini 3 Pro Image (Nano Banana Pro) 生成 AI 首页图片的生成器。 *作者： [@BuildShipGrowRepeat](https://github.com/BuildShipGrowRepeat)*
- [Changelog Generator](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/changelog-generator) - Automatically creates user-facing changelogs from git commits by analyzing history and transforming technical commits into customer-friendly release notes.  
	[变更日志生成器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/changelog-generator) - 通过分析历史记录并将技术提交转换为客户友好的发布说明，自动从 git 提交创建面向用户的变更日志。
- [Chrome Relay](https://chrome-relay.kushalsm.com/) - Drives the user's already-open Chrome session — cookies, SSO, extensions, localhost — through a local CLI bridge. Real-Chrome counterpart to Playwright Browser Automation; install via `npx skills add chrome-relay` + a [Chrome Web Store extension](https://chromewebstore.google.com/detail/chrome-relay/cpdiapbifblhlcpnmlmfpgfjlacebokb). No remote relay, no Playwright fixtures, no MCP server needed.  
	[Chrome Relay](https://chrome-relay.kushalsm.com/) - 通过本地 CLI 桥接器驱动用户已打开的 Chrome 会话（包括 cookie、SSO、扩展程序和本地主机）。它是 Playwright Browser Automation 的 Chrome 版本；可通过 `npx skills add chrome-relay` 和 [Chrome 网上应用商店扩展程序](https://chromewebstore.google.com/detail/chrome-relay/cpdiapbifblhlcpnmlmfpgfjlacebokb) 进行安装。无需远程中继、Playwright fixtures 或 MCP 服务器。
- [Claude Code Terminal Title](https://github.com/bluzername/claude-code-terminal-title) - Gives each Claud-Code terminal window a dynamic title that describes the work being done so you don't lose track of what window is doing what.  
	[Claude Code 终端标题](https://github.com/bluzername/claude-code-terminal-title) - 为每个 Claud-Code 终端窗口赋予一个动态标题，描述正在执行的工作，这样您就不会忘记哪个窗口正在执行什么操作。
- [Connect](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/connect) - Connect Claude to any app. Send emails, create issues, post messages, update databases - take real actions across Gmail, Slack, GitHub, Notion, and 1000+ services.  
	[连接](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/connect) - 将 Claude 连接到任何应用程序。发送电子邮件、创建问题、发布消息、更新数据库 - 在 Gmail、Slack、GitHub、Notion 和 1000 多个服务中执行实际操作。
- [D3.js Visualization](https://github.com/chrisvoncsefalvay/claude-d3js-skill) - Teaches Claude to produce D3 charts and interactive data visualizations. *By [@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay)*  
	[D3.js 可视化](https://github.com/chrisvoncsefalvay/claude-d3js-skill) - 教 Claude 制作 D3 图表和交互式数据可视化。 *作者： [@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay)*
- [FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) - Integrates the ffuf web fuzzer so Claude can run fuzzing tasks and analyze results for vulnerabilities. *By [@jthack](https://github.com/jthack)*  
	[FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) - 集成了 ffuf Web Fuzzer，使 Claude 能够运行模糊测试任务并分析结果以发现漏洞。 *作者： [@jthack](https://github.com/jthack)*
- [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - Guides completion of development work by presenting clear options and handling chosen workflow.  
	[完成开发分支](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - 通过提供清晰的选项和处理选定的工作流程来指导开发工作的完成。
- [Full-Page Screenshot](https://github.com/LewisLiu007/full-page-screenshot) - Captures full-page screenshots of web pages via Chrome DevTools Protocol with zero dependencies. *By [@LewisLiu007](https://github.com/LewisLiu007)*  
	[全页面截图](https://github.com/LewisLiu007/full-page-screenshot) - 通过 Chrome 开发者工具协议捕获网页全页面截图，无需任何依赖项。 *作者： [@LewisLiu007](https://github.com/LewisLiu007)*

---

- [great\_cto](https://github.com/avelikiy/great_cto) - Claude Code plugin: 7 specialised subagents (tech-lead, senior-dev, qa-engineer, security-officer, devops, l3-support, project-auditor) orchestrating a full SDLC pipeline — architecture, TDD, 12-angle code review, QA, security audit, deploy.  
	[great\_cto](https://github.com/avelikiy/great_cto) - Claude Code 插件：7 个专业子代理（技术主管、高级开发人员、质量保证工程师、安全官、DevOps、L3 支持、项目审计员）协调完整的 SDLC 管道——架构、TDD、12 角度代码审查、质量保证、安全审计、部署。  
	11 project archetypes auto-detected, 13 compliance frameworks (GDPR/PCI-DSS/HIPAA/SOC2/ISO 27001), self-improving knowledge layer that learns from every incident.*By [@avelikiy](https://github.com/avelikiy)*  
	自动检测 11 种项目原型，支持 13 种合规框架（GDPR/PCI-DSS/HIPAA/SOC2/ISO 27001），并拥有可从每次事件中学习的自我改进知识层。 *作者： [@avelikiy](https://github.com/avelikiy)*

---

- [iOS Simulator](https://github.com/conorluddy/ios-simulator-skill) - Enables Claude to interact with iOS Simulator for testing and debugging iOS applications. *By [@conorluddy](https://github.com/conorluddy)*  
	[iOS 模拟器](https://github.com/conorluddy/ios-simulator-skill) - 使 Claude 能够与 iOS 模拟器交互，以便测试和调试 iOS 应用程序。 *作者： [@conorluddy](https://github.com/conorluddy)*
- [jules](https://github.com/sanjay3290/ai-skills/tree/main/skills/jules) - Delegate coding tasks to Google Jules AI agent for async bug fixes, documentation, tests, and feature implementation on GitHub repos. *By [@sanjay3290](https://github.com/sanjay3290)*  
	[Jules](https://github.com/sanjay3290/ai-skills/tree/main/skills/jules) - 将编码任务委托给 Google Jules AI 代理，用于 GitHub 代码库中的异步错误修复、文档编写、测试和功能实现。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [LangSmith Fetch](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/langsmith-fetch) - Debug LangChain and LangGraph agents by automatically fetching and analyzing execution traces from LangSmith Studio. First AI observability skill for Claude Code. *By [@OthmanAdi](https://github.com/OthmanAdi)*  
	[LangSmith Fetch](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/langsmith-fetch) - 通过自动从 LangSmith Studio 获取和分析执行轨迹，调试 LangChain 和 LangGraph 代理。首个面向 Claude Code 的 AI 可观测性技能。 *作者： [@OthmanAdi](https://github.com/OthmanAdi)*
- [lean-ctx](https://github.com/yvgude/lean-ctx) - MCP server and context runtime for AI coding agents: session caching, AST-aware compression, and 90+ shell patterns to reduce token usage. Supports Claude Code, Cursor, Copilot, and other integrations. Install the Claude Code skill with `lean-ctx init --agent claude-code`; docs at [leanctx.com](https://leanctx.com/). *By [@yvgude](https://github.com/yvgude)*  
	[lean-ctx](https://github.com/yvgude/lean-ctx) 是一个面向 AI 编码代理的 MCP 服务器和上下文运行时环境：支持会话缓存、AST 感知压缩以及 90 多种 shell 模式，可减少令牌使用。支持 Claude Code、Cursor、Copilot 和其他集成。使用 `lean-ctx init --agent claude-code` 安装 Claude Code 技能；文档请访问 [leanctx.com](https://leanctx.com/) 。 *作者： [@yvgude](https://github.com/yvgude)*
- [MCP Builder](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/mcp-builder) - Guides creation of high-quality MCP (Model Context Protocol) servers for integrating external APIs and services with LLMs using Python or TypeScript.  
	[MCP Builder](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/mcp-builder) - 指导使用 Python 或 TypeScript 创建高质量的 MCP（模型上下文协议）服务器，以便将外部 API 和服务与 LLM 集成。
- [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - Analyzes Move language packages against the official Move Book Code Quality Checklist for Move 2024 Edition compliance and best practices.  
	[move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - 根据官方的 Move Book 代码质量检查表分析 Move 语言包，以确保其符合 Move 2024 版的合规性和最佳实践。
- [OpenWeb](https://github.com/openweb-org/openweb) - Agent-native way to access any website. Calls the same APIs the website calls (JSON in, JSON out) with auth (cookies, JWT, CSRF, signing) auto-resolved per request. 90+ sites built in. *By [@openweb-org](https://github.com/openweb-org)*  
	[OpenWeb——](https://github.com/openweb-org/openweb) 一种以代理原生方式访问任何网站的方法。它调用网站使用的相同 API（JSON 输入，JSON 输出），并自动解析每个请求的身份验证（cookie、JWT、CSRF、签名）。内置 90 多个网站。 *由 [@openweb-org](https://github.com/openweb-org)* 开发
- [overkill](https://github.com/santiago-vargas-de-kruijf/claude-overkill) - Surfaces advanced, maximalist alternatives to whatever solution is being discussed — advanced data structures, distributed-systems algorithms, niche frameworks, design patterns, and frontier tooling — each ranked on a calibrated complexity scale with learning links and the scenario in which the path pays off.*By [@santiago-vargas-de-kruijf](https://github.com/santiago-vargas-de-kruijf)*  
	[过度设计](https://github.com/santiago-vargas-de-kruijf/claude-overkill) ——针对正在讨论的解决方案，提出各种先进且极致的替代方案，包括高级数据结构、分布式系统算法、小众框架、设计模式和前沿工具——每项方案都按照校准后的复杂度等级进行排名，并附有学习链接和适用场景。 *作者： [@santiago-vargas-de-kruijf](https://github.com/santiago-vargas-de-kruijf)*
- [Playwright Browser Automation](https://github.com/lackeyjb/playwright-skill) - Model-invoked Playwright automation for testing and validating web applications. *By [@lackeyjb](https://github.com/lackeyjb)*  
	[Playwright 浏览器自动化](https://github.com/lackeyjb/playwright-skill) - 基于模型调用的 Playwright 自动化，用于测试和验证 Web 应用程序。 *作者： [@lackeyjb](https://github.com/lackeyjb)*
- [prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) - Teaches well-known prompt engineering techniques and patterns, including Anthropic best practices and agent persuasion principles.  
	[提示工程](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) - 教授众所周知的提示工程技术和模式，包括人因工程最佳实践和代理说服原则。
- [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - Design comprehensive test cases using PICT (Pairwise Independent Combinatorial Testing) for requirements or code, generating optimized test suites with pairwise coverage.  
	[pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - 使用 PICT（成对独立组合测试）为需求或代码设计全面的测试用例，生成具有成对覆盖率的优化测试套件。
- [reddit-fetch](https://github.com/ykdojo/claude-code-tips/tree/main/skills/reddit-fetch) - Fetches Reddit content via Gemini CLI when WebFetch is blocked or returns 403 errors.  
	[reddit-fetch](https://github.com/ykdojo/claude-code-tips/tree/main/skills/reddit-fetch) - 当 WebFetch 被阻止或返回 403 错误时，通过 Gemini CLI 获取 Reddit 内容。
- [Septim Agents Pack](https://septimlabs.com/tools/agents?utm_source=awesome-claude-skills&utm_medium=awesome-list&utm_campaign=oss-backlink) - 10 named Claude Code sub-agents (Atlas, Luca, Canon, Ember, Tally, Nova, Ward, Mira, Juno, Pip) covering planning, architecture, brand, marketing, finance, design, legal, customer, research, and coordination. Drop into `.claude/agents/`. *By [@septimlabs-code](https://github.com/septimlabs-code)*  
	[Septim Agents Pack](https://septimlabs.com/tools/agents?utm_source=awesome-claude-skills&utm_medium=awesome-list&utm_campaign=oss-backlink) - 包含 10 个以 Claude Code 命名的子代理（Atlas、Luca、Canon、Ember、Tally、Nova、Ward、Mira、Juno、Pip），涵盖规划、建筑、品牌、市场营销、财务、设计、法律、客户、研究和协调等领域。请将文件放入 `.claude/agents/` 目录。 *作者： [@septimlabs-code](https://github.com/septimlabs-code)*
- [Skill Creator](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/skill-creator) - Provides guidance for creating effective Claude Skills that extend capabilities with specialized knowledge, workflows, and tool integrations.  
	[技能创建器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/skill-creator) - 提供指导，帮助创建有效的 Claude 技能，通过专业知识、工作流程和工具集成来扩展功能。
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - Automatically converts any documentation website into a Claude AI skill in minutes. *By [@yusufkaraaslan](https://github.com/yusufkaraaslan)*  
	[Skill Seekers——](https://github.com/yusufkaraaslan/Skill_Seekers) 只需几分钟即可将任何文档网站自动转换为 Claude AI 技能。 *作者： [@yusufkaraaslan](https://github.com/yusufkaraaslan)*
- [software-architecture](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) - Implements design patterns including Clean Architecture, SOLID principles, and comprehensive software design best practices.  
	[软件架构](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) - 实现包括整洁架构、SOLID 原则和综合软件设计最佳实践在内的设计模式。
- [subagent-driven-development](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) - Dispatches independent subagents for individual tasks with code review checkpoints between iterations for rapid, controlled development.  
	[子代理驱动开发](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) - 为各个任务调度独立的子代理，并在迭代之间设置代码审查检查点，以实现快速、可控的开发。
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - Use when implementing any feature or bugfix, before writing implementation code.  
	[测试驱动开发](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - 在编写实现代码之前，用于实现任何功能或错误修复。
- [using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) - Creates isolated git worktrees with smart directory selection and safety verification.  
	[using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) - 创建具有智能目录选择和安全验证的隔离 git 工作树。
- [Webapp Testing](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/webapp-testing) - Tests local web applications using Playwright for verifying frontend functionality, debugging UI behavior, and capturing screenshots.  
	[Web 应用程序测试](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/webapp-testing) - 使用 Playwright 测试本地 Web 应用程序，以验证前端功能、调试 UI 行为和捕获屏幕截图。

### Data & Analysis数据与分析

- [CSV Data Summarizer](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - Automatically analyzes CSV files and generates comprehensive insights with visualizations without requiring user prompts. *By [@coffeefuelbump](https://github.com/coffeefuelbump)*  
	[CSV 数据汇总器](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - 自动分析 CSV 文件，无需用户干预即可生成包含可视化图表的全面洞察。 *作者： [@coffeefuelbump](https://github.com/coffeefuelbump)*
- [deep-research](https://github.com/sanjay3290/ai-skills/tree/main/skills/deep-research) - Execute autonomous multi-step research using Gemini Deep Research Agent for market analysis, competitive landscaping, and literature reviews. *By [@sanjay3290](https://github.com/sanjay3290)*  
	[深度研究](https://github.com/sanjay3290/ai-skills/tree/main/skills/deep-research) - 使用 Gemini 深度研究代理执行自主多步骤研究，进行市场分析、竞争格局分析和文献综述。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) - Execute safe read-only SQL queries against PostgreSQL databases with multi-connection support and defense-in-depth security. *By [@sanjay3290](https://github.com/sanjay3290)*  
	[postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) - 支持多连接和纵深防御安全机制，可对 PostgreSQL 数据库执行安全的只读 SQL 查询。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [recursive-research](https://github.com/Anjos2/recursive-research) - Recursive research up to PhD level across any domain (science, tech, business, arts, humanities) with source tiering, WDM + Munger inversion for autonomous decisions, and disk checkpointing to survive context compaction. *By [@Anjos2](https://github.com/Anjos2)*  
	[递归研究](https://github.com/Anjos2/recursive-research) - 在任何领域（科学、技术、商业、艺术、人文）进行博士级别的递归研究，采用源分层、WDM + Munger 逆向算法进行自主决策，以及磁盘检查点机制以应对上下文压缩。 *作者： [@Anjos2](https://github.com/Anjos2)*
- [root-cause-tracing](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) - Use when errors occur deep in execution and you need to trace back to find the original trigger.  
	[根本原因追踪](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) - 当错误发生在执行的深处，需要追溯到原始触发因素时使用。

### Business & Marketing商业与市场营销

- [Brand Build Skills](https://github.com/rampstackco/claude-skills) - 59-skill library covering the full website lifecycle: brand, design, content, SEO, dev, ops, growth, and research. Stack-agnostic with an Ahrefs MCP-powered SEO audit suite. Includes a meta-skill for writing your own. *By [@rampstackco](https://github.com/rampstackco)*  
	[品牌建设技能](https://github.com/rampstackco/claude-skills) ——包含 59 项技能的技能库，涵盖网站的完整生命周期：品牌、设计、内容、SEO、开发、运维、增长和研究。该技能库与技术栈无关，并配备由 Ahrefs MCP 提供支持的 SEO 审核套件。此外，还包含一项元技能，用于编写您自己的 SEO 审核。 *作者： [@rampstackco](https://github.com/rampstackco)*
- [Brand Guidelines](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/brand-guidelines) - Applies Anthropic's official brand colors and typography to artifacts for consistent visual identity and professional design standards.  
	[品牌指南](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/brand-guidelines) - 将 Anthropic 的官方品牌颜色和字体应用于产品，以实现一致的视觉识别和专业设计标准。
- [Competitive Ads Extractor](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/competitive-ads-extractor) - Extracts and analyzes competitors' ads from ad libraries to understand messaging and creative approaches that resonate.  
	[竞争对手广告提取器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/competitive-ads-extractor) - 从广告库中提取和分析竞争对手的广告，以了解引起共鸣的信息传递和创意方法。
- [Domain Name Brainstormer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/domain-name-brainstormer) - Generates creative domain name ideas and checks availability across multiple TLDs including.com,.io,.dev, and.ai extensions.  
	[域名创意生成器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/domain-name-brainstormer) - 生成创意域名，并检查包括.com、.io、.dev 和.ai 在内的多个顶级域名的可用性。
- [Internal Comms](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/internal-comms) - Helps write internal communications including 3P updates, company newsletters, FAQs, status reports, and project updates using company-specific formats.  
	[内部沟通](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/internal-comms) - 帮助撰写内部沟通材料，包括 3P 更新、公司新闻简报、常见问题解答、状态报告和项目更新，使用公司特定的格式。
- [Lead Research Assistant](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/lead-research-assistant) - Identifies and qualifies high-quality leads by analyzing your product, searching for target companies, and providing actionable outreach strategies.  
	[首席研究助理](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/lead-research-assistant) - 通过分析您的产品、寻找目标公司并提供可行的推广策略，识别和筛选高质量的潜在客户。

### Communication & Writing沟通与写作

- [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - Extract full article text and metadata from web pages.  
	[文章提取器](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - 从网页中提取完整的文章文本和元数据。
- [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) - Transform rough ideas into fully-formed designs through structured questioning and alternative exploration.  
	[头脑风暴](https://github.com/obra/superpowers/tree/main/skills/brainstorming) ——通过结构化的提问和另辟蹊径的探索，将粗略的想法转化为完整的设计。
- [Content Research Writer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/content-research-writer) - Assists in writing high-quality content by conducting research, adding citations, improving hooks, and providing section-by-section feedback.  
	[内容研究撰稿人](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/content-research-writer) - 通过进行研究、添加引用、改进引人入胜的开头以及提供逐节反馈来协助撰写高质量的内容。
- [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) - Provides assistance with planning family history and genealogy research projects.  
	[家族史研究](https://github.com/emaynard/claude-family-history-research-skill) - 提供家族史和家谱研究项目规划方面的帮助。
- [Meeting Insights Analyzer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/meeting-insights-analyzer) - Analyzes meeting transcripts to uncover behavioral patterns including conflict avoidance, speaking ratios, filler words, and leadership style.  
	[会议洞察分析器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/meeting-insights-analyzer) - 分析会议记录，以发现行为模式，包括避免冲突、发言比例、填充词和领导风格。
- [NotebookLM Integration](https://github.com/PleasePrompto/notebooklm-skill) - Lets Claude Code chat directly with NotebookLM for source-grounded answers based exclusively on uploaded documents. *By [@PleasePrompto](https://github.com/PleasePrompto)*  
	[NotebookLM 集成](https://github.com/PleasePrompto/notebooklm-skill) - 让 Claude Code 可以直接与 NotebookLM 聊天，获取完全基于上传文档的、基于源代码的答案。 *作者： [@PleasePrompto](https://github.com/PleasePrompto)*
- [Twitter Algorithm Optimizer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/twitter-algorithm-optimizer) - Analyze and optimize tweets for maximum reach using Twitter's open-source algorithm insights. Rewrite and edit tweets to improve engagement and visibility.  
	[Twitter 算法优化器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/twitter-algorithm-optimizer) - 利用 Twitter 的开源算法洞察，分析并优化推文，以最大限度地扩大覆盖范围。重写和编辑推文，以提高互动率和曝光度。

### Creative & Media创意与媒体

- [anydesign](https://github.com/uxKero/anydesign) - Analyzes any image, URL, or Figma file and generates a structured `design.md` with the full design system, component inventory, and reconstruction notes — portable to v0, Lovable, Cursor or any AI builder. *By [@uxKero](https://github.com/uxKero)*  
	[anydesign——](https://github.com/uxKero/anydesign) 分析任何图像、URL 或 Figma 文件，并生成包含完整设计系统、组件清单和重构说明的结构化 `design.md` 文件——可移植到 v0、Lovable、Cursor 或任何 AI 构建器。 *作者： [@uxKero](https://github.com/uxKero)*
- [Canvas Design](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/canvas-design) - Creates beautiful visual art in PNG and PDF documents using design philosophy and aesthetic principles for posters, designs, and static pieces.  
	[Canvas Design](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/canvas-design) - 使用设计理念和美学原则，为海报、设计和静态作品创作精美的 PNG 和 PDF 文档视觉艺术作品。
- [imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - Generate images using Google Gemini's image generation API for UI mockups, icons, illustrations, and visual assets. *By [@sanjay3290](https://github.com/sanjay3290)*  
	[imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - 使用 Google Gemini 的图像生成 API 生成图像，用于 UI 模型、图标、插图和视觉素材。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [Image Enhancer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/image-enhancer) - Improves image and screenshot quality by enhancing resolution, sharpness, and clarity for professional presentations and documentation.  
	[图像增强器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/image-enhancer) - 通过提高分辨率、锐度和清晰度来改善图像和屏幕截图的质量，适用于专业演示和文档。
- [Slack GIF Creator](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/slack-gif-creator) - Creates animated GIFs optimized for Slack with validators for size constraints and composable animation primitives.  
	[Slack GIF 创建器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/slack-gif-creator) - 创建针对 Slack 优化的动画 GIF，带有大小限制验证器和可组合的动画原语。
- [Theme Factory](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/theme-factory) - Applies professional font and color themes to artifacts including slides, docs, reports, and HTML landing pages with 10 pre-set themes.  
	[Theme Factory](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/theme-factory) - 为幻灯片、文档、报告和 HTML 登录页面等素材应用专业的字体和颜色主题，提供 10 个预设主题。
- [Video Downloader](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/video-downloader) - Downloads videos from YouTube and other platforms for offline viewing, editing, or archival with support for various formats and quality options.  
	[视频下载器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/video-downloader) - 从 YouTube 和其他平台下载视频，以便离线观看、编辑或存档，支持各种格式和质量选项。
- [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - Fetch transcripts from YouTube videos and prepare summaries.  
	[youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - 从 YouTube 视频中提取文字稿并生成摘要。
- [swiftui-design-skill](https://github.com/wholiver/swiftui-design-skill) - SwiftUI 前端设计 skill — 反 AI Slop 六条铁律、设计方向顾问、品牌资产协议、五维评审。支持 Claude Code / Cursor / Codex / OpenCode 等全部 AI agent 平台。 *By [@wholiver](https://github.com/wholiver)*  
	[swiftui-design-skill - SwiftUI 前端设计技能](https://github.com/wholiver/swiftui-design-skill) — 反 AI Slop 六条铁律、设计方向顾问、品牌资产协议、五维评审。支持 Claude Code / Cursor / Codex / OpenCode 等全部 AI 代理平台。 *By [@wholiver](https://github.com/wholiver)*
- [Pixelbin-Media-Generation](https://github.com/anandpareek-hub/pixelbin-claude-skill) - Generate and edit images & videos with 85+ API portfolio and build visually appealing website pages  
	[Pixelbin-媒体生成](https://github.com/anandpareek-hub/pixelbin-claude-skill) - 利用 85 多个 API 生成和编辑图像及视频，并构建视觉效果出色的网站页面

### Productivity & Organization生产力和组织能力

- [File Organizer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/file-organizer) - Intelligently organizes files and folders by understanding context, finding duplicates, and suggesting better organizational structures.  
	[文件整理器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/file-organizer) - 通过理解上下文、查找重复项并建议更好的组织结构，智能地整理文件和文件夹。
- [Invoice Organizer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/invoice-organizer) - Automatically organizes invoices and receipts for tax preparation by reading files, extracting information, and renaming consistently.  
	[发票整理器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/invoice-organizer) - 通过读取文件、提取信息和统一重命名，自动整理发票和收据，以便进行税务准备。
- [kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) - Applies continuous improvement methodology with multiple analytical approaches, based on Japanese Kaizen philosophy and Lean methodology.  
	[改善（Kaizen）](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) ——运用多种分析方法，基于日本的改善（Kaizen）理念和精益方法，进行持续改进。
- [n8n-skills](https://github.com/haunchen/n8n-skills) - Enables AI assistants to directly understand and operate n8n workflows.  
	[n8n-skills](https://github.com/haunchen/n8n-skills) - 使 AI 助手能够直接理解和操作 n8n 工作流程。
- [Raffle Winner Picker](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/raffle-winner-picker) - Randomly selects winners from lists, spreadsheets, or Google Sheets for giveaways and contests with cryptographically secure randomness.  
	[抽奖赢家选择器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/raffle-winner-picker) - 从列表、电子表格或 Google 表格中随机选择赠品和竞赛的赢家，采用加密安全的随机性。
- [solo-skills](https://github.com/rockscy/solo-skills) - 7 bilingual (EN+中文) skills for solo founders and indie devs: launch tweets, customer emails, decision frameworks, postmortems. Each skill includes an explicit "When NOT to use" section.  
	[solo-skills——](https://github.com/rockscy/solo-skills) 专为独立创始人及开发者打造的 7 项双语（英+中文）技能：发布推文、客户邮件、决策框架、事后分析。每项技能都包含明确的“何时不应使用”部分。
- [Tailored Resume Generator](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/tailored-resume-generator) - Analyzes job descriptions and generates tailored resumes that highlight relevant experience, skills, and achievements to maximize interview chances.  
	[定制简历生成器](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/tailored-resume-generator) - 分析职位描述并生成定制简历，突出相关经验、技能和成就，以最大限度地提高面试机会。
- [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - Skill to help iterate on what to build or learn next, based on feedback loops.  
	[ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - 根据反馈循环，帮助迭代下一步构建或学习的内容的技能。
- [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) - Interlink and summarize related documents into knowledge networks.  
	[将](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) 相关文档相互链接并汇总成知识网络。

### Collaboration & Project Management协作与项目管理

- [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - Automate git operations and repository interactions.  
	[git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - 自动化 git 操作和存储库交互。
- [google-workspace-skills](https://github.com/sanjay3290/ai-skills/tree/main/skills) - Suite of Google Workspace integrations: Gmail, Calendar, Chat, Docs, Sheets, Slides, and Drive with cross-platform OAuth. *By [@sanjay3290](https://github.com/sanjay3290)*  
	[google-workspace-skills](https://github.com/sanjay3290/ai-skills/tree/main/skills) - 一套完整的 Google Workspace 集成方案：支持跨平台 OAuth 的 Gmail、日历、聊天、文档、表格、幻灯片和云端硬盘集成。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [mercury-mcp](https://www.teamoffsite.ai/proton/docs/skill) - Cheatsheet for the Mercury (Proton) MCP tools. Message agent teammates, manage threads, create tasks, and schedule automations across coordinated agent teams. *By [Mercury](https://mercury.build/)*  
	[mercury-mcp](https://www.teamoffsite.ai/proton/docs/skill) - Mercury (Proton) MCP 工具速查表。用于向代理团队成员发送消息、管理讨论串、创建任务以及安排跨代理团队的自动化操作。 *由 [Mercury](https://mercury.build/) 提供。*
- [outline](https://github.com/sanjay3290/ai-skills/tree/main/skills/outline) - Search, read, create, and manage documents in Outline wiki instances (cloud or self-hosted). *By [@sanjay3290](https://github.com/sanjay3290)*  
	[Outline](https://github.com/sanjay3290/ai-skills/tree/main/skills/outline) - 在 Outline wiki 实例（云端或自托管）中搜索、阅读、创建和管理文档。 *作者： [@sanjay3290](https://github.com/sanjay3290)*
- [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - Evaluate code implementation plans and align with specs.  
	[审查实施](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - 评估代码实施计划并使其符合规范。
- [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - Detect failing tests and propose patches or fixes.  
	[测试修复](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - 检测失败的测试并提出补丁或修复方案。

### Security & Systems安全与系统

- [computer-forensics](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) - Digital forensics analysis and investigation techniques.  
	[计算机取证](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) ——数字取证分析和调查技术。
- [file-deletion](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) - Secure file deletion and data sanitization methods.  
	[文件删除](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) - 安全的文件删除和数据清除方法。
- [metadata-extraction](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) - Extract and analyze file metadata for forensic purposes.  
	[元数据提取](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) - 提取和分析文件元数据以用于取证目的。
- [threat-hunting-with-sigma-rules](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) - Use Sigma detection rules to hunt for threats and analyze security events.  
	[使用 Sigma 规则进行威胁狩猎](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) - 使用 Sigma 检测规则来狩猎威胁并分析安全事件。

### Assistive Technology辅助技术

- [ASD-AuDHD-PAI-Skills](https://github.com/emory/ASD-AuDHD-PAI-Skills) - New collection, first skill [pda-reframing](https://github.com/emory/ASD-AuDHD-PAI-Skills/blob/main/Skills/pda-reframing/SKILL.md) can reframe requests or decisions to defeat Persistent Demand Avoidance flavors of autism spectrum disorders, or people with ADHD that struggle to Start tasks and need help aligning with a task.  
	[ASD-AuDHD-PAI-Skills](https://github.com/emory/ASD-AuDHD-PAI-Skills) - 新系列，第一个技能 [pda-reframing](https://github.com/emory/ASD-AuDHD-PAI-Skills/blob/main/Skills/pda-reframing/SKILL.md) 可以重新构建请求或决定，以克服自闭症谱系障碍的持续性需求回避 (PAI) 类型，或难以开始任务且需要帮助才能完成任务的多动症患者。

### App Automation via Composio通过 Composio 实现应用自动化

Pre-built workflow skills for 78 SaaS apps via [Rube MCP (Composio)](https://composio.dev/). Each skill includes tool sequences, parameter guidance, known pitfalls, and quick reference tables — all using real tool slugs discovered from Composio's API.  
通过 [Rube MCP（Composio）](https://composio.dev/) 为 78 个 SaaS 应用预构建工作流技能。每个技能都包含工具序列、参数指南、已知陷阱和快速参考表——所有这些都使用从 Composio API 中发现的真实工具 slug。

**CRM & Sales  
客户关系管理与销售**

- [Close Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/close-automation) - Automate Close CRM: leads, contacts, opportunities, activities, and pipelines.  
	[成交自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/close-automation) - 自动化成交 CRM：潜在客户、联系人、商机、活动和销售渠道。
- [HubSpot Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/hubspot-automation) - Automate HubSpot CRM: contacts, deals, companies, tickets, and email engagement.  
	[HubSpot 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/hubspot-automation) - 自动化 HubSpot CRM：联系人、交易、公司、工单和电子邮件互动。
- [Pipedrive Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/pipedrive-automation) - Automate Pipedrive: deals, contacts, organizations, activities, and pipelines.  
	[Pipedrive 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/pipedrive-automation) - 自动化 Pipedrive：交易、联系人、组织、活动和管道。
- [Salesforce Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/salesforce-automation) - Automate Salesforce: objects, records, SOQL queries, and bulk operations.  
	[Salesforce Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/salesforce-automation) - 自动化 Salesforce：对象、记录、SOQL 查询和批量操作。
- [Zoho CRM Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/zoho-crm-automation) - Automate Zoho CRM: leads, contacts, deals, accounts, and modules.  
	[Zoho CRM 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/zoho-crm-automation) - 自动化 Zoho CRM：潜在客户、联系人、交易、帐户和模块。

**Project Management  
项目管理**

- [Asana Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/asana-automation) - Automate Asana: tasks, projects, sections, assignments, and workspaces.  
	[Asana Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/asana-automation) - 自动化 Asana：任务、项目、版块、分配和工作区。
- [Basecamp Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/basecamp-automation) - Automate Basecamp: to-do lists, messages, people, groups, and projects.  
	[Basecamp 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/basecamp-automation) - 自动化 Basecamp：待办事项列表、消息、人员、群组和项目。
- [ClickUp Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/clickup-automation) - Automate ClickUp: tasks, lists, spaces, goals, and time tracking.  
	[ClickUp 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/clickup-automation) - 自动化 ClickUp：任务、列表、空间、目标和时间跟踪。
- [Jira Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/jira-automation) - Automate Jira: issues, projects, boards, sprints, and JQL queries.  
	[Jira Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/jira-automation) - 自动化 Jira：问题、项目、看板、迭代和 JQL 查询。
- [Linear Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/linear-automation) - Automate Linear: issues, projects, cycles, teams, and workflows.  
	[线性自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/linear-automation) - 自动化线性流程：问题、项目、周期、团队和工作流程。
- [Monday Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/monday-automation) - Automate Monday.com: boards, items, columns, groups, and workspaces.  
	[星期一自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/monday-automation) - Automate Monday.com：看板、项目、列、组和工作区。
- [Notion Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/notion-automation) - Automate Notion: pages, databases, blocks, comments, and search.  
	[Notion Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/notion-automation) - 自动化 Notion：页面、数据库、区块、评论和搜索。
- [Todoist Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/todoist-automation) - Automate Todoist: tasks, projects, sections, labels, and filters.  
	[Todoist 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/todoist-automation) - 自动化 Todoist：任务、项目、部分、标签和过滤器。
- [Trello Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/trello-automation) - Automate Trello: boards, cards, lists, members, and checklists.  
	[Trello 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/trello-automation) - 自动化 Trello：看板、卡片、列表、成员和清单。
- [Wrike Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/wrike-automation) - Automate Wrike: tasks, folders, projects, comments, and workflows.  
	[Wrike Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/wrike-automation) - 自动化 Wrike：任务、文件夹、项目、评论和工作流。

**Communication  
沟通**

- [Discord Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/discord-automation) - Automate Discord: messages, channels, servers, roles, and reactions.  
	[Discord 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/discord-automation) - 自动化 Discord：消息、频道、服务器、角色和反应。
- [Intercom Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/intercom-automation) - Automate Intercom: conversations, contacts, companies, tickets, and articles.  
	[对讲自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/intercom-automation) - 自动化对讲：对话、联系人、公司、工单和文章。
- [Microsoft Teams Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/microsoft-teams-automation) - Automate Teams: messages, channels, teams, chats, and meetings.  
	[Microsoft Teams 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/microsoft-teams-automation) - 自动化 Teams：消息、频道、团队、聊天和会议。
- [Slack Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/slack-automation) - Automate Slack: messages, channels, search, reactions, threads, and scheduling.  
	[Slack 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/slack-automation) - 自动化 Slack：消息、频道、搜索、反应、主题和日程安排。
- [Telegram Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/telegram-automation) - Automate Telegram: messages, chats, media, groups, and bots.  
	[Telegram 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/telegram-automation) - 自动化 Telegram：消息、聊天、媒体、群组和机器人。
- [WhatsApp Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/whatsapp-automation) - Automate WhatsApp: messages, media, templates, groups, and business profiles.  
	[WhatsApp 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/whatsapp-automation) - 自动化 WhatsApp：消息、媒体、模板、群组和企业个人资料。

**Email  
电子邮件**

- [Gmail Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/gmail-automation) - Automate Gmail: send/reply, search, labels, drafts, and attachments.  
	[Gmail 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/gmail-automation) - 自动化 Gmail：发送/回复、搜索、标签、草稿和附件。
- [Outlook Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/outlook-automation) - Automate Outlook: emails, folders, contacts, and calendar integration.  
	[Outlook 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/outlook-automation) - 自动化 Outlook：电子邮件、文件夹、联系人和日历集成。
- [Postmark Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/postmark-automation) - Automate Postmark: transactional emails, templates, servers, and delivery stats.  
	[Postmark 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/postmark-automation) - 自动化 Postmark：交易电子邮件、模板、服务器和投递统计。
- [SendGrid Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/sendgrid-automation) - Automate SendGrid: emails, templates, contacts, lists, and campaign stats.  
	[SendGrid 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/sendgrid-automation) - 自动化 SendGrid：电子邮件、模板、联系人、列表和活动统计信息。

**Code & DevOps  
代码与 DevOps**

- [Bitbucket Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/bitbucket-automation) - Automate Bitbucket: repos, PRs, branches, issues, and workspaces.  
	[Bitbucket 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/bitbucket-automation) - 自动化 Bitbucket：仓库、PR、分支、问题和工作区。
- [CircleCI Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/circleci-automation) - Automate CircleCI: pipelines, workflows, jobs, and project configuration.  
	[CircleCI 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/circleci-automation) - 自动化 CircleCI：管道、工作流、作业和项目配置。
- [Datadog Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/datadog-automation) - Automate Datadog: monitors, dashboards, metrics, incidents, and alerts.  
	[Datadog Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/datadog-automation) - 自动化 Datadog：监控、仪表盘、指标、事件和警报。
- [GitHub Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/github-automation) - Automate GitHub: issues, PRs, repos, branches, actions, and code search.  
	[GitHub Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/github-automation) - 自动化 GitHub：问题、PR、仓库、分支、操作和代码搜索。
- [GitLab Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/gitlab-automation) - Automate GitLab: issues, MRs, projects, pipelines, and branches.  
	[GitLab 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/gitlab-automation) - 自动化 GitLab：问题、合并请求、项目、流水线和分支。
- [PagerDuty Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/pagerduty-automation) - Automate PagerDuty: incidents, services, schedules, escalation policies, and on-call.  
	[PagerDuty 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/pagerduty-automation) - 自动化 PagerDuty：事件、服务、日程安排、升级策略和值班。
- [Render Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/render-automation) - Automate Render: services, deploys, and project management.  
	[渲染自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/render-automation) - 自动化渲染：服务、部署和项目管理。
- [Sentry Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/sentry-automation) - Automate Sentry: issues, events, projects, releases, and alerts.  
	[Sentry Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/sentry-automation) - 自动化 Sentry：问题、事件、项目、版本和警报。
- [Supabase Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/supabase-automation) - Automate Supabase: SQL queries, table schemas, edge functions, and storage.  
	[Supabase Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/supabase-automation) - 自动化 Supabase：SQL 查询、表架构、边缘函数和存储。
- [Vercel Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/vercel-automation) - Automate Vercel: deployments, projects, domains, environment variables, and logs.  
	[Vercel 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/vercel-automation) - 自动化 Vercel：部署、项目、域、环境变量和日志。

**Storage & Files  
存储和文件**

- [Box Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/box-automation) - Automate Box: files, folders, search, sharing, collaborations, and sign requests.  
	[Box Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/box-automation) - 自动化 Box：文件、文件夹、搜索、共享、协作和签署请求。
- [Dropbox Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/dropbox-automation) - Automate Dropbox: files, folders, search, sharing, and batch operations.  
	[Dropbox 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/dropbox-automation) - 自动化 Dropbox：文件、文件夹、搜索、共享和批量操作。
- [Google Drive Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/google-drive-automation) - Automate Google Drive: upload, download, search, share, and organize files.  
	[Google 云端硬盘自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/google-drive-automation) - 自动化 Google 云端硬盘：上传、下载、搜索、共享和整理文件。
- [OneDrive Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/one-drive-automation) - Automate OneDrive: files, folders, search, sharing, permissions, and versioning.  
	[OneDrive 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/one-drive-automation) - 自动化 OneDrive：文件、文件夹、搜索、共享、权限和版本控制。

**Spreadsheets & Databases  
电子表格和数据库**

- [Airtable Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/airtable-automation) - Automate Airtable: records, tables, bases, views, and field management.  
	[Airtable 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/airtable-automation) - 自动化 Airtable：记录、表格、数据库、视图和字段管理。
- [Coda Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/coda-automation) - Automate Coda: docs, tables, rows, formulas, and automations.  
	[Coda Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/coda-automation) - 自动化 Coda：文档、表格、行、公式和自动化。
- [Google Sheets Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/googlesheets-automation) - Automate Google Sheets: read/write cells, formatting, formulas, and batch operations.  
	[Google Sheets 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/googlesheets-automation) - 自动化 Google Sheets：读取/写入单元格、格式设置、公式和批量操作。

**Calendar & Scheduling  
日历和日程安排**

- [Cal.com Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/cal-com-automation) - Automate Cal.com: event types, bookings, availability, and scheduling.  
	[Cal.com 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/cal-com-automation) - 自动化 Cal.com：活动类型、预订、可用性和日程安排。
- [Calendly Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/calendly-automation) - Automate Calendly: events, invitees, event types, scheduling links, and availability.  
	[Calendly 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/calendly-automation) - 自动化 Calendly：事件、受邀者、事件类型、日程安排链接和可用性。
- [Google Calendar Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/google-calendar-automation) - Automate Google Calendar: events, attendees, free/busy, and recurring schedules.  
	[Google 日历自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/google-calendar-automation) - 自动管理 Google 日历：事件、与会者、空闲/忙碌状态和重复性日程安排。
- [Outlook Calendar Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/outlook-calendar-automation) - Automate Outlook Calendar: events, attendees, reminders, and recurring schedules.  
	[Outlook 日历自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/outlook-calendar-automation) - 自动执行 Outlook 日历：事件、与会者、提醒和重复日程。

**Social Media  
社交媒体**

- [Instagram Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/instagram-automation) - Automate Instagram: posts, stories, comments, media, and business insights.  
	[Instagram 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/instagram-automation) - 自动化 Instagram：帖子、快拍、评论、媒体和商业洞察。
- [LinkedIn Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/linkedin-automation) - Automate LinkedIn: posts, profiles, companies, images, and comments.  
	[LinkedIn 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/linkedin-automation) - 自动执行 LinkedIn 操作：帖子、个人资料、公司、图片和评论。
- [Reddit Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/reddit-automation) - Automate Reddit: posts, comments, subreddits, voting, and moderation.  
	[Reddit 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/reddit-automation) - 自动化 Reddit：帖子、评论、子版块、投票和版主管理。
- [TikTok Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/tiktok-automation) - Automate TikTok: video uploads, queries, and creator management.  
	[TikTok 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/tiktok-automation) - 自动化 TikTok：视频上传、查询和创作者管理。
- [Twitter Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/twitter-automation) - Automate Twitter/X: tweets, search, users, lists, and engagement.  
	[Twitter Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/twitter-automation) - 自动化 Twitter/X：推文、搜索、用户、列表和互动。
- [YouTube Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/youtube-automation) - Automate YouTube: videos, channels, playlists, comments, and subscriptions.  
	[YouTube 自动化](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/youtube-automation) - 自动化 YouTube：视频、频道、播放列表、评论和订阅。

**Marketing & Email Marketing**

- [ActiveCampaign Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/activecampaign-automation) - Automate ActiveCampaign: contacts, deals, campaigns, lists, and automations.
- [Brevo Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/brevo-automation) - Automate Brevo: contacts, email campaigns, transactional emails, and lists.
- [ConvertKit Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/convertkit-automation) - Automate ConvertKit (Kit): subscribers, tags, sequences, broadcasts, and forms.
- [Klaviyo Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/klaviyo-automation) - Automate Klaviyo: profiles, lists, segments, campaigns, and events.
- [Mailchimp Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/mailchimp-automation) - Automate Mailchimp: audiences, campaigns, templates, segments, and reports.

**Support & Helpdesk**

- [Freshdesk Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/freshdesk-automation) - Automate Freshdesk: tickets, contacts, agents, groups, and canned responses.
- [Freshservice Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/freshservice-automation) - Automate Freshservice: tickets, assets, changes, problems, and service catalog.
- [Help Scout Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/helpdesk-automation) - Automate Help Scout: conversations, customers, mailboxes, and tags.
- [Zendesk Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/zendesk-automation) - Automate Zendesk: tickets, users, organizations, search, and macros.

**E-commerce & Payments**

- [Shopify Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/shopify-automation) - Automate Shopify: products, orders, customers, inventory, and GraphQL queries.
- [Square Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/square-automation) - Automate Square: payments, customers, catalog, orders, and locations.
- [Stripe Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/stripe-automation) - Automate Stripe: charges, customers, products, subscriptions, and refunds.

**Design & Collaboration**

- [Canva Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/canva-automation) - Automate Canva: designs, templates, assets, folders, and brand kits.
- [Confluence Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/confluence-automation) - Automate Confluence: pages, spaces, search, CQL, labels, and versions.
- [DocuSign Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/docusign-automation) - Automate DocuSign: envelopes, templates, signing, and document management.
- [Figma Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/figma-automation) - Automate Figma: files, components, comments, projects, and team management.
- [Miro Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/miro-automation) - Automate Miro: boards, sticky notes, shapes, connectors, and items.
- [Webflow Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/webflow-automation) - Automate Webflow: CMS collections, items, sites, publishing, and assets.

**Analytics & Data**

- [Amplitude Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/amplitude-automation) - Automate Amplitude: events, cohorts, user properties, and analytics queries.
- [Google Analytics Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/google-analytics-automation) - Automate Google Analytics: reports, dimensions, metrics, and property management.
- [Mixpanel Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/mixpanel-automation) - Automate Mixpanel: events, funnels, cohorts, annotations, and JQL queries.
- [PostHog Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/posthog-automation) - Automate PostHog: events, persons, feature flags, insights, and annotations.
- [Segment Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/segment-automation) - Automate Segment: sources, destinations, tracking, and warehouse connections.

**HR & People**

- [BambooHR Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/bamboohr-automation) - Automate BambooHR: employees, time off, reports, and directory management.

**Automation Platforms**

- [Make Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/make-automation) - Automate Make (Integromat): scenarios, connections, and execution management.

**Zoom & Meetings**

- [Zoom Automation](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/zoom-automation) - Automate Zoom: meetings, recordings, participants, webinars, and reports.

## Getting Started

### Using Skills in Claude.ai

1. Click the skill icon (🧩) in your chat interface.
2. Add skills from the marketplace or upload custom skills.
3. Claude automatically activates relevant skills based on your task.

### Using Skills in Claude Code

1. Place the skill in `~/.config/claude-code/skills/`:
	```
	mkdir -p ~/.config/claude-code/skills/
	cp -r skill-name ~/.config/claude-code/skills/
	```
2. Verify skill metadata:
	```
	head ~/.config/claude-code/skills/skill-name/SKILL.md
	```
3. Start Claude Code:
	```
	claude
	```
4. The skill loads automatically and activates when relevant.

### Using Skills via API

Use the Claude Skills API to programmatically load and manage skills:

```
import anthropic

client = anthropic.Anthropic(api_key="your-api-key")

response = client.messages.create(
    model="claude-3-5-sonnet-20241022",
    skills=["skill-id-here"],
    messages=[{"role": "user", "content": "Your prompt"}]
)
```

See the [Skills API documentation](https://docs.claude.com/en/api/skills-guide) for details.

## Creating Skills

### Skill Structure

Each skill is a folder containing a `SKILL.md` file with YAML frontmatter:

```
skill-name/
├── SKILL.md          # Required: Skill instructions and metadata
├── scripts/          # Optional: Helper scripts
├── templates/        # Optional: Document templates
└── resources/        # Optional: Reference files
```

### Basic Skill Template

```
---
name: my-skill-name
description: A clear description of what this skill does and when to use it.
---

# My Skill Name

Detailed description of the skill's purpose and capabilities.

## When to Use This Skill

- Use case 1
- Use case 2
- Use case 3

## Instructions

[Detailed instructions for Claude on how to execute this skill]

## Examples

[Real-world examples showing the skill in action]
```

### Skill Best Practices

- Focus on specific, repeatable tasks
- Include clear examples and edge cases
- Write instructions for Claude, not end users
- Test across Claude.ai, Claude Code, and API
- Document prerequisites and dependencies
- Include error handling guidance

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/CONTRIBUTING.md) for details on:

- How to submit new skills
- Skill quality standards
- Pull request process
- Code of conduct

### Quick Contribution Steps

1. Ensure your skill is based on a real use case
2. Check for duplicates in existing skills
3. Follow the skill structure template
4. Test your skill across platforms
5. Submit a pull request with clear documentation

## Resources

### Official Documentation

- [Claude Skills Overview](https://www.anthropic.com/news/skills) - Official announcement and features
- [Skills User Guide](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - How to use skills in Claude
- [Creating Custom Skills](https://support.claude.com/en/articles/12512198-creating-custom-skills) - Skill development guide
- [Skills API Documentation](https://docs.claude.com/en/api/skills-guide) - API integration guide
- [Agent Skills Blog Post](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Engineering deep dive

### Community Resources

- [Anthropic Skills Repository](https://github.com/anthropics/skills) - Official example skills
- [Claude Community](https://community.anthropic.com/) - Discuss skills with other users
- [Skills Marketplace](https://claude.ai/marketplace) - Discover and share skills

### Inspiration & Use Cases

- [Lenny's Newsletter](https://www.lennysnewsletter.com/p/everyone-should-be-using-claude-code) - 50 ways people use Claude Code
- [Notion Skills](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) - Notion integration skills
- [Top Claude Skills](https://composio.dev/content/top-claude-skills)

## Join the Community

- [Join our Discord](https://discord.com/invite/composio) - Chat with other developers building Claude Skills
- [Follow on Twitter/X](https://x.com/composio) - Stay updated on new skills and features
- Questions? [support@composio.dev](mailto:support@composio.dev)

---

**Join 20,000+ developers building agents that ship**

## License

This repository is licensed under the Apache License 2.0.

Individual skills may have different licenses - please check each skill's folder for specific licensing information.

---

**Note**: Claude Skills work across Claude.ai, Claude Code, and the Claude API. Once you create a skill, it's portable across all platforms, making your workflows consistent everywhere you use Claude.