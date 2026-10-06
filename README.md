# Hi, I'm Bernardo Camargo 👋

**Senior Software Engineer** — 10 years building high-scale distributed systems in Proptech and Fintech, now focused on productionizing AI services.

I care about the boring things that make systems work in production: observability, resilience patterns, and clean boundaries between domain and infrastructure.

## What I work with

**🤖 AI in production** — LLM orchestration and [Model Context Protocol](https://modelcontextprotocol.io) agents wired into enterprise data with strict access control; sub-second agent workflows with token-cost optimization; AI-service observability with Grafana, Prometheus, and OpenTelemetry.

**🏗️ Platform & IaC** — Architected a custom **Terraform Provider in Go** on the SailPoint IdentityNow API, turning manual access governance into a self-service IaC product: provisioning went from **5 days to seconds for 6,000+ employees**.

**📨 Event-driven backends** — Kafka and Debezium CDC pipelines sustaining **2.5k RPS at sub-50ms latency**, AWS SQS/Lambda microservices in Hexagonal Architecture, and a real-time PIX transaction-limit engine with circuit breakers, retries, and timeouts.

## Side project — [VagaRemota.dev](https://vagaremota.dev)

A **remote-jobs platform for the Brazilian market** that I built and run solo — engineered end-to-end **with AI agents** (Cursor, ZCode). It's the "AI in production" pillar above, shipped as a real product instead of a slide.

- **Backend** — Node.js + Express serving a server-rendered multi-page UI with session auth, and request-ID tracing on every call
- **Data pipeline** — aggregates 8 heterogeneous job sources, normalizes their schemas and deduplicates them into one clean catalog: 600+ live jobs, refreshed continuously
- **AI layer** — Gemini-powered CV→job fit scoring (0–100) and AI-assisted cover letters, privacy-first by design: CVs are analyzed in the moment and never stored
- **Operations** — served through a Caddy reverse proxy with hardened security headers (CSP, HSTS, nosniff) on my own VPS; a live product with real users and paid Pro plans

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
