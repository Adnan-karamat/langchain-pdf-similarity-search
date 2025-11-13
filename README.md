# langchain-pdf-similarity-search
A Google Colab-ready implementation of PDF similarity search using LangChain and FAISS.  Load PDFs, chunk the content, create embeddings, and perform semantic similarity searches.
# LangChain PDF Similarity Search

This repository provides a **Colab-ready implementation** of a PDF similarity search system using **LangChain**, **FAISS**, and **SentenceTransformer embeddings**.

The notebook allows you to:

1. Load a PDF document.
2. Chunk the document into smaller pieces.
3. Create embeddings using a pre-trained SentenceTransformer model.
4. Build a FAISS vector store for efficient similarity search.
5. Query the PDF and retrieve the most relevant chunks.

---

## Features

- Supports **multiple PDFs**.
- Uses **FAISS** for fast semantic search.
- Fully compatible with **Google Colab**.
- Modular and easy to extend to full **RAG pipelines** later.

---

## Requirements

Install required packages:

```bash
!pip install langchain unstructured PyPDF2 faiss-cpu sentence-transformers
