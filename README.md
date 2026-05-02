# 📄 Document Question Answering System (LoRA + RAG)

A document question answering system built using large language models with **LoRA (Low-Rank Adaptation)** for efficient fine-tuning while keeping base model parameters frozen. The system leverages **Retrieval-Augmented Generation (RAG)** to provide accurate and context-aware answers from documents.

## 🚀 Features
- Parameter-efficient fine-tuning using LoRA (PEFT)  
- Retrieval-Augmented Generation (RAG) for better contextual responses  
- Integration with Haystack and LangChain  
- Quantization using BitsAndBytes for reduced memory usage  
- Accelerated training with DeepSpeed  
- Supports scalable and efficient document querying  

## 🛠️ Tech Stack
- Python  
- Hugging Face Transformers  
- PEFT (LoRA)  
- BitsAndBytes  
- DeepSpeed  
- Haystack (RAG)  
- LangChain  

## ⚙️ How It Works
1. Documents are indexed and stored using a retriever (Haystack).  
2. User queries are processed and relevant context is retrieved.  
3. LLM generates answers using retrieved context (RAG pipeline).  
4. LoRA fine-tunes the model efficiently without updating full parameters.  

## 📊 Evaluation
- Accuracy  
- F1-score  
- Response relevance  
- Iterative hyperparameter tuning for performance improvement  

## 📌 Use Cases
- Document-based search systems  
- Enterprise knowledge assistants  
- Research paper Q&A  
- Chatbots with document understanding  
