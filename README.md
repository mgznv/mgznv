# Hi, I'm Manuel 👋

I'm a **Backend Developer & Data Engineer** specializing in Ruby on Rails and AI-powered data infrastructure, based in Mexico 🇲🇽. I work on the Business Intelligence team at **Flex**, where I build the backend, ETL pipelines, and internal AI tooling that power enterprise analytics.

Lately I've been focused on the intersection of Rails and LLMs: natural language database interfaces, embedding-based classification, and tooling that makes AI integration feel native to Ruby.

When I'm not coding, I'm probably playing PlayStation, tinkering with 3D models, or creating content for my family gaming channel **ALANCRAFT** 🎮.

---

## 🛠️ Tech Stack

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=rubyonrails&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-gray?style=for-the-badge)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

---

## 🚀 Featured Projects

### 🤖 [ask-your-db](https://github.com/mgznv/ask-your-db)

> Query your PostgreSQL database in plain English — no SQL required.

Type a natural language question, get real query results. Powered by OpenAI and Model Context Protocol (MCP) for schema-aware SQL generation, with a real-time Hotwire interface and read-only execution for safety.

`Rails` · `OpenAI API` · `MCP` · `PostgreSQL` · `Hotwire` · `Turbo Streams`

---

### 💎 [rubycanusellm](https://github.com/mgznv/rubycanusellm)

[![Gem Version](https://img.shields.io/gem/v/rubycanusellm?style=flat-square&color=CC342D)](https://rubygems.org/gems/rubycanusellm) [![Downloads](https://img.shields.io/gem/dt/rubycanusellm?style=flat-square&color=blue)](https://rubygems.org/gems/rubycanusellm)

> Unified Ruby gem to work with multiple LLM providers. Ruby can use LLM.

A published Ruby gem that gives Rails apps a clean, consistent interface to OpenAI, Anthropic, and other providers — eliminating vendor lock-in. Includes streaming support, error handling, and Rails generators for quick integration.

`Ruby Gem` · `OpenAI API` · `Anthropic API` · `Streaming` · `Rails Generators`

---

### ⚡ [Hydra](https://github.com/mgznv/hydra)

> Many providers, one endpoint.

A lightweight HTTP proxy (Ruby/Sinatra) that load-balances LLM requests across multiple providers using round-robin. Maximizes free-tier usage across Groq, OpenRouter, Anthropic, and others. Supports both blocking and streaming (SSE) responses.

**Complements `rubycanusellm`:** the gem is the client you use inside Rails apps; Hydra is the infrastructure layer you point it at.

`Ruby` · `Sinatra` · `LLM Proxy` · `Load Balancing` · `SSE Streaming`

---

### 🌸 Open Source Contributions

- [**lingdojo/kana-dojo**](https://github.com/lingdojo/kana-dojo) — Contributor to a Japanese language learning app (Hiragana/Katakana trainer).

---

## 💼 Professional Experience @ Flex (BI Team)

As part of the Business Intelligence team, I own backend infrastructure and data pipelines that power enterprise analytics. My role spans Data Engineering, Backend Development, and DevOps.

- **🤖 AI-Powered Excel Processor (Internal):** Designed and built a Rails application that standardizes non-uniform Excel files using OpenAI embeddings and pgvector similarity search for automated column mapping and commodity classification (In Scope / Out of Scope).

- **📄 Contract Governance System (Internal):** Designed and built an enterprise contract lifecycle management system in Rails 7 from scratch, solo. Multi-role approval workflow with guarded state transitions, region-aware liability calculations across three geographies, and a full audit trail implemented at the PostgreSQL trigger level (Logidze + fx) rather than at the application layer. Generates PDF contracts, exports to Excel (44-column reports), imports validated CSV, and handles nested forms with bidirectional JS autofill against a reference table. Replaced a manual spreadsheet+email process with centralized, auditable, real-time contract availability.
  **Stack:** Rails 7.1 · Hotwire · PostgreSQL · Logidze · Devise · Petergate · Wicked PDF · Axlsx · Tailwind · Stimulus.

- **📊 ETL & Data Pipelines:** Design and maintain complex ETL flows using Tableau Prep and custom scripts to integrate data from Salesforce, Snowflake, and legacy SQL Server databases.

- **⚙️ Backend Automation:** Develop scheduled tasks (cron jobs, Rake tasks) to ensure data consistency, trigger reports, and maintain backend health.

- **🔗 Salesforce Integration:** Build and maintain integrations between Salesforce CRM and internal data warehouses for real-time reporting.

---

## 📬 Get in Touch

- 💼 [LinkedIn](https://www.linkedin.com/in/mgznv/)
- 🐙 [GitHub](https://github.com/mgznv)
- 🌐 [Website](http://www.manuelguzman.xyz)
- ✉️ [leunam.toshi@gmail.com](mailto:leunam.toshi@gmail.com)
