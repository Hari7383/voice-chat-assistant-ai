# Voice Chat Assistant AI

A real-time **AI-powered voice assistant** that listens to your voice, processes commands, and responds with natural speech.

This project integrates speech recognition, language understanding, and text-to-speech to create a conversational assistant — similar to Siri, Alexa, or Google Assistant, but fully open-source and customizable.

---

## 🚀 Project Overview

This voice assistant:
✔ Captures microphone audio  
✔ Converts speech → text (STT)  
✔ Generates responses using an AI model  
✔ Speaks replies back (TTS)  
✔ Runs locally or as a service

Use cases:
- Hands-free assistant for desktop
- Voice-controlled automations
- Voice interface for apps
- Accessibility tools

---

## 🧠 Key Components

| Component | Role |
|-----------|------|
| Speech-to-Text (STT) | Transcribe spoken words |
| Language Model | Understands & responds |
| Text-to-Speech (TTS) | Converts replies to voice |
| Audio I/O | Microphone input & speaker output |
| Optional UI | Visual interface for interaction |

---

## 🛠️ Tech Stack

- Python 3.8+  
- SpeechRecognition / Whisper  
- Text-to-Speech (gTTS / pyttsx3 / edge-tts)  
- PyAudio  
- AI model backend (OpenAI / local LLM)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Hari7383/voice-chat-assistant-ai.git
cd voice-chat-assistant-ai
```
Create and activate virtual environment:
```
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows
```
---
## License

This project is licensed under the MIT License.
---
