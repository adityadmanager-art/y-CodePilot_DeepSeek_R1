# 🚀 CodePilot – Local AI Coding Assistant

## 📌 Overview

**CodePilot** is a local AI-powered coding assistant built with Python, Streamlit, LangChain, and the DeepSeek-R1 model via Ollama.  
Ask coding questions, debug code, and get explanations — all running entirely on your machine with no API key or internet connection required.

---

## 🗂️ Documentation

> All detailed documentation lives in the [`docs/`](docs/) folder.

| Document | Description |
|----------|-------------|
| [docs/README.md](docs/README.md) | Documentation hub and project overview |
| [docs/profile.md](docs/profile.md) | Developer / project owner profile |
| [docs/setup.md](docs/setup.md) | Full installation and setup instructions |
| [docs/contribution.md](docs/contribution.md) | How to contribute to this project |
| [docs/contact.md](docs/contact.md) | Contact details and links |
| [docs/overview_story.md](docs/overview_story.md) | The story and motivation behind CodePilot |

---

## ⚙️ Tech Stack

- **Python**
- **Streamlit** (UI)
- **LangChain** (Prompt handling)
- **Ollama** (Local LLM runner)
- **DeepSeek-R1** model (1.5B / 3B)

---

## 🧠 Features

- 💬 Chat-based coding assistant
- 🐛 Supports debugging and code explanations
- 🔒 Works completely locally — no API key required
- 🗂️ Maintains conversation history across a session
- ⚙️ Model selection (1.5B / 3B)

---

## 🏗️ Architecture

```
Streamlit UI → LangChain Prompt → Ollama (DeepSeek-R1) → Response
```

---

## ▶️ Quick Start

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Pull the DeepSeek model

```bash
ollama run deepseek-r1:1.5b
```

### 3. Run the app

```bash
streamlit run app.py
```

For full setup details, see [docs/setup.md](docs/setup.md).