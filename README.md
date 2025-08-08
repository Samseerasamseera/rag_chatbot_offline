# rag_chatbot_offline
 PDF Question Answering with FAISS & Local LLM

This project allows you to **ask questions about the contents of a PDF** using:
- **SentenceTransformers** for text embeddings
- **FAISS** for fast semantic search


It works by:
1. Extracting and chunking text from a PDF.
2. Creating vector embeddings of the chunks.
3. Indexing them with FAISS for efficient retrieval.
4. Using a local LLM to generate an answer based on the most relevant chunks.

---
## 📦 Installation

1. **Clone or download** this repository.

2. **Install dependencies** from `requirements.txt`:
   ```bash
   pip install -r requirements.txt

3. ▶️ Running the Script
    Run the following command in your terminal:
   ```bash
   python main.py


