Multimodal Retrieval-Augmented Generation (MMRAG)
Overview

This project implements a Multimodal Retrieval-Augmented Generation (MMRAG) system that enables intelligent question answering from PDF documents containing both text and images. The system extracts, processes, summarizes, indexes, and retrieves multimodal content to generate accurate and context-aware responses using Large Language Models (LLMs).

Features
Extracts text and images from PDF documents.
Generates semantic summaries for textual and visual content.
Converts summaries into vector embeddings for efficient retrieval.
Stores embeddings in a Chroma Vector Database.
Performs Maximum Marginal Relevance (MMR) retrieval for diverse and relevant search results.
Uses Cross-Encoder re-ranking to improve retrieval accuracy.
Generates context-aware answers using LLMs.
Supports multimodal document understanding and question answering.
System Architecture
Document Processing
PDF parsing using Docling.
Extraction of text chunks and images.
Content Summarization
Text summarization using Large Language Models.
Image understanding and description generation using Gemini 2.5 Flash.
Embedding Generation
Semantic embeddings generated using MixedBread AI Embedding Model.
Vector Storage
Embeddings stored in ChromaDB for efficient similarity search.
Retrieval Pipeline
Maximum Marginal Relevance (MMR) retrieval.
Cross-Encoder re-ranking using BAAI BGE Reranker.
Response Generation
Context construction from retrieved text and image summaries.
Final answer generation using Llama 3.
Technologies Used
Python
LangChain
ChromaDB
Docling
Google Gemini 2.5 Flash
Llama 3
MixedBread AI Embeddings
BAAI BGE Reranker
Retrieval-Augmented Generation (RAG)
Applications
Intelligent document search
Research paper analysis
Knowledge management systems
Enterprise document assistants
Multimodal question answering
Future Enhancements
Support for additional document formats.
Real-time document ingestion.
Hybrid keyword and semantic search.
Interactive web-based user interface.
Multi-document conversational retrieval.
