# Hi, I'm Joun 👋

Engineering manager and hands-on engineer. I build **observability systems** and **AI systems** — and the teams that ship them.

---

### What I've been doing

Most recently I established **ScienceLogic's first India product-engineering site**, growing it from zero to 15 engineers across two teams. I stayed hands-on the whole way:

- Architected an **MCP server** exposing monitoring-platform capabilities to AI coding agents — adopted across every integration team
- Built core components of a **multi-agent RAG system** that resolves support escalations before they reach an engineer
- Wrote the **release-testing automation** that cut cycle time 61% and made platform validation ~6x faster
- Scaled a monitoring collector from 400 to **1,000 devices** per 4-core/8GB node

Before that, backend architecture for education and job platforms across Indonesia — multi-tenant systems at 600k users and 100k concurrent, P95 held near 150ms.

### What I've been building

[**monitoring-integration-agent**](https://github.com/joun-kazmi/monitoring-integration-agent) — an agent that writes Prometheus exporters and SNMP collector configs from API docs and MIBs, then proves they work by running them against the real target and diffing scraped metrics against a spec it committed to earlier. Validation costs zero LLM tokens, so failures get classified deterministically and repaired with live evidence instead of a guess. Five real runs, all verified, committed under `examples/runs/`.

### What I work with

**Languages** Python · JavaScript · SQL
**AI / LLM** RAG · multi-agent systems · MCP · embeddings & semantic chunking · Qdrant · LLM orchestration · LangGraph · Langfuse
**Observability** AIOps · SNMP / SSH / REST collection · Prometheus · Grafana · ELK · distributed tracing
**Backend** FastAPI · Django · Flask · REST · WebSockets · microservices · multi-tenancy
**Data** PostgreSQL · MongoDB · Redis · Elasticsearch · Kafka · RabbitMQ · Celery · Prefect
**Cloud** AWS · GCP · Docker · Nginx

### Things I care about

Monitoring that tells you something true. AI that removes real toil rather than demoing well. Engineers who get better for having worked with me.

---

📫 [LinkedIn](https://www.linkedin.com/in/mohd-joun-kazmi/) · kazmifaraz153@gmail.com

*Open to Engineering Manager, Staff and Principal Engineer roles.*
