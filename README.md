# Zyro Dynamics HR Chatbot

A Retrieval-Augmented Generation (RAG) based HR policy chatbot built for the NIAT Masterclass RAG Challenge.

## Project Overview

This chatbot answers employee HR policy questions using Zyro Dynamics internal policy documents.

## Features

- Loads HR policy PDF documents
- Splits documents into chunks
- Creates embeddings using Sentence Transformers
- Stores vectors using FAISS
- Uses Groq LLM for answer generation
- Uses LangSmith for tracing
- Provides Streamlit app deployment
- Handles out-of-scope questions with guardrails

## Tech Stack

- Python
- LangChain
- FAISS
- HuggingFace Sentence Transformers
- Groq
- LangSmith
- Streamlit
- Kaggle

## Streamlit App

https://zyro-dynamics-hr-chatbot.streamlit.app

## LangSmith Trace

https://smith.langchain.com/public/0f7ef6a0-b41d-4fc9-9ddf-59881acb5a2f/r

## Kaggle Score

87.96

## Files

- `submission.csv` - Final Kaggle submission file
- `requirements.txt` - Required dependencies
- Notebook file - Complete RAG pipeline implementation