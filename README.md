***Originally developed in May 2025***

Overview

This project demonstrates the development of a domain-specific conversational agent using LangChain, OpenAI, and vector-based retrieval (FAISS).
It explores how prompt-engineering strategies and conversational memory can be combined to create accurate, context-aware chatbots that maintain dialogue coherence across multiple turns.

The system implements Retrieval-Augmented Generation (RAG), where a language model answers questions by grounding responses in relevant academic or domain-specific text.
Using free Hugging Face embeddings (sentence-transformers/all-MiniLM-L6-v2), the notebook runs fully in Google Colab with no API costs.

Key Features

Integration of LangChain with Hugging Face models
Retrieval-Augmented Generation (RAG) using FAISS vector search
ConversationBufferMemory for multi-turn context retention
Comparison of Zero-Shot, Few-Shot, Chain-of-Thought, and Self-Reflection prompting.

Run the notebook

Execute each cell in order — all dependencies install automatically.
