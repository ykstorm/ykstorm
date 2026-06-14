# Lakshyaraj Singh Rao

Backend engineer. AI infrastructure. DevOps. Jaipur, India.

I build the libraries I needed while shipping AI products that couldn't lie to
users.

## Open source — all Apache 2.0

- 🪨 [**Anchor**](https://github.com/ykstorm/anchor) — Provenance-first RAG with
  cosine-floor refusal. Returns `refused: true` when similarity falls below 0.30.
  [Live playground](https://anchor-iota-ten.vercel.app/playground).
- ⚡ [**Goldset**](https://github.com/ykstorm/goldset) — Three-runner AI eval
  framework as a GitHub Action. PR comment diffs the delta, merge-blocks on
  regression. Published to npm + Marketplace.
- 🚦 [**Tripwire**](https://github.com/ykstorm/tripwire) — Mid-stream LLM safety.
  Token-by-token rule engine, sub-millisecond abort on rule trip.
- 📊 [**Quickdraw**](https://github.com/ykstorm/quickdraw) — LLM streaming
  benchmark CLI. TTFT, tokens/sec, $/1K. Nightly bench against OpenAI + Anthropic.
- ☸️ [**Stackup**](https://github.com/ykstorm/stackup) — Production-shape
  Kubernetes locally in 10 minutes. ArgoCD + Argo Rollouts + Grafana via one
  `make up`.
- 💻 [**Codecraft**](https://github.com/ykstorm/codecraft-ai) — In-browser IDE
  with real Node.js via WebContainers.
  [Live](https://codecraft-ai-tau.vercel.app).

On npm: [@ykstormsorg](https://www.npmjs.com/~ykstormsorg) — goldset, quickdraw,
tripwire. Anchor lives at [@ykstorm/anchor](https://www.npmjs.com/package/@ykstorm/anchor).

## Currently building

**Anvil** *(in progress)* — idempotent webhook to BullMQ
worker pipeline. HMAC-SHA256 with constant-time compare, exponential backoff
[1s, 5s, 30s, 5m], dead-letter replay via separate consumer.

## Day job

Sole engineer on [Homesty.ai](https://homesty.ai) — live commission-driven
real-estate AI on Next.js 15 + Postgres + pgvector + Prisma 7 + GPT-4o + Claude
+ Sentry + Upstash Redis + Docker + Vercel.

## Stack

Backend: TypeScript · Node 20 · Postgres + pgvector · Prisma 7 · Redis · BullMQ
AI: OpenAI · Anthropic · RAG · LLM streaming · prompt-injection defense
Infra: Docker · k8s (kind, ArgoCD, Argo Rollouts) · Terraform · Vercel
Observability: Sentry · Prometheus · Grafana · Loki · Tempo

## Open to

Backend platform / AI infrastructure / DevOps roles at Mumbai or Bangalore
startups · YC seed-stage founding engineer · contract work on RAG, streaming
LLM, queue/webhook reliability.

📍 [lakshyaraj-dev.vercel.app](https://lakshyaraj-dev.vercel.app) · 📧 raolakshyaraj@gmail.com · 🐦 [@ykstorm](https://x.com/ykstorm)
