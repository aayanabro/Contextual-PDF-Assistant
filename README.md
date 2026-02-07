# RAG Chatbot: Interactive PDF Assistant

This repository contains a **Retrieval-Augmented Generation (RAG)** chatbot built with Streamlit and LangChain. It allows users to upload a PDF and ask questions directly to the document using powerful LLMs via Groq.

## ✨ Features
- **PDF Document Loading**: Automatically processes and parses PDF files (configured for `reflexion.pdf`).
- **Intelligent Chunking**: Uses `RecursiveCharacterTextSplitter` to maintain context within text segments.
- **Vector Search**: Utilizes **FAISS** for efficient, local similarity searches.
- **High-Performance LLM**: Integrated with **Groq** for lightning-fast responses using models like `gpt-oss-120b`.
- **Session History**: Maintains a chat interface that remembers the conversation flow.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **Orchestration**: LangChain
- **Embeddings**: HuggingFace (`sentence-transformers/all-MiniLM-L6-v2`)
- **LLM**: Groq API
- **Vector Store**: FAISS

## 🚀 Getting Started

1. **Clone the Repo**:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
