# Retrieval-Augmented Generation (RAG) Project

## Overview
This project implements a **Retrieval-Augmented Generation (RAG) pipeline**, combining document retrieval with language model generation to improve response accuracy. It processes documents, segments them into manageable chunks, retrieves relevant information, and generates informed responses.

## Features
- **Data Ingestion & Preprocessing**: Splits documents into 200–400 token chunks with a 50-token overlap.
- **Retrieval Mechanism**: Uses similarity search for efficient document retrieval.
- **Text Generation**: Generates responses based on retrieved context.

## Installation
It is recommended to create a virtual environment to avoid version conflicts:
```bash
python -m venv rag_env
source rag_env/bin/activate  # On Windows use: rag_env\Scripts\activate
pip install -r requirements.txt
```

## Usage
Run the notebook to execute the RAG pipeline step by step:
```bash
jupyter notebook RAG_Assignment.ipynb
```

## Dependencies
- Python 3.x
- Jupyter Notebook
- LangChain
- FAISS or another vector database
- OpenAI API (or another LLM provider)

## Future Enhancements
- Integration with a real-time chatbot
- Improved chunking strategies for better retrieval
- Optimization for large-scale datasets

## License
This project is open-source and available under the MIT License.

