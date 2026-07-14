# 🎥 AI Video Assistant

AI Video Assistant is an AI-powered application that transforms YouTube videos and local audio/video files into interactive knowledge sources. It automatically transcribes multilingual content, generates summaries, extracts key insights, and enables users to ask questions using Retrieval-Augmented Generation (RAG).

---

## 🚀 Features

- 🎥 Process YouTube videos by simply providing a URL
- 📁 Upload local audio and video files
- 🌍 Multilingual transcription (English, Hindi & Hinglish)
- 📝 AI-generated summaries and video titles
- 🔑 Extract key points and action items
- 💬 Chat with video content using Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search using vector embeddings
- ⚡ Interactive Streamlit interface

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### AI & Machine Learning
- OpenAI Whisper
- Sarvam AI
- Mistral AI
- LangChain

### Vector Database
- ChromaDB

### Embeddings
- Hugging Face Sentence Transformers

### NLP
- Transformers
- Deep Translator

### Libraries
- yt-dlp
- pydub
- ffmpeg
- tiktoken

---

## 📂 Project Structure

```
AI-Video-Assistant/
│
├── app.py
├── main.py
├── requirements.txt
├── .env
│
├── core/
│   ├── transcriber.py
│   ├── summarizer.py
│   ├── extractor.py
│   ├── rag_engine.py
│
├── utils/
│   ├── audio_processor.py
│
├── chroma_db/
│
└── README.md
```

---

## ⚙️ How It Works

```
YouTube URL / Local File
            │
            ▼
     Audio Extraction
            │
            ▼
 Multilingual Transcription
            │
            ▼
 AI Summarization
            │
            ▼
 Key Point Extraction
            │
            ▼
 Text Chunking
            │
            ▼
 HuggingFace Embeddings
            │
            ▼
 ChromaDB Vector Store
            │
            ▼
      LangChain RAG
            │
            ▼
     Chat with Video
```

---

## 📋 Supported Inputs

- YouTube URLs
- MP4
- MP3
- WAV
- M4A
- MOV
- AVI

---

## ✨ AI Pipeline

### 1️⃣ Video Processing

- Download YouTube audio using **yt-dlp**
- Extract audio from uploaded videos

### 2️⃣ Speech Recognition

- Whisper AI
- Sarvam AI

Supports:

- English
- Hindi
- Hinglish

### 3️⃣ AI Processing

Generates:

- Video title
- Summary
- Key insights
- Action items

using **Mistral AI**

### 4️⃣ RAG Pipeline

- Split transcript into chunks
- Generate embeddings
- Store vectors in ChromaDB
- Retrieve relevant context
- Answer user questions

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yanujakhandar/AI-Video-Assistant.git

cd AI-Video-Assistant
```

---

### Create Virtual Environment

```bash
python -m venv .venv
```

Activate

Windows

```bash
.venv\Scripts\activate
```

Linux / Mac

```bash
source .venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Create .env

```env
MISTRAL_API_KEY=your_key
SARVAM_API_KEY=your_key
HUGGINGFACEHUB_API_TOKEN=your_key
```

---

### Run

```bash
streamlit run app.py
```

---

## 📖 Example Workflow

1. Paste a YouTube URL or upload a local media file.
2. The application extracts audio and transcribes the content.
3. AI generates a concise summary, title, and key insights.
4. The transcript is converted into vector embeddings.
5. Ask questions naturally and receive context-aware answers grounded in the video content.

---

## 🔮 Future Improvements

- Speaker diarization
- Timestamp-based citations
- PDF export of summaries
- Voice-based interaction
- Multi-video knowledge base
- Cloud deployment
- Support for additional languages



## 👩‍💻 Author

**Anuja Khandar**

