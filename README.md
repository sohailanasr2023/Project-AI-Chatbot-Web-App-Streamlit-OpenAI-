# 🤖 AI Chatbot Web App (Streamlit + OpenAI)

A simple and interactive AI chatbot web application built using **Streamlit** and **OpenAI API**.  
The project provides a ChatGPT-like experience directly in the browser.

---

## ✨ Features

- 💬 Chat-like interface (ChatGPT style)
- 🧠 Powered by OpenAI GPT models
- ⚡ Real-time responses
- 🗂️ Conversation history stored in session
- 🌐 Runs in browser using Streamlit
- 🎯 Beginner-friendly and extendable

---

## 🧰 Tech Stack

- Python 3
- Streamlit
- OpenAI API

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/ai-chatbot-webapp.git
cd ai-chatbot-webapp

Install dependencies:

pip install -r requirements.txt
🔑 Setup API Key

Get your API key from:
👉 https://platform.openai.com/api-keys

Then replace in app.py:

client = OpenAI(api_key="YOUR_API_KEY")

⚠️ Do NOT share your API key publicly.

▶️ Run the App
streamlit run app.py

Then open:
http://localhost:8501

📁 Project Structure
ai-chatbot-webapp/
│
├── app.py
├── requirements.txt
└── README.md



💡 How it works
User types a message in the chat box
Message is sent to OpenAI API
GPT model generates a response
Response is displayed in Streamlit UI
Conversation is stored in session memory
