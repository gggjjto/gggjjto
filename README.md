<h1 align="center">gggjjto</h1>

<p align="center">
  <strong>Agent Systems / FastAPI Engineering / API Contract Design</strong>
</p>

<p align="center">
  <a href="https://github.com/gggjjto">
    <img src="https://komarev.com/ghpvc/?username=gggjjto&style=flat-square&color=0e75b6" alt="profile views" />
  </a>
  <a href="https://github.com/gggjjto/fastapi-template">
    <img src="https://img.shields.io/badge/Focus-FastAPI%20Engineering-009688?style=flat-square" alt="FastAPI Engineering" />
  </a>
</p>

I focus on **agent-oriented backends** and **modern FastAPI engineering**. Beyond shipping individual endpoints, I care about whether a backend can evolve safely over time: clear API contracts, stable error models, testable service boundaries, reliable database migrations, frontend collaboration, and engineering documentation that is useful for both humans and AI tools.

## What I'm Working On

- Designing a real-world FastAPI backend template with auth, permissions, exceptions, logging, rate limiting, caching, task queues, tests, and CI/CD.
- Working through complex API scenarios such as support, chat, aliases, handoff flows, i18n display names, and permission-aware visibility.
- Exploring agent backend problems: tool use, memory, RAG, async jobs, chat workflows, and API contracts.
- Turning repeated engineering lessons into templates, rules, documentation, and reusable development workflows.

## Featured Work

### [fastapi-template](https://github.com/gggjjto/fastapi-template)

A FastAPI backend template built around the problems real projects repeatedly run into. It is more than a simple scaffold: it includes domain-oriented structure, response envelopes, JWT auth, RBAC, async SQLAlchemy, Alembic, Redis, Arq, structured logging, rate limiting, health checks, Docker, GitHub Actions, and integration tests.

What I focus on in this project:

- API contracts: response envelopes, stable business error codes, and readable OpenAPI documentation.
- Engineering boundaries: clear router / service / repository / schema / model separation.
- Production readiness: environment validation, structured logging, health checks, CI, and Docker builds.
- Testing strategy: real integration tests with PostgreSQL and Redis instead of relying only on mocks.

`FastAPI` `Pydantic v2` `SQLAlchemy 2.0` `PostgreSQL` `Redis` `Arq` `Alembic` `Docker` `pytest` `GitHub Actions`

## Engineering Details I Care About

```text
API Contract        OpenAPI / response envelope / error code / pagination
Backend Structure  router / service / repository / schema / model
Reliability        migration / integration test / CI / Docker / health check
AI Backend         LLM orchestration / RAG / async worker / chat workflow
Collaboration      frontend handoff / i18n data / permission visibility
```

## Tech Stack

**Core Backend**

`Python` · `FastAPI` · `Pydantic v2` · `SQLAlchemy 2.0` · `Alembic` · `PostgreSQL` · `Redis`

For maintainable business backends: domain boundaries, auth, response envelopes, exception models, database migrations, caching, and task queues.

**Agent & AI Backend**

`Agent Workflow` · `Tool Use` · `Memory` · `RAG` · `pgvector` · `Async Worker` · `Chat System`

For agent capabilities: tool orchestration, contextual memory, vector retrieval, async jobs, chat workflows, and model-provider integration.

**Engineering Practice**

`OpenAPI` · `pytest` · `Docker` · `GitHub Actions` · `CI/CD` · `Observability`

For long-term maintainability: API documentation, integration testing, containerization, local reproducibility, CI, and observability.

**Frontend Collaboration**

`TypeScript` · `React` · `Vue` · `API Handoff` · `i18n Data`

For understanding real frontend integration needs and designing clearer API contracts and response structures.

## Current Direction

I will keep focusing on **agent systems** and **FastAPI engineering**: building maintainable backends for tool use, memory, RAG, workflows, permissions, documentation, and tests.
