# 📖 CodePilot – Documentation

Welcome to the **CodePilot** documentation hub. This folder contains all the key information about the project, its setup, contribution guidelines, and more.

---

## 📂 Contents

| File | Description |
|------|-------------|
| [profile.md](profile.md) | Developer / project owner profile |
| [setup.md](setup.md) | How to install and run the project |
| [contribution.md](contribution.md) | Guidelines for contributing |
| [contact.md](contact.md) | Contact details and links |
| [overview_story.md](overview_story.md) | The story behind CodePilot |

---

## 🧭 Project Overview

**CodePilot** is a local AI-powered coding assistant built with Python, Streamlit, LangChain, and the DeepSeek-R1 model via Ollama.  
It lets developers ask coding questions, debug code, and get explanations — all without sending data to external APIs.

### Key Features

- 💬 Chat-based coding assistant
- 🐛 Supports debugging and code explanations
- 🔒 Runs completely locally — no API key needed
- 🗂️ Maintains conversation history across a session
- ⚙️ Switchable model sizes (1.5B / 3B)

---

## 🚀 Quick Start

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Pull the DeepSeek model via Ollama
ollama run deepseek-r1:1.5b

# 3. Launch the app
streamlit run app.py
```

For detailed setup instructions, see [setup.md](setup.md).

---

## 🤝 Contributing

We welcome contributions of all kinds! Please read [contribution.md](contribution.md) before opening a pull request.

---

## 📬 Contact

Have questions or suggestions? Check [contact.md](contact.md) for ways to reach out.
