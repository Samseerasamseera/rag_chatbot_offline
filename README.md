# rag_chatbot_offline
# PDF Question Answering with FAISS & Local LLM

This project allows you to **ask questions about the contents of a PDF** using:
- **SentenceTransformers** for text embeddings
- **FAISS** for fast semantic search
- **FLAN-T5** (via Hugging Face) as a local Large Language Model for answer generation

It works by:
1. Extracting and chunking text from a PDF.
2. Creating vector embeddings of the chunks.
3. Indexing them with FAISS for efficient retrieval.
4. Using a local LLM to generate an answer based on the most relevant chunks.

---



