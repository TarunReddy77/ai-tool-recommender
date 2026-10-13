# AI Tool Recommender

A recommender that suggests AI tools from interaction and content signals. Work in progress.

- Two-tower embedding retrieval model for candidate generation over a Pinecone ANN index, benchmarked against a collaborative-filtering (matrix-factorization) baseline.
- Two-stage retrieval and ranking, with a learned ranking layer over content and behavioral features.
- Served via FastAPI with Redis embedding caching, evaluated on Recall@K and NDCG@K.

**Stack:** PyTorch, FAISS, Pinecone, Redis, FastAPI

Status: in progress, code coming soon.
