# Rajeh – Saudi Legal AI Assistant  
RAG + LLM Powered Legal Intelligence

## 📌 Project Overview
**Rajeh** is an intelligent legal assistant specialized in Saudi law, built using **Retrieval-Augmented Generation (RAG)** and **Large Language Models (LLMs)**.  
The system analyzes Saudi regulations and legal documents to provide **accurate answers with explicit legal references**.

The goal of Rajeh is to enable individuals and organizations to receive clear, reliable, and reference-backed legal insights **without reading dozens of legal pages**.

---

## 🎯 Key Objective
To deliver a smart legal system capable of:
- Providing accurate, trustworthy answers.
- Citing the official legal source for every response.
- Simplifying access to Saudi regulations and decisions.
- Offering fast, low-cost legal consultation for the public and businesses.

---

## 🔍 System Workflow

### 1. **Document Extraction**
Collecting Saudi legal systems and regulations from official sources.

### 2. **Preprocessing & Cleaning**
Standardizing formats, removing noise, and preparing text for processing.

### 3. **Legal-Level Chunking**
Splitting the content into meaningful chunks at the **article level** to enhance retrieval accuracy.

### 4. **Metadata Enrichment**
Adding contextual metadata for each chunk, including:
- Regulation name  
- Article number  
- Category  
- Source URL  
This significantly improves retrieval precision.

### 5. **Arabic Embedding Generation**
Using an Arabic language embedding model to ensure strong semantic understanding of Arabic legal text.

### 6. **Vector Database Construction**
Building a high-performance vector index using **FAISS** for fast and accurate retrieval.

### 7. **RAG Integration**
Retrieved chunks are combined with an LLM to generate:
- Accurate, contextual responses  
- Cited legal references  
- Clear system-aligned answers  

### 8. **Prompt Engineering**
Designed prompts to:
- Improve clarity  
- Enforce reference citation  
- Prevent hallucination  
- Maintain legal accuracy  

### 9. **User Interface Development**
A simple ready-to-use UI that allows users to ask legal questions and receive instant answers.

---

## 🛠️ Tech Stack
- Python  
- LangChain  
- FAISS Vector Database  
- Arabic Embedding Models (e.g., AraBERT-based)  
- LLMs for legal reasoning  
- FastAPI (backend)  
- Streamlit / React (frontend)  
- Prompt Engineering  

---

## 🚀 Features
- Accurate legal answers  
- Official reference citations  
- Fast legal search  
- Native Arabic understanding  
- User-friendly interface  
- Modular architecture for scaling  

---



