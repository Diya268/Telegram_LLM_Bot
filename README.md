# 🤖 Telegram Chatbot using Groq LLM (LLaMA 3)

This is a Telegram chatbot powered by **Groq's LLaMA 3 (or Mixtral)** and written in **Python**. It allows users to chat with an AI directly inside Telegram, with backend processing done via Groq’s blazing-fast LLM API.

---

## 🚀 Features

- 💬 Telegram chatbot interface
- ⚡ Ultra-fast LLM responses using Groq API
- 🔐 Secure API key handling
- 🧠 Easy-to-modify system prompt
- 🧩 Modular code (LLM & bot logic separated)

---

## 🧰 Tech Stack

- Python 3.8+
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [aiohttp](https://docs.aiohttp.org/)
- Groq API (Chat Completion endpoint)

---

## 🛠️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/diya268/telegram-groq-bot.git
cd telegram-groq-bot
```
 ### 2. Install requirements

 pip install -r requirements.txt

### 3. Add your API keys

cp config_example.py config.py

### 4. Run the bot
python bot.py

## 📌 Folder Structure

telegram-groq-bot/
├── bot.py               # Telegram bot logic
├── llm_groq.py          # Handles Groq API calls
├── config.py            # API keys (gitignored)
├── config_example.py    # Public example config
└── README.md

