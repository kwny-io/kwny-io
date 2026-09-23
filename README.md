<div align="center">

# kwny

**Python · TypeScript · AI Agents**

I build agent runtimes — the harness, the tools, and the observability that keeps them honest.

![Python] ![FastAPI] ![TypeScript] ![React] ![PostgreSQL] ![Docker] ![Kubernetes]

</div>

---

## What I work on

Agent runtimes and the unglamorous parts around them:

- **Runtime & orchestration** — session lifecycle, durable execution, policy-gated tool calls
- **Retrieval & memory** — RAG pipelines, session memory, MCP tool integration
- **Reliability** — guard tests that fail when a *promise* breaks, not when a feature breaks
- **Observability** — OTLP traces, SLOs, and alert rules that are asserted against real metrics

## Featured

### warden-agent · Python · MIT
An agent platform built to a production bar: FastAPI service, one store interface over
SQLite and PostgreSQL, policy engine, memory, RAG, MCP tool calls, multi-agent dispatch.

- `1114 tests passing` · `coverage 85.26%` · `mypy --strict` clean · `ruff` clean
- Guard tests assert invariants rather than features: config surface, import direction
  (ArchUnit-style), Kubernetes manifest rules, and alert rules that must reference
  metrics that actually exist
- OTLP/Jaeger tracing, Prometheus SLOs, Alertmanager rules, Kubernetes manifests, Docker Compose

## Elsewhere
