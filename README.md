
markdown
Copy
Edit
# QA-chatBot-Haystack-RAG

A simple question-answering chatbot built using the Haystack framework with Retrieval-Augmented Generation (RAG). It answers questions about the Seven Wonders of the World using a publicly available dataset and runs in a Jupyter notebook or terminal without a UI.

##  Description

This project demonstrates how to build a lightweight, document-based QA system using Haystack and RAG architecture. It uses the `seven-wonders` dataset from Hugging Face and provides accurate, context-aware answers to user questions.

The system includes:

- Document preprocessing and indexing with FAISS
- Dense passage retrieval
- Answer generation using a transformer model
- Command-line or notebook interaction (no UI)

##  Dataset

- [Seven Wonders Dataset](https://huggingface.co/datasets/bilgeyucel/seven-wonders)
- Format: JSON lines, containing short passages about the Seven Wonders

##  Tech Stack

- Python
- Haystack
- Hugging Face Transformers
- FAISS (for dense vector search)

##  How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/VivekanandVivekQA-chatBot-Haystack-RAG.git
   cd QA-chatBot-Haystack-RAG
Install dependencies
Make sure you have Python 3.8+ and run:

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebook
Open main.ipynb and run all cells, or use it in a script to interact via terminal.

Ask Questions
Type natural language questions about the Seven Wonders and receive generated answers.

Example
text
Copy
Edit
Question: What is the Hanging Gardens of Babylon?
Answer: The Hanging Gardens were described as a remarkable feat of engineering with an ascending series of tiered gardens...
Use Cases
Educational Q&A systems

Introductory project for RAG-based models

Lightweight document-based chatbot prototype
