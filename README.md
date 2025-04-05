# 🧠 Website Q&A Bot using LangChain + ChromaDB + LLaMA

This project is an interactive **Q&A chatbot** that ingests the content of any website, stores it as semantic embeddings in a **Chroma vector database**, and answers user queries using an open-source **LLaMA model** via HuggingFace.

---

## 🚀 Features

- 🌐 Extracts clean website content (text only)
- ✂️ Splits content into smart chunks
- 🧠 Converts chunks to embeddings using HuggingFace embeddings
- 🗂 Stores vectors in **ChromaDB** for fast retrieval
- 🔁 Combines retrieved context with your question
- 🤖 Responds with high-quality answers using an LLaMA-based model

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| **LangChain** | Build chains of LLM + retriever |
| **ChromaDB** | Vector database for document search |
| **Sentence Transformers** | Embeddings (`all-MiniLM-L6-v2`) |
| **HuggingFace Transformers** | Load open-source LLMs like LLaMA |
| **Jupyter Notebook** | Prototype, debug, and iterate |

---

🧪 Example Use Case
Website: https://lmsys.org/blog/2023-03-30-vicuna/

Questions you can ask:

“What is Vicuna?”

“How is it different from Alpaca?”

“Who developed it?”
