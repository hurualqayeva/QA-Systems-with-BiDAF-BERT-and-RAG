#  RAG Open-Domain QA System

## 🚀 Project Overview
This project implements a full Retrieval-Augmented Generation (RAG) pipeline for Open-Domain Question Answering. Unlike standard RAG that relies solely on vector search, this system uses a **Hybrid Retrieval** approach (TF-IDF + SBERT) and compares Extractive (BiDAF/BERT) vs. Generative (T5) answering strategies.

## 🛠️ Technical Architecture
- **Retrieval:** Hybrid Sparse (TF-IDF) and Dense (Sentence-BERT `multi-qa-MiniLM-L6-cos-v1`) retrievers.
- **Extractive QA:** Implemented **BiDAF (Bidirectional Attention Flow)** with character-level CNNs and BERT embeddings.
- **Generative QA:** Fine-tuned **T5-base** for answer synthesis.
- **Dataset:** SQuAD v1.1.

## 👩‍💻 My Key Contributions
- Designed the **Hybrid RAG Architecture**.
- Implemented the **Dense Retriever** using Sentence Transformers.
- Built the **Generative QA** module using T5.
- Conducted hyperparameter tuning and evaluation (EM/F1 scores).

## 📄 Documentation
For deep technical details, please see the attached [Technical Report](Technical_Report_Hybrid_RAG.pdf) and [Project Presentation](NLP_Project_Presentation.pdf).
