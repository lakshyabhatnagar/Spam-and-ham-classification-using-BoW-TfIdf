# 📧 Spam vs Ham Classification Project

This is a Machine Learning project that aims to classify SMS messages as **Spam** or **Ham (Not Spam)** using traditional NLP techniques such as **Bag of Words (BoW)** and **TF-IDF**, followed by classification using various ML models.

---

## 📂 Project Structure

- `27.2-Spam Ham Classification Project Using BOW And TFIDF And ML.ipynb`: Main Jupyter notebook with complete end-to-end pipeline.
- `spam.csv`: Dataset used for training and evaluation.

---

## 🔍 Problem Statement

The goal is to build a binary classifier that can automatically distinguish between spam and legitimate (ham) SMS messages. This helps in filtering out unwanted text messages and improving user experience.

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- pandas, numpy
- scikit-learn (CountVectorizer, TfidfVectorizer, MultinomialNB, etc.)
- matplotlib, seaborn for visualization

---

## 🧠 ML/NLP Concepts Used

- **Data Cleaning**: Removing special characters, converting to lowercase, stopwords removal, stemming.
- **Feature Extraction**: Using `CountVectorizer` (BoW) and `TfidfVectorizer`.
- **Modeling**: Trained with:
  - Multinomial Naive Bayes
  - Logistic Regression (optional)
  - Support Vector Machine (optional)
- **Evaluation**: Accuracy, Confusion Matrix, Classification Report

---

## 📈 Results

Model performance is evaluated using accuracy and precision/recall metrics. Generally, TF-IDF with Naive Bayes yields high accuracy (~97–98%) on this dataset.

---

## 📊 Dataset

- The dataset is a collection of ~5,500 SMS messages labeled as `ham` or `spam`.
- Source: [UCI SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---
