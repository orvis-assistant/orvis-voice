# Orvis Voice

![Banner](readme/orvis_banner.jpg)  
*A framework for building AI-powered voice assistants with blockchain expertise.*

## 🚀 Overview
Orvis Voice is a flexible library for creating task-specific AI voice assistants. It supports speech recognition, natural language processing, and deep integration with blockchain technologies.

## ✨ Features
- 🎙️ **Speech Recognition & Synthesis** – Seamless interaction using cutting-edge STT & TTS models.
- 🧠 **Custom AI Models** – Fine-tuned for specialized tasks and adaptable to various use cases.
- 🔗 **Blockchain Integration** – Understands smart contracts, transactions, and decentralized protocols.
- ⚡ **Modular & Extensible** – Designed for easy customization and scalability.

## 📦 Installation
### Clone the repo
```sh
git clone https://github.com/orvis-assistant/orvis-voice
cd orvis-voice
```

### Get API Keys
Get API keys from [OpenAI](https://openai.com/) and [ElevenLabs](https://elevenlabs.com/).

### Configure Environment Variables
Create the `.env.local` file and add your API keys:
```sh
OPENAI_API_KEY="YOUR OPENAI API KEY"
OPENAI_BASE_URL=(Optional)
NEXT_PUBLIC_ELEVENLABS_API_KEY="YOUR ELEVENLABS API KEY"
NEXT_PUBLIC_ELEVENLABS_VOICE_ID="YOUR ELEVENLABS VOICE ID"
TASK_SPECIFIC_PROMPT="YOUR CUSTOM PROMPT FOR TASK-SPECIFIC ASSISTANT"
TASK_CREATIVE_LEVEL="SET THE CREATIVITY LEVEL (0-1, LOWER = STRICTER TO PROMPT)"
```

### Install Dependencies
```sh
npm install
```

### Run the App
```sh
npm run dev
```

### Deploy to Vercel
```sh
vercel
```

## 📜 License
This project is licensed under the MIT License.
