# Brian Ramírez

**AI-native automation engineer.** I build LLM-augmented workflows and agents-with-tools, backed by a multi-year track record shipping production automation for retail and e-commerce teams.

📩 brian_d13@icloud.com · 💼 [linkedin.com/in/bdramirez](https://linkedin.com/in/bdramirez)

---

## What I build

**Agents and AI systems.** Telegram-native assistants built on a custom Claude tool-use loop (no LangChain), with multi-tier memory, pgvector RAG, structured outputs under strict JSON Schema, and prompt-injection defense in depth. One of them runs hardened and self-hosted under least privilege.

**Production automation at scale.** Python and JavaScript pipelines that pull, clean, and report on Amazon Seller Central, eBay, Walmart, and Best Buy. Scheduled jobs that replace hours of daily manual reporting, running unattended.

I currently lead workflow automation at **Focus Camera** (US retailer, fully remote) and freelance as a **Top Rated** Automation Engineer on [Upwork](https://www.upwork.com/freelancers/~012a3ee325020ff5ae) at 100% job success.

## Featured projects

**AI and agents**
- **[openclaw-assistant](https://github.com/dominicci13/openclaw-assistant)** — Hardened, self-hosted AI assistant on the OpenClaw gateway: Claude over Telegram with least-privilege mail (read and draft), a default-DENY egress proxy, and prompt-injection defense in depth.
- **[personal-ai-assistant](https://github.com/dominicci13/personal-ai-assistant)** — A Claude agent built from primitives: custom tool-use loop, 3-tier memory (identity, pgvector RAG, summarized history), 12 tools across calendar, email, and web. No framework.
- **[speed-to-lead-ai-responder](https://github.com/dominicci13/speed-to-lead-ai-responder)** — Classifies, scores, and replies to inbound leads using OpenAI Structured Outputs with strict JSON Schema. Built twice in parallel (n8n and Make.com).
- **[job-search-automation](https://github.com/dominicci13/job-search-automation)** — A scheduled Claude CLI agent that searches job markets, deduplicates, tailors per-role resumes, and emails an HTML digest.

**Marketplace automation**
- **[ebay-best-offers](https://github.com/dominicci13/ebay-best-offers)** — Nightly bot that accepts and counters pending Best Offers across accounts on configurable rebate and profit rules.
- **[amzn-account-health](https://github.com/dominicci13/amzn-account-health)**, **[amzn-shipments](https://github.com/dominicci13/amzn-shipments)**, **[amzn-feedback-manager](https://github.com/dominicci13/amzn-feedback-manager)** — Daily Amazon Seller Central scrapers feeding Excel dashboards and SQL Server.
- **[sellercloud-sync](https://github.com/dominicci13/sellercloud-sync)** — Idempotent daily ETL loading a catalog export into SQL Server via parameterized pyodbc.
- **[shared-python-utils](https://github.com/dominicci13/shared-python-utils)** — Reusable utilities (SeleniumBase login, OTP, xlwings, pyodbc, Rich logging) shared across the marketplace projects.

## Stack

| | |
|---|---|
| **AI / LLM** | Agentic tool-use loops (from primitives) · RAG (pgvector) · Structured Outputs / JSON Schema · Prompt-injection defense · OpenAI Responses API · Anthropic Claude · Claude Code |
| **Languages** | Python · JavaScript · Excel VBA |
| **Automation** | n8n · Make · Power Automate · Zapier |
| **Data** | Power BI · Power Query · DAX · SQL Server · MySQL |
| **APIs** | Amazon Seller Central · eBay · Walmart Marketplace · REST / JSON |

## What's next

An **LLM-as-judge eval framework**: the production-reliability piece that closes the loop on the agent work above. It will land here as a standalone repo.

---

📩 [brian_d13@icloud.com](mailto:brian_d13@icloud.com) · 💼 [LinkedIn](https://linkedin.com/in/bdramirez) · 🌎 Bilingual: Spanish and English
