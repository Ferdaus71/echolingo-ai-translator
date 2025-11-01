# 🎧 EchoLingo – AI Audio Transcriber + Multilingual Translator

**EchoLingo** is an AI-powered web application that transcribes speech from uploaded or recorded audio and instantly translates it into multiple languages using state-of-the-art deep learning models.  
Built with **OpenAI Whisper**, **M2M100 multilingual translation**, and **Gradio**, it offers a clean, modern interface for seamless voice-to-text translation.

---

## 🚀 Features

✅ **Speech-to-Text (Transcription)** – Converts spoken audio into text using OpenAI’s Whisper model.  
✅ **Multilingual Translation** – Translates the transcribed text into more than 10 supported languages.  
✅ **Interactive Web Dashboard** – Built with Gradio, featuring a modern blue–white themed UI.  
✅ **Audio Recording or Upload** – Supports both direct microphone input and file uploads.  
✅ **GPU Acceleration** – Automatically detects CUDA for faster inference when available.  
✅ **Custom UI Styling** – Elegant gradient header, rounded buttons, and white text boxes for a professional look.

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| **Transcription** | [OpenAI Whisper](https://github.com/openai/whisper) |
| **Translation** | [Facebook M2M100 Transformer](https://huggingface.co/facebook/m2m100_418M) |
| **Frontend / UI** | [Gradio](https://gradio.app) |
| **Language** | Python 3.x |
| **Libraries** | `torch`, `transformers`, `openai-whisper`, `gradio`, `librosa`, `soundfile` |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Ferdaus71/echolingo-ai-translator.git
cd echolingo-ai-translator
