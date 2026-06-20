# ILM AI

> **Your Personal AI Learning Companion**

ILM AI is an AI-powered learning companion that helps people learn from their own materials. Instead of providing another course or content library, ILM AI transforms textbooks, lecture notes, research papers, documentation, books, and personal notes into an interactive learning experience.

Users upload their materials, ask questions, take quizzes, identify knowledge gaps, and receive personalized learning plans tailored to their goals.

---

## The Problem

Every learner faces the same challenge:

* Too much information
* Too little retention
* No personalized feedback
* No clear learning roadmap

Whether preparing for university entrance exams, learning a new programming framework, studying medical guidelines, or exploring a new topic, people often collect materials but struggle to truly understand and apply them.

Most learning platforms are built around content.

**ILM AI is built around the learner.**

---

## Key Features

### 📚 Personal Knowledge Base

Upload and organize:

* PDF documents
* Word files
* Plain text documents
* Research papers
* Lecture notes
* Books and study materials

Documents are automatically processed, chunked, embedded, and stored for semantic retrieval.

---

### 🤖 AI Learning Companion

A conversational AI tutor that:

* Answers questions based on uploaded materials
* Cites the exact source section used
* Detects misunderstandings
* Encourages active learning through Socratic questioning
* Supports Uzbek, Russian, and English

---

### 📝 Quiz & Practice Mode

Generate quizzes directly from uploaded materials:

* Multiple-choice questions
* Short-answer questions
* Open-ended reasoning questions

After every answer:

* Explain mistakes
* Provide feedback
* Link back to relevant study material

---

### 🧠 Knowledge Gap Detection

Track learning progress over time and identify:

* Frequently missed concepts
* Weak knowledge areas
* Topics requiring revision

Generate dynamic gap reports that improve after every learning session.

---

### 🎯 Learning Plan Generator

Create personalized study plans based on:

* Learning goals
* Target dates
* Available study materials
* Knowledge gap reports

Plans automatically adapt as progress changes.

---

### 📈 Learning Analytics

Monitor:

* Sessions completed
* Topics studied
* Quiz performance
* Knowledge score trends
* Learning consistency

---

### 📱 Telegram Integration

* Daily study reminders
* Quick 5-question quizzes
* Learning streak tracking
* Instant access without opening the web application

---

### 💳 Premium Subscription System

#### Free Tier

* 3 quiz sessions/day
* Up to 5 uploaded files
* Basic AI companion access

#### Premium Tier

* Unlimited quizzes
* Unlimited uploads
* Learning plans
* Knowledge gap reports
* Priority response speed

Payment support:

* Payme
* Click
* Stripe

---

## Target Users

ILM AI is designed for anyone learning anything:

* High school students
* University students
* Developers
* Medical professionals
* Language learners
* Entrepreneurs
* Career changers
* Lifelong learners

---

## Technology Stack

### Frontend

* Next.js
* React
* Tailwind CSS

### Backend

* FastAPI (Python)

### AI Layer

* OpenAI GPT-4o
* LangChain
* LlamaIndex
* OpenAI Embeddings

### Database

* PostgreSQL
* pgvector

### Storage

* AWS S3 / Supabase Storage

### Integrations

* Telegram Bot API
* Payme API
* Click API
* Stripe

### Deployment

* Docker
* Docker Compose
* GitHub Actions
* Railway / Render / VPS

---

## System Architecture

```text
User
 │
 ▼
Next.js Frontend
 │
 ▼
FastAPI Backend
 │
 ├── Authentication
 ├── File Upload Service
 ├── Quiz Engine
 ├── Learning Plan Agent
 ├── Knowledge Gap Agent
 │
 ▼
RAG Pipeline
 │
 ├── Document Parsing
 ├── Chunking
 ├── Embeddings
 ├── Vector Search
 │
 ▼
LLM (GPT-4o)
 │
 ▼
Responses, Quizzes, Plans
```

---

## Roadmap

### MVP

* [ ] Authentication
* [ ] Material Upload
* [ ] RAG Chat
* [ ] Quiz Generation
* [ ] Knowledge Gap Detection
* [ ] Learning Plan Generator
* [ ] Telegram Bot
* [ ] Subscription System

### Future Features

* [ ] Voice Mode
* [ ] Image-to-Text Upload
* [ ] AI Flashcards
* [ ] Learning Circles
* [ ] Mobile Application
* [ ] Offline Learning Support

---

## Project Goal

ILM AI is built on a simple belief:

> Learning is not about consuming more content.
> Learning is about understanding, remembering, and applying knowledge.

Our mission is to give every learner a personal AI tutor that adapts to their materials, goals, and learning journey.

---

## License

MIT License

---

**ILM AI — Because learning is not a phase of life. It is life.**
