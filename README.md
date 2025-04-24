# 📰 AI Fake News Detector

## 1. Overview

This project aims to develop an AI-based system to detect **fake news** using machine learning and natural language processing (NLP). The model is trained on labeled news articles and predicts whether a news statement is real or fake. Several classification algorithms, including Logistic Regression and Passive Aggressive Classifier, are implemented and compared to identify the most accurate model.

## 2. Features

- Text preprocessing using NLP (stopword removal, stemming, etc.)
- Feature extraction with TF-IDF Vectorization
- Implementation of multiple ML models
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Visualizations using Matplotlib and Seaborn

## 3. Tech Stack

- **Python**
- **Pandas** & **NumPy**
- **Scikit-Learn**
- **Matplotlib** & **Seaborn**
- **NLTK** / **SpaCy** (for NLP tasks)

## 4. Results & Findings

- The best-performing model (Logistic Regression) achieved an accuracy of **~96%**
- Passive Aggressive Classifier also performed well with high precision
- TF-IDF proved effective for converting text data into numerical features

## 5. Future Enhancements

- Integration with a **web application** (Flask/Streamlit) for live predictions
- Use of advanced models like **BERT** or **LSTM** for improved accuracy
- Support for multilingual fake news detection
- Real-time news scraping and prediction system



