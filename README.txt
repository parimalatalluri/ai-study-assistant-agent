# AI Study Assistant Agent

## Overview
The AI Study Assistant Agent is a Python-based application that helps students learn from PDF study materials using a Large Language Model (LLM) and Retrieval-Augmented Generation (RAG).

## Features
- Extracts text from PDF study materials.
- Splits documents into manageable text chunks.
- Generates semantic embeddings for document retrieval.
- Retrieves relevant information using cosine similarity.
- Answers questions based on retrieved study material.
- Generates study summaries and practice quizzes.
- Uses the Groq API to generate AI-powered responses.

## Technologies Used
- Python
- Jupyter Notebook
- Groq API
- Retrieval-Augmented Generation (RAG)
- Sentence Transformers
- PyMuPDF
- NumPy
- Scikit-learn

## Setup and Execution
1. Install Python and Jupyter Notebook.
2. Install the required packages using:

   `pip install -r requirements.txt`

3. Open `AI_Study_Assistant_Agent.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.
5. Enter your Groq API key when prompted.
6. Place your own study PDF in the notebook's working directory and update the PDF filename in the notebook if needed.
7. Ask questions, generate summaries, and create practice quizzes.

## Security
Never commit API keys, passwords, or other credentials to GitHub.

## Project Status
Initial implementation of a RAG-based AI Study Assistant Agent.