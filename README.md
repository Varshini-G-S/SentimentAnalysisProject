# Sentiment Analysis Project

🚀 **CodTech Task 4** - Sentiment Analysis using Python  

This project demonstrates **text sentiment classification** using both **VADER (lexicon-based)** and **Naive Bayes with TF-IDF**. It is designed as a simple NLP project for short text sentiment analysis, suitable for portfolio or demo purposes.

---

## 🔹 Features

- **VADER Sentiment Analysis**:
  - Rule-based sentiment analysis using NLTK.
  - Works well for short sentences and social media text.
  - Labels text as **Positive**, **Negative**, or **Neutral**.

- **Optional ML Model (Naive Bayes + TF-IDF)**:
  - Preprocesses text (handles lowercasing, punctuation, stopwords, and negations).
  - Vectorizes text using TF-IDF with unigrams and bigrams.
  - Trains a simple Naive Bayes classifier.
  - Demonstrates basic ML-based sentiment prediction.

- **Preprocessing Highlights**:
  - Keeps negation words (`not`, `no`, `never`) for better sentiment understanding.
  - Removes unwanted characters while preserving contractions.
  - Handles text cleaning efficiently for both VADER and ML models.

---

## 🔹 Sample Output

**VADER Predictions:**

Text: I absolutely loved the service!
Sentiment: Positive

Text: This was a horrible experience.
Sentiment: Negative

Text: It's fine, not too bad.
Sentiment: Positive

Text: Amazing performance, really enjoyed it!
Sentiment: Positive

Text: Waste of time and money.
Sentiment: Negative
