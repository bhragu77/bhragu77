<h1 align="center">Hi 👋, I'm Bhragu Gour</h1>

<h3 align="center">AI Engineer | LLM · RAG · Agentic AI · LLMOps | Python · FastAPI</h3>

<p align="center">
  <b>I build production-oriented AI systems that can retrieve, reason, use tools, verify evidence, and fail safely.</b>
</p>

<p align="center">
  Applied AI Engineer with ~2 years of production backend engineering experience,
  specializing in LLM applications, RAG, agentic systems, evaluation, and LLMOps.
</p>

---

## 🧠 About Me

* 🔭 Currently building **DocuChunk** — a production-shape RAG & agentic document-intelligence platform
* 🤖 Building **multi-agent systems** using LangGraph, tool-use, bounded self-correction, and evidence-based verification
* 🔍 Specialized in **RAG, hybrid retrieval, reranking, vector databases, embeddings, and semantic search**
* 📊 Strong focus on **LLM evaluation, observability, regression testing, cost attribution, and production reliability**
* 🐍 Working primarily with **Python, FastAPI, LangChain, LangGraph, and LlamaIndex**
* ☁️ Experience with **GCP, AWS Bedrock, Docker, Redis, PostgreSQL, pgvector, and production REST APIs**
* 💼 Working as a **Software Engineer — Backend & AI Integrations** at Think Exam
* 🚀 Interested in building **reliable AI products rather than AI demos**
* 👯 Open to collaborating on **LLM, RAG, Agentic AI, and AI infrastructure projects**

---

# 🚀 Featured AI Projects

## 1. DocuChunk

### Production-Shape RAG & Agentic Document-Intelligence Platform

**Python · FastAPI · LangChain · LlamaIndex · pgvector · ChromaDB · Pinecone · Redis · Docker**

An end-to-end RAG platform designed around measurable retrieval quality, agent reliability, evaluation, observability, and production-style architecture.

**16K+ LOC · 510 passing tests**

### 🔍 Retrieval Engineering

* Hybrid retrieval combining **dense vectors + BM25 + Reciprocal Rank Fusion**
* Cross-encoder reranking using **FlashRank**
* Multiple chunking and retrieval strategies
* MMR-based retrieval
* Improved **MRR from 0.78 → 0.97** on a 42-document distractor benchmark

### 🗄️ Vector Database Architecture

* Built a common abstraction across:

  * **pgvector**
  * **ChromaDB**
  * **Pinecone**
* Per-document backend routing
* Cross-backend query merging
* Benchmarked retrieval consistency, latency, and infrastructure trade-offs

### 🤖 Agentic Retrieval

* Implemented an **agentic ReAct retrieval loop**
* Tool-based retrieval and reasoning
* Five safety/reliability guardrails:

  * Step limits
  * Loop detection
  * Fallback-to-RAG
  * Controlled tool execution
  * Bounded execution
* Achieved **+0.43 context recall** over vanilla RAG under constrained retrieval budgets

### ✅ LLM Verification & Trust

Built a verification layer around generated answers:

* Citation parsing and validation
* Evidence-groundedness checking
* Faithfulness evaluation
* Abstention when evidence is insufficient
* Fail-closed verification architecture

**Faithfulness: 0.71 → 0.89**

The system is explicitly designed so a verifier failure cannot silently turn into a confident answer.

### 📊 Evaluation & LLMOps

* RAGAS-aligned evaluation harness
* Faithfulness
* Answer relevancy
* Context precision
* Context recall
* LLM-as-judge evaluation
* Hermetic CI regression gates
* Langfuse tracing with **21 span types**
* Per-query cost attribution

**Approx. cost: ₹0.09/query**

### 🔌 Model Infrastructure

Integrated multiple LLM providers behind a common protocol:

* Google Gemini
* OpenAI-compatible APIs
* Ollama
* Deterministic test stub
* Open-source/local models

Also implemented:

* SSE streaming
* Semantic caching
* Model routing
* Fallback handling

