# Advance-Personal-AI-Assistant
# 🤖 ARIS (ARTIFICIAL RESEARCH INTELLIGENCE SYSTEM)

ARIS is a Python-based AI assistant that can answer both general and real-time questions using AI models and web search.

This is **Version 1.0**, the first public release of the project.

---

## ✨ Features (Version 1.0)

- 💬 General AI chat using the Groq API.
- 🌐 Real-time question answering using the Tavily Search API.
- ⏰ Answers time and date-related questions using your computer's local system time (no API required).
- 🔄 Switch between General Chat and Real-time Chat modes.
- 🖥️ Simple terminal-based interface.

---

## 🛠 Technologies Used

- Python 3
- Groq API
- Tavily Search API

---

## 📦 Requirements

Install all required packages:

```bash
pip install -r requirements.txt
```

---

## 🔑 API Keys Required

Before running ARIS, create a `.env` file and add your API keys:

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
```

You can get API keys from:

- Groq: https://console.groq.com/
- Tavily: https://app.tavily.com/

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone <your-repository-link>
```

2. Move into the project folder.

```bash
cd Advance-Personal-AI-Assistant
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Add your API keys to the `.env` file.

5. Run the application.

```bash
python run.py
```

6. Open another terminal and run:

```bash
python test.py
```

---

## 🚀 Future Plans

Some planned features for future versions:

- Long-term memory
- Voice input and output
- File understanding (PDF, DOCX, etc.)
- Better conversation management
- More intelligent personal assistant features

---

## 👨‍💻 Developer

Created by **Abhishek Mishra**

This project is part of my journey to build my own advanced AI assistant from scratch while improving my software engineering and AI development skills.

---

## 💡 Inspiration

ARIS was inspired by the idea of creating an intelligent AI assistant that can grow over time.

Like many technology enthusiasts, I have been inspired by the AI assistants seen in science fiction, especially J.A.R.V.I.S. from Iron Man. Rather than trying to recreate a fictional assistant directly, this project is my journey to learn software engineering, artificial intelligence, and system design by building my own personal AI assistant from the ground up.

Every version of ARIS represents a step toward becoming a better engineer and creating a more capable assistant.
