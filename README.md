# Hi, I'm Bastian 👋

**Python Backend · ETL Pipelines · Automation · Web3** · Viña del Mar, Chile · Open to remote work

I build tools that extract value from data and automate what shouldn't be manual — real-time blockchain monitors, ETL pipelines, REST APIs, Telegram bots, and AI-powered platforms.

---

## What I can build for you

| Need | What I deliver |
|---|---|
| 🐋 **On-chain / Web3 data** | Real-time tx monitoring, wallet labeling, whale alerts |
| 📊 **ETL data pipeline** | Extract → clean (Polars) → load (DuckDB/PostgreSQL) + REST API |
| 🕷️ **Scrape a website or API** | Scrapling/Playwright scraper → clean JSON/CSV/DB |
| 🤖 **Telegram / Discord bot** | Commands, alerts, scheduled messages, inline buttons |
| 🚀 **FastAPI / Django backend** | CRUD API, auth, pagination, Docker, tests, CI/CD |
| 🔌 **Connect two APIs** | Aggregation, transformation, sync, webhooks |
| 📈 **Price / data monitor** | Alerts when conditions are met, history stored |

---

## Tech Stack

```python
stack = {
    "backend":     ["FastAPI", "Django/DRF", "SQLAlchemy", "Pydantic v2", "Alembic"],
    "data":        ["Polars", "DuckDB", "pandas", "PostgreSQL", "SQLite", "Redis"],
    "scraping":    ["Scrapling", "httpx", "BeautifulSoup", "Playwright"],
    "bots":        ["python-telegram-bot", "asyncio", "WebSockets"],
    "ai":          ["Anthropic Claude", "OpenAI GPT-4o", "Google Gemini"],
    "crypto":      ["Web3.py", "Alchemy", "CoinGecko API", "Binance API", "Polymarket API"],
    "devops":      ["Docker", "GitHub Actions CI/CD", "pytest", "Ruff", "Black"],
}
```

---

## Featured Projects

### 🐋 [Crypto Whale Tracker](https://github.com/Arcan17/crypto-whale-tracker)
Real-time Ethereum on-chain intelligence pipeline. Streams pending transactions via WebSocket, detects whale movements above a configurable USD threshold, labels known exchange/DeFi/bridge wallets, and sends instant Telegram alerts. Exposes a FastAPI REST API with paginated queries, wallet intelligence summaries, and CSV/XLSX export. Includes a browser dashboard, 30 passing tests, and GitHub Actions CI/CD.
`Web3.py` `Alchemy` `FastAPI` `SQLAlchemy` `PostgreSQL` `asyncio` `Docker` `CI/CD`

### 🏠 [Real Estate ETL Pipeline](https://github.com/Arcan17/real-estate-etl)
End-to-end ETL for Chilean real estate listings. Scrapes ~240 live property listings with Scrapling (anti-bot fingerprinting), cleans and normalizes with Polars, loads into DuckDB, and exposes a FastAPI query layer with analytical endpoints and Excel/XLSX export. Interactive Streamlit dashboard with filters and clickable property links.
`Scrapling` `Polars` `DuckDB` `FastAPI` `Streamlit` `Plotly` `openpyxl` `CI/CD`

### 📊 [Crypto Price Monitor](https://github.com/Arcan17/crypto-price-monitor)
ETL pipeline that fetches BTC/ETH/USDC prices from CoinGecko every 5 minutes, stores in PostgreSQL, and exposes a REST API with 24h stats and CSV export (`/api/export/prices.csv`).
`Django` `Celery` `Redis` `PostgreSQL` `DRF` `Docker`

### 🔔 [ML Price Tracker](https://github.com/Arcan17/ml-price-tracker)
Telegram bot that monitors MercadoLibre Chile prices and alerts users when a product drops to their target price. Checks every 30 minutes with async job scheduling — no API key needed.
`python-telegram-bot` `MercadoLibre API` `SQLAlchemy` `FastAPI` `Docker`

### 🚗 [SoloMiro](https://github.com/Arcan17/solomiro)
Full-stack AI platform that helps Chilean drivers decide whether to keep or switch their car. Calculates real total cost of ownership and delivers a personalized recommendation via Claude / GPT-4o / Gemini. AI provider is swappable via a single env variable.
`FastAPI` `Next.js 14` `PostgreSQL` `SQLAlchemy` `Anthropic` `OpenAI` `Docker`

### 📋 [Task Manager API](https://github.com/Arcan17/task-manager-api)
Production-ready REST API with full CRUD, status filtering, pagination, Pydantic v2, Alembic migrations, 20+ tests, and GitHub Actions CI. Clean architecture base for any backend project.
`FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Alembic` `Docker`

---

## Every project I ship includes

- ✅ Clean, typed Python code with comments
- ✅ Unit + integration tests (pytest)
- ✅ Docker + docker-compose ready
- ✅ GitHub Actions CI/CD
- ✅ `.env.example` — no hardcoded credentials
- ✅ Clear README with quickstart in 3 commands

---

## Currently

- 🔭 Open to freelance projects: ETL, scraping, bots, APIs, automation, Web3
- 🌎 Open to remote roles: Python Developer · Backend Engineer · Data Engineer
- 📍 Based in Chile — available for US/EU time zones

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bastian_Altamirano-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/bastian-altamirano/)
[![GitHub](https://img.shields.io/badge/GitHub-Arcan17-181717?style=flat&logo=github)](https://github.com/Arcan17)
[![Upwork](https://img.shields.io/badge/Upwork-Available-6FDA44?style=flat&logo=upwork)](https://www.upwork.com/freelancers/~01250252bf559aadff)
