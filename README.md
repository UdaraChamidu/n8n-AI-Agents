# n8n-AI-Agents

# 🤖 Zenra – My Personal AI Assistant via Telegram (Built with n8n)

Zenra is a smart personal assistant designed using [n8n](https://n8n.io/), integrated with Telegram and powered by OpenAI. It can understand text, images, PDFs, and audio messages, while also performing useful tasks like sending emails, managing calendar events, checking weather and crypto prices, and more — all from your Telegram chat.

---

## 🚀 Features

- 🧠 **Natural Language Understanding** using GPT-4o
- 💬 **Telegram Integration**: Chat with Zenra via text, audio, image, or PDF
- 📅 **Google Calendar Assistant**: Create and view events
- 📧 **Gmail Integration**: Read unread emails or send new ones
- ☁️ **Google Drive Uploader**: Upload user files (images, PDFs, videos)
- 🌦️ **Weather Reports** for any location
- 💰 **Live Crypto Price Checker** (via CoinGecko API)
- 🐍 **Code Executor**: Run Python code snippets
- 📄 **PDF Reader**: Analyze uploaded PDF files using PDF.co and GPT
- 🖼️ **Image Analyzer**: Visual understanding of uploaded images
- 🔊 **Voice-to-Text Transcription** and response with text/audio
- 📂 **GitHub Integration**: Interact with your repositories
- 🔗 **LinkedIn Post Generator** *(planned)*

---

## 🛠️ Tech Stack

- **n8n** – Low-code workflow automation
- **OpenAI GPT-4o-mini** – LLM for language tasks
- **Telegram Bot API** – Interface for communication
- **Google APIs** – Calendar, Drive, Gmail
- **PDF.co API** – PDF text extraction
- **CoinGecko API** – Cryptocurrency price data
- **OpenWeatherMap API** – Weather info
- **LangChain Memory** – Short-term conversation memory

---

## ⚙️ How It Works

Zenra operates via a Telegram bot and intelligently routes user input through n8n flows:

1. **Triggers** on Telegram messages (text, image, voice, or file)
2. **Classifies** input type using Switch node
3. **Routes** to tools (like GPT, transcription, or calendar)
4. **Executes** actions and returns results to Telegram

For example:
- Send a voice note → Transcribed by OpenAI → Understood and replied
- Upload a PDF → Content extracted → Q&A supported
- Ask "What's the weather in Colombo?" → Answer retrieved and sent

---

## 📦 Installation & Setup

> ⚠️ You must have n8n installed and configured with necessary credentials.

### 1. Clone the Repository

```bash
git clone https://github.com/UdaraChamidu/zenra-ai-assistant.git
cd zenra-ai-assistant
