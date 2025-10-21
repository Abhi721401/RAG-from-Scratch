# RAG-from-Scratch using GroqLLM and chromaDb
This is a project where I will be building the pipelines of RAG.
Steps include:
1. Data ingestion pipeline

   a. Data ingestion

   b. Data parsing

   c. Embedding

3. User Query

4. Vectore store ---> Retrevier

5. Retreval Pipeline
 
   a. LLM

   b. output generation

# Overview

A simple implementation of Retrieval-Augmented Generation (RAG) built from scratch using LangChain, Groq API, and FAISS.
This project loads PDF documents, splits them into chunks, stores them in a vector database, and enables question-answering over your own data.

# Features

a) Load and process multiple PDF files

b) Text chunking for efficient retrieval

c) FAISS vector store for similarity search

d) LLM integration using Groq API (Gemma-2 9B)

e) Ask natural language questions and get accurate contextual answers

# Tech Stack
Python

LangChain

FAISS

Groq API (Gemma-2 9B model)

dotenv

# How It Works
1.Load and extract text from PDFs

2.Split text into smaller chunks

3. Create vector embeddings and store them in FAISS

4.Use Groq’s LLM to generate contextual answers based on retrieved chunks

### Example
Input:
What are the key concepts discussed in Chapter 3 of the AI notes?

Output:
Chapter 3 focuses on Neural Networks — covering perceptrons, backpropagation, and activation functions with mathematical derivations.
