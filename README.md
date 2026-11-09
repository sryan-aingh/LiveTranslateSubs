# LiveTranslateSubs 🎙️🌍

LiveTranslateSubs is a real-time speech translation system designed for low-latency subtitle generation. It captures live audio, converts speech into text, translates it into English, and displays subtitles in real time.

## 🚀 Key Features

- **Real-Time Speech Recognition**: Captures live audio and transcribes speech continuously.
- **Multi-Language Translation**: Translates spoken languages into English.
- **Live Subtitles**: Displays translated subtitles with minimal delay.
- **AI-Powered Transcription**: Uses Faster-Whisper for efficient and accurate speech recognition.
- **Audio Processing**: Processes incoming audio streams for continuous transcription.
- **User-Friendly Interface**: Provides an accessible interface for viewing live translated subtitles.

## 🏗️ System Architecture

The application follows a modular architecture consisting of:

- **Frontend**: Handles audio input and displays translated subtitles.
- **Backend**: Processes incoming audio and manages transcription requests.
- **Speech Recognition**: Uses Faster-Whisper to convert speech into text.
- **Translation Engine**: Translates recognized speech into English.
- **Real-Time Communication**: Uses WebSockets for continuous audio and subtitle streaming.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Faster-Whisper | Speech recognition |
| Flask | Web application framework |
| WebSockets | Real-time communication |
| JavaScript | Frontend logic |
| HTML & CSS | User interface |
| Web Audio API | Live audio capture |

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/avy2025/LiveTranslateSubs.git
   cd LiveTranslateSubs
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**

   ```bash
   python main.py
   ```

4. **Access the application:**

   Open your browser and navigate to:

   ```text
   http://127.0.0.1:5000
   ```

## 💻 How It Works

1. The application captures live microphone audio through the browser.
2. Audio is streamed to the backend in real time.
3. Faster-Whisper processes the incoming audio and generates transcriptions.
4. The recognized speech is translated into English.
5. Translated subtitles are streamed back to the browser and displayed in real time.

## 🎯 Project Objective

The goal of LiveTranslateSubs is to make real-time communication more accessible by eliminating language barriers through live speech recognition and translation.

---

**Developed as a real-time AI-powered speech translation and subtitle generation system.**
