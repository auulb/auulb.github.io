---
{"dg-publish":true,"permalink":"/Clippings/awesome-ai-web-scraping/","title":"awesome-ai-web-scraping","tags":["clippings"],"dg-note-properties":{"title":"awesome-ai-web-scraping","source":"https://github.com/h4ckf0r0day/awesome-ai-web-scraping#1","author":null,"published":null,"created":"2026-10-12","description":null,"tags":["clippings"]}}
---

## Awesome AI Web Scraping超棒的 AI 网络爬虫

A curated list of tools, libraries, and resources for AI-powered web scraping.  
一份精选的用于人工智能驱动的网络爬虫的工具、库和资源列表。

---

Frameworks, hosted APIs, browser infrastructure, MCP servers, and research for turning the web into clean, structured data for LLMs, RAG pipelines, and agents.  
框架、托管 API、浏览器基础设施、MCP 服务器以及将网络转化为 LLM、RAG 管道和代理所需的干净、结构化数据的研究。

**Scope:** Tools where AI or LLMs play a meaningful role in extraction, navigation, or content understanding. General-purpose scrapers (Scrapy, BeautifulSoup) belong in [awesome-web-scraping](https://github.com/lorien/awesome-web-scraping). Autonomous browser agents belong in [awesome-web-agents](https://github.com/steel-dev/awesome-web-agents).  
**范围：** 人工智能或语言学习模型在提取、导航或内容理解方面发挥重要作用的工具。通用爬虫（例如 Scrapy、BeautifulSoup）属于 [awesome-web-scraping](https://github.com/lorien/awesome-web-scraping) 范畴。自主浏览器代理属于 [awesome-web-agents](https://github.com/steel-dev/awesome-web-agents) 范畴。

## Contents内容

## Frameworks & Libraries框架和库

Self-hosted, open-source. Most pair a headless browser with an LLM for schema-based or prompt-based extraction.  
自托管、开源。大多数方案都将无头浏览器与 LLM 结合使用，以实现基于模式或基于提示的提取。

- [Crawl4AI](https://github.com/unclecode/crawl4ai) - LLM-friendly web crawler with Markdown output and JSON-schema or LLM-based extraction. Python.  
	[Crawl4AI](https://github.com/unclecode/crawl4ai) - 一款支持 LLM 的网络爬虫，支持 Markdown 输出和基于 JSON Schema 或 LLM 的数据提取。使用 Python 编写。
- [Scrapling](https://github.com/D4Vinci/Scrapling) - Adaptive Python framework with smart element tracking that relocates elements after site changes. Cloudflare Turnstile bypass, spider framework with pause/resume, and a built-in MCP server.  
	[Scrapling](https://github.com/D4Vinci/Scrapling) - 一个自适应的 Python 框架，具有智能元素跟踪功能，可在网站更改后重新定位元素。它绕过了 Cloudflare Turnstile 限制，拥有暂停/恢复功能的爬虫框架，并内置了 MCP 服务器。
- [ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai) - Python scraper using LLM + graph pipelines. Describe data in natural language, get typed JSON. Works with OpenAI, Anthropic, Groq, Gemini, Ollama.  
	[ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai) - 使用 LLM 和图管道的 Python 爬虫。用自然语言描述数据，获取类型化的 JSON。支持 OpenAI、Anthropic、Groq、Gemini 和 Ollama。
- [llm-scraper](https://github.com/mishushakov/llm-scraper) - TypeScript library for structured extraction with Zod schemas. Supports GPT, Claude, Gemini, Llama, Qwen.  
	[llm-scraper](https://github.com/mishushakov/llm-scraper) - 用于使用 Zod schema 进行结构化数据提取的 TypeScript 库。支持 GPT、Claude、Gemini、Llama 和 Qwen。
- [Reader](https://github.com/jina-ai/reader) - Jina AI's URL-to-Markdown converter. Engine behind `r.jina.ai`.  
	[Reader](https://github.com/jina-ai/reader) - Jina AI 的 URL 转 Markdown 转换器 `r.jina.ai` 背后的引擎。
- [Stagehand](https://github.com/browserbase/stagehand) - Browser automation framework with `act`, `extract`, and `observe` primitives over Playwright.  
	[Stagehand](https://github.com/browserbase/stagehand) - 基于 Playwright 的浏览器自动化框架，包含 `act` 、 `extract` 和 `observe` 等基本功能。
- [Browser-Use](https://github.com/browser-use/browser-use) - Agent framework commonly used for scraping complex, login-walled sites.  
	[浏览器端](https://github.com/browser-use/browser-use) - 代理框架，通常用于抓取复杂、需要登录才能访问的网站。
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Browser automation for forms, logins, and dynamic content.  
	[Skyvern](https://github.com/Skyvern-AI/skyvern) - 用于表单、登录和动态内容的浏览器自动化工具。
- [LaVague](https://github.com/lavague-ai/LaVague) - Natural language web automation framework.  
	[LaVague——](https://github.com/lavague-ai/LaVague) 自然语言 Web 自动化框架。
- [CyberScraper 2077](https://github.com/itsOwen/CyberScraper-2077) - LLM scraper with Streamlit UI. Supports OpenAI, Gemini, and Ollama. Tor support included.  
	[CyberScraper 2077](https://github.com/itsOwen/CyberScraper-2077) - 一款基于 Streamlit UI 的 LLM 爬虫。支持 OpenAI、Gemini 和 Ollama。内置 Tor 支持。
- [ScraperAI](https://github.com/scraperai/scraperai) - AI scraper with auto-detection of page types, pagination, and catalog cards.  
	[ScraperAI](https://github.com/scraperai/scraperai) - 一款人工智能爬虫，可自动检测页面类型、分页和目录卡片。
- [SpiderCreator](https://github.com/carlosplanchon/spidercreator) - Generates Playwright spiders from natural language prompts.  
	[SpiderCreator](https://github.com/carlosplanchon/spidercreator) - 根据自然语言提示生成 Playwright 爬虫。
- [PulsarRPA](https://github.com/platonai/pulsarRPA) - AI-powered browser automation and data extraction.  
	[PulsarRPA](https://github.com/platonai/pulsarRPA) - 基于人工智能的浏览器自动化和数据提取。

## Hosted APIs托管式 API

Managed services that turn URLs into LLM-ready Markdown or JSON. JS rendering, proxies, and anti-bot handled internally.  
提供将 URL 转换为 LLM 兼容的 Markdown 或 JSON 格式的托管服务。JS 渲染、代理和反机器人功能均由内部处理。

- [Firecrawl](https://firecrawl.dev/) - Scrape, crawl, map, search, agent, and interact endpoints. LLM-ready Markdown. 500 free credits, paid plans from $16/mo.  
	[Firecrawl](https://firecrawl.dev/) - 抓取、爬取、映射、搜索、代理和交互端点。支持 LLM 格式的 Markdown。提供 500 个免费积分，付费套餐每月 16 美元起。
- [Jina Reader](https://jina.ai/reader/) - Prepend `r.jina.ai/` to any URL for LLM-friendly text. Free tier with no API key required.  
	[Jina Reader](https://jina.ai/reader/) - 在任何 URL 前添加 `r.jina.ai/` 即可生成 LLM 友好型文本。免费版无需 API 密钥。
- [Diffbot](https://www.diffbot.com/) - Computer vision and NLP extraction with a knowledge graph layer. Paid.  
	[Diffbot](https://www.diffbot.com/) - 一款基于知识图谱层的计算机视觉和自然语言处理提取工具。付费。
- [Apify](https://apify.com/) - Marketplace of 10,000+ pre-built scrapers ("Actors") plus a runtime for your own. Free tier and paid plans.  
	[Apify——](https://apify.com/) 拥有超过 10000 个预构建爬虫（“Actor”）的市场，并提供运行时环境供您自行开发。提供免费套餐和付费方案。
- [Bright Data](https://brightdata.com/) - Scraping with 150M+ proxies and pre-built APIs for 120+ sites. Free tier and paid plans.  
	[Bright Data](https://brightdata.com/) - 提供超过 1.5 亿个代理和预构建的 API，支持 120 多个网站的数据抓取。提供免费套餐和付费方案。
- [Zyte](https://www.zyte.com/) - Scraping API with AI extraction. Formerly Scrapinghub. Paid.  
	[Zyte](https://www.zyte.com/) - 具备人工智能提取功能的抓取 API。前身为 Scrapinghub。付费。
- [ScrapingBee](https://www.scrapingbee.com/) - JS rendering, AI extraction, Markdown, and Google SERP support. Free trial and paid plans.  
	[ScrapingBee——](https://www.scrapingbee.com/) 支持 JS 渲染、AI 提取、Markdown 和 Google SERP。提供免费试用和付费方案。
- [ZenRows](https://www.zenrows.com/) - Anti-bot focused scraping API with Markdown output. Free trial and paid plans.  
	[ZenRows](https://www.zenrows.com/) - 一款专注于反机器人抓取的 API，支持 Markdown 输出。提供免费试用和付费方案。
- [Oxylabs](https://oxylabs.io/) - Proxies plus a Web Scraper API with adaptive parsing. Paid.  
	[Oxylabs](https://oxylabs.io/) - 代理服务器以及带有自适应解析功能的网页抓取 API。付费。
- [Spider](https://spider.cloud/) - Concurrent crawler and scraper API with LLM-ready output. Free tier and paid plans.  
	[Spider](https://spider.cloud/) - 可同时运行的爬虫和抓取 API，支持 LLM 格式的输出。提供免费套餐和付费方案。
- [WebScraping.AI](https://webscraping.ai/) - Scraping API with question-answering and field-extraction endpoints. Free tier and paid plans.  
	[WebScraping.AI](https://webscraping.ai/) - 提供问答和字段提取接口的抓取 API。提供免费套餐和付费方案。
- [Scrapeless](https://www.scrapeless.com/) - Scraping API with anti-bot bypass and structured extraction. Free tier and paid plans.  
	[Scrapeless](https://www.scrapeless.com/) - 具有反机器人绕过和结构化数据提取功能的抓取 API。提供免费版和付费版。
- [Kadoa](https://www.kadoa.com/) - Self-healing extraction that adapts when sites change. Paid.  
	[Kadoa——](https://www.kadoa.com/) 一种可根据皮肤变化自动调节的自愈式提取技术。付费。
- [Expand.ai](https://www.expand.ai/) - Turns any website into a type-safe API. Paid.  
	[Expand.ai——](https://www.expand.ai/) 将任何网站转换为类型安全的 API。付费。
- [Reworkd](https://reworkd.ai/) - Agentic AI for no-code structured extraction. Paid.  
	[Reworkd](https://reworkd.ai/) - 用于无代码结构化数据提取的智能体人工智能。付费。

## Browser Infrastructure for AI人工智能浏览器基础设施

Headless browsers designed for AI agents and scrapers.  
专为人工智能代理和爬虫程序设计的无头浏览器。

- [Steel.dev](https://steel.dev/) - Open-source headless browser API for AI agents. Self-host or use the hosted service.  
	[Steel.dev](https://steel.dev/) - 面向人工智能代理的开源无头浏览器 API。可自行托管或使用托管服务。
- [Browserbase](https://www.browserbase.com/) - Hosted headless browser. Powers Stagehand. Paid.  
	[Browserbase——](https://www.browserbase.com/) 托管式无头浏览器。为 Stagehand 提供支持。付费。
- [Hyperbrowser](https://www.hyperbrowser.ai/) - Browser platform with stealth, scraping, and agent endpoints. Free tier and paid plans.  
	[Hyperbrowser——](https://www.hyperbrowser.ai/) 一款浏览器平台，具备隐身、爬虫和代理端点功能。提供免费套餐和付费方案。
- [Anchor Browser](https://anchorbrowser.io/) - Browser API with built-in auth and session persistence. Paid.  
	[Anchor Browser——](https://anchorbrowser.io/) 内置身份验证和会话持久性的浏览器 API。付费。
- [Browserless](https://www.browserless.io/) - Headless Chrome as a service. Free tier and paid plans.  
	[Browserless——](https://www.browserless.io/) 无头 Chrome 即服务。提供免费套餐和付费方案。
- [Obscura](https://github.com/h4ckf0r0day/obscura) - Rust-based headless browser. CDP-compatible with Puppeteer and Playwright. Built-in stealth and tracker blocking.  
	[Obscura](https://github.com/h4ckf0r0day/obscura) - 基于 Rust 的无头浏览器。兼容 CDP，支持 Puppeteer 和 Playwright。内置隐身功能和追踪器拦截。
- [Browserable](https://github.com/browserable/browserable) - Open-source, self-hostable browser automation library.  
	[Browserable——](https://github.com/browserable/browserable) 开源、可自托管的浏览器自动化库。

## No-Code AI Scrapers无代码人工智能爬虫

Visual or point-and-click tools that use AI to extract data without writing code.  
利用人工智能提取数据而无需编写代码的可视化或点击式工具。

- [Browse AI](https://www.browse.ai/) - Chrome extension and SaaS for AI-assisted scraping with scheduled monitoring.  
	[浏览 AI](https://www.browse.ai/) - Chrome 扩展程序和 SaaS，用于 AI 辅助抓取并进行定时监控。
- [Bardeen.ai](https://bardeen.ai/) - Chrome extension combining AI scraping with automation across 100+ apps.  
	[Bardeen.ai](https://bardeen.ai/) - Chrome 扩展程序，将 AI 抓取与自动化相结合，支持 100 多个应用程序。
- [Thunderbit](https://thunderbit.com/) - Two-click Chrome extension with AI "Suggest Fields" for instant extraction.  
	[Thunderbit](https://thunderbit.com/) - 只需点击两下即可使用 AI“建议字段”功能的 Chrome 扩展程序，实现即时提取。
- [Gumloop](https://www.gumloop.com/) - Visual workflow builder for scraping, LLM calls, and data transforms.  
	[Gumloop](https://www.gumloop.com/) - 用于抓取、LLM 调用和数据转换的可视化工作流构建器。
- [Octoparse](https://www.octoparse.com/) - Visual scraper with AI-assisted field detection.  
	[Octoparse](https://www.octoparse.com/) - 具有 AI 辅助字段检测功能的视觉爬虫。
- [ParseHub](https://www.parsehub.com/) - Visual scraper with template-based extraction.  
	[ParseHub](https://www.parsehub.com/) - 基于模板提取的可视化爬虫。

## MCP Servers for Scraping用于网络爬虫的 MCP 服务器

[Model Context Protocol](https://modelcontextprotocol.io/) servers that expose scraping capabilities to Claude, Cursor, Windsurf, and other LLM clients.  
[模型上下文协议](https://modelcontextprotocol.io/) 服务器向 Claude、Cursor、Windsurf 和其他 LLM 客户端公开抓取功能。

- [Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server) - Official MCP wrapper for Firecrawl's scrape, crawl, and extract endpoints.  
	[Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server) - Firecrawl 抓取、爬取和提取端点的官方 MCP 封装。
- [Bright Data MCP](https://github.com/brightdata/brightdata-mcp) - Search, scrape, and extract from 60+ sources with anti-bot bypass. 5,000 free requests/month.  
	[Bright Data MCP](https://github.com/brightdata/brightdata-mcp) - 可从 60 多个数据源搜索、抓取和提取数据，并具备反机器人绕过功能。每月 5,000 次免费请求。
- [Scrapling MCP](https://scrapling.readthedocs.io/en/latest/ai/mcp-server/) - Built-in MCP server bundled with [Scrapling](https://github.com/D4Vinci/Scrapling). Install with `pip install "scrapling[ai]"`.  
	[Scrapling MCP](https://scrapling.readthedocs.io/en/latest/ai/mcp-server/) - [Scrapling](https://github.com/D4Vinci/Scrapling) 内置的 MCP 服务器。使用 `pip install "scrapling[ai]"` 安装。
- [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Anthropic's official fetch MCP server. URL-to-Markdown.  
	[Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Anthropic 的官方 Fetch MCP 服务器。URL 转 Markdown。
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - MCP server exposing Browserbase sessions and Stagehand primitives.  
	[Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - MCP 服务器，公开 Browserbase 会话和 Stagehand 原语。
- [Puppeteer MCP](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/puppeteer) - Browser automation for scraping and interaction.  
	[Puppeteer MCP](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/puppeteer) - 用于抓取和交互的浏览器自动化。
- [Apify MCP](https://github.com/apify/actors-mcp-server) - Run any Apify Actor as an MCP tool.  
	[Apify MCP](https://github.com/apify/actors-mcp-server) - 将任何 Apify Actor 作为 MCP 工具运行。
- [WebScraping.AI MCP](https://webscraping.ai/docs/mcp) - MCP integration for WebScraping.AI's extraction tools.  
	[WebScraping.AI MCP](https://webscraping.ai/docs/mcp) - MCP 集成，用于 WebScraping.AI 的提取工具。

## Web Search APIs for LLMs面向法学硕士的 Web 搜索 API

Search APIs that return structured, LLM-friendly results with full-page content.  
搜索 API 返回结构化的、LLM 友好的结果，并包含完整的页面内容。

- [Exa](https://exa.ai/) - Neural search API. Returns clean content alongside results.  
	[Exa](https://exa.ai/) - 神经搜索 API。除了搜索结果外，还会返回干净的内容。
- [Tavily](https://tavily.com/) - Search API optimized for LLMs and RAG.  
	[Tavily](https://tavily.com/) - 针对 LLM 和 RAG 优化的搜索 API。
- [Linkup](https://www.linkup.so/) - Search API with verified sources.  
	[Linkup](https://www.linkup.so/) - 拥有经过验证来源的搜索 API。
- [Perplexity Sonar](https://docs.perplexity.ai/) - Perplexity's online search and answer API.  
	[Perplexity Sonar](https://docs.perplexity.ai/) - Perplexity 的在线搜索和答案 API。
- [Serper](https://serper.dev/) - Fast, low-cost Google search API.  
	[Serper](https://serper.dev/) - 快速、低成本的谷歌搜索 API。
- [SerpAPI](https://serpapi.com/) - Search engine results API.  
	[SerpAPI](https://serpapi.com/) - 搜索引擎结果 API。
- [Brave Search API](https://brave.com/search/api/) - Independent search index.  
	[Brave Search API](https://brave.com/search/api/) - 独立搜索索引。
- [You.com API](https://api.you.com/) - Web, news, and snippet endpoints.  
	[You.com API](https://api.you.com/) - Web、新闻和摘要端点。
- [Kagi Search API](https://help.kagi.com/kagi/api/search.html) - Premium, ad-free search results.  
	[Kagi 搜索 API](https://help.kagi.com/kagi/api/search.html) - 高级、无广告搜索结果。

## Proxy & Anti-Bot Infrastructure代理和反机器人基础设施

- [Bright Data](https://brightdata.com/) - 150M+ proxies, Web Unblocker, browser cloud.  
	[Bright Data](https://brightdata.com/) - 1.5 亿+代理服务器、网页解锁器、浏览器云服务。
- [Oxylabs](https://oxylabs.io/) - Residential, datacenter, and ISP proxies plus Web Unblocker.  
	[Oxylabs](https://oxylabs.io/) - 住宅、数据中心和 ISP 代理，以及 Web Unblocker。
- [Decodo (Smartproxy)](https://decodo.com/) - Residential proxies and scraping APIs.  
	[Decodo（Smartproxy）](https://decodo.com/) - 住宅代理和抓取 API。
- [NetNut](https://netnut.io/) - ISP and residential proxy network.  
	[NetNut](https://netnut.io/) - 互联网服务提供商和住宅代理网络。
- [ZenRows](https://www.zenrows.com/) - Anti-bot proxy and scraping API.  
	[ZenRows](https://www.zenrows.com/) - 反机器人代理和爬虫 API。
- [ScraperAPI](https://www.scraperapi.com/) - Proxy rotation and CAPTCHA handling.  
	[ScraperAPI](https://www.scraperapi.com/) - 代理轮换和验证码处理。

## Datasets数据集

Pre-scraped web data for RAG, training, or benchmarking.  
用于 RAG、训练或基准测试的预先抓取的网络数据。

- [Common Crawl](https://commoncrawl.org/) - The largest public web crawl. Petabytes of pages, monthly updates.  
	[Common Crawl——](https://commoncrawl.org/) 规模最大的公共网络爬虫。抓取 PB 级页面，每月更新。
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 15T-token deduplicated web dataset from Hugging Face.  
	[FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 来自 Hugging Face 的 15T 标记去重网络数据集。
- [RedPajama-Data-v2](https://github.com/togethercomputer/RedPajama-Data) - 30T-token open web dataset.  
	[RedPajama-Data-v2](https://github.com/togethercomputer/RedPajama-Data) - 30T 令牌开放网络数据集。
- [C4](https://huggingface.co/datasets/allenai/c4) - Colossal Clean Crawled Corpus derived from Common Crawl.  
	[C4](https://huggingface.co/datasets/allenai/c4) - 源自 Common Crawl 的巨型清洁爬取语料库。
- [The Pile](https://pile.eleuther.ai/) - 825 GiB diverse text corpus including web data.  
	[The Pile](https://pile.eleuther.ai/) - 包含网络数据的 825 GiB 多样化文本语料库。

## Benchmarks & Research基准与研究

- [SWDE](https://www.microsoft.com/en-us/research/publication/from-one-tree-to-a-forest-a-unified-solution-for-structured-web-data-extraction/) - Structured Web Data Extraction benchmark from Microsoft Research.  
	[SWDE](https://www.microsoft.com/en-us/research/publication/from-one-tree-to-a-forest-a-unified-solution-for-structured-web-data-extraction/) - 微软研究院的结构化 Web 数据提取基准测试。
- [WebSRC](https://x-lance.github.io/WebSRC/) - Dataset for web-based structural reading comprehension.  
	[WebSRC](https://x-lance.github.io/WebSRC/) - 基于网络的结构化阅读理解数据集。
- [AXE](https://arxiv.org/abs/2406.06237) - Research on DOM pruning for token-efficient LLM extraction.  
	[AXE](https://arxiv.org/abs/2406.06237) - 研究 DOM 修剪以实现高效的 LLM 提取。
- [NEXT-EVAL](https://arxiv.org/abs/2503.05036) - Benchmark comparing HTML representations for LLM extraction accuracy.  
	[NEXT-EVAL](https://arxiv.org/abs/2503.05036) - 比较 HTML 表示形式在 LLM 提取准确性方面的基准测试。

## Tutorials & Guides教程与指南

- [Firecrawl Docs](https://docs.firecrawl.dev/) - Guides for RAG ingestion, structured extraction, and agent integration.  
	[Firecrawl 文档](https://docs.firecrawl.dev/) - RAG 摄取、结构化提取和代理集成指南。
- [Crawl4AI Documentation](https://docs.crawl4ai.com/) - Walk-throughs for LLM-based extraction strategies.  
	[Crawl4AI 文档](https://docs.crawl4ai.com/) - 基于 LLM 的提取策略演练。
- [Jina Reader Quickstart](https://jina.ai/reader/) - One-line URL conversion.  
	[Jina Reader 快速入门](https://jina.ai/reader/) - 单行 URL 转换。
- [LangChain Web Loaders](https://python.langchain.com/docs/integrations/document_loaders/) - Document loaders for web content.  
	[LangChain Web Loaders](https://python.langchain.com/docs/integrations/document_loaders/) - 用于网页内容的文档加载器。
- [LlamaIndex Web Connectors](https://llamahub.ai/) - Web data connectors for LlamaIndex.  
	[LlamaIndex Web Connectors](https://llamahub.ai/) - LlamaIndex 的 Web 数据连接器。

## Contributing贡献

Contributions welcome. Open a pull request to add a new tool or resource.  
欢迎贡献代码。提交 pull request 即可添加新工具或资源。

Guidelines:  
指南：

- Keep entries focused on AI/LLM-powered scraping. Generic scrapers belong elsewhere.  
	条目应重点关注基于人工智能/LLM 的爬虫技术。通用爬虫技术应放在其他地方。
- Follow the format: `- [Name](url) - One-line description.`  
	请按照以下格式操作： `- [Name](url) - One-line description.`
- Add the GitHub stars badge for open-source projects.  
	为开源项目添加 GitHub 星标徽章。
- Mention pricing in the description if relevant (free tier, paid, etc.).  
	如果相关，请在描述中提及价格（免费版、付费版等）。

## License执照

To the extent possible under law, the contributors have waived all copyright and related rights to this work.  
在法律允许的范围内，贡献者已放弃对本作品的所有版权及相关权利。