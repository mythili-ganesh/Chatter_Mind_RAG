# Chatter Mind with RAG

Chatter Mind is a Retrieval-Augmented Generation (RAG) chatbot that answers user questions from PDF documents.

## Features

* PDF document loading
* Text chunking
* Sentence Transformer embeddings
* ChromaDB vector storage
* Semantic search
* Local LLM inference using CapybaraHermes-Mistral-7B

## Tech Stack

* LangChain
* ChromaDB
* Sentence Transformers
* LlamaCpp
* Hugging Face
* Python

## Setup

Install dependencies:

pip install -r requirements.txt

Place PDF files inside the RAG folder.

Run the notebook and start querying your documents.

## Model

This project uses:

TheBloke/CapybaraHermes-2.5-Mistral-7B-GGUF

The model is downloaded separately and is not included in this repository.
