# n8n-AI-Agents

# 🤖 Zenra – My Personal AI Assistant via Telegram (Built with n8n)

Zenra is a smart personal assistant designed using [n8n](https://n8n.io/), integrated with Telegram and powered by OpenAI. It can understand text, images, PDFs and audio messages, while also performing useful tasks like sending emails, managing calendar events, checking weather and crypto prices and more — all from my Telegram chat.

---

## 🚀 Features

- 🧠 **Natural Language Understanding** using GPT-4o
- 💬 **Telegram Integration**: Chat with Zenra via text, audio, image or PDF
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

- **n8n** – Low code workflow automation
- **OpenAI GPT-4o-mini** – LLM for language tasks
- **Telegram Bot API** – Interface for communication
- **Google APIs** – Calendar, Drive, Gmail
- **PDF.co API** – PDF text extraction
- **CoinGecko API** – Cryptocurrency price data
- **OpenWeatherMap API** – Weather info
- **LangChain Memory** – Short term conversation memory

---

## ⚙️ How It Works

Zenra operates via a Telegram bot and intelligently routes user input through n8n flows:

1. **Triggers** on Telegram messages (text, image, voice or file)
2. **Classifies** input type using Switch node
3. **Routes** to tools (like GPT, transcription or calendar)
4. **Executes** actions and returns results to Telegram

For example:
- Send a voice note → Transcribed by OpenAI → Understood and replied
- Upload a PDF → Content extracted → Q&A supported
- Ask "What's the weather in Colombo?" → Answer retrieved and sent
- Sending emails to friends
- Add events in calendar 

---

## 📸 Demo

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/ffd71e30-3be6-443b-826e-40aff74aca85" />


Linkedln video link: https://www.linkedin.com/posts/udara-herath-530006217_ai-n8n-openai-activity-7346547954507292672-4SaZ?utm_source=share&utm_medium=member_desktop&rcm=ACoAADaj23QBzc37-AoJdt04GuyP1DRJf15rN1Y

---

## 📄 Example Commands

### Task	        →                  Example Input

- Get weather	        →        What's the weather in Colombo?
- Read unread emails	   →         Read my emails
- Create event	     →           Add event: Meeting at 5 PM tomorrow
- Transcribe voice note	    →        Send voice note
- Analyze image	       →         Upload photo with caption
- Upload file to Drive	  →      Send PDF/image/video file
- Ask PDF content	     →         Upload PDF and ask a question

---

## 📦 Installation & Setup

> ⚠️ You must have n8n installed and configured with necessary credentials.

1. Download Zenra.json file
2. Open it in n8n platform
3. Set API keys. (OpenAI, Gmail, Google Calendar, Google Drive, Telegram, PDF.co, OpenWeatherMap, CoinGecko)
4. Execute the setup

---

## 🧠 Future Plans

- Improve more current workflow
- Develop a RAG based workflow
- Add knowledge based long term memory
- Add persistent chat sessions
- Add WhatsApp integration
- Integrate google drive

 

 

 