➡️ **[Explore DocuChunk →](https://github.com/bhragu77/docuchunk)**

---

# 🤖 2. Enterprise Transformation Research Agent

### Multi-Agent AI Research Platform

**Python · FastAPI · LangGraph · React · TypeScript · PostgreSQL · pgvector · Redis · Groq · Gemini · Docker · GCP · Render**

A multi-agent research system designed around structured research workflows and evidence-backed responses.

### Architecture

* LangGraph-based multi-agent orchestration
* **8-stage processing pipeline**
* Guardrail screening
* Query decomposition
* Parallel specialist agents
* Evidence collection
* Evidence fusion
* Synthesis
* Independent verification
* Bounded self-correction loop
* A2A protocol for external research

### 🛡️ Trust Architecture

The system deliberately prevents the model from being the sole judge of its own answer.

Every claim must:

1. Reference supporting evidence
2. Pass citation validation
3. Be checked for groundedness
4. Receive confidence based on measured signals
5. Abstain when sufficient evidence is unavailable

➡️ **[Explore the project →](#)**

---

# 💼 Professional Experience

## Software Engineer — Backend & AI Integrations

**Think Exam — A Ginger Webs Company**
**Jul 2025 – Present**

Working on backend systems and AI integrations for a large-scale online examination platform.

### Backend Engineering

* Designed and optimized REST APIs using **Laravel, PHP, MySQL**
* Improved API response times by **30%+** through query optimization and indexing
* Worked with joins, aggregations, caching, and database optimization
* Implemented secure authentication using **RBAC, JWT/Sanctum**
* Built background workflows and asynchronous processing

### AI Integrations

* Integrated third-party **AI-based proctoring systems** for face, gaze, and anomaly detection
* Built REST/webhook-based event ingestion pipelines
* Implemented asynchronous processing and violation persistence
* Worked with AI services inside production examination workflows

### Production Engineering

* Diagnosed and resolved a **~40× authentication latency regression**
* Reduced authentication latency from **4.8s → 0.12s**
* Used staged DNS/TCP/TLS timing analysis and connection pooling
* Fixed first-boot database bootstrap issues
* Debugged production systems through Linux logs and controlled reproduction

### Infrastructure

* Validated the same application across:

  * Render PaaS
  * Self-hosted secure tunnel
  * Documented scale-out architecture
* Implemented GCS signed-URL based PDF report sharing

🏆 **Recognized as Engineer of the Year** for consistent delivery and end-to-end ownership.

---

# 🧰 Technical Stack

### Generative AI / LLM

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge\&logo=python\&logoColor=ffdd54)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge\&logo=langchain\&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge\&logo=openai\&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge\&logo=googlegemini\&logoColor=white)

**RAG · Prompt Engineering · Agentic AI · ReAct · Multi-Agent Systems · Tool Use · Guardrails · Embeddings · Semantic Search · Model Routing · Streaming · Semantic Caching**

---

### 🔎 Retrieval & Vector Databases

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge\&logo=pinecone\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge)

**pgvector · Pinecone · ChromaDB · BM25 · RRF · MMR · Cross-Encoder Reranking · FlashRank · Chunking Strategies**

---

### 📊 LLMOps & Evaluation

![RAGAS](https://img.shields.io/badge/RAGAS-Evaluation-6E56CF?style=for-the-badge)
![Langfuse](https://img.shields.io/badge/Langfuse-Observability-000000?style=for-the-badge)

**Faithfulness · Answer Relevancy · Context Precision · Context Recall · LLM-as-Judge · CI Regression Gates · Tracing · Prompt/Version Management · Cost Attribution · Monitoring · Fallbacks**

---

### ⚙️ Backend & Data

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge\&logo=laravel\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge\&logo=php\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge\&logo=mysql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)

**Python · FastAPI · PHP · Laravel · REST APIs · PostgreSQL · MySQL · Redis · SQL · JWT · OAuth 2.0 · RBAC · Webhooks · Async Workers**

---

### ☁️ Cloud & DevOps

![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge\&logo=docker\&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge\&logo=googlecloud\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)

**GCP · AWS Bedrock · Docker · Docker Compose · Render · Linux · Git · GitHub Actions · CI/CD · Postman · GCS**

---

# 🧩 Engineering Foundations

**Data Structures · Algorithms · OOP · DBMS · SQL · REST Architecture · Design Patterns · Authentication · Authorization · Production Debugging · Distributed Systems Fundamentals**

---

# 📈 What I Care About

> **An AI system isn't production-ready just because it generates a good answer.**

I care about:

**Retrieval quality → Grounded generation → Evaluation → Observability → Reliability → Cost → Safe failure**

My goal is to build AI systems that can be **measured, debugged, evaluated, and trusted** — not just demonstrated.

---

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bhragu77&show_icons=true&theme=default&hide_border=true" alt="Bhragu's GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhragu77&layout=compact&theme=default&hide_border=true" alt="Top languages" height="165" />
</p>

---

# 🔗 Connect

<p align="left">
<a href="https://linkedin.com/in/bhragu77" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

<a href="mailto:bhragugaur77@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<a href="https://github.com/bhragu77" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
</p>

---

<p align="center">
  <i>Building reliable AI systems, one evaluation at a time.</i>
</p>
