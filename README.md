# 🌍 AI-Driven Corporate Greenwashing Detection Framework

## 📌 Project Overview
This capstone project develops an AI-powered NLP framework to detect corporate greenwashing using transformer-based models. The system analyzes corporate sustainability reports and classifies whether claims are genuine or misleading.

---

## ❓ Problem Statement
Many companies exaggerate or misrepresent their environmental efforts (greenwashing). Detecting such misleading claims manually is time-consuming and subjective.

This project automates greenwashing detection using NLP and Deep Learning.

---

## 🎯 Objectives
- Build a binary classification model using DistilBERT
- Detect misleading sustainability claims
- Develop a Streamlit dashboard for real-world deployment
- Provide analytics insights for decision-makers

---

## 📊 Dataset
Dataset Used: Climate Fever / Corporate Sustainability Dataset  
- Text-based sustainability statements  
- Labeled as: Genuine / Greenwashing  

Preprocessing Steps:
- Tokenization
- Stopword removal
- Padding & truncation
- Train-test split

---

## 🧠 Model Architecture

- Model: DistilBERT
- Framework: HuggingFace Transformers
- Loss Function: Binary Cross Entropy
- Optimizer: AdamW
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/greenwashing-detection.git
cd greenwashing-detection
pip install -r requirements.txt
