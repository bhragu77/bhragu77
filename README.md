<h1 align="center">Bhragu Gour</h1>

<p align="center"><b>Applied AI Engineer · AI Software Engineer</b></p>

<p align="center">
I build production-shaped LLM applications — RAG systems, multi-agent workflows, and evaluation-driven AI backends — on a foundation of real backend engineering.
</p>

<p align="center">
  <a href="https://linkedin.com/in/bhragu77">LinkedIn</a> ·
  <a href="https://ginger-latitude-e7470.tailbd3d1f.ts.net/me">Portfolio</a> ·
  <a href="mailto:bhragugaur77@gmail.com">Email</a>
</p>

---

### What I build

- **RAG systems** — hybrid retrieval, reranking, and *measurable* retrieval quality
- **Agentic AI** — LangGraph multi-agent orchestration, tool / function calling, and guardrails
- **Evaluation & observability** — RAGAS-aligned metrics, LLM-as-judge, Langfuse tracing, CI regression gates
- **Production AI backends** — FastAPI, REST, PostgreSQL / Redis, Docker, cloud
- **Reliable AI** — citation-grounded answers, groundedness verification, and honest abstention when evidence is weak

I focus on the part most demos skip: *does the system retrieve the right context, ground its answer, get evaluated, and fail safely?*

---

### Featured work

**🤖 [researchAgent](https://github.com/bhragu77/researchAgent) — Multi-Agent Enterprise Research System**
A LangGraph-orchestrated multi-agent pipeline: guardrail screening → query decomposition → parallel specialist agents → evidence fusion → synthesis → independent verification, with a bounded self-correction loop and an A2A protocol for external agents. Every claim is citation-validated and groundedness-checked before it surfaces — the model is never the sole judge of its own answer.
`Python · FastAPI · LangGraph · PostgreSQL + pgvector · Redis · Groq · Gemini · Docker`

**📄 [DocuChunk](https://github.com/bhragu77/DocuChunk) — Production-Shape RAG Platform**
An end-to-end document-RAG platform built around measurable retrieval quality and evaluation: hybrid retrieval (dense + BM25 + RRF) with cross-encoder reranking, a RAGAS-aligned evaluation harness wired into CI regression gates, and Langfuse tracing. Multi-provider LLM layer with SSE streaming, semantic caching, and per-query cost attribution.
*Retrieval MRR 0.78 → 0.97 · answer faithfulness 0.71 → 0.89 on a 42-doc distractor benchmark.*
`Python · FastAPI · ChromaDB · pgvector · Pinecone · HuggingFace · Redis · Docker`

**🎙️ [hunar](https://github.com/bhragu77/hunar) — Voice-AI HR Platform**
A unified voice-AI platform — hiring assistant, people search & reach-out, and attendance — built on one reusable Voice Core. Shows multi-feature product engineering and a shared-service architecture rather than a single-purpose demo.
`Python · FastAPI · LLMs · Voice`

---

### Selected engineering highlights

- Lifted retrieval **MRR 0.78 → 0.97** on a 42-doc distractor benchmark (hybrid retrieval + reranking)
- Raised answer **faithfulness 0.71 → 0.89** with a fail-closed verification layer
- **+0.43 context recall** from an agentic retrieval loop under tight retrieval budgets
- Ships evaluation-gated: RAGAS-aligned harness → **CI regression gates** → **Langfuse** tracing

---

### Experience

**Software Engineer — Backend & AI Integrations** · Think Exam (A Ginger Webs Company) · Jul 2025 – Present

- Integrated third-party **AI proctoring** (face / gaze / anomaly detection) into a live, high-stakes online-exam platform via REST + webhooks — event ingestion, async processing, and violation-flag persistence.
- Diagnosed and fixed a **~40× auth-path latency regression (4.8s → 0.12s)** using staged DNS/TCP/TLS timing analysis and connection pooling; also fixed a first-boot DB bootstrap bug that would have broken new deployments.
- Built and optimized REST APIs (**+30%** via query optimization and indexing), with RBAC and JWT/OAuth2 auth and background/async workflows; recognized **Engineer of the Year** for end-to-end ownership.

*Full stack from that work: Python, PHP/Laravel, MySQL, Redis, Docker, GCP, Linux.*

---

### Tech stack

**AI / LLM** — RAG · Agentic AI · AI Agents · Tool / Function Calling · Structured Outputs · Guardrails · Prompt Engineering · LLM Application Development
**Agent frameworks** — LangGraph · LangChain (LCEL) · LlamaIndex
**Retrieval & vector DBs** — Hybrid search (dense + BM25 + RRF) · Cross-encoder reranking · Embeddings · pgvector · ChromaDB · Pinecone
**Evaluation & observability** — RAGAS-aligned metrics (faithfulness · answer relevancy · context precision / recall) · LLM-as-judge · CI regression gates · Langfuse tracing · cost attribution
**Backend** — Python · FastAPI · REST APIs · PostgreSQL · Redis · MySQL · JWT / OAuth2 · async workers
**Infra & cloud** — Docker · GitHub Actions (CI/CD) · GCP · AWS Bedrock · Linux · Git
**Also** — PHP / Laravel *(production backend experience)*

---

<p align="center"><i>Building AI systems that can be measured, debugged, and trusted — not just demoed.</i></p>
