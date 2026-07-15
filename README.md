# 📚 StoryLens AI

> **An AI-powered Story Intelligence Platform that transforms books into interactive conversations using Retrieval-Augmented Generation (RAG).**

StoryLens AI allows users to upload story PDFs and interact with them through natural language. Instead of manually searching through hundreds of pages, users can ask questions, explore characters, understand plots, and retrieve contextual information instantly.

---

## ✨ Features

- 📖 Upload and analyze story PDFs
- 🤖 AI-powered question answering using RAG
- 🔍 Semantic search with Sentence Transformers
- ⚡ Fast document retrieval using FAISS Vector Database
- 🧠 Context-aware responses powered by Mistral AI
- 🌐 Clean and responsive web interface
- 📚 Intelligent chunking for improved retrieval accuracy

---

## 🏗️ Architecture

```
                Story PDF
                    │
                    ▼
          PDF Text Extraction
                    │
                    ▼
        Recursive Text Chunking
                    │
                    ▼
      Sentence Transformer Embeddings
                    │
                    ▼
          FAISS Vector Database
                    │
      User Question
                    │
                    ▼
      Semantic Similarity Search
                    │
                    ▼
       Retrieved Relevant Context
                    │
                    ▼
            Mistral AI (LLM)
                    │
                    ▼
             Intelligent Answer
```

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask

### AI & Machine Learning
- Retrieval-Augmented Generation (RAG)
- Mistral AI
- Sentence Transformers
- Semantic Search

### Vector Database
- FAISS

### Document Processing
- PyPDF

### Frontend
- HTML
- CSS
- JavaScript

---

## 📂 Project Structure

```
StoryLens-AI/
│
├── app.py                 # Flask application
├── rag.py                 # RAG pipeline
├── index.html             # Frontend
├── style.css              # Styling
├── script.js              # Client-side logic
├── .env                   # API Keys (ignored)
├── .gitignore
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/StoryLens-AI.git
cd StoryLens-AI
```

---

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

Linux/macOS

```bash
source venv/bin/activate
```

Windows

```bash
venv\Scripts\activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Create a `.env` file

```env
MISTRAL_API_KEY=YOUR_API_KEY
```

---

### 5. Run the application

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

## 🔍 How It Works

1. Upload a story PDF.
2. Extract text from the document.
3. Split the text into meaningful chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Retrieve the most relevant chunks based on the user's query.
7. Provide context to Mistral AI.
8. Generate an accurate and context-aware response.

---

## 💡 Example Queries

- Who is Sherlock Holmes?
- What is the main mystery in the story?
- Summarize Chapter 5.
- What clues did Holmes discover?
- Explain the ending.
- Who are the important characters?

---

## 📈 Future Improvements

- 🎙️ Voice-based interaction
- 🌍 Multi-language support
- 📊 Story timeline generation
- 👥 Character relationship graph
- 📝 Automatic quiz generation
- 📖 Chapter-wise navigation
- ❤️ Emotion and sentiment analysis
- 📚 Multi-document support
- ☁️ Cloud deployment

---

## 🎯 Why StoryLens AI?

Traditional PDF readers only allow keyword searches.

StoryLens AI understands the **meaning** behind your questions, retrieves the most relevant context using semantic search, and generates intelligent answers using a Large Language Model, making reading faster, more interactive, and more engaging.

---

## 👨‍💻 Author

**Lokesh Pradhan**

AI & Machine Learning Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!
