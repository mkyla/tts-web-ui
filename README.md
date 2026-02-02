# TTS Web UI

A lightweight and minimalist web interface for text-to-speech developed with native HTML, CSS, and JavaScript. It allows users to input text and generate MP3 audio via the Go TTS API, providing a clean, responsive UI for speech synthesis.

# 📖 Overview

TTS Web UI is a frontend application that interacts with the Go TTS API to convert text to speech. It features a simple form for text input and automatic audio playback, making TTS accessible through a web browser.

# 🎬 Demo

Open index.html, enter "Hello!", click "Generate", play the MP3.

# ✨ Features

### 🎤 TTS Integration
- Calls Go TTS API for MP3 generation.
- Real-time audio playback.

### 📱 Responsive Design
- Clean, centered layout.
- Hover effects on buttons.

### 🚀 Lightweight
- No frameworks, pure HTML/JS.
- Fast loading.

# 📦 Installation

### 🌐 Web Access

Host index.html on a web server, ensure CORS for API calls.

### 🔧 Local Development

# Clone
git clone https://github.com/mkyla/tts-web-ui.git
cd tts-web-ui

# Open
open index.html

# 📋 Usage Guide

- ✏️ Enter text in the input field.
- 🔊 Click "Generate TTS" to get MP3.
- ▶️ Play the audio.

# ⚙️ Configuration

- API URL: Hardcoded to http://localhost:8080/tts

# 🛠️ Development

### 🧩 Core Components

1. **index.html**: Form and audio elements.
2. **script.js**: Fetch API, play audio.
3. **style.css**: Centered, responsive design.

### 🛠️ Tech Stack

- Frontend: HTML/CSS/JS
- API: Go TTS API

### 💻 Development Setup

# 1. Clone
git clone https://github.com/mkyla/tts-web-ui.git

# 2. Edit files

# 3. Open in browser

# 📄 License

BSD-3-Clause