# Automated Hate Speech and Offensive Language Detection in Social Media Text

This repository contains an end-to-end Machine Learning pipeline designed to classify social media text data (tweets) into three target categories: Hate Speech, Offensive Language, or Neutral. 

## 📌 Project Abstract & Significance
The escalation of toxic speech on public platforms creates significant scalability issues for manual content moderation systems. This project explores automated multi-class text classification algorithms using classical Natural Language Processing (NLP) methodologies to address computational efficiency and classification accuracy in content moderation pipelines.

## 🛠️ Methodology & Technical Architecture
The pipeline implements a complete data science lifecycle directly within the Jupyter environment:
1. **Exploratory Data Analysis (EDA):** Class distribution inspection to evaluate target variable imbalances.
2. **Text Preprocessing & Tokenization:** Case normalization, removal of URLs, punctuation handles, and stop words, followed by stemming/lemmatization.
3. **Feature Engineering:** Vectorization using Term Frequency-Inverse Document Frequency (TF-IDF) to convert raw strings into numerical feature matrices.
4. **Supervised Machine Learning:** Training baseline and optimized models (e.g., Logistic Regression, Naive Bayes, or Tree-Based Classifiers) to establish performance benchmarks.

## 📊 Performance Matrix
*Below are the core metrics evaluated during model validation:*

| Algorithm | Precision | Recall | F1-Score | Global Accuracy |
| :--- | :--- | :--- | :--- | :--- |
| Baseline Classifier | *[Fill this]* | *[Fill this]* | *[Fill this]* | *[Fill this]* |
| Final Optimized Model | *[Fill this]* | *[Fill this]* | *[Fill this]* | *[Fill this]* |

## 🚀 Environment & Setup
To replicate this pipeline locally, install the core dependencies:
```bash
pip install pandas numpy scikit-learn jupyter
