# -Research-Paper-Answer-Bot
🧠 Project Description

The Research Paper Answer Bot is an intelligent chatbot system built on top of a RAG (Retrieval-Augmented Generation) architecture. Designed for a scenario similar to ArXiv, this bot answers user queries related to Generative AI by extracting contextual knowledge from seminal research papers.

The system leverages vector databases, retrieval strategies, and large language models (LLMs) to provide accurate, explainable answers while referencing the source documents used to generate them.

🎯 Project Objectives

 Ingest and preprocess research papers (PDF format)
 Index documents into a vector database (e.g., FAISS, Chroma, Weaviate)
 Experiment with multiple embedding models:
OpenAI Embeddings (text-embedding-ada-002)
HuggingFace Models (bge-base, jina-embeddings-v2)
 Compare different retrieval strategies:
Cosine similarity
BM25 + Hybrid Retrieval
Reranking (e.g., Cohere, BGE-Reranker)
 Build a RAG pipeline using an LLM (e.g., GPT-4, Mixtral)
 Test the system with sample queries
 Display top 3 source documents for each generated answer

 ✅ Option 1: Multi-user conversational RAG system
Enables memory-based, session-aware conversations
Built with LangChain agents and chat history persistence
 Option 2: Agentic Corrective RAG + Web Search
Use agent patterns to fetch web documents for real-time correction
Combine with LangChain's Tool & Agent modules
