# ⚙️ Setup Guide

This guide walks you through installing and running **CodePilot** on your local machine.

---

## ✅ Prerequisites

Make sure the following are installed before proceeding:

| Requirement | Version | Notes |
|-------------|---------|-------|
| Python | 3.9 or higher | [python.org](https://python.org) |
| pip | Latest | Comes with Python |
| Ollama | Latest | [ollama.com](https://ollama.com) |
| Git | Any recent version | For cloning the repo |

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/y-CodePilot_DeepSeek_R1.git
cd y-CodePilot_DeepSeek_R1
```

### 2. Create a Virtual Environment *(recommended)*

```bash
python -m venv venv

# Activate on Linux / macOS
source venv/bin/activate

# Activate on Windows
venv\Scripts\activate
```

### 3. Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

## 🤖 Set Up the AI Model

### 4. Install and Start Ollama

Download Ollama from [ollama.com](https://ollama.com) and follow the installer instructions for your OS.

### 5. Pull the DeepSeek-R1 Model

```bash
# Lightweight 1.5B model (recommended for most machines)
ollama pull deepseek-r1:1.5b

# Alternatively, the 3B model for better responses
ollama pull deepseek-r1:3b
```

> **Tip:** The 1.5B model runs well on machines with 8 GB RAM. Use the 3B model if you have 16 GB or more.

---

## ▶️ Running the Application

### 6. Start CodePilot

```bash
streamlit run app.py
```

The app will open automatically in your default browser at `http://localhost:8501`.

---

## 🛑 Stopping the Application

Press `Ctrl + C` in the terminal to stop the Streamlit server.  
Deactivate the virtual environment with:

```bash
deactivate
```

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| `ollama: command not found` | Ensure Ollama is installed and added to your PATH |
| `ModuleNotFoundError` | Re-run `pip install -r requirements.txt` inside your virtual environment |
| App not opening in browser | Manually navigate to `http://localhost:8501` |
| Slow responses | Switch to the 1.5B model or close other memory-heavy applications |

---

## 🔄 Updating

```bash
git pull origin main
pip install -r requirements.txt
```
