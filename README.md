# Hi, I'm Bernardo Camargo 👋

**Senior Software Engineer** — 10 years building and operating distributed systems across Proptech, Fintech, and AI products.

I care about the boring things that make systems work in production: observability, resilience patterns, and clean boundaries between domain and infrastructure. That toolkit transfers — any domain, any kind of problem a backend can throw at you.

## What I work with

**🔌 MCP tools & agent infrastructure** — Building [Model Context Protocol](https://modelcontextprotocol.io) servers that turn real systems into typed, documented tools agents can call safely: schema-first design in Kotlin and Go, server-side policy with access control and audit trails, and observability (Grafana, Prometheus, OpenTelemetry) on every tool call.

**🏗️ Platform & IaC** — Building custom **Terraform providers in Go** and turning manual operations into self-service platforms: identity governance (SailPoint IdentityNow), codified workflows, and API integrations other teams can consume safely.

**📨 Event-driven backends** — Designing event-driven microservices with **Kafka**, **Debezium CDC**, and AWS SQS/Lambda in Hexagonal Architecture; real-time transaction systems hardened with circuit breakers, retries, and timeouts.

## Side project — [VagaRemota.dev](https://vagaremota.dev)

A **remote-jobs platform for the Brazilian market** that I built and run solo — engineered end-to-end **with AI agents** (Cursor, ZCode). It's the "AI in production" pillar above, shipped as a real product instead of a slide.

- **Platform** — Spring Boot REST API in **Kotlin** (JVM 21) + a **Python** scraping worker communicating over **RabbitMQ**; **PostgreSQL** (pg_trgm) + **Redis** for cache and rate limiting; **Angular** frontend with SSR and a key-holding BFF
- **Data pipeline** — three-tier extraction (JSON/RSS → CSS selectors → LLM fallback) across 8 ToS-vetted sources, normalized and deduplicated: 600+ live jobs
- **AI layer** — Gemini-powered CV→job fit scoring (0–100) and AI-assisted cover letters, privacy-first by design: CVs are analyzed in the moment and never stored
- **AI harness** — repo-level `AGENTS.md` with a documented source-of-truth hierarchy, 16 project-specific agent skills, worktree-based parallel agent sessions, MCP integrations
- **Operations** — Caddy reverse proxy with hardened security headers on my own VPS; 730+ conventional commits in the first three weeks

## AI-native workflow

Shipping a platform solo at this speed takes a **harness**, not just a chat window — the same discipline I brought to teams (at QuintoAndar I created AI Agent Skills used across the group). The full playbook is open source: **[ai-native-harness](https://github.com/bernacamargo/ai-native-harness)**.

- **Agent skills + AGENTS.md conventions** — repo-level playbooks encoding domain context and quality bars, so every agent session starts with senior-engineer context instead of rediscovering it
- **MCP tool integrations** — agents act through typed tools with guardrails, not raw shell access; I build my own, like [iam-mcp-server](https://github.com/bernacamargo/iam-mcp-server) and [incident-mcp-server](https://github.com/bernacamargo/incident-mcp-server)
- **Git worktree strategies** — several agent sessions running in parallel across isolated worktrees and merging clean: solo speed without merge chaos

## Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

**Also fluent in:** Kafka · AWS (SQS/SNS, Lambda) · Terraform · Kubernetes · PostgreSQL · Redis · OpenSearch · Spring Boot · Datadog/Grafana/Prometheus/OTel

## Now

- 🎓 Postgraduate degree in **Software Architecture** @ FIAP (in progress)
- 🚀 Running [vagaremota.dev](https://vagaremota.dev) — remote-jobs platform built solo with AI agents (see above)
- 🔨 Just shipped **two MCP servers** — same protocol, two ecosystems: [iam-mcp-server](https://github.com/bernacamargo/iam-mcp-server) (Kotlin + Spring AI, identity governance) and [incident-mcp-server](https://github.com/bernacamargo/incident-mcp-server) (Go + official go-sdk, on-call response). Both policy-enforced, audited, tested, and released.
- 📫 [LinkedIn](https://www.linkedin.com/in/bernardocamargo/)

---

*My day-job repos live in private orgs, so the contribution graph here undercounts — the pinned repositories below are mine.*
