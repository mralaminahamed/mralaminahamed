# Al Amin Ahamed — AI-First Senior Software Engineer

**TypeScript · React · Next.js · Node.js · Python · Rust · Go · PHP** | AI agents, RAG and MCP servers | Backend services, payments and APIs | Dhaka, Bangladesh (remote)

[Portfolio](https://alaminahamed.com) · [LinkedIn](https://linkedin.com/in/mralaminahamed) · [Email](mailto:alamin.ahamed.dev@gmail.com) · [WordPress.org profile](https://profiles.wordpress.org/mralaminahamed/) · [Resume](https://alaminahamed.com/about/resume.txt)

## Summary

AI-first senior software engineer at [Codexpert](https://codexpert.io) (GitHub: [@codexpertio](https://github.com/codexpertio)), building commercial WordPress, WooCommerce and Next.js products and the AI features inside them. Working in web development since August 2021. I build production software in TypeScript, React, Next.js, Python, Rust, Go and PHP, and I build with AI coding agents (Claude Code, MCP servers, agent skills) while validating output with tests, evaluation suites and CI gates rather than trusting generated code.

- **AI engineering:** retrieval-augmented generation (RAG), tool-using LLM agents, MCP servers, pgvector hybrid search, multi-provider LLM routing (Anthropic Claude, OpenAI, Gemini, DeepSeek, Ollama), prompt versioning, LLM cost controls and evals in CI.
- **Product engineering:** AI features shipped to commerce, telehealth and help-desk products: product-description generation, fraud detection, recommendations, a Messenger booking assistant and a RAG auto-responder.
- **Backend and payments:** REST APIs, webhooks, idempotent payment flows, OAuth 2.0, relational schema design and query optimisation in PostgreSQL and MySQL; Stripe, PayPal, bKash, Paystack, GoCardless, Razorpay, HitPay and 2Checkout.
- **Leadership:** led a cross-functional PHP and React team as Team Lead of Product; architecture and code review, mentoring, internal AI learning sessions.
- **Certified:** six Anthropic certificates (Claude API, Model Context Protocol, Subagents, Claude Code, AI Fluency) and three Google certificates (Generative AI, LLMs, Responsible AI).

**Open to:** senior and lead roles in AI engineering, applied AI, full-stack and backend engineering, AI infrastructure, and Rust services; product companies in commerce, developer tooling and healthcare technology.

## Technical skills

| Area | Skills |
|---|---|
| AI and LLM | Generative AI, RAG, LLM agents, ReAct, tool use and function calling, MCP (Model Context Protocol), Claude Code, subagents, agent skills, prompt engineering, prompt versioning, LLM evaluation, embeddings, vector search, pgvector, BM25, reciprocal rank fusion, reranking, tree-sitter, LangChain, Anthropic Claude, OpenAI, Gemini, DeepSeek, Ollama, n8n automation |
| Languages | TypeScript, JavaScript (ES6+), Python 3.12, Rust, Go, PHP 8, SQL |
| Frontend | React 18 and 19, Next.js 16, Tailwind CSS, Vite, Capacitor, Gutenberg block development, Divi 5 block API |
| Backend | Node.js, FastAPI, Celery, Laravel, WordPress, WooCommerce, REST API design, gRPC, NATS JetStream, WebSocket, webhooks, OAuth 2.0, WP-CLI |
| Data | PostgreSQL, pgvector, MySQL, MongoDB, Redis, SQLite, schema design, indexing, query optimisation, caching |
| Payments | Stripe, PayPal, bKash, Nagad, Paystack, GoCardless, Razorpay, HitPay, 2Checkout, ShipStation, Shippo, FedEx, DHL |
| Cloud and DevOps | Docker, Kubernetes, Terraform, AWS ECS Fargate, GitHub Actions CI/CD, Linux, Caddy, Hetzner, Cloudflare |
| Observability | Prometheus, Grafana, OpenTelemetry |
| Testing and quality | Playwright, pytest, PHPUnit, Brain\Monkey, PHPStan, PHPCS, mypy (strict), ruff, end-to-end testing, evaluation datasets |
| Practice | System design, software architecture, code review, mentoring, Agile and Scrum, technical documentation, open-source maintenance |

## Experience

**Codexpert Inc., Dhaka** — Aug 2025 to present. Software Engineer, then Team Lead of Product (Nov 2025), then Senior Software Engineer.
- Senior Software Engineer: own architecture, performance and admin surfaces across the product line: EasyCommerce, Uposham (telehealth), NiroHelp (AI help desk), WC Affiliate, ThumbPress (image optimisation and CDN) and PluginTracker.
- Built an MCP server integration that exposes test-data generators to coding agents, and n8n workflows that turn changelogs into release posts with Gemini and Slack delivery.
- Run GitHub Actions CI/CD with PHPUnit, PHPStan and PHPCS gates; mentor junior and mid-level engineers.
- Team Lead of Product: led the product lifecycle of EasyCommerce, an AI-first commerce platform on dedicated database tables (3 to 5 times the throughput of post-based storage): architecture, prioritisation, release planning and team execution.
- Shipped AI features (product-description generation, image optimisation, fraud detection, recommendations) with up to a 35% conversion uplift in beta, and automated store creation that cut merchant setup time by about 70%.
- Software Engineer: built the modular platform core and the Stripe, PayPal and bKash integrations for checkout and payouts.

**Software Engineer** — weDevs, Dhaka · 2024 to 2025
- Dokan (60,000+ active installs), wePOS and WooCommerce Conversion Tracking: React vendor dashboards, commission logic, REST API integrations, Facebook and Google Ads tracking. 60 merged pull requests and 17 code reviews.

**Software Engineer** — Riseup Labs, Dhaka · 2023 to 2024
- Sole developer of two WordPress.org plugins; delivered themes, plugins and Elementor widgets with caching and query optimisation.

**Software Engineer, previously Software QA Engineer** — EchoaSoft, Dhaka · 2021 to 2023
- Moved from QA into engineering: block themes, Gutenberg blocks and Divi modules in React; contributor to Squad Modules for Divi.

## Education and certifications

- Post Graduate Diploma in Information Technology (Computer Engineering), Jahangirnagar University, 2023 to 2024.
- Anthropic: Building with the Claude API, Introduction to Model Context Protocol, Introduction to Subagents, Claude Code 101, Claude Code in Action, AI Fluency (2026).
- Google: Introduction to Generative AI, Introduction to Large Language Models, Introduction to Responsible AI (2026).

## AI projects

- **[codebase-research-agent](https://github.com/mralaminahamed/codebase-research-agent)** — Python, FastAPI, tree-sitter, pgvector, MCP SDK. ReAct tool-using agent over hybrid code retrieval (pgvector cosine, BM25 and symbol graph fused with reciprocal rank fusion), cloud or fully local with Ollama, exposed as a Claude Code MCP server with file and line citations.
- **[bd-legal-rag](https://github.com/mralaminahamed/bd-legal-rag)** — Python, FastAPI, PostgreSQL, pgvector, Celery. Bilingual Bengali and English RAG over Bangladeshi statute law with section-aware chunking, multilingual embeddings, mandatory reranking and cited answers.
- **[legal-rag](https://github.com/mralaminahamed/legal-rag)** — section-scoped chunking and exemplar prompting; edit distance fell from 168 to 43 on a held-out set, with an eval suite in CI.
- **[codetrail](https://github.com/mralaminahamed/codetrail)** — Go, React, PostgreSQL, pgvector. Codebase question answering with citations tied to the commit.
- **[wp-dev-skills](https://github.com/mralaminahamed/wp-dev-skills)** (28 stars) — agent skills for Claude Code, Gemini CLI, Cursor, Windsurf, Cline, Codex, GitHub Copilot and opencode.
- **[ai-provider-for-minimax](https://github.com/mralaminahamed/ai-provider-for-minimax)** and **[ai-provider-for-opencode-zen](https://github.com/mralaminahamed/ai-provider-for-opencode-zen)** — WordPress AI Client adapters, published on WordPress.org.
- **wp-support-rag**, **jobpulse-rag** and **scrumloop** (private) — a RAG support desk with an embeddable widget, a 12-source job-discovery platform with resume-grounded cover letters, and sprint automation on GitHub Projects v2.
- **triagepilot** (private) — Go, React, Qdrant, MCP. AI support triage that drafts a cited reply and waits for a human to apply it.

## Rust, Go and systems projects

- **[tundra](https://github.com/mralaminahamed/tundra)** (6 stars) — Rust and React. Self-hosted server-management platform, an alternative to Plesk and cPanel, with native deployment of WordPress, Laravel, Node.js, Python, Go and Rust applications. Plan and status: [alaminahamed.com/rust](https://alaminahamed.com/rust).
- **[valet-manager](https://github.com/mralaminahamed/valet-manager)** — Rust. Native Linux desktop app for Laravel Valet environments.
- **[sitemon](https://github.com/mralaminahamed/sitemon)** — Go, NATS JetStream, MongoDB, Redis, React 19, Kubernetes. Site-health monitoring in six services with Slack, Discord and Telegram alerts, Claude-written incident summaries and an MCP server.
- **[flagcast](https://github.com/mralaminahamed/flagcast)** — Go, gRPC, NATS, MongoDB, Terraform, AWS ECS Fargate. Feature flags and experimentation in five services with an MCP server.
- **[reclaim](https://github.com/mralaminahamed/reclaim)** — Go CLI for process-aware storage reclamation on Ubuntu and Debian.

## Product work (Next.js, PHP, WordPress, WooCommerce)

Commercial work. Most repositories are private.

- **[Uposham](https://uposham.com)** — telehealth for Bangladesh, booked inside Facebook Messenger. Bangla, English and romanised-Bangla assistant, BMDC-verified doctors, bKash, Nagad and Rocket payments, video consultation and prescriptions. API-first WordPress backend with about 50 REST routes, three Next.js 16 apps and a Capacitor build for the doctor dashboard.
- **[PluginTracker](https://plugintracker.dev)** — analytics for WordPress.org plugin authors: install estimates, keyword rank tracking, review and support health, alerts, AI-drafted replies and an opt-in Composer telemetry SDK. Next.js 16, React 19, PHP.
- **[NiroHelp](https://nirohelp.com)** — AI-native help desk for WordPress: knowledge base, ticketing, email piping, a docs-grounded chatbot and an auto-responder that stays quiet below a confidence threshold. Free core [on WordPress.org](https://wordpress.org/plugins/nirohelp/).
- **[EasyCommerce](https://easycommerce.dev)** — AI-first WooCommerce alternative on dedicated database tables, with Paystack, Razorpay, HitPay, 2Checkout, UnionPay, ShipStation, FedEx, DHL and Zapier integrations. Rated 4.7 on [WordPress.org](https://wordpress.org/plugins/easycommerce/).
- **[WC Affiliate](https://wcaffiliate.com)** — WooCommerce affiliate program with React dashboards, multi-level commissions, automatic payouts and cross-domain attribution. Rated 4.6.
- **[ThumbPress](https://thumbpress.co)** — 30,000+ active installs. Image compression, WebP and AVIF conversion, CDN gateway.
- **[Squad Modules](https://squadmodules.com)** — 65 free Divi modules that run in the Divi 5 Visual Builder. [Squad Modules Lite on WordPress.org](https://wordpress.org/plugins/squad-modules-for-divi/).
- **[Dokan](https://github.com/getdokan/dokan)** — multi-vendor marketplace plugin for WooCommerce, 60,000+ active businesses (contributor at weDevs).
- **Laravel applications** — a CMS, a school management system, a property-management aggregator and client SaaS products (Laravel, Livewire, React, MySQL).

## Developer tooling and open source

- **PHPStan stubs for the WordPress ecosystem** — 18 Composer packages, including [WooCommerce Subscriptions](https://github.com/mralaminahamed/phpstan-woocommerce-subscriptions-stubs), [Action Scheduler](https://github.com/mralaminahamed/phpstan-action-scheduler-stubs), [Freemius SDK](https://github.com/mralaminahamed/phpstan-freemius-stubs), [Easy Digital Downloads](https://github.com/mralaminahamed/phpstan-easy-digital-downloads-stubs), [Fluent Cart](https://github.com/mralaminahamed/phpstan-fluent-cart-stubs) and [SureCart](https://github.com/mralaminahamed/phpstan-surecart-stubs).
- **[wp-pgsql-database](https://github.com/mralaminahamed/wp-pgsql-database)** — drop-in `wpdb` replacement that runs WordPress on PostgreSQL.
- **[easycommerce-fakerpress](https://github.com/mralaminahamed/easycommerce-fakerpress)** (17 stars) — test-data generator with 14 generators, WP-CLI integration and 131 Playwright end-to-end tests. **[storeseeder](https://github.com/mralaminahamed/storeseeder)** builds whole shops from a recipe file.
- **[wc-paystack](https://github.com/mralaminahamed/wc-paystack)**, **[wc-gocardless-payments](https://github.com/mralaminahamed/wc-gocardless-payments)**, **[wp-cli-magic-login](https://github.com/mralaminahamed/wp-cli-magic-login)** and **[author-profile-blocks](https://github.com/mralaminahamed/author-profile-blocks)**.
- **WordPress.org plugin developer** — 13 plugins published on my account: [Squad Modules Lite](https://wordpress.org/plugins/squad-modules-for-divi/) (1,000+ active installs), [Squad Form Styler](https://wordpress.org/plugins/form-styler-for-divi/) (100+), [Squad Post Grid](https://wordpress.org/plugins/post-grid-module-for-divi/) (70+), [AI Provider for MiniMax](https://wordpress.org/plugins/alamin-ai-provider-for-minimax/), [AI Provider for OpenCode Zen](https://wordpress.org/plugins/alamin-ai-provider-for-opencode-zen/), [StoreSeeder](https://wordpress.org/plugins/storeseeder/), [StoreSheet](https://wordpress.org/plugins/storesheet/), [EasyCommerce FakerPress](https://wordpress.org/plugins/easycommerce-fakerpress/), [Warranty Cart](https://wordpress.org/plugins/warranty-cart/), [Author Profile Blocks](https://wordpress.org/plugins/author-profile-blocks/), [Swift Menu Duplicator](https://wordpress.org/plugins/swift-menu-duplicator/), [Donation Router for GiveWP & PayPal](https://wordpress.org/plugins/alamin-donation-router/) and [Vendor Tasks for Dokan & ClickUp](https://wordpress.org/plugins/alamin-vendor-tasks-dokan-clickup/). Primary developer of four more under employer accounts: WP Before After Image Slider, Reading Time & Progress Bar, Dokan Kits and EasyCommerce.
- **Community** — WordPress Core and Polyglots team member since August 2021; Bengali (bn_BD) Translation Editor since 2023 for WooCommerce, Site Kit by Google, Dokan, EasyCommerce, FluentCart and Squad Modules Lite (18 translations); WordCamp Sylhet attendee (2023, 2024); WordCamp Dhaka 2025 Sponsor Team and Contributor Day. Profile: [profiles.wordpress.org/mralaminahamed](https://profiles.wordpress.org/mralaminahamed/).

## Contact

[alaminahamed.com](https://alaminahamed.com) · [alamin.ahamed.dev@gmail.com](mailto:alamin.ahamed.dev@gmail.com) · [LinkedIn](https://linkedin.com/in/mralaminahamed) · [WordPress.org](https://profiles.wordpress.org/mralaminahamed/)

<!-- Keywords: AI-first senior software engineer, AI engineer, LLM engineer, generative AI, RAG engineer, MCP server, Claude Code, agentic workflows, full-stack engineer, backend engineer, TypeScript developer, React developer, Next.js developer, Node.js developer, Python developer, FastAPI, Rust developer, Go developer, PHP developer, Laravel developer, WordPress developer, WooCommerce developer, PostgreSQL, pgvector, payments integration, REST API, Dhaka, Bangladesh, remote -->
