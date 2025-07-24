Live Translator

Live Translator is a real-time speech translation web application that captures live speech through your microphone, transcribes it, and displays translated subtitles over a webcam feed. It can operate in either browser-based free mode or API-powered mode using OpenAI Whisper and DeepL.

Overview:
This project is designed for real-time multilingual communication. The interface is inspired by iOS/macOS design systems, and the application is built with standard web technologies without external frameworks. It supports dynamic language switching, custom subtitle timing, and optional API integrations for enhanced accuracy.

Core Features:
- Real-time speech-to-text transcription
- Instant language translation
- Webcam overlay with subtitles
- Web Speech API (Free Mode)
- OpenAI Whisper + DeepL integration (API Mode)
- Minimal, touch-friendly UI
- Smart debug panel with live logs

Technology Stack:
- HTML, CSS, JavaScript
- Web Speech API
- WebRTC (for webcam access)
- OpenAI Whisper (API)
- DeepL API / Google Translate API fallback

Setup Instructions:
### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/live-translator.git
cd live-translator
