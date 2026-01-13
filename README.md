#  Hate Speech & Offensive Language Detection (NLP)

##  Project Overview
This project applies Natural Language Processing (NLP) and Machine Learning
to automatically detect hate speech and offensive language in user-generated content.

Two approaches were implemented and compared:
- A classical machine learning baseline (TF-IDF + Logistic Regression)
- An advanced transformer-based model (BERT)

The project focuses on performance, interpretability, and real-world deployment considerations.

---

##  Business Problem
Hate speech and offensive language can cause psychological harm and negatively
impact online communities.

Online platforms require automated moderation systems to:
- Protect users
- Reduce manual moderation costs
- Enforce content policies consistently
- Scale moderation across large volumes of data

---

##  Dataset
Source: Kaggle – Hate Speech and Offensive Language Dataset

Classes:
- Hate Speech
- Offensive Language
- Neither

Due to class imbalance, **F1-score (macro)** was prioritized as the main evaluation metric.

---

## 🛠️ Project Structure
