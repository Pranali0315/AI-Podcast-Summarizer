# 🎧 AI-Podcast Summarizer

**AI-Podcast Summarizer** is an open-source tool designed to generate clean and concise summaries from podcast audio. By processing uploaded audio files using state-of-the-art AI models, it helps users quickly understand the key points of long-form podcast content without listening to the entire episode.

## 🚀 Project Overview

AI-Podcast Summarizer transcribes spoken audio and passes it through an advanced language model to generate meaningful summaries. The project is designed to work entirely in the backend and does not store any intermediate files, ensuring a lightweight and fast experience.

### Key Features

- **Automatic Transcription**: Converts audio to text using open-source models.
- **Smart Summarization**: Generates clear summaries using advanced NLP techniques.
- **Fast & Stateless Processing**: Everything happens in-memory — no file storage.
- **Open-Source & Customizable**: Easy to modify and extend for other use cases.
- **Clean Output**: Provides a simple and user-friendly summary of lengthy audio.

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🛠️ Technology Stack

- **Backend**: Python, FastAPI
- **Transcription**: OpenAI Whisper / Faster-Whisper (on CPU/GPU)
- **Summarization**: Hugging Face Transformers (e.g., BART, T5)
- **Audio Processing**: PyDub, FFmpeg
- **Environment**: Docker (for containerized execution)

## 📝 Getting Started

### Prerequisites

- Python 3.8+
- `ffmpeg` installed and added to system path
- `pip` for Python package management

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Pranali0315/AI-Podcast-Summarizer.git
   cd AI_Based_Podcast_Summarizer_Tool

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   venv/Scripts/activate

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

4. **Run the Application**
   ```bash
   python main.py

## 🎉 Usage
**Upload Audio File** : Provide an audio file (e.g., .mp3, .wav).
**Processing**: The backend transcribes and summarizes the content.
**Receive Output**: A clean text summary is returned instantly.
