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

##  Project Structure
---

##  Models Implemented

### 1️ TF-IDF + Logistic Regression
- Fast and interpretable baseline
- Suitable for lightweight moderation systems
- Strong performance with low computational cost

### 2️ BERT (Transformer-based Model)
- Captures contextual meaning in text
- Better at detecting subtle and implicit hate speech
- Higher F1-score compared to the baseline

---

##  Model Evaluation
Models were evaluated using:
- F1-score (macro)
- Accuracy
- Precision and Recall
- Confusion Matrix

A visual comparison between models is available in:

metrics_comparison.png

---

##  Inference & Deployment
A production-oriented inference script (`predict.py`) was implemented to:
- Load trained models
- Perform real-time predictions
- Support future API or service integration

---

##  Model Artifacts
Due to repository size constraints, the trained BERT weights
(`pytorch_model.bin`) are not included.

The full training pipeline, configuration files, and tokenizer
are available, allowing the model to be retrained or loaded from
pretrained checkpoints.
