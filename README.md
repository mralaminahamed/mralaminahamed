<h1 align="center">Al Amin Ahamed</h1>

<p align="center">
  <strong>Senior Software Engineer &nbsp;·&nbsp; Rust Services &nbsp;·&nbsp; AI Infrastructure</strong>
</p>

<p align="center">
  Rust &nbsp;·&nbsp; Python &nbsp;·&nbsp; TypeScript &nbsp;·&nbsp; Go &nbsp;·&nbsp; PHP &nbsp;·&nbsp; React &nbsp;·&nbsp; WordPress Polyglots Translation Editor
</p>

<p align="center">
  <a href="https://alaminahamed.com">alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="mailto:alamin.ahamed.dev@gmail.com">alamin.ahamed.dev@gmail.com</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/mralaminahamed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://profiles.wordpress.org/mralaminahamed/">WordPress.org</a>
</p>

---

Senior software engineer building Rust services and AI infrastructure. I am Team Lead of Product at [@codexpertio](https://github.com/codexpertio), Dhaka, where I own commercial commerce products end to end. Rust became my primary stack in October 2026; before that I spent years shipping payment systems, marketplaces and retrieval-based AI in PHP, Python and Go. Since 2025 most of my work has been putting retrieval and agents where an answer has to be correct, cited, and cheap to serve.

**Anthropic Certified** — Claude API · MCP · Subagents · Agentic Workflows · Claude Code · AI Fluency.

---

### Rust

New services, daemons and tools start in Rust. The plan, its milestones and the status of each are public at [alaminahamed.com/rust](https://alaminahamed.com/rust).

**[tundra](https://github.com/mralaminahamed/tundra)** `6★`
Self-hosted server-management platform — an alternative to Plesk and cPanel. Full operator control, native deployment of WordPress, Laravel, Node.js, Python, Go and Rust applications.
`Rust` `React` `DevOps`

**[valet-manager](https://github.com/mralaminahamed/valet-manager)**
Native Linux desktop application for managing Laravel Valet environments.
`Rust` `Linux` `Desktop`

---

### Products

Commercial work. Most repositories are private; this is what the code does.

**[Squad Modules](https://squadmodules.com)** — [The WP Squad](https://thewpsquad.com)
65 free modules and 8 extensions from a single codebase. All 65 run natively in the Divi 5 Visual Builder Block API and 64 also run in the classic Divi 4 builder, so existing layouts keep working. Plus the Pro tier and a Divi-native affiliate product with first-party referral and coupon tracking. [Squad Modules Lite on WordPress.org](https://wordpress.org/plugins/squad-modules-for-divi/)
`PHP` `React` `Divi 5 Block API`

**[NiroHelp](https://nirohelp.com)** — AI-native help desk for WordPress
Knowledge base, ticketing with eight stages and automatic assignment, email piping over IMAP or POP3, and a dashboard with a copilot that answers questions about the support queue itself. The chatbot answers from the site's own docs behind one script tag; the auto-responder replies only when the docs clear a confidence threshold and stays quiet when they do not. One-click migration from BetterDocs, weDocs, Echo KB, BasePress, Awesome Support, SupportCandy and JS Help Desk. Docs stay WordPress posts, tickets stay posts, replies stay comments, and the help desk runs with no external service unless the AI is switched on. Free core [on WordPress.org](https://wordpress.org/plugins/nirohelp/); part of the [Niro Suite](https://nirosuite.com).
`PHP` `REST API` `RAG` `Next.js`

**[Uposham](https://uposham.com)** — telehealth for Bangladesh, live
Booked entirely inside Facebook Messenger: no app, no account. The assistant reads the complaint in Bangla, English or romanized Bangla, maps it to a specialty, shows BMDC-verified doctors with their fees and open slots, books, takes payment via bKash, Nagad or Rocket, delivers the video call link, and returns the prescription to the same thread. Around 70 verified doctors across 15 specialties at ৳200 to ৳800 a visit. API-first WordPress backend with roughly 50 REST routes, three Next.js apps including a Capacitor build for the doctor dashboard, per-actor auth, and signed outbound webhooks so the bot is replaceable.
`PHP` `Next.js` `Capacitor` `LLM agent` `bKash / Nagad`

**[PluginTracker](https://plugintracker.dev)** — 900+ plugins tracked, 820+ authors
Analytics for WordPress.org plugin authors. The directory floors active installs to one significant figure and keeps no history; PluginTracker reads what it publishes daily and adds granular install estimates, keyword rank tracking, competitor movement, review and support-ticket health, alerts and AI-drafted replies. Alongside it, an opt-in Composer telemetry SDK reports PHP and WordPress versions, release spread and deactivation reasons: nothing is sent before a site admin consents, the author chooses which fields exist at all, and an opt-out applies at ingestion so it reaches installs already in the wild.
`PHP` `Next.js` `Composer` `Telemetry`

**[EasyCommerce](https://easycommerce.dev)** — [Codexpert](https://codexpert.io)
AI-first commerce plugin built on dedicated database tables rather than WordPress posts, for 3 to 5 times the throughput of post-based stores. I built the integration surface across fourteen repositories: Paystack, Razorpay, HitPay, 2Checkout, UnionPay, ShipStation, FedEx, DHL, Zapier, subscriptions and licensing. Rated 4.7 on [WordPress.org](https://wordpress.org/plugins/easycommerce/).
`PHP` `REST API` `Payments` `LLM`

**[WC Affiliate](https://wcaffiliate.com)** — WooCommerce-native affiliate program, 4.6 from 280+ users
Admin and affiliate dashboards in React over a REST API, trait-based PHP, multi-level commissions, coupon-based tracking, a shortlink generator, affiliate banners, and automatic payouts through PayPal, Stripe, Wise and Payoneer. I built the cross-domain cookie sharing that keeps attribution intact when a referral moves between separate storefronts, funnels or microsites. Now at v3, free core [on WordPress.org](https://wordpress.org/plugins/wc-affiliate/).
`PHP` `React` `WooCommerce` `Payouts`

**[ThumbPress](https://thumbpress.co)** — 30,000+ active installs
Image optimization and media management: compression, WebP and AVIF conversion, thumbnail control, duplicate and unused-image detection, lazy loading and hotlink protection, with its own CDN gateway and origin service. [On WordPress.org](https://wordpress.org/plugins/image-sizes/).
`PHP` `TypeScript` `CDN`

**Postimatic** — AI content generation for WordPress · [@commandcenterio](https://github.com/commandcenterio)
Keyword-to-published-post runners, bulk post refinement, and marker-based mapping so regenerated sections land back in the right place. Client product, private repository.
`PHP` `Elementor` `LLM`

**[Dokan](https://github.com/getdokan/dokan)** — weDevs, 2024 to 2025
60 merged pull requests and 17 code reviews across Dokan, Dokan Invoice, wePOS and WooCommerce Conversion Tracking, as an engineer at weDevs. Vendor dashboards, commission logic, subscription and invoicing fixes, WooCommerce REST API work. Dokan serves 60,000+ active businesses.
`PHP` `React` `WooCommerce`

**Payments and fulfilment**
Production integrations for Stripe, PayPal, bKash, Paystack, GoCardless, Razorpay, HitPay and 2Checkout; ShipStation, Shippo, FedEx and DHL. Webhooks, idempotency, refunds, HPOS.
Public: [wc-paystack](https://github.com/mralaminahamed/wc-paystack) · [wc-gocardless-payments](https://github.com/mralaminahamed/wc-gocardless-payments)

**Laravel applications**
Twelve applications outside the WordPress stack: a CMS, a school management system, a property-management aggregator, client SaaS products, and the WP Squad support app and marketing site.
`Laravel` `Livewire` `React` `MySQL`

---

### AI Systems

**[wp-support-rag](https://github.com/mralaminahamed/wp-support-rag)**
Self-hosted RAG support desk for plugin authors. Ingests GitHub issues and WordPress.org forum threads, answers with citations, and degrades to source links rather than guessing when the model is unavailable. FastAPI + pgvector + Celery backend, React/Tailwind admin, embeddable widget, Playwright E2E, Turborepo monorepo.
`Python` `FastAPI` `pgvector` `Celery` `Redis` `OpenAI` `Anthropic` `TypeScript` `React` `Docker`

**[codebase-research-agent](https://github.com/mralaminahamed/codebase-research-agent)**
ReAct tool-using agent over hybrid code retrieval: pgvector cosine + BM25 + symbol graph via RRF. AST-aware chunking via tree-sitter. Cloud or fully local (Ollama) for proprietary code. Exposed as a **Claude Code MCP server** with streaming SSE and file/line citations.
`Python` `FastAPI` `tree-sitter` `pgvector` `MCP SDK` `Anthropic` `OpenAI` `Docker`

**[codetrail](https://github.com/mralaminahamed/codetrail)**
The same problem in Go: codebase question answering with citations verifiable against the commit they came from. AST-aware chunking, symbol graph, Postgres and pgvector.
`Go` `React` `PostgreSQL` `pgvector`

**[legal-rag](https://github.com/mralaminahamed/legal-rag)**
Legal document RAG. Section-scoped chunking + exemplar prompting. Edit distance: 168 → 43 on held-out eval. CI eval suite on every commit.
`Python` `pgvector` `Anthropic` `FastAPI` `PostgreSQL`

**[bd-legal-rag](https://github.com/mralaminahamed/bd-legal-rag)**
RAG service for Bangladeshi statute law — bilingual Bengali/English, section-hierarchy-aware chunking, Cohere multilingual embeddings, mandatory rerank, grounded answers with canonical legal citations.
`Python` `pgvector` `Cohere` `FastAPI` `PostgreSQL`

**[jobpulse-rag](https://github.com/mralaminahamed/jobpulse-rag)**
Job discovery across 12 sources behind one async adapter protocol, with resume-grounded scoring and cover letter generation.
`Python` `FastAPI` `pgvector` `Celery` `React`

**[wp-dev-skills](https://github.com/mralaminahamed/wp-dev-skills)** `27★`
WordPress plugin development skills for AI coding agents — Claude Code, Gemini CLI, Cursor, Windsurf, Cline, Codex, GitHub Copilot, opencode, and more. Skills activate automatically when their description matches the task. Alongside [wordpress-official-agent-skills](https://github.com/mralaminahamed/wordpress-official-agent-skills) and [scrumloop](https://github.com/mralaminahamed/scrumloop), which runs sprint ceremonies and backlog grooming against GitHub Projects v2.
`WordPress` `Claude Code` `Agent Skills` `PHP`

**WordPress AI Providers (original — published on WordPress.org)**
[ai-provider-for-minimax](https://github.com/mralaminahamed/ai-provider-for-minimax) · [ai-provider-for-opencode-zen](https://github.com/mralaminahamed/ai-provider-for-opencode-zen) — MiniMax and OpenCode Zen adapters for the WordPress AI Client ecosystem.
`PHP` `WordPress`

---

### Go & Systems

**[sitemon](https://github.com/mralaminahamed/sitemon)**
Site-health monitoring as six services over NATS JetStream: HTTP, SSL and load-testing checks, MongoDB history, Redis-cached status, Slack / Discord / Telegram alerting, React 19 dashboard, Claude-written incident summaries via the Anthropic Go SDK, and an MCP server. Prometheus and Grafana, Docker and Kubernetes manifests, race-tested CI gate.
`Go` `NATS` `MongoDB` `React` `Kubernetes`

**[flagcast](https://github.com/mralaminahamed/flagcast)**
Feature flags and experimentation: five services over gRPC and NATS, MongoDB behind a Redis cache, React console, rollout analysis via the Anthropic Go SDK, MCP server exposing flag operations as agent tools. Deployed to AWS ECS Fargate via Terraform.
`Go` `gRPC` `NATS` `Terraform` `AWS`

**triagepilot** — private
AI support-triage desk. Drafts a cited reply and proposes tags, severity and routing, then stops: nothing the model produces reaches a ticket until a human presses Apply. RAG over a knowledge base and past tickets, agentic tool-use loop, Qdrant vector search, MCP.
`Go` `React` `Qdrant` `MCP` `RAG`

**carelane** — private, in progress
Multi-market telehealth: the patient books, pays, holds the consultation and receives a prescription, and the platform pays doctors and issues refunds without a human moving money by hand. Region is the deployment unit and the global plane holds no PHI, enforced at build time.
`Go` `PostgreSQL` `Multi-region`

**[reclaim](https://github.com/mralaminahamed/reclaim)**
Process-aware storage reclamation CLI for Ubuntu and Debian. Tiered, dry-run by default, no third-party dependencies.
`Go` `CLI` `Linux`

---

### Developer Tooling

**PHPStan stubs for the WordPress ecosystem** — 18 published
Static analysis on a plugin stops at the first call into another plugin's code. These Composer packages fix that.
[WooCommerce Subscriptions](https://github.com/mralaminahamed/phpstan-woocommerce-subscriptions-stubs) · [Product Add-Ons](https://github.com/mralaminahamed/phpstan-woocommerce-product-addons-stubs) · [Action Scheduler](https://github.com/mralaminahamed/phpstan-action-scheduler-stubs) · [Easy Digital Downloads](https://github.com/mralaminahamed/phpstan-easy-digital-downloads-stubs) · [EDD Pro](https://github.com/mralaminahamed/phpstan-easy-digital-downloads-pro-stubs) · [Freemius SDK](https://github.com/mralaminahamed/phpstan-freemius-stubs) · [SureCart](https://github.com/mralaminahamed/phpstan-surecart-stubs) · [StoreEngine](https://github.com/mralaminahamed/phpstan-storeengine-stubs) · [Fluent Cart](https://github.com/mralaminahamed/phpstan-fluent-cart-stubs) · [Fluent Cart Pro](https://github.com/mralaminahamed/phpstan-fluent-cart-pro-stubs) · [FluentCRM](https://github.com/mralaminahamed/phpstan-fluent-crm-stubs) · [Fluent Forms](https://github.com/mralaminahamed/phpstan-fluent-forms-stubs) · [WPForms Lite](https://github.com/mralaminahamed/phpstan-wpforms-lite-stubs) · [Ninja Forms](https://github.com/mralaminahamed/phpstan-ninja-forms-stubs) · [Forminator](https://github.com/mralaminahamed/phpstan-forminator-stubs) · [Secure Custom Fields](https://github.com/mralaminahamed/phpstan-secure-custom-fields-stubs) · [EasyCommerce](https://github.com/mralaminahamed/phpstan-easycommerce-stubs) · [Squad Modules](https://github.com/mralaminahamed/phpstan-squad-modules-lite-stubs)

**[wp-pgsql-database](https://github.com/mralaminahamed/wp-pgsql-database)**
Drop-in `wpdb` replacement that runs WordPress on PostgreSQL instead of MySQL, following the SQLite drop-in pattern.

**[easycommerce-fakerpress](https://github.com/mralaminahamed/easycommerce-fakerpress)** `17★`
Test data generator for WordPress eCommerce — 14 generators, WP-CLI integration, 131 Playwright E2E tests. [storeseeder](https://github.com/mralaminahamed/storeseeder) goes further: whole shops from a recipe file, one driver per store plugin, live preview and a batch queue.

**[wp-cli-magic-login](https://github.com/mralaminahamed/wp-cli-magic-login)**
One-command admin login links, with mu-plugin installation and Valet site path resolution.

**[author-profile-blocks](https://github.com/mralaminahamed/author-profile-blocks)**
Gutenberg block library for rich author bios, social links, and responsive profile grids. Published on WordPress.org.

---

### Core Stack

| Layer | Technologies |
|---|---|
| **AI / LLM** | Anthropic Claude · OpenAI · Gemini · DeepSeek · Ollama · pgvector · MCP SDK · LangChain · tree-sitter |
| **Languages** | Rust · Python 3.12 · TypeScript · Go · PHP 8.x |
| **Backend** | WordPress · WooCommerce · Laravel · FastAPI · gRPC · NATS · REST · WebSocket · WP-CLI |
| **Frontend** | React 18/19 · Next.js · TypeScript · Tailwind CSS · Vite · Gutenberg &amp; Divi 5 Block APIs |
| **Data** | PostgreSQL + pgvector · MySQL · MongoDB · Redis · SQLite |
| **DevOps** | Docker · Kubernetes · Terraform · GitHub Actions CI/CD · AWS ECS · Hetzner · WordPress.org SVN |
| **Observability** | Prometheus · Grafana · OpenTelemetry · structlog |
| **Testing** | PHPUnit · Brain\Monkey · PHPStan · PHPCS · pytest · mypy strict · Playwright |

---

### GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mralaminahamed&show_icons=true&hide_border=true&count_private=true&theme=dark&bg_color=0d1117&title_color=c9d1d9&text_color=8b949e&icon_color=58a6ff" width="48%" />
  <img src="https://streak-stats.demolab.com/?user=mralaminahamed&theme=dark&background=0d1117&hide_border=true&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9" width="48%" />
</p>

---

### Community

- **[WordPress.org Plugin Developer](https://profiles.wordpress.org/mralaminahamed/)** — 13 plugins published on my account:
  [Squad Modules Lite](https://wordpress.org/plugins/squad-modules-for-divi/) (1,000+ installs) · [Squad Form Styler](https://wordpress.org/plugins/form-styler-for-divi/) (100+) · [Squad Post Grid](https://wordpress.org/plugins/post-grid-module-for-divi/) (70+) · [AI Provider for MiniMax](https://wordpress.org/plugins/alamin-ai-provider-for-minimax/) · [AI Provider for OpenCode Zen](https://wordpress.org/plugins/alamin-ai-provider-for-opencode-zen/) · [StoreSeeder](https://wordpress.org/plugins/storeseeder/) · [StoreSheet](https://wordpress.org/plugins/storesheet/) · [EasyCommerce FakerPress](https://wordpress.org/plugins/easycommerce-fakerpress/) · [Warranty Cart](https://wordpress.org/plugins/warranty-cart/) · [Author Profile Blocks](https://wordpress.org/plugins/author-profile-blocks/) · [Swift Menu Duplicator](https://wordpress.org/plugins/swift-menu-duplicator/) · [Donation Router for GiveWP & PayPal](https://wordpress.org/plugins/alamin-donation-router/) · [Vendor Tasks for Dokan & ClickUp](https://wordpress.org/plugins/alamin-vendor-tasks-dokan-clickup/)
- Primary developer of four more published under employer accounts: WP Before After Image Slider, Reading Time & Progress Bar, Dokan Kits, EasyCommerce
- **Polyglots Bengali (bn_BD) Translation Editor** for WooCommerce (7M+ installs), Site Kit by Google (5M+), Dokan, EasyCommerce, FluentCart and Squad Modules Lite · contributor across 18 locales
- **Core and Polyglots team member** on WordPress.org since August 2021
- **WordCamp Dhaka 2025** — Sponsor Team · Contributor Day attendee
- **Anthropic Certified** — Claude API · MCP · Subagents · Agentic Workflows · Claude Code · AI Fluency (May 2026)

---

### Open to

Senior and lead engineering roles building Rust services and AI infrastructure, and at product companies working on commerce platforms, developer tooling, or applied AI. Happy to talk about commerce at scale, keeping large PHP codebases analysable, Go services over NATS, MCP server design, or putting retrieval somewhere it has to be correct.

---

<p align="center">
  <a href="https://alaminahamed.com">alaminahamed.com</a>
  &nbsp;·&nbsp;
  <a href="mailto:alamin.ahamed.dev@gmail.com">alamin.ahamed.dev@gmail.com</a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/mralaminahamed">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://profiles.wordpress.org/mralaminahamed/">WordPress.org</a>
</p>
