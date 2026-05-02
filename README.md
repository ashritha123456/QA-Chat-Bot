# 🤖 QA Chat Bot using RAG (Retrieval-Augmented Generation)

This project is an AI-powered Question Answering chatbot built using **Retrieval-Augmented Generation (RAG)**.  
It allows users to upload a PDF and ask questions based on its content.

---

## 🚀 Features

- 📄 Upload PDF documents
- 🔍 Extract and chunk document text
- 🧠 Generate embeddings using IBM Watsonx
- 📚 Store embeddings in Chroma vector database
- 🤖 Answer questions using IBM Granite LLM
- 🌐 Simple Gradio web interface

---

## 🛠️ Tech Stack

- Python
- LangChain
- IBM Watsonx AI (Granite LLM + Embeddings)
- ChromaDB (Vector Store)
- Gradio (UI)
- PyPDFLoader

---

## 📁 Project Structure
QA-Chat-Bot/
│
├── qabot.py # Main application (RAG chatbot code)
├── requirements.txt # Python dependencies
├── README.md # Project documentation
│
├── flagged/ # Gradio logs and uploaded files (ignore in production)
│ ├── log.csv
│ └── Upload PDF File/
│
└── .theia/ # IDE configuration files (auto-generated)
└── settings.json

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/ashritha123456/QA-Chat-Bot.git
cd QA-Chat-Bot
