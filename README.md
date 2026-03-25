# kmtaiwo-youtube-sentiment-analysis
Understanding audience sentiment and engagement patterns in YouTube content using NLP
# YouTube Sentiment Analysis

## 📌 Overview

This project analyses sentiment in YouTube comments to understand audience reactions and engagement patterns. The goal is to extract insights from user-generated text data and classify sentiment using machine learning techniques.

---

## 🎯 Problem Statement

Content creators and platforms need to understand how audiences respond to videos. Comments provide valuable feedback, but analysing large volumes of text manually is impractical.

This project builds a machine learning pipeline to classify sentiment in YouTube comments and uncover patterns in audience engagement.

---

## 📊 Dataset

- YouTube comments dataset  
- Text-based user-generated content  
- Includes positive, negative, and neutral sentiment  

---

## 🔧 Approach

### 1. Data Preprocessing
- Text cleaning (lowercasing, punctuation removal)
- Tokenization
- Stopword removal

### 2. Feature Engineering
- TF-IDF vectorisation
- Text representation for modeling

### 3. Modeling
- Logistic Regression (baseline)
- Naive Bayes (optional comparison)

### 4. Evaluation
- Accuracy
- Precision / Recall / F1-score

---

## 📈 Results

- Logistic Regression achieved strong baseline performance  
- Model effectively distinguishes positive vs negative sentiment  
- Performance balanced across key evaluation metrics  

---

## 🔍 Key Insights

- Negative sentiment often correlates with specific topics or video themes  
- Engagement patterns vary with sentiment intensity  
- Text data provides strong signals for audience behaviour  

---

## ⚖️ Trade-offs

- Simpler models offer interpretability but may miss nuance  
- More complex NLP models could improve performance but add complexity  

---

## 🚀 Future Improvements

- Use deep learning models (e.g. LSTM, transformers)  
- Perform topic modelling alongside sentiment  
- Analyse sentiment trends over time  

---

## 🛠️ Tech Stack

Python • Pandas • Scikit-learn • NLP • TF-IDF  

---

## 📁 Project Structure
