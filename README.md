# FinSight-AI

FinSight-AI is an AI project that allows users to ask questions about financial documents using natural language. It uses a technique called Retrieval-Augmented Generation (RAG) to find the most relevant answers.

## Features
- Upload and read PDF/text documents
- Breaks the documents into small parts (chunks)
- Converts those parts into numbers (embeddings) using MiniLM
- Stores them in a vector database (ChromaDB)
- Lets users ask questions and gets AI-generated answers

## Technologies Used
- Python
- LangChain
- SentenceTransformers (MiniLM-L6-v2)
- ChromaDB
- OpenAI API (for LLM responses)

## How to Run
```bash
pip install -r requirements.txt
python main.py
