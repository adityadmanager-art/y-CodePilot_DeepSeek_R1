# CodePilot – Local AI Coding Assistant

🚀 Overview

This project is a local AI coding assistant built using Streamlit, LangChain, and Ollama.
It allows users to ask coding questions and get responses from a locally running DeepSeek model.

⚙️ Tech Stack
Python
Streamlit (UI)
LangChain (prompt handling)
Ollama (local LLM)
DeepSeek-R1 model
🧠 Features
Chat-based coding assistant
Supports debugging and code explanations
Works completely locally (no API required)
Maintains conversation history
Model selection (1.5B / 3B)
🏗️ Architecture

Streamlit UI → LangChain Prompt → Ollama (DeepSeek) → Response

▶️ How to Run
Install dependencies
pip install -r requirements.txt
Start Ollama and pull model
ollama run deepseek-r1:1.5b
Run the app
streamlit run app.py
⚠️ Limitations
Chat history is not stored permanently
No file upload support
Basic error handling
🔮 Future Improvements
Add persistent chat storage
Support code/file uploads
Streaming responses
Better UI/UX