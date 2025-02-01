# Orvis Voice

![Banner](readme/orvis_banner.jpg)  
*A framework for building AI-powered voice assistants with blockchain expertise.*

## Overview
Orvis Voice is a flexible library for creating task-specific AI voice assistants. It supports speech recognition, natural language processing, and deep integration with blockchain technologies.

## Features
- **Advanced Speech Recognition & Synthesis** – Supports state-of-the-art STT (speech-to-text) and TTS (text-to-speech) models for seamless interaction.
- **Custom AI Models** – Fine-tuned for specific tasks, enabling tailored responses and enhanced user experience.
- **Blockchain Integration** – Provides built-in support for smart contracts, transaction analysis, and decentralized protocol interactions.
- **Modular & Extensible Architecture** – Designed for easy customization, allowing developers to expand functionality through plugins and APIs.
- **Context Awareness** – Maintains conversational context, improving response accuracy and relevance over time.
- **Adaptive Learning** – Can refine responses based on user feedback and evolving requirements.

## Installation
### Clone the Repository
```sh
git clone https://github.com/orvis-assistant/orvis-voice
cd orvis-voice
```

### Get API Keys
Obtain API keys from [OpenAI](https://openai.com/) and [ElevenLabs](https://elevenlabs.com/).

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

### Run the Application
```sh
npm run dev
```

### Deploy to Vercel
```sh
vercel
```

## Use Cases
Orvis Voice can be applied in various domains, including:
- **Mental Health & Emotional Support** – Act as a conversational companion, offering supportive dialogues, mindfulness exercises, and mental well-being recommendations.
- **Therapeutic Assistance** – Assist users with guided meditations, stress relief techniques, and positive reinforcement strategies.
- **Customer Support** – Automate customer interactions while maintaining contextual awareness.
- **Blockchain & Crypto Advisory** – Provide real-time insights into smart contracts, transactions, and token analytics.
- **Personal Assistants** – Help users manage tasks, schedules, and provide AI-driven recommendations.
- **IoT & Smart Home Integration** – Control connected devices through voice commands.
- **Educational Tools** – Offer interactive learning experiences powered by AI-generated responses.

## License
This project is licensed under the MIT License.
