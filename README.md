# Hey, I'm Hari

**I build AI products. I also write the code for them.**

I have been coding since 2016 and building with AI/ML since the GPT-3 days. I come from Chennai, grew up around engineering culture, and I genuinely enjoy going deep into systems — whether that's fine-tuning a 4B parameter model on a weekend or wiring up Kafka pipelines for real-time data.

I believe the best product folks are the ones who have opened the hood. So I open hoods.

---

### What I'm building right now

**[CricketMind](https://github.com/brettleehari/cricketmind)** — I fine-tuned NVIDIA's Nemotron-Mini-4B for cricket domain expertise. Used QLoRA, response distillation with Claude as teacher, and built my own eval benchmark (CricketBench). Wrote a [6-part article series](https://github.com/brettleehari/cricketmind/tree/main/article) about why every PM should fine-tune a model at least once. Cost me $4 on a RunPod A100.

**[CIAL / BTCExpert](https://github.com/brettleehari/BTCExpert)** — Crypto intelligence platform. FastAPI + TimescaleDB + Kafka + pgvector + Redis. WebSocket streaming for 10K+ connections. Full observability with Prometheus and OpenTelemetry. This one taught me a lot about production-grade system design.

**[GlucoLens](https://github.com/brettleehari/glucolens)** — Health monitoring platform that takes CGM glucose data along with sleep, exercise, and meal logs, then runs causal discovery (PCMCI) and pattern detection (STUMPY) to find what actually affects your blood sugar. Not just correlations — actual causal relationships.

**[Code-RAG](https://github.com/brettleehari/code-RAG)** — Built a local RAG-based code assistant from scratch. Indexing, vector search, retrieval tuning (top-k, temperature). Wanted to understand the full RAG pipeline hands-on, not just through API calls.

**[Cricket Height Research](https://github.com/brettleehari/cricheightresearch)** — Analysing height selection pressure across 23 ICC World Cups (1975-2026). ANOVA, regression, population-adjusted analysis. The cricket nerd in me meets the data nerd.

**[Kafka Stream Transformer](https://github.com/brettleehari/kafka-stream-transformer)** — Real-time Kafka microservice with a live WebSocket dashboard. Schema validation, Docker deployment, the works.

---

### Open source

- Got a PR merged into **LlamaIndex** — [PR #15311](https://github.com/run-llama/llama_index/pull/15311), fixed file path loading issues. Felt good to contribute to a framework I actually use.
- Built **[Review Buddy](https://github.com/pitchdarkdata/MVP1)** — a GitHub App that assigns code reviewers based on who actually wrote the code, not who is the team lead. Because the person who touched the file last week knows it better than the architect who hasn't looked at it in months.
- Forked and explored **[Aider](https://github.com/brettleehari/arivuaider)** to understand how AI code assistants work under the hood.

---

### How I think about building AI products

I have spent enough time below the API layer to know what's actually hard and what's marketing. Some things I have learnt by doing:

- **Fine-tuning is not magic.** I fine-tuned Nemotron-Mini on 170 examples. The data curation took longer than the training. Every PM should understand this.
- **Evaluation is the product decision most people skip.** I built CricketBench with weighted difficulty tiers and LLM-as-judge scoring. If you cannot measure it properly, you are shipping vibes.
- **I write PRDs and code both.** My RAG, streaming, and fine-tuning experience means I know what is feasible before the sprint planning starts. That saves everyone time.

---

### Tech I work with

**AI/ML:** Fine-tuning (QLoRA, LoRA) · RAG · LLM evaluation · Causal discovery · pgvector · LlamaIndex
**Backend:** Python · FastAPI · Celery · Kafka · Redis · TimescaleDB · PostgreSQL · Docker
**Frontend:** React · TypeScript · Tailwind · WebSocket dashboards
**Infra:** AWS · GitHub Actions · Prometheus · OpenTelemetry · Sentry
**Languages:** Python · JavaScript/TypeScript · Java · SQL

---

Also on GitHub as [pitchdarkdata](https://github.com/pitchdarkdata) (my OSS contributions account).

Building since 2016. From Chennai. Currently in Dallas, TX.
