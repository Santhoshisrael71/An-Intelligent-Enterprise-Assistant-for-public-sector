# An-Intelligent-Enterprise-Assistant-for-public-sector

# Intelligent Enterprise Assistant Chatbot
### SIH1706 – Smart India Hackathon Problem

AI-powered enterprise chatbot that helps employees get information about **HR policies, IT support, company events, and organizational documents** using **NLP and Deep Learning**.

---

# Features

- Natural language chatbot for employee queries
- HR policy and IT support question answering
- Document upload and analysis
- Document summarization
- Keyword extraction from documents
- Email based **2 Factor Authentication (2FA)**
- Bad language filtering
- Supports **minimum 5 parallel users**
- Response time < **5 seconds**

---

# Tech Stack

| Component | Technology |
|---|---|
| Frontend | Streamlit |
| Backend | FastAPI |
| NLP | HuggingFace Transformers |
| LLM Framework | LangChain |
| Vector Database | FAISS |
| Database | SQLite |
| Document Processing | PyPDF2 |
| Authentication | Email OTP (SMTP) |
| Deployment | Docker |

---

# System Architecture
Users
|
Frontend (Streamlit)
|
Backend API (FastAPI)
|
NLP Engine (LangChain + Transformers)
|
Vector Database (FAISS)
|
Knowledge Base (HR / IT / Events Data)

---


---

# Project Structure

enterprise-chatbot
│
├── app.py
├── auth.py
├── chatbot.py
├── document_processor.py
├── profanity_filter.py
├── knowledge_base
│ └── hr_policy.txt
│
├── requirements.txt
├── README.md


