# Story Book Project

This project is a simple story-book retrieval app that uses a RAG-style workflow with a PDF document and embeddings.

## Features
- Upload or access a story PDF
- Search and retrieve relevant content using embeddings
- Serve a simple web interface

## Files
- `app.py` - Main application entry point
- `rag.py` - Retrieval and embedding logic
- `index.html` - Frontend page
- `script.js` - Client-side JavaScript
- `style.css` - Styling for the frontend

## Setup
1. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```
2. Install dependencies if needed:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python app.py
   ```

## Notes
- The PDF file is ignored by Git via `.gitignore`.
- Make sure the required embedding files are present before running the app.
