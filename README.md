📄 AI RAG Assistant Using LangChain

A Retrieval-Augmented Generation (RAG) application that allows users to upload a PDF document and ask questions about its contents.
The system retrieves relevant information from the PDF and uses a Large Language Model to generate accurate, contextual answers.

🚀 Project Overview

This project uses:

IBM Watsonx.ai LLM (Mistral)

LangChain for orchestration

ChromaDB for vector storage

IBM Watsonx Embeddings

Gradio for UI

Users can upload any PDF, ask questions, and receive answers grounded in the uploaded document.

🧠 How It Works (RAG Pipeline)

Upload PDF via the Gradio interface

Load Document using PyPDFLoader

Split into chunks (1000 tokens, 200 overlap)

Generate embeddings using Watsonx embedding model

Store vectors in ChromaDB

Retrieve relevant chunks

LLM generates the answer using IBM Watsonx Mistral model

🛠️ Tech Stack
Component	Technology
LLM	IBM Watsonx — Mistral-small-3-1-24B
Framework	LangChain
Embeddings	Watsonx Embeddings
Vector Store	ChromaDB
UI	Gradio
PDF Handling	PyPDFLoader
Language	Python
📌 Features

🔍 Ask questions directly from your PDF

⚡ Fast retrieval using vector embeddings

🤖 LLM answers grounded strictly in the document

🧩 Clean modular architecture

🌐 Simple & interactive Gradio UI
