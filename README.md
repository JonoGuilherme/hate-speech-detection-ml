#  Hate Speech & Offensive Language Detection (NLP)

##  Project Overview
This project applies Natural Language Processing (NLP) and Machine Learning
to automatically detect hate speech and offensive language in user-generated content.

The goal is to support content moderation systems by identifying harmful text
before it spreads across online platforms.

---

##  Business Problem
Hate speech and offensive language can cause psychological harm and
negatively impact online communities.

Automated moderation tools help platforms:
- Protect vulnerable groups
- Reduce moderation costs
- Enforce content policies consistently

---

##  Dataset
Source: Kaggle – Hate Speech and Offensive Language Dataset

The dataset contains labeled social media posts classified as:
- Hate Speech
- Offensive Language
- Neither

---

##  Models Implemented
### 1️⃣ Baseline Model
- TF-IDF + Logistic Regression
- Fast, interpretable, strong baseline

### 2️⃣ Advanced Model
- BERT (Transformer-based model)
- Captures contextual meaning
- Improved performance on complex language patterns

---

##  Evaluation Metrics
- F1-score (macro) – primary metric
- Precision
- Recall
- Accuracy
- Confusion Matrix

---

##  Key Findings
- Offensive language is easier to detect than hate speech
- Context-aware models (BERT) outperform traditional ML models
- F1-macro is essential due to class imbalance

---

##  Deployment Considerations
This model could be deployed as:
- A REST API for real-time moderation
- An internal moderation support tool
- A pre-filtering step in social platforms
