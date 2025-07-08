# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)

---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit

## 🧠 About

This repository contains a smart AI Medical ChatAssistant - Medically, that leverages state-of-the-art open-source tools to deliver an interactive healthcare assistant experience. It uses HuggingFace embeddings for semantic understanding, Faiss (CPU) for fast vector similarity search, and Mistral as the underlying language model. The user interface is built using Streamlit, making the chatbot simple and accessible to interact with.

The project provides a step-by-step implementation for building an efficient and responsive medical chatbot, offering practical exposure to natural language processing, retrieval-augmented generation (RAG), and AI-driven healthcare solutions.

## 🚀 Features

- Real-time medical conversation interface
- Retrieval-augmented responses using Faiss
- Lightweight and CPU-friendly
- No prior experience needed to run
## 🛠️ Tech Stack

- Python
- Streamlit
- HuggingFace Transformers
- FAISS (CPU)
- Mistral (LLM)



