# Medical-RAG-Chatbot-with-BioMistral-and-LangChain

This repository provides a framework for building a PDF-based Q&A system using **LangChain** and **LLaMA**. The code loads and processes PDF documents into text chunks, generates embeddings using **Hugging Face** models, and stores them in a **Chroma** vector database. It leverages a **Retrieval-Augmented Generation (RAG)** pipeline, powered by **LlamaCpp**, to perform context-aware question answering based on the extracted content, making it ideal for querying extensive PDF datasets. The final responses are formatted in Markdown for clear presentation.
