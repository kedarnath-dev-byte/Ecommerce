# Red Diamond AI Starter Codebase

A starter full-stack skeleton for:
- FastAPI backend
- React frontend
- LangGraph research workflow
- upload + PDF parsing + local RAG
- research start endpoint
- company analysis endpoint
- base UI pages

## Run backend
```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
cp .env.example .env
uvicorn app.main:app --reload
```

## Run frontend
```bash
cd frontend
npm install
npm run dev
```

## Current status
This is a starter skeleton, not a finished product. Next additions:
- real web retrieval tools
- financial data provider integration
- proper strategy agents
- authentication
- report export
- background jobs / streaming
