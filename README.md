# Rafael de Novaes

AI Engineer based in São Paulo, Brazil (GMT-3), working remotely with US teams.

I spent 12 years building software in banking and capital markets, and the last two years fully on applied AI: LLM agents that run in production, the tooling around them (MCP servers, RAG, orchestration) and the part most demos skip, which is evaluation, guardrails and cost control.

**Stack:** TypeScript (NestJS, Fastify, LangGraph JS) and Python (LangGraph, FastAPI), PostgreSQL + pgvector, Prisma, BullMQ, Docker. LangSmith for tracing. OpenAI, Anthropic and Groq behind a provider-agnostic routing layer.

## What to look at

| Repository | Why it is worth opening |
|---|---|
| [CarInsight](https://github.com/rafaelnovaes22/CarInsight) | WhatsApp sales assistant on LangGraph: RAG with pgvector, multi-provider LLM routing with a circuit breaker, 1000+ tests, and an eval spine (adversarial set, golden set, LLM judge) wired as a promotion gate in CI. Also carries a full ISO/IEC 42001 AI management system under `governance/`, validated by CI. |
| [multi-agent-company-os](https://github.com/rafaelnovaes22/multi-agent-company-os) | The measurement that self-evaluation lies at scale: an internal evaluator passed ~100% of a generated agent fleet, an independent judge from a different model family passed 33% of the same agents. The repo is the verification architecture built in response. |
| [ai-cfo-platform](https://github.com/rafaelnovaes22/ai-cfo-platform) | Reference architecture for LLM document intelligence: multi-tenant, OpenAPI + Zod contracts, eval-gated promotions, 100% synthetic data. |
| [clickup-automation](https://github.com/rafaelnovaes22/clickup-automation) | Agent workflows with human approval gates, and sync daemons that reconcile project status against real evidence (files, PRs, CI) instead of trusting manual updates. |
| [agent-governance-framework](https://github.com/rafaelnovaes22/agent-governance-framework) | The governance layer the projects above share: versioned constitution, SHADOW to AUTONOMOUS promotion gates, unit economics, audit trail. |

Public repositories are portfolio samples: read the `NOTICE.md` in each one for terms, and assume every business scenario, brand and metric in them is synthetic unless stated otherwise.

## Contact

- LinkedIn: [rafaeldenovaes](https://www.linkedin.com/in/rafaeldenovaes/)
- Email: rafaeldenovaes@gmail.com
- Languages: Portuguese (native), English (fluent)
