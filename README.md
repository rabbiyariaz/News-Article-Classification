
# 📰 Smart News Classifier

**Automating News Categorization with Machine Learning**
**December 2024**

## 📌 Overview

Smart News Classifier is a machine learning-based system designed to automatically categorize news articles into 42 distinct topics. It utilizes TF-IDF feature extraction combined with classical machine learning algorithms (Naïve Bayes and Support Vector Machines) to achieve accurate and scalable multi-class classification.

## 🚀 Features

* Classifies articles into **42 real-world news categories**
* Uses **Naïve Bayes** and **SVM** classifiers
* Achieves **80% test accuracy**, evaluated using precision, recall, and F1-score
* Processes **210,000 articles** from a large-scale dataset
* Robust **data preprocessing pipeline** using NLTK and Scikit-learn

---

## 📂 Dataset

**Source**: [News Category Dataset](https://www.kaggle.com/rmisra/news-category-dataset)

* Size: 210,000+ news articles
* Fields used: `headline`, `short_description`, `category`
* Classes: 42 unique news categories
* Split: Stratified into **training**, **validation**, and **test** sets to preserve class balance

---

## ⚙️ Preprocessing Pipeline

Implemented using **NLTK** and **Scikit-learn**:

* Text normalization (lowercasing, punctuation removal)
* Tokenization
* Stopword removal
* Lemmatization
* Feature extraction using **TF-IDF Vectorizer**

---

## 🧠 Model Training

Two models were implemented and compared:

* **Logistic Regression**
* **Random Forest**
* **Support Vector Machine**

---

## 🛠 Tech Stack

* Python 3.x
* [Scikit-learn](https://scikit-learn.org/)
* [NLTK](https://www.nltk.org/)
* NumPy, Pandas
* Jupyter Notebooks

---

