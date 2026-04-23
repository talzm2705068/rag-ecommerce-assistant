# Architecture

User Query
↓
Embedding
↓
Vector DB (FAISS)
↓
Top-K Retrieval
↓
Reranker
↓
LLM Response

## Data Ingestion
- 商品資料收集
- 清理與轉換

## Embedding
- BGE-M3

## Retrieval
- Top-K = 5
