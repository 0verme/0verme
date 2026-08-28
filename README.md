# 见远而行 · Horizon Joins Journey

> Building open-source products at the intersection of data engineering and AI.
>
> 把真实的数据工程、AI 工作流与研究问题，做成可运行、可审计、可复现的软件。

I build focused tools, self-hosted products, and research infrastructure around data engineering, metadata governance, reproducibility, and reviewable AI-assisted workflows.

## Featured open source

### [ashare-turnaround](https://github.com/0verme/ashare-turnaround)

A local-first research foundation for A-share fundamental-turnaround analysis. It builds a PIT-safe historical research corpus with raw-field provenance, canonical views, replay, evaluation, and explicit barriers against future information leakage.

Research infrastructure, not an investment-return or stock-picking product.

### [LarkLedger](https://github.com/0verme/LarkLedger) · [Live](https://ledger.overme.cn/)

A self-hosted Feishu / Lark bookkeeping platform with Web and API entry points. Deterministic financial workflows, typed assistant responses, and query capabilities keep business actions reviewable; AI turns input into validated actions and does not directly operate the database.

### [Data Asset Portal](https://github.com/0verme/data-asset-portal-community) · [Live](https://data.overme.cn/)

A lightweight metadata management portal for data warehouses: discover and maintain data assets, field and table mappings, lineage, and governance-oriented metadata workflows. It is designed for real data-platform workflows and offline or self-hosted deployment.

### [lineage-viewer](https://github.com/0verme/lineage-viewer) · [Live](https://lineage.overme.cn/)

A lightweight, framework-free, embeddable Web Component for interactive table and column lineage. It uses JSON, SVG, Shadow DOM, and zero runtime dependencies so lineage views can fit into existing applications.

## Data engineering toolchain

[Data Asset Portal](https://data.overme.cn/) and [Audit](https://audit.overme.cn/) are companion tools in the same data engineering toolchain: the public portal covers data assets, metadata, lineage, and governance workflows; Audit is the private companion for engineering audit. They are presented here as a product relationship, not as an already-integrated system.

- **Data Asset Portal** — public metadata and lineage workflows: [data.overme.cn](https://data.overme.cn/) · [source](https://github.com/0verme/data-asset-portal-community)
- **Audit** — private, not open source: [audit.overme.cn](https://audit.overme.cn/)

## Open source contributions

### [DBX](https://github.com/t8y2/dbx)

Active contributor to a lightweight cross-platform database client. Recent upstream work spans SQL editor behavior, PostgreSQL correctness, schema diff, Kafka and data-transfer workflows, performance, frontend UX, and regression fixes.

My usual path is:

`reproduce → isolate the root cause → make a scoped fix → add or strengthen regression coverage → send the change upstream`

## Current focus

- Data infrastructure, metadata, and governance
- AI-native software engineering and agent workflows
- Point-in-time-safe quantitative research tooling
- Self-hosted products and lightweight automation
- Database tooling and upstream open-source contribution

## Working principles

- **Inspectable by default** — schemas, rules, assumptions, evidence, and generated artifacts should stay reviewable.
- **Verification over vibes** — reproduce → isolate → fix → regress; prefer evidence over guesses.
- **Local-first where practical** — keep sensitive metadata, credentials, workflow state, and usage data local or self-hosted when feasible.
- **AI-native engineering** — use Codex, Claude Code, Pi, and other coding agents as leverage while preserving acceptance criteria, tests, provenance, reviewability, and reproducibility.
- **Small integration surface** — prefer focused CLIs, APIs, and reusable components over an unnecessary all-in-one platform.
- **Respect upstream** — distinguish original work, forks, inspiration, and upstream contributions.

## Stack

Python · TypeScript · Rust · Vue · React · FastAPI · PostgreSQL · SQLite · DuckDB · Parquet · Cloudflare Workers · D1 · Docker · LLM / agent workflows

## Links

- Website: [www.overme.cn](https://www.overme.cn/)
- GitHub: [github.com/0verme](https://github.com/0verme)
- Data Platform: [Asset Portal](https://data.overme.cn/) · [Audit](https://audit.overme.cn/) (Private, not open source)
- Lineage: [lineage.overme.cn](https://lineage.overme.cn/)
- Ledger: [ledger.overme.cn](https://ledger.overme.cn/)
- AI Usage: [token.overme.cn](https://token.overme.cn/)
