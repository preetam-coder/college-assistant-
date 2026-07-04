# College Assistant

A smart college assistant built with Python, LangGraph, LangChain, Streamlit, and RAG (Retrieval-Augmented Generation).  
It helps students ask questions about academic rules and fee structure using uploaded PDF documents.

## Features

- Ask questions about:
  - Academic policies
  - Fee structure
  - General college-related queries
- Uses a LangGraph workflow to classify user questions
- Uses RAG to retrieve relevant information from PDF documents
- Provides a simple Streamlit web interface

## Tech Stack

- Python
- Streamlit
- LangChain
- LangGraph
- Groq LLM
- FAISS
- HuggingFace Embeddings
- PyPDFLoader

## Project Structure

- `app.py` - Streamlit web app
- `conditional_RAG.py` - LangGraph-based RAG workflow
- `sequential_base.py` - Basic sequential workflow example
- `requirements.txt` - Python dependencies

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
