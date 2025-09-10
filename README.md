# 📰 Fake News Detector (AI/ML Project)

This project is an **AI/ML-powered Fake News Detector** that uses **Natural Language Processing (NLP)** techniques to classify news articles as *real* or *fake*.  

## 🔹 Overview
- Loads and preprocesses datasets (`True.csv` for real news, `Fake.csv` for fake news).  
- Cleans and combines article titles & text for better analysis.  
- Uses **TF-IDF Vectorization** to convert text into numerical features.  
- Trains and evaluates two machine learning models:  
  - Logistic Regression  
  - Passive-Aggressive Classifier  
- Saves trained models for reusability (`logreg.joblib`, `pa.joblib`, `tfidf.joblib`).  
- Provides a simple demo for predicting whether a new article is real or fake.  

## 🚀 Key Features
- End-to-end pipeline: preprocessing → training → evaluation → prediction.  
- High accuracy on test data.  
- Easily extendable with new models or datasets.  

## 🛠 Tech Stack
- Python  
- scikit-learn  
- pandas, numpy, re  
- joblib  

## 📌 Applications
- Detecting misinformation on social media.  
- Assisting fact-checking platforms.  
- Research in NLP and fake news detection.  

---
✨ *A step towards ensuring trustworthy information in the digital age.*
