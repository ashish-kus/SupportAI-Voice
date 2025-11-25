# 🎙️ **SupportAI Voice**

_A Practice Application Showcasing My Ability to Build Voice-Enabled AI Agents_

SupportAI Voice is a voice-powered Retrieval-Augmented Generation (RAG) system built using the **OpenAI SDK**, **Qdrant**, and **Streamlit**.
This project demonstrates my capability to build intelligent **voice agents** that process documentation, retrieve relevant information, and respond using natural-sounding speech.

This is a **practice application**, and I will be adding more features soon.

## 🚀 **What is SupportAI Voice?**

SupportAI Voice is a documentation assistant powered by voice.
It crawls or loads documents, embeds them into a vector database, retrieves relevant chunks for any user query, and speaks the answer back using OpenAI’s TTS models.

This app can:

- Process documentation or PDFs
- Understand your question
- Retrieve relevant answers via RAG
- Generate natural voice responses
- Provide downloadable audio output

Perfect for exploring how voice agents can assist with technical documentation.

## ✨ **Features**

### 📚 Documentation & PDF RAG

- Crawl website documentation or upload PDF files
- Automatically chunk, embed, and store content
- Uses **FastEmbed** embeddings
- Stores vectors in **Qdrant** for lightning-fast search

### 🎤 Voice-Powered AI Responses

- Uses OpenAI SDK's TTS models
- Multiple voice options (Nova, Coral, Alloy, Sage, etc.)
- Generates downloadable MP3 responses
- Produces conversation-friendly answers optimized for speech

### 🧠 Dual-Agent Architecture

- **Processor Agent:** Generates clear, helpful responses
- **TTS Agent:** Optimizes text for spoken delivery

### 🖥️ Streamlit Interface

- Clean, simple UI
- Tracks document processing progress
- Displays sources used in the answer
- Supports multiple document uploads
- Real-time status and audio playback

### 📦 Additional Features

- Source URL tracking
- Multi-document handling
- Progress indicators for crawling & embedding
- Practice-ready code base focusing on voice agent skills

---

## 🛠️ **How to Get Started**

### 1. Clone the repository

```bash
git clone https://github.com/ashish-kus/CustomerSupport_Voice_agent
cd CustomerSupport_Voice_agent/
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up your environment

Create a `.env` file:

```bash
OPENAI_API_KEY='your-openai-api-key'
QDRANT_URL='your-qdrant-url'
QDRANT_API_KEY='your-qdrant-api-key'
```

You will need:

- **OpenAI API Key**
- **Qdrant Cloud URL & API key**

### 4. Run the application

```bash
streamlit run rag_voice.py
```

### 5. Open the interface

Visit the URL shown in your terminal to start interacting with SupportAI Voice.

---

## 🧩 **How It Works**

### 📝 1. Document Processing

- Upload PDFs or scrape a documentation URL
- Split documents into chunks
- Generate embeddings using FastEmbed
- Store vectors in Qdrant

### 🔍 2. Query Processing

- Convert user query into embeddings
- Perform similarity search in Qdrant
- Retrieve the best chunks as context
- Processor Agent generates a clear answer
- TTS Agent refines text for speaking

### 🔊 3. Voice Response Generation

- OpenAI TTS converts the answer to speech
- Audio is streamed and playable
- Users can download MP3 responses
- Multiple voice personalities supported

---

## 🧪 **Why This Project?**

SupportAI Voice is a **practice application** built to showcase my skills in:

- AI agents
- Voice-based interfaces
- RAG systems
- Vector databases
- Streamlit app development
- Full-stack AI integrations

This forms the foundation for more advanced voice-driven tools I will release soon.

---

## 🚧 **Upcoming Features**

- Realtime microphone input
- Live conversation mode
- Multi-language TTS
- Better UI/UX
- Context awareness and memory
- Web search integration
- Agentic workflows
