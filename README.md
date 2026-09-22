# Rafael de Novaes

AI Engineer based in Sao Paulo, Brazil (GMT-3), working remotely with US teams.

I spent 12 years building software in banking and capital markets, and the last two years fully on applied AI: backends that serve real traffic, plus the verification layer most demos skip (deterministic checks, evals, guardrails, cost control).

**Stack:** Python (FastAPI, Pytest), TypeScript (NestJS, Fastify, LangGraph JS), PostgreSQL + pgvector, Prisma, BullMQ, Docker. LangSmith for tracing. OpenAI, Anthropic and Groq behind a provider-agnostic routing layer.

## For hiring managers: start here in 5 minutes

1. Verifiers that gate merges: [adversarial golden set](https://github.com/rafaelnovaes22/CarInsight/blob/main/src/evaluation/adversarial-golden-dataset.ts), [recommendation golden set](https://github.com/rafaelnovaes22/CarInsight/blob/main/src/evaluation/golden-dataset.ts), [LLM judge with versioned rubric](https://github.com/rafaelnovaes22/CarInsight/blob/main/src/evaluation/llm-judge.ts)
2. Scalable backend: [carinsight-backend](https://github.com/rafaelnovaes22/carinsight-backend) (NestJS, Prisma, Swagger, Jest + supertest e2e)
3. Full system: [CarInsight](https://github.com/rafaelnovaes22/CarInsight) (LangGraph, RAG on pgvector, multi-LLM router with circuit breaker, 1,106 tests)

## What to look at

| Repository | Why it is worth opening |
|---|---|
| [CarInsight](https://github.com/rafaelnovaes22/CarInsight) | Production WhatsApp sales assistant. Run `npm run eval` for the 3-layer gate (adversarial, precision@3, role adherence). Run `npm run verify:strict` for format, lint, build and tests. See [evals](https://github.com/rafaelnovaes22/CarInsight/tree/main/evals) and [tests](https://github.com/rafaelnovaes22/CarInsight/tree/main/tests). |
| [carinsight-backend](https://github.com/rafaelnovaes22/carinsight-backend) | Companion scalable API: JWT auth, throttling, Swagger docs, Prisma migrations, dockerized test DB. Best proof of REST design and backend habits. |
| [clara-reforma-tributaria](https://github.com/rafaelnovaes22/clara-reforma-tributaria) | Conversational copilot for Brazil's consumption-tax reform (Python, TypeScript, LangGraph, OpenAI API): official-source grounding, per-client context, synthetic NF-e XML triage, security evals and audit trail. Single verify gate via `scripts/verify.py`. |
| [ai-cfo-platform](https://github.com/rafaelnovaes22/ai-cfo-platform) | Reference architecture for LLM document intelligence: multi-tenant, OpenAPI + Zod contracts, eval-gated promotions, 100% synthetic data. |
| [clickup-automation](https://github.com/rafaelnovaes22/clickup-automation) | Agent workflows with human approval gates, and sync daemons that reconcile project status against real evidence (files, PRs, CI) instead of trusting manual updates. |
| [agent-governance-framework](https://github.com/rafaelnovaes22/agent-governance-framework) | The governance layer the projects above share: versioned constitution, SHADOW to AUTONOMOUS promotion gates, unit economics, audit trail. |
| [multi-agent-company-os](https://github.com/rafaelnovaes22/multi-agent-company-os) | The measurement that self-evaluation lies at scale: an internal evaluator passed about 100% of a generated fleet, an independent judge from another model family passed 33% of the same agents. The repo is the verification architecture built in response. |

Public repositories are portfolio samples: read the `NOTICE.md` in each one for terms, and assume every business scenario, brand and metric in them is synthetic unless stated otherwise.

## Contact

- LinkedIn: [rafaeldenovaes](https://www.linkedin.com/in/rafaeldenovaes/)
- Email: [rafaeldenovaes@gmail.com](mailto:rafaeldenovaes@gmail.com)
- Languages: Portuguese (native), English (fluent, daily working language)
