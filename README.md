# Lakshyaraj Singh Rao

Full-stack engineer. I build AI products that actually run in production.

Mumbai · raolakshyaraj@gmail.com · [linkedin.com/in/lakshyaraj](https://linkedin.com/in/lakshyaraj)

---

## What I'm running right now

[**homesty.ai**](https://homesty.ai) — a real-estate AI advisor I built solo for the South Bopal & Shela micro-market in Ahmedabad. Live commission model, 16 RERA-verified projects indexed, 165 production deploys, 0 critical Sentry classes firing.

The interesting bit isn't the chat. It's the anti-fabrication layer. LLMs love to invent founding years, amenity lists, and OTPs — especially when they're under pressure to sound confident. So I wrote a 5-stop pipeline: hard-stop rules in the system prompt, an onChunk markdown abort, a 17-class regex audit, a source-provenance API blockade, and GUARD_LIST RAG grounding. Closed 8 production hallucination classes that way — including a particularly fun OTP-simulation bug where GPT-4o decided to "verify" a phone number that didn't exist.

The repo is [buyerchat](https://github.com/ykstorm/buyerchat). Next.js 15, Postgres + pgvector, Prisma 7, GPT-4o, Claude Sonnet, Sentry, Upstash Redis, Docker. Apache 2.0.

---

## Other things I've shipped

[**rag-starter**](https://github.com/ykstorm/rag-starter) — A production RAG template I extracted from buyerchat. pgvector retrieval with a 600ms timeout and a 0.30 cosine floor, so anything below that is silently dropped instead of feeding the model garbage. Embed-writer, backfill script, provenance API for grounded citations.

[**guardrail-proxy**](https://github.com/ykstorm/guardrail-proxy) — Streaming LLM safety. Mid-chunk abort when the audit catches a violation, so the user never sees the bad response finish rendering. 17-class regex audit, PII scrub.

[**devops-showcase**](https://github.com/ykstorm/devops-showcase) — Kubernetes + ArgoCD GitOps stack. Canary deploys, Prometheus, Grafana. Built it to learn k8s end-to-end, ended up using the patterns in homesty's Docker setup.

[**stream-bench**](https://github.com/ykstorm/stream-bench) — Benchmarks for LLM streaming. Time-to-first-token, throughput, total latency across OpenAI, Anthropic, Bedrock.

[**k8s-deploy-tracker**](https://github.com/ykstorm/k8s-deploy-tracker) — Go service that consumes Kubernetes deploy events and feeds the failing ones to GPT-4 for a one-paragraph summary. Saves me from staring at kube logs on bad days.

[**codecraft-ai**](https://github.com/ykstorm/codecraft-ai) — Browser-based AI IDE. WebContainers + Monaco + Claude. Smaller project, but Monaco-inside-WebContainer was a fun debug.

---

## Reach me

Email — raolakshyaraj@gmail.com
LinkedIn — [linkedin.com/in/lakshyaraj](https://linkedin.com/in/lakshyaraj)

License: Apache 2.0 across these repos.
