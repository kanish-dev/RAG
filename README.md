# 🚀 RAG Pipeline from Scratch (Retrieval-Augmented Generation)

An end-to-end **Retrieval-Augmented Generation (RAG)** system built from scratch to enable accurate question answering over custom documents using semantic search and LLMs.

---

## 📌 Overview

This project implements a complete RAG pipeline that:
- Ingests documents (PDFs, CSVs)
- Converts them into embeddings
- Stores them in a vector database
- Retrieves relevant context
- Generates accurate responses using an LLM

👉 The goal is to **bridge the gap between raw data and intelligent AI responses**

---

## 🧠 What is RAG?

Retrieval-Augmented Generation (RAG) combines:
- **Retrieval** → Fetch relevant information from a knowledge base  
- **Generation** → Use LLMs to generate context-aware answers  

This improves factual accuracy and reduces hallucinations in AI systems.

---

## ⚙️ Features

✅ Document ingestion (PDF, CSV)  
✅ Text chunking & preprocessing  
✅ Embedding generation  
✅ Vector similarity search  
✅ LLM-based response generation  
✅ Modular pipeline design  
✅ Debugging & error handling  

---

## 🏗️ Project Structure
```bash
RAG/
│── data/                # Input documents 
│── notebook/            # Experiments & testing
│── src/
│   ├── search.py        # Retrieval logic
│   ├── ...
│── main.py              # Entry point
│── requirements.txt     # Dependencies
│── .env                 # API keys 
│── .gitignore
│── README.md
```


---

## 🔧 Tech Stack

- Python  
- LangChain / LangGraph  
- ChromaDB / FAISS (Vector DB)  
- LLMs (OpenAI / Groq / LLaMA)  
- Jupyter Notebook  

---

## 🔄 Pipeline Flow
```text
User Query
↓
Embedding Generation
↓
Vector Search (Top-K Retrieval)
↓
Context Injection
↓
LLM Response Generation

```
<img width="596" height="298" alt="image" src="https://github.com/user-attachments/assets/41d2f6cd-ec04-431f-8d1d-cae7583dd8b6" />

<img width="594" height="345" alt="image" src="https://github.com/user-attachments/assets/06a4f3a1-bad3-48b3-b911-c109f89b2309" />

---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/kanish-dev/RAG.git
cd RAG
```
###2️⃣ Install dependencies
``` bash
pip install -r requirements.txt
```
### 3️⃣ Add your data
``` bash
/data
```
### 4️⃣ Run the project
```bash
python main.py
```


### 🧠 Key Learnings
  - Chunking strategy directly impacts retrieval quality
  - Retrieval quality > generation quality
  - Handling noisy/unstructured data is challenging
  - Vector database design is critical
  - Debugging real-world pipelines is non-trivial

<img width="925" height="377" alt="image" src="https://github.com/user-attachments/assets/4bf6c076-a1a6-4b1b-87bb-55e5d2dc19f3" />


### 🚀 Future Improvements
  -  🔄 Reranking (Cross-Encoder)
  -  ⚡ Hybrid Search (BM25 + Vector)
  -  🧠 Query optimization
  -  🌐 UI interface (Streamlit / FastAPI)
  -  📊 Evaluation metrics for RAG

## 📬 Contact

**Kanishka**  
📧 Email: your-email@example.com  
🔗 LinkedIn: https://www.linkedin.com/in/your-profile  

---

## ⭐ Support

If you found this project useful:

⭐ Star this repository  
🍴 Fork it  
📢 Share it with others  

It really helps and motivates me to build more!
