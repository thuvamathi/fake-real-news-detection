# 📰 Fake News Detection Using Machine Learning

This project aims to detect fake news articles using machine learning models such as **Naïve Bayes** and **Logistic Regression**.  
It compares different text vectorization techniques — **CountVectorizer**, **TF-IDF**, and **TF-IDF with Bigrams** — to identify the most accurate model.

## 📌 Introduction
The spread of fake news impacts society and public opinion.  
This project implements multiple classification techniques to identify fake news, using data from various news sources.

## 🎯 Aim & Objectives
**Aim:**  
Build and evaluate models to classify news as *real* or *fake*.

**Objectives:**
1. Collect and preprocess a dataset of real and fake news articles.
2. Implement Naïve Bayes and Logistic Regression models.
3. Compare performance across vectorization techniques.
4. Evaluate using accuracy, precision, recall, and F1-score.
5. Recommend the most effective model for fake news detection.

## 📂 Dataset
Dataset: [Fake and Real News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data)  
- **True.csv** → Real news articles  
- **Fake.csv** → Fake news articles  

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
