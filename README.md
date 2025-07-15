# Creative-Prompt-Designer
# 🎨 Creative Prompt Designer for Graphic Artists

This project helps artists, designers, and content creators spark inspiration by generating rich, imaginative design prompts — powered by a local Large Language Model (LLM) using Ollama.

---

## 💡 What It Does

- ✨ Takes a simple theme or keyword (like "space", "retro", "cyberpunk")
- 🎯 Generates a complete creative prompt for poster, logo, album art, UI, etc.
- 🧠 Powered locally via Mistral (Ollama), no API key needed
- 🎨 Designed to unlock creativity, quickly

---

## 🛠 Tech Stack

- **Python**
- **Streamlit** (for web UI)
- **Ollama + Mistral** (local LLM)
- **Requests** (to connect with the LLM)

---

## ▶️ How to Run

1. **Install Ollama**: [https://ollama.com](https://ollama.com)  
   Then run in a terminal:

```bash
ollama run mistral
creative_prompt_designer/
├── app.py
├── requirements.txt
└── README.md
