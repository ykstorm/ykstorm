# Lakshyaraj Singh Rao

**Full-Stack Engineer · AI Systems · Backend · DevOps**

Jaipur, India · open to Bangalore / Mumbai / remote · raolakshyaraj@gmail.com

> Production-shipped a live AI advisor handling real users. Now building infra-layer tools.

---

## Production Product

### [homesty.ai](https://homesty.ai) — Live AI real-estate advisor

Solo-shipped. 165 production deployments. 0 critical Sentry classes under live traffic. 159 unit tests passing. 5-layer anti-fabrication architecture: PART 0 hard-stop rules + onChunk markdown abort + 17-class regex audit + source-provenance API blockade + GUARD_LIST RAG grounding. 8-stage chat pipeline: rate-limit → intent → RAG → GPT-4o stream → audit → log.

Stack: Next.js 15 · Postgres + pgvector · Prisma 7 · GPT-4o · Claude Sonnet 4.6 · Sentry · Docker
Repo: [buyerchat](https://github.com/ykstorm/buyerchat) (Apache 2.0)

---

## AI Infra & Tooling

### [vercel-ai-eval](https://github.com/ykstorm/vercel-ai-eval) — npm: LLM evals for Vercel AI SDK
`npm install -D vercel-ai-eval`
Drop-in eval framework. GitHub Actions CI. LLM-as-judge + golden datasets + regression detection.

### [llm-otel-exporter](https://github.com/ykstorm/llm-otel-exporter) — OpenTelemetry for LLM calls
`npm install llm-otel-exporter`
Standards-track OTEL exporter (gen_ai.* semantic conventions). Pipe LLM traces into Datadog, Honeycomb, Grafana — the dashboards you already pay for.

### [idempotency-key](https://github.com/ykstorm/idempotency-key) — Stripe-style idempotency middleware
`npm install idempotency-key`
Drop-in Express/Hono/Next.js middleware. Body-hash replay protection. Configurable storage (memory / Redis / Postgres).

### [rag-starter](https://github.com/ykstorm/rag-starter) — Production RAG template
pgvector retrieval (sub-50ms p99). Embed-writer, cosine-floor, provenance API.

### [guardrail-proxy](https://github.com/ykstorm/guardrail-proxy) — LLM streaming safety
Mid-stream abort, 17-class regex audit, PII scrub.

---

## Platform & DevOps

### [devops-showcase](https://github.com/ykstorm/devops-showcase) — GitOps platform-in-a-box
Kubernetes · ArgoCD · canary · Prometheus · Grafana.

### [k8s-deploy-tracker](https://github.com/ykstorm/k8s-deploy-tracker) — Deployment audit trail
Go · k8s event stream · GPT-4 problem-deploy summarization.

### [stream-bench](https://github.com/ykstorm/stream-bench) — LLM streaming benchmark
Latency, throughput, TTFT across providers.

---

## Dev Tools

### [codecraft-ai](https://github.com/ykstorm/codecraft-ai) — Browser-based AI IDE
WebContainers · Monaco · Claude-powered code agents.

---

## All Repos

| Repo | Stack | Status |
|---|---|---|
| [buyerchat](https://github.com/ykstorm/buyerchat) | Next.js · Postgres · GPT-4o | LIVE @ homesty.ai |
| [vercel-ai-eval](https://github.com/ykstorm/vercel-ai-eval) | TypeScript · npm | shipping |
| [llm-otel-exporter](https://github.com/ykstorm/llm-otel-exporter) | TypeScript · OTEL · npm | planned |
| [idempotency-key](https://github.com/ykstorm/idempotency-key) | TypeScript · npm | planned |
| [rag-starter](https://github.com/ykstorm/rag-starter) | pgvector · Node.js | stable |
| [guardrail-proxy](https://github.com/ykstorm/guardrail-proxy) | Node · regex audit | stable |
| [devops-showcase](https://github.com/ykstorm/devops-showcase) | k8s · ArgoCD | stable |
| [k8s-deploy-tracker](https://github.com/ykstorm/k8s-deploy-tracker) | Go · Postgres | stable |
| [stream-bench](https://github.com/ykstorm/stream-bench) | Node · benchmarks | stable |
| [codecraft-ai](https://github.com/ykstorm/codecraft-ai) | Next.js · WebContainers | beta |

---

## Reach

[linkedin.com/in/lakshyaraj](https://linkedin.com/in/lakshyaraj) · raolakshyaraj@gmail.com

License: Apache 2.0 across all repos.

![GitHub Stars](https://img.shields.io/github/stars/ykstorm?style=for-the-badge) ![Profile Views](https://komarev.com/ghpvc/?username=ykstorm&style=for-the-badge&color=ff4081)
