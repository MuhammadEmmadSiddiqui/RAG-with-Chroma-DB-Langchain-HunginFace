# RAG with Chroma DB, LangChain, and Hugging Face
This project demonstrates a complete pipeline for building a Retrieval-Augmented Generation (RAG) system from scratch. The workflow includes creating a vector database, generating embeddings, and performing RAG using advanced models.

# Key Features:
Vector Database: Utilizes Chroma DB for efficient text storage and retrieval.
Embedding Model: Converts text into vector representations using BERT Uncased embeddings.
LLM for Text Generation: Leverages T5 (hosted on Hugging Face) to generate responses based on retrieved context.
# Highlights:
The RAG system effectively minimizes or eliminates hallucinations.
Results are generated strictly based on the provided context, ensuring reliability.
References are included alongside the generated answers, allowing validation and improving transparency.
This notebook offers an end-to-end solution for integrating Chroma DB, LangChain, and Hugging Face models for creating a robust and accurate RAG system.
