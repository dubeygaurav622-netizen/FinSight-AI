# 🚀 FinSight AI – Financial Document Intelligence Platform

## 📌 Overview
FinSight AI is a production-grade AI-powered system designed to manage, analyze, and semantically search financial documents such as invoices, reports, and contracts.

The platform uses Retrieval-Augmented Generation (RAG) and vector databases to provide accurate and context-aware search results.

---

## 🔥 Key Features

- 🔐 JWT Authentication (Secure login & access control)
- 📁 Document Management (Upload, view, delete documents)
- 🧠 RAG-Based Semantic Search
- 🎯 Smart Reranking (Top relevant results)
- 🛡️ Role-Based Access Control (Admin, Analyst, Auditor, Client)
- ⚡ High-performance FastAPI backend

---

## 🏗️ Architecture

### Document Processing Pipeline:
1. Upload Document
2. Text Extraction (PDF/DOCX)
3. Chunking (LangChain)
4. Embedding Generation
5. Storage in Vector Database (Qdrant)

### Retrieval Flow:
1. User Query
2. Query Embedding
3. Vector Search (Top 20 results)
4. Reranking
5. Return Top 5 Results

---

## 🛠️ Tech Stack

- FastAPI (Backend Framework)
- PostgreSQL (Relational Database)
- Qdrant / FAISS (Vector Database)
- LangChain (Document Processing)
- Python (Core Language)
- JWT / OAuth2 (Authentication)
- Docker (Deployment)

---

## 📡 API Endpoints

### Auth APIs
- POST /auth/register
- POST /auth/login
- GET /auth/me

### Document APIs
- POST /documents/upload
- GET /documents
- DELETE /documents/{id}

### RAG APIs
- POST /rag/search
- POST /rag/index-document

---

## 🎯 Use Cases

- Financial document analysis
- Risk assessment insights
- Smart document retrieval
- Enterprise document intelligence

---

## 👨‍💻 Author

Gaurav Dubey  
MS SQL DBA | Data Science & AI Enthusiast  

---

## 📌 Future Improvements

- Add LLM-based summarization
- Dashboard UI integration
- Real-time analytics
- Cloud deployment (AWS/Azure)

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!
