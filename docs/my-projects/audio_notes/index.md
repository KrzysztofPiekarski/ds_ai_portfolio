# 🎙️ Audio Notes App — Smart Voice Notes with Transcription & Search

*Date of creation: 2025-03*

**Audio Notes** is a lightweight and powerful application for recording, transcribing, storing, and searching **voice notes**. Perfect for students, creators, researchers, or anyone who prefers speaking instead of typing.

---

## 🚀 Key Features

### 🎤 Record & Playback
- Record **short voice notes** directly from the interface
- Store recordings locally or in the cloud
- Playback functionality for quick reference

### ✍️ AI-Powered Transcription
- Transcribe voice notes to text using **OpenAI's Whisper API**
- Accurate transcription of multiple languages
- Automatic punctuation and formatting

### 🔐 Secure API Key Management
- Use `.env` file to store your **OpenAI API key** securely
- Keys are never hard-coded or exposed

### 📦 Semantic Storage with Qdrant
- Automatically **embed and store** transcribed notes in a **Qdrant vector database**
- Semantic search for meaning-based note retrieval
- Fast similarity-based querying using embeddings

### 🔍 Smart Search
- Search through notes by **keywords or semantic meaning**
- Find relevant notes even if you don’t remember exact phrases

---

## 🧱 Tech Stack

- Python 3.10+
- **Streamlit** (GUI)
- **OpenAI Whisper API** (for transcription)
- **Qdrant** (vector database for semantic search)
- **FAISS** (optional, for local vector search alternative)
- **Sounddevice** or **pyaudio** for audio input/output

[Link to repository](https://github.com/KrzysztofPiekarski/audio_notes)
