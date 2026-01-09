# 🔊 AI Voice Assistant

This project is an AI-powered voice assistant that listens to user speech, understands intent using large language models, and responds with natural voice output in real time. It supports multiple voice commands and can perform real-world tasks such as managing calendars, emails, and web searches through voice interaction.

## 🧠 How It Works

The assistant captures audio input from the microphone and converts it into text using **Speech-to-Text (STT)**.  
The transcribed text is processed by an **LLM (Llama3/Gemini)** to generate context-aware and task-specific responses.  
The final response is converted back into speech using **Text-to-Speech (TTS)** and played to the user.  
The system is optimized for low-latency, enabling smooth real-time conversations.

## 🛠️ Technologies Used

- **Python**
- **Deepgram** for real-time Speech-to-Text (STT)
- **Llama3 / Gemini** for LLM-based reasoning
- **Text-to-Speech (TTS)** engine for voice responses
- **Google Calendar, Gmail, Contacts APIs**
- **Web Search APIs**
- **Real-time audio processing and pipeline optimization**
