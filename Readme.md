# RAG System with LangChain & Ollama LLM

![Python](https://img.shields.io/badge/Python-3.11-blue)
![LangChain](https://img.shields.io/badge/LangChain-0.1.0-green)
![Ollama LLM](https://img.shields.io/badge/Ollama-LLM-purple)

---

## Project Description
This project is a **PDF Question-Answering system** built using **LangChain**, **Chroma vector store**, and **Ollama LLM (LLaMA2:7B)**. Users can upload PDF documents, split them into chunks, generate embeddings, and query the document using natural language.

It demonstrates a **retrieval-augmented generation (RAG) pipeline** for document-based question answering.

---

## Features
- Load and process PDF documents  
- Split documents into chunks for semantic understanding  
- Generate embeddings using **OllamaEmbeddings**  
- Store embeddings in **Chroma vector database**  
- Query PDFs with natural language using **Ollama LLM**  
- Easy retrieval using **LangChain RetrievalQA** pipeline  

---

## Tech Stack
- **Python 3.11+**  
- **LangChain** – Orchestrates document processing and retrieval pipelines  
- **Ollama LLM** – Local LLaMA2:7B model for question answering  
- **Chroma** – Vector database for storing embeddings  
- **Python Libraries:** `langchain`, `langchain_text_splitters`, `Chroma`  

---

## Installation & Setup

Follow these steps to get the system running:

1. **Clone the repository**  
```bash
git clone https://github.com/yourusername/pdf-qa-ollama.git
cd pdf-qa-ollama
```
## Create a virtual environment and activate it
```bash
python -m venv venv
# Activate the environment:
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

```
## Install all required dependencies

```bash
pip install langchain langchain_text_splitters chromadb ollama

or 

pip install -r requirements.txt

```
## Add your PDF file
```bash
python app.py  # or run in Jupyter/VSCode cells

```
## Run the script

``` bash
python app.py  # or run in Jupyter/VSCode cells
