# Enterprise RAG System

Features:
- Multi PDF upload
- Retrieval-Augmented Generation (RAG)
- Citations (source file names)
- Semantic search using embeddings
- FastAPI backend
- Chroma vector database
- Simple web UI

## Run

```bash
pip install -r requirements.txt
uvicorn app:app --reload
```

Open: http://127.0.0.1:8000

## API
- POST `/upload`
- POST `/ask`
