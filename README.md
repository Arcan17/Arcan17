# Hi, I'm Bastian 👋

**Python Backend Developer · AI Automation · RAG Systems · ETL Pipelines**  
📍 Viña del Mar, Chile &nbsp;|&nbsp; 🌐 Open to remote roles

I build backend systems, data pipelines, and AI automation tools using Python, FastAPI, PostgreSQL, Docker, and LLM APIs. My projects run in production with automated tests, CI/CD, and architecture documentation.

---

## Featured Projects

### 🔒 [PrivRAG](https://github.com/Arcan17/privrag) · [Live API Demo](https://privrag-production.up.railway.app/docs)
Privacy-preserving RAG pipeline for enterprise document Q&A. Semantic chunking, ChromaDB vector store, cosine similarity threshold, SHA256 query cache (30–45% hit rate), and regex + spaCy PII stripping (100% RUT/email detection). Raw sensitive data never reaches external APIs.  
`Python` `FastAPI` `ChromaDB` `PostgreSQL` `spaCy` `Docker` `CI/CD` — **61 tests**

---

### 🤖 [AgentForge](https://github.com/Arcan17/agentforge)
Production multi-agent research platform built with LangGraph. 5-node pipeline (Planner → Researcher → Analyst → Critic → Writer), human-in-the-loop gating, SSE streaming, Celery task queue, cost tracking per run ($0.025/task avg), and a Next.js 15 dashboard.  
`Python` `LangGraph` `FastAPI` `Next.js 15` `Celery` `Redis` `PostgreSQL` `Docker` — **130 tests**

---

### 🏠 [Real Estate ETL Pipeline](https://github.com/Arcan17/real-estate-etl)
End-to-end ETL scraping ~240 live Chilean property listings, normalizing with Polars, loading into DuckDB, and exposing a FastAPI query layer with analytics endpoints, Excel export, and a Streamlit dashboard.  
`Python` `Scrapling` `Polars` `DuckDB` `FastAPI` `Streamlit` `Docker` `CI/CD`

---

### ⚙️ [PeopleOps Workflow API](https://github.com/Arcan17/peopleops-workflow-api)
Production-grade REST API for HR workflow automation: role-based permissions, Celery async notifications, approval chains, audit logs, and OpenAPI docs. Built as a Django/DRF reference for enterprise patterns.  
`Python` `Django REST Framework` `PostgreSQL` `Celery` `Redis` `Docker` `CI/CD`

---

### 🔔 [Crypto Whale Tracker](https://github.com/Arcan17/crypto-whale-tracker)
Real-time Ethereum on-chain intelligence pipeline. Streams pending transactions via WebSocket, detects whale movements, labels known exchange/DeFi wallets, and sends instant Telegram alerts.  
`Python` `Web3.py` `Alchemy` `FastAPI` `PostgreSQL` `asyncio` `Docker` — **30 tests**

---

## Tech Stack

| Area | Tools |
|------|-------|
| **Languages** | Python 3.11+, TypeScript, SQL |
| **Backend** | FastAPI, Django REST Framework, SQLAlchemy 2.0 |
| **AI / LLMs** | LangGraph, LangChain, Anthropic Claude, OpenAI GPT-4o, ChromaDB, RAG |
| **Data / ETL** | Polars, DuckDB, Scrapling, Streamlit |
| **Databases** | PostgreSQL, Redis, SQLite, ChromaDB |
| **DevOps** | Docker, GitHub Actions CI/CD, Railway, Alembic |
| **Testing** | pytest, pytest-asyncio, coverage |
| **Async** | asyncio, WebSockets, SSE, Celery |

---

## Standards

Every project I ship includes:
- ✅ Type hints and clean, readable code
- ✅ Unit + integration tests (pytest)
- ✅ Docker + docker-compose
- ✅ GitHub Actions CI/CD
- ✅ Architecture documentation
- ✅ Zero hardcoded credentials

---

📬 **mixtape.bast@gmail.com** · [LinkedIn](https://linkedin.com/in/bastian-altamirano-3805b4309) · [Portfolio](https://portfolio-seven-dusky-80.vercel.app)
