# PDF Retrieval-Augmented Generation (RAG) Pipeline with LangChain

This repository demonstrates a pipeline for **loading PDFs, embedding their content, storing in a vector database, and performing retrieval-augmented queries** using LangChain and related libraries.

---

## Features

- Load PDFs from URLs or local files using `PyPDFLoader`.
- Split large documents into manageable chunks (`RecursiveCharacterTextSplitter`).
- Embed text using HuggingFace's `sentence-transformers`.
- Store and query embeddings in Chroma vector store.
- Perform similarity search with optional metadata filtering.
- Create retrievers for RAG-based applications.

---

## Installation

```bash
pip install -qU langchain langgraph langchain_chroma langchain-google-genai langchain-community PYPDF
pip install -U sentence-transformers
