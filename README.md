# TAMUSA Policy Assistant

An AI-powered university policy assistant built using Retrieval-Augmented Generation (RAG).
This system allows students to ask questions in natural language and receive answers directly from official university policy documents.

## Project Overview

University policy documents are often long and difficult to navigate. Students usually spend a lot of time searching through handbooks and catalogs to find the right information.

To address this problem, this project implements an AI-powered assistant that retrieves relevant sections from university policy documents and generates accurate answers using a Large Language Model.

## How It Works

1. Policy documents are split into smaller text chunks
2. Each chunk is converted into vector embeddings
3. Embeddings are stored in a FAISS vector database
4. When a user asks a question, the system retrieves the most relevant policy sections
5. A Large Language Model generates the final answer using Retrieval-Augmented Generation (RAG)

## Technologies Used

* Python
* Streamlit
* LangChain
* FAISS Vector Database
* HuggingFace Sentence Transformers
* Groq LLM API

## Key Feature

The assistant generates responses **only from official university policy documents**, which reduces hallucinations and improves the reliability of answers.

## Use Cases

* Helping students quickly understand university policies
* Reducing time spent searching through policy documents
* Demonstrating real-world applications of RAG-based AI systems

## Future Improvements

* Add more university policy datasets
* Improve retrieval accuracy
* Deploy the assistant for public access


