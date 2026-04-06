# 🚀 CodePilot – Local AI Coding Assistant

## 📌 Overview
This project is a **local AI coding assistant** built using Streamlit, LangChain, and Ollama.  
It allows users to ask coding questions and get responses from a locally running DeepSeek model.

---

## ⚙️ Tech Stack
- **Python**
- **Streamlit** (UI)
- **LangChain** (Prompt handling)
- **Ollama** (Local LLM)
- **DeepSeek-R1** model

---

## 🧠 Features
- Chat-based coding assistant  
- Supports debugging and code explanations  
- Works completely locally (no API required)  
- Maintains conversation history  
- Model selection (1.5B / 3B)  

---

## 🏗️ Architecture

Streamlit UI → LangChain Prompt → Ollama (DeepSeek) → Response


---

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
2. Start Ollama and pull model
ollama run deepseek-r1:1.5b
3. Run the app
streamlit run app.py