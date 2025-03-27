# 🧠 Medical RAG Chatbot using GROQ and Langchain

This project demonstrates a Retrieval-Augmented Generation (RAG) chatbot built with Langchain and GROQ API. It fetches the latest medical documents from 20 online sources and allows intelligent Q&A via a large language model.

## 🚀 Features
- Loads 20 medical web documents
- Embeds using `all-mpnet-base-v2`
- Vector search using FAISS
- Answer generation via GROQ LLMs (e.g., `llama3-70b-8192`)
- Clean modular LangChain implementation

## 🔧 Requirements
Install packages with:
```bash
pip install -r requirements.txt
