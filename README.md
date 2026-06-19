# AI-Powered-PDF-Q-A-System

**🧠 Overview**
This project implements an interactive AI system that allows users to ask questions about the content of a PDF document and receive answers in multiple formats — text, image, or audio.
The notebook automatically processes the PDF, extracts and indexes its content, and uses Retrieval‑Augmented Generation (RAG) to produce accurate, context‑aware answers.

**🚀 Features**
PDF Parsing — automatic text extraction from PDF
Vector Indexing — ChromaDB + OpenAI embeddings
Semantic Retrieval — finds the most relevant text chunks
Structured Output — extracts the user question and preferred answer format
Multi‑modal Answers:
- text
- image (generated with DALL·E 3)
- audio (MP3 via TTS)
RAG Pipeline — combines retrieved context with LLM reasoning

**PDF Used**
Python Programming by Hans‑Petter Halvorsen
140 pages

**🛠️ How It Works**
PDF Parsing — the document is read and split into text segments
Embedding Generation — each segment is converted into a vector
ChromaDB Indexing — vectors are stored for fast semantic search
User Query Processing — the model extracts:
the question
the desired answer format (text / image / audio)
RAG Retrieval — retrieves the most relevant context chunks
Answer Generation — the LLM produces the final answer
Optional Output — generates an image or audio file if requested
