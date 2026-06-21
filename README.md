# DevelopersHub Corporation — AI/ML Internship Tasks - Phase 2

**Intern:** Javeria

**Department:** AI/ML Engineering

**DHC ID:** DHC-2448

**Date:** 30 June, 2026

---

## Overview

This repository contains 4 advanced tasks completed as part of Phase 2 of the AI/ML Engineering Internship at DevelopersHub Corporation. These tasks cover cutting-edge AI/ML techniques including transformer models, ML pipelines, multimodal learning, and conversational AI.

---

## Tasks Summary

---

### Task 1 – News Topic Classifier Using BERT

**Objective:** Fine-tune a BERT transformer model to classify news headlines into topic categories.

**Dataset:** AG News Dataset (HuggingFace Datasets)

**Model Used:** bert-base-uncased

**Key Results:**
- Tokenized and preprocessed AG News dataset
- Fine-tuned BERT using HuggingFace Trainer API
- Evaluated using Accuracy and F1-Score
- Deployed an interactive classifier using Gradio

**Libraries Used:** transformers, datasets, torch, scikit-learn, gradio

---

### Task 2 – End-to-End ML Pipeline with Scikit-learn

**Objective:** Build a reusable production-ready ML pipeline to predict customer churn.

**Dataset:** Telco Customer Churn Dataset

**Models Used:** Logistic Regression, Random Forest with GridSearchCV

**Key Results:**
- Built full preprocessing pipeline using ColumnTransformer
- Applied StandardScaler for numerical and OneHotEncoder for categorical features
- Tuned Random Forest with GridSearchCV hyperparameter optimization
- Evaluated using Accuracy, Classification Report, and Confusion Matrix
- Exported final pipeline using joblib for reusability

**Libraries Used:** scikit-learn, pandas, numpy, matplotlib, seaborn, joblib

---

### Task 3 – Multimodal ML – Housing Price Prediction

**Objective:** Predict housing prices by combining image features with tabular data.

**Dataset:** Housing Sales Dataset + Synthetic Image Data

**Models Used:** ResNet18 (CNN) for image features + Linear Regression

**Key Results:**
- Extracted deep image features using pretrained ResNet18
- Reduced image features using PCA
- Combined CNN image features with tabular property data
- Trained regression model on combined multimodal features
- Evaluated using MAE and RMSE

**Libraries Used:** torch, torchvision, scikit-learn, pandas, numpy, matplotlib, seaborn

---

### Task 4 – Context-Aware Chatbot Using LangChain and RAG

**Objective:** Build a conversational chatbot that remembers context and retrieves external knowledge.

**Dataset:** Custom Knowledge Base (AI/ML topic documents)

**Model Used:** Mistral-7B-Instruct via HuggingFace + sentence-transformers

**Key Results:**
- Built a vectorized document store using FAISS
- Used sentence-transformers for document embeddings
- Implemented ConversationBufferMemory for context tracking
- Created ConversationalRetrievalChain for RAG-based responses
- Built command-line chatbot interface

**Libraries Used:** langchain, langchain-community, faiss-cpu, sentence-transformers, HuggingFace

---

## Repository Structure

```
DevelopersHub-ML-Internship-Phase-2/
├── LICENSE
├── README.md
├── phase2_task1.ipynb
├── phase2_task2.ipynb
├── phase2_task3.ipynb
├── phase2_task4.ipynb
```

---

## Installation

```bash
pip install transformers datasets torch scikit-learn gradio pandas numpy matplotlib seaborn joblib langchain langchain-community faiss-cpu sentence-transformers torchvision langchain-huggingface
```

---

## Important Notes

- Task 1 and Task 3 should be run on **Google Colab** for GPU support
- Task 4 requires a free **HuggingFace token** from huggingface.co/settings/tokens
- Replace `YOUR_HF_TOKEN_HERE` in the Task 4 notebook with your actual token

---

## Author

**Javeria**

AI/ML Engineering Intern – DevelopersHub Corporation
