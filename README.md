# FinSight

AI-powered stock market intelligence dashboard

# FinSight

AI-powered stock market intelligence dashboard built with Python, DuckDB, Streamlit, and Claude API.

## Architecture

Data Source (yfinance) → Pipeline (Python) → Storage (DuckDB) → Analytics (SQL) → Dashboard (Streamlit + Plotly) → AI Insights (Claude API)

## Features

- Real-time OHLCV data ingestion for 15+ stocks
- SQL-powered technical indicators (RSI, moving averages, sector comparison)
- Interactive candlestick charts with indicator overlays
- Portfolio tracker with P&L analysis
- AI-generated plain-English market insights via Claude API

## Tech Stack

| Layer          | Technology                   |
| -------------- | ---------------------------- |
| Data ingestion | yfinance, Python             |
| Storage        | DuckDB                       |
| Analytics      | SQL (window functions, CTEs) |
| Dashboard      | Streamlit, Plotly            |
| AI insights    | Anthropic Claude API         |
| CI/CD          | GitHub Actions               |

## Setup

```bash
git clone https://github.com/YOUR_USERNAME/finsight.git
cd finsight
pip install -r requirements.txt
cp .env.example .env   # add your API key
```

## Running

```bash
streamlit run dashboard/app.py
```

## Project Status

- [x] Phase 1: Repository + structure
- [ ] Phase 2: Data pipeline
- [ ] Phase 3: SQL analytics
- [ ] Phase 4: Dashboard
- [ ] Phase 5: AI insights
- [ ] Phase 6: CI/CD + deployment
