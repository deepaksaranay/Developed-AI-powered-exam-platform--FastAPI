# 🚀 AI Exam Platform

An AI-powered backend system to generate STEM Multiple Choice Questions (MCQs) from any topic.

---

## 📌 Overview
AI Exam Platform helps students and educators generate high-quality MCQs using a simple API.

---

## 🔥 Features
- Generate MCQs from any topic
- FastAPI backend
- Modular architecture
- Swagger API documentation

---

## 🛠 Tech Stack
- FastAPI  
- Python  
- Pydantic  

---

## 🚀 Run Project

```bash
pip install fastapi uvicorn
uvicorn app.main:app --reload
```

---

## 📡 API Endpoint

POST `/api/generate`

### Sample Input

```json
{
  "topic": "Newton Laws",
  "difficulty": "medium",
  "num_questions": 3
}
```

---

## 📖 API Docs
http://localhost:8000/docs

---

## 👤 Author
Deepak Kumar

---

⭐ Star this repo if you like it!
