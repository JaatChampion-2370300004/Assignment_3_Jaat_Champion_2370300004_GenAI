# 🔍 LangChain RAG Pipeline using Ollama, Chroma, and Local PDF

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using:
- 🔗 [LangChain](https://www.langchain.com/)
- 🧠 [Ollama LLMs](https://ollama.com/)
- 📚 Chroma vector store
- 🤗 HuggingFace embeddings
- 📄 Local PDF documents (e.g., academic syllabus)

---

## 📦 Installation

### 🐍 Create and activate a virtual environment (optional)
```bash
python -m venv rag_env
source rag_env/bin/activate  # or `rag_env\Scripts\activate` on Windows
pip install langchain chromadb unstructured pypdf sentence-transformers

📂 rag_project/
├── rag_pipeline.py            # Main pipeline code
├── bsc_math_syllabus.pdf      # Your PDF document
├── README.md                  # This file

python rag_pipeline.py


❓ Example Questions to Ask

What subjects are covered in Semester 1?

How many credits are assigned to Calculus?

What is the objective of this syllabus?

What is the evaluation method used?

Are there any practical/lab-based courses?..

⚠️ Disclaimer
This tool uses AI-generated answers based on local document retrieval. Please verify critical academic information with official sources.

📬 Credits
Built using:

LangChain

HuggingFace Transformers

Chroma DB

Ollama LLMs


---
