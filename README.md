# VAC-ai-lang-tutor

# MultiLingo AI (VAC-ai-lang-tutor)

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![Django](https://img.shields.io/badge/django-4.2-green)
![LangChain](https://img.shields.io/badge/LangChain-0.1-orange)
![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)

**MultiLingo AI** is an intelligent, adaptive language learning platform powered by a **Multi-Agent AI System**. Unlike static learning apps, it provides immersive, conversational experiences for languages like **Japanese, German, and Telugu**. It features real-time grammar correction, proficiency tracking, and role-playing scenarios.

---

## 🚀 Key Features

### 🤖 Multi-Agent Architecture
* **Agent 1: Teaching Assistant (Tutor Bot):** Explains grammar, provides cultural context, and answers queries with examples.
* **Agent 2: Progress Tracker (Analytics Agent):** Monitors learning patterns, classifies proficiency (Beginner/Intermediate/Advanced), and tracks daily goals.
* **Agent 3: Conversation Partner (Practice Bot):** Engages in realistic role-play scenarios (e.g., "Ordering Coffee," "At the Train Station") to practice pronunciation and usage.

### 📚 Adaptive Learning System
* **Beginner Mode:** Focuses on vocabulary building (Word + Image + Pronunciation).
* **Intermediate Mode:** Emphasizes sentence formation and common phrases.
* **Advanced Mode:** Challenges users with complex idioms and cultural nuances.

### 🛠 Tools & Practice
* **Speaking Zone:** Voice input with AI pronunciation feedback.
* **Flashcard Studio:** AI-generated flashcards with Spaced Repetition System (SRS).
* **Daily Goals:** Tracks minimum 5 new words/day.

---

## 🏗 Technical Architecture

**Stack:**
* **Backend:** Django (Python) - REST API
* **AI Orchestration:** LangChain & LangGraph
* **LLM Integration:** OpenAI GPT-4 / Google Gemini / Anthropic Claude
* **Memory/RAG:** Vector Database (ChromaDB/FAISS) for context retention
* **Database:** PostgreSQL
* **Deployment:** Docker

---

## ⚡ Getting Started

### Prerequisites
* Python 3.10+
* Docker (optional, for containerized run)
* API Keys for OpenAI or Google Gemini

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/VAC-ai-lang-tutor.git](https://github.com/your-username/VAC-ai-lang-tutor.git)
    cd VAC-ai-lang-tutor
    ```

2.  **Create a Virtual Environment**
    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Environment Setup**
    Create a `.env` file in the root directory:
    ```env
    DEBUG=True
    SECRET_KEY=your_django_secret_key
    OPENAI_API_KEY=your_openai_key
    DATABASE_URL=postgres://user:password@localhost:5432/multilingo
    ```

5.  **Run Migrations**
    ```bash
    python manage.py migrate
    ```

6.  **Start the Server**
    ```bash
    python manage.py runserver
    ```

---

## 🗺 Roadmap

* [ ] **Phase 1: Foundation** - Database Schema & Auth
* [ ] **Phase 2: The Brain** - Agent 1 (Tutor) Integration via LangChain
* [ ] **Phase 3: The Tracker** - Agent 2 (Analytics) & Progress Dashboard
* [ ] **Phase 4: Immersion** - Agent 3 (Roleplay) & Voice Support
* [ ] **Phase 5: Polish** - UI/UX & Deployment

---

## 🤝 Contributing

Contributions are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

