# GPUOpen QA Chatbot

This project is a prototype chatbot developed in Google Colab that answers technical questions about AMD GPU programming, using content from GPUOpen.

It uses a local Retrieval-Augmented Generation (RAG) setup with LangChain, HuggingFace models, and custom document loaders built from selected GPUOpen articles.

## Features

- Scrapes and loads GPUOpen documentation
- Splits and indexes documents using local embeddings
- Answers questions with a custom prompt and HuggingFace model
- Implements a LangGraph pipeline for retrieval and response generation
