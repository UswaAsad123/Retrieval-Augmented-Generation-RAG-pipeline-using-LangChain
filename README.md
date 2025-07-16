# RAG Pipeline with LangChain, Gemini LLM, FAISS, and HuggingFace Embeddings

##  Project Overview

This project implements a **Retrieval-Augmented Generation (RAG)** system using the LangChain framework. It demonstrates how to:

* Load data from the web
* Split it into chunks
* Generate vector embeddings
* Store them in a FAISS vector store
* Retrieve context based on user queries
* Use Google Gemini LLM to generate intelligent answers

## 💡 Key Components

* **LangChain**: Framework for chaining LLMs and tools
* **FAISS**: Fast vector search for similarity retrieval
* **HuggingFace Embeddings**: `all-MiniLM-L6-v2` used for document embeddings
* **Google Gemini**: Used as the LLM for answering based on context

##  Technologies

* Python
* LangChain
* HuggingFace Transformers
* FAISS
* Google Generative AI (Gemini)
* Jupyter / Python scripts


## 📄 Example Query

```python
query = "What is a heuristic function?"
result = graph.invoke({"question": query})
print(result["answer"])
```

## 📂 Project Structure

```
.
├── .env               # API keys (not pushed)
├── .env.example       # Example placeholder
├── rag_pipeline.py    # Main code
├── README.md          # This file
├── requirements.txt   # Dependencies
```

## 🛡️ Security & Tips

* NEVER push `.env` to GitHub.
* Regenerate API keys if accidentally exposed.
* Share `.env.example` for collaborators.

## 🤝 Contributions

PRs are welcome! Feel free to fork and suggest improvements.


