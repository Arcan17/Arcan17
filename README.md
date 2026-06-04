# Hi, I'm Bastian 👋

### Python Backend & Applied AI Engineer

**I build production APIs, AI agents and RAG systems** — with FastAPI, LangGraph, PostgreSQL, Docker and CI/CD.  
📍 Viña del Mar, Chile &nbsp;·&nbsp; 🌐 Open to remote roles worldwide

&nbsp;

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-seven-dusky-80.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bastian-altamirano)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mixtape.bast@gmail.com)

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

![LangGraph](https://img.shields.io/badge/LangGraph-7C3AED?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D97706?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)

![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFC832?style=flat-square&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 🚀 Featured Projects

### 🎯 [JobOps AI](https://github.com/Arcan17/jobops-ai) — AI-powered Job-Search CRM
Paste a job → get a **defensible hybrid fit score** (deterministic weighted components + **pgvector** embeddings; the LLM only *explains* the result, **never sets the number**, so scores stay reproducible) → generate recruiter outreach, track applications on a status board, and run a **rule-based recruiter safety check** that flags scam signals. Full-stack with a **Next.js** dashboard; built spec-driven; **deterministic offline tests — no paid LLM calls in CI**.  
`FastAPI` `pgvector` `SQLAlchemy 2.0` `Next.js` `TypeScript` `Docker` `CI/CD` — **35 tests**

---

### 🎟️ [AgentDesk AI](https://github.com/Arcan17/agentdesk-ai)
Human-in-the-loop AI **SupportOps** platform. A **LangGraph** workflow (classifier → retriever → draft → critic → decision) drafts support replies grounded in a **pgvector** knowledge base; operators **approve / edit / reject** and low-confidence cases auto-escalate. Multi-tenant (JWT + RBAC), audit log, metrics, **HMAC-signed webhooks** with bounded Celery retries, and a Next.js dashboard. Built spec-driven; **deterministic offline tests — no paid LLM calls in CI**.  
`FastAPI` `LangGraph` `pgvector` `Celery` `Redis` `Next.js` `Docker` `CI/CD` — **42 tests**

---

### 🤖 [AgentForge](https://github.com/Arcan17/agentforge)
Production multi-agent research pipeline with **LangGraph** and **FastAPI**. 5-node pipeline (Planner → Researcher → Analyst → Critic → Writer), human-in-the-loop approval, real-time SSE streaming, cost tracking and a Next.js dashboard.  
`LangGraph` `FastAPI` `Celery` `Redis` `PostgreSQL` `Docker` — **123 tests**

---

### 🔒 [PrivRAG](https://github.com/Arcan17/privrag) &nbsp;·&nbsp; **[Live Demo ↗](https://privrag-production.up.railway.app/docs)**
Privacy-preserving RAG API for enterprise documents. Strips PII (RUT/email/phone) before it reaches the LLM. SHA256 cache (30–45% hit rate), cosine threshold filtering, 61 automated tests.  
`FastAPI` `ChromaDB` `PostgreSQL` `fastembed` `spaCy` `Railway`

---

### ⚙️ [IntegrationOps](https://github.com/Arcan17/integrationops)
Backend platform for data ingestion, async job processing, HMAC-signed webhooks and operational audit trails. JWT auth + RBAC (admin/operator/viewer), Celery/Redis workers, Next.js dashboard.  
`FastAPI` `Celery` `Redis` `PostgreSQL` `Docker` `CI/CD` — **100+ tests**

---

### 🏠 [Real Estate ETL Pipeline](https://github.com/Arcan17/real-estate-etl) &nbsp;·&nbsp; **[Live Demo ↗](https://real-estate-etl-production.up.railway.app)**
End-to-end ETL for Chilean property listings. Scraping with anti-bot fingerprinting, Polars transforms, DuckDB analytics, FastAPI REST layer and Streamlit dashboard with Excel export.  
`Python` `Scrapling` `Polars` `DuckDB` `FastAPI` `Streamlit` `Docker`

---

### 🔔 [Crypto Whale Tracker](https://github.com/Arcan17/crypto-whale-tracker)
Real-time Ethereum on-chain intelligence pipeline. Streams pending transactions via WebSocket, detects whale movements, labels known exchange/DeFi wallets and sends instant Telegram alerts.  
`Python` `Web3.py` `FastAPI` `PostgreSQL` `asyncio` `Docker` — **30 tests**

---

## 📊 GitHub Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Arcan17&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Arcan17&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</p>

---

*Every project ships with tests, Docker, CI/CD and clear documentation — because production code needs to be maintainable, not just functional.*
