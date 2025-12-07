🚀 Overview

This project is a YouTube Comment Sentiment Analyzer built using Machine Learning and Natural Language Processing (NLP).
It fetches comments from YouTube videos using the YouTube Data API, preprocesses the text, and classifies sentiment using an ML model.
The goal is to understand audience reactions and extract insights from YouTube engagement data.

This project demonstrates:

Real-world NLP

ML model building & evaluation

Data extraction using APIs

Preprocessing & feature engineering

Visualization of sentiment distribution

🧠 Features

📥 Fetch YouTube comments via YouTube Data API

🧹 Clean and preprocess text

stopword removal

lowercasing

punctuation removal

optional lemmatization

🤖 Train ML models

Logistic Regression (default)

Naive Bayes (optional)

📊 Sentiment Classification

Positive

Negative

Neutral

📈 Visualize sentiment distribution

🔐 Secure API key usage via Colab Secrets

🛠️ Tech Stack

Python

Google Colab

YouTube Data API v3

scikit-learn (Logistic Regression / Naive Bayes)

pandas, numpy

matplotlib / seaborn

NLTK for preprocessing
