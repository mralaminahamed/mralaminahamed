<h1 align="center">Al Amin Ahamed</h1>

<p align="center">
  <strong>Senior Software Engineer &nbsp;·&nbsp; AI Integration &nbsp;·&nbsp; LLM Pipelines &nbsp;·&nbsp; RAG &nbsp;·&nbsp; Agentic Systems</strong>
</p>

<p align="center">
  PHP &nbsp;·&nbsp; Python &nbsp;·&nbsp; TypeScript &nbsp;·&nbsp; React &nbsp;·&nbsp; WordPress Core Contributor
</p>

<p align="center">
  <a href="https://alaminahamed.com">alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="mailto:me@alaminahamed.com">me@alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/mralaminahamed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://profiles.wordpress.org/mralaminahamed/">WordPress.org</a>
</p>

---

I build production AI systems — LLM pipelines, RAG architectures, and agentic workflows — and ship them inside real products used by real businesses.

As **Team Lead of Product** and **Senior Software Engineer** at [Codexpert, Inc.](https://codexpert.io), I lead **EasyCommerce**: an AI-powered WordPress eCommerce platform integrating OpenAI, Anthropic Claude, Gemini, and DeepSeek for automated product content generation, smart pricing logic, fraud detection, and predictive analytics. Custom database architecture delivering 3–5× faster performance than WooCommerce. 35% conversion uplift in beta.

4+ years of full-stack production engineering. 8 plugins independently authored on WordPress.org. Code contributed to products serving 60,000+ active businesses. WordPress Core Contributor since 2021.

---

### Core Stack

| Layer | Technologies |
|---|---|
| **AI / LLM** | OpenAI · Anthropic Claude · Gemini · DeepSeek · Ollama · LangChain · pgvector · RAG · MCP SDK |
| **Languages** | PHP 8.x · Python 3.12 · TypeScript · Go · Rust |
| **Backend** | FastAPI · Laravel · WordPress · REST · WebSocket · SSE · WP-CLI |
| **Frontend** | React 18 · TypeScript · Tailwind CSS · Vite · Gutenberg Block API · Inertia.js |
| **Data** | PostgreSQL + pgvector · MySQL · Redis · SQLite · Meilisearch |
| **DevOps** | Docker · GitHub Actions CI/CD · Caddy · Linux · Hetzner |
| **Testing** | PHPUnit · Brain\Monkey · PHPStan · pytest · Playwright · WP_Mock |

---

### AI Projects

**[JobPulse RAG](https://github.com/mralaminahamed/jobpulse-rag)**
AI-powered job discovery platform with RAG-grounded cover letter generation. Multi-source pipeline across 12 sources in 3 tiers: search engines (SerpAPI, JSearch), free boards (RemoteOK, WWR, Remotive, HN), and ATS public APIs (Greenhouse, Lever, Ashby, Workable, SmartRecruiters). Resume embedding via text-embedding-3-large + pgvector cosine retrieval — all cover letters grounded in actual resume content via Claude Sonnet. Composite scoring: semantic + BM25 + salary + geo.
`Python` `FastAPI` `pgvector` `Redis` `Celery` `OpenAI` `Anthropic` `React 18` `Tailwind` `Docker`

**[codebase-research-agent](https://github.com/mralaminahamed/codebase-research-agent)**
Tool-using ReAct AI agent that researches codebases through multi-step reasoning over a hybrid retrieval substrate. Agent loop wraps semantic search, AST navigation, symbol lookup, grep, and git blame as callable tools via OpenAI function calling and Anthropic tool use — iterates think → act → observe until grounded. Privacy-first dual mode: cloud (OpenAI + Claude Sonnet) or fully local (Ollama + deepseek-coder). Exposed as a **Claude Code MCP server** with streaming SSE and file/line citations.
`Python` `FastAPI` `tree-sitter` `pgvector` `BM25` `Ollama` `OpenAI` `Anthropic` `MCP SDK` `Docker`

**[Specialized Technical Assistant (RAG)](https://github.com/mralaminahamed/specialized-technical-assistant-rag)**
Domain-specific AI assistant pipeline grounded in your own documentation. Python-based RAG with LangChain, pgvector, PostgreSQL, Claude, and Sentence Transformers.
`Python` `LangChain` `pgvector` `PostgreSQL` `Claude` `Sentence Transformers`

---

### Production AI Engineering — EasyCommerce

**[EasyCommerce](https://wordpress.org/plugins/easycommerce/)** — Codexpert flagship product
AI-powered WordPress eCommerce plugin. I lead architecture and product engineering.

- AI content generation pipeline: OpenAI GPT-4o + Google Gemini for automated product descriptions, DALL·E 3 image generation, and personalised marketing copy
- Smart recommendation engine: vector similarity search + collaborative filtering — 35% conversion uplift in beta
- Anthropic Claude + DeepSeek as fallback providers with cost-aware routing and content-hash caching
- Fraud detection: behavioural analysis + predictive scoring integrated into checkout via REST API
- Dedicated database architecture delivering 3–5× performance gains vs WooCommerce
- LLM cost circuit breakers, prompt versioning, and structured evals

---

### WordPress & Open Source

**[EasyCommerce FakerPress](https://github.com/mralaminahamed/easycommerce-fakerpress)** `19★`
Realistic test data generator for EasyCommerce stores — 14 data generators, WP-CLI integration, 131 Playwright E2E tests.

**[Fluent Cart FakerPress](https://github.com/mralaminahamed/fluent-cart-fakerpress)**
Test data generation for Fluent Cart — locale-aware sample data, WP-CLI support.

**[EasyCommerce Email Tester](https://github.com/mralaminahamed/easycommerce-email-tester)**
Developer tool for testing, previewing, and debugging all EasyCommerce email notifications — dry-run preview, recipient override, placeholder detection.

**[Author Profile Blocks](https://github.com/mralaminahamed/author-profile-blocks)**
Gutenberg block library for rich author bios, social links, and responsive profile grids.

**[WP PostgreSQL Database](https://github.com/mralaminahamed/wp-pgsql-database)**
Drop-in `wpdb` replacement that runs full WordPress sites on PostgreSQL instead of MySQL.

**AI Providers for WordPress**
[Minimax AI Provider](https://github.com/mralaminahamed/ai-provider-for-minimax) · [OpenCode Zen AI Provider](https://github.com/mralaminahamed/ai-provider-for-opencode-zen) — pluggable AI backends for the WordPress AI Client ecosystem supporting Claude, OpenAI, and Gemini via a unified adapter interface.

**[Dokan Multivendor Marketplace](https://github.com/getdokan/dokan)** — open-source contributor
Active contributor to the leading WooCommerce multi-vendor platform (60,000+ active installs). Vendor dashboard features, commission logic, REST API integrations, documentation.

**PHPStan Stubs Collection**
Purpose-built stub packages enabling static analysis for major WordPress plugins that don't ship their own stubs:
[Freemius SDK](https://github.com/mralaminahamed/phpstan-freemius-stubs) · [WooCommerce Subscriptions](https://github.com/mralaminahamed/phpstan-woocommerce-subscriptions-stubs) · [Fluent Forms](https://github.com/mralaminahamed/phpstan-fluent-forms-stubs) · [WPForms Lite](https://github.com/mralaminahamed/phpstan-wpforms-lite-stubs) · [Forminator](https://github.com/mralaminahamed/phpstan-forminator-stubs) · [Squad Modules for Divi](https://github.com/mralaminahamed/phpstan-squad-modules-lite-stubs)

---

### GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mralaminahamed&show_icons=true&hide_border=true&count_private=true&theme=dark&bg_color=0d1117&title_color=c9d1d9&text_color=8b949e&icon_color=58a6ff" width="48%" alt="GitHub Stats" />
  <img src="https://streak-stats.demolab.com/?user=mralaminahamed&theme=dark&background=0d1117&hide_border=true&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9" width="48%" alt="GitHub Streak" />
</p>

---

### Community

- **WordPress Core Contributor** since August 2021 · 5 hrs/week
- **Polyglots Bengali (bn_BD) Translation Editor** — WooCommerce (7M+ installs), Site Kit by Google (5M+), Dokan, EasyCommerce, FluentCart · reviewed 8,000+ strings across 6 languages
- **WordCamp Dhaka 2025** — Sponsor Team · Contributor Day · Core Team table
- **Badges** — Plugin Developer · Translation Editor · Translation Contributor

---

### Open to

Technical discussions on AI systems, LLM pipeline architecture, RAG design, agentic workflows, WordPress plugin engineering, eCommerce platform design, and multi-vendor marketplace systems. Open-source collaboration, code reviews, and engineering mentorship welcome.

---

<p align="center">
  <a href="https://alaminahamed.com">alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="mailto:me@alaminahamed.com">me@alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/mralaminahamed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://profiles.wordpress.org/mralaminahamed/">WordPress.org</a>
</p>
