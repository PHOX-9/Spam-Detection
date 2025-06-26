# 📧 Spam Detection Model using Multinomial Naive Bayes

This project is a machine learning-based spam detection system that classifies emails as **spam** or **ham** (not spam) using the **Multinomial Naive Bayes** algorithm.

## 🧠 Model Overview

- **Algorithm:** Multinomial Naive Bayes
- **Dataset:** Email dataset with two classes: `spam` and `ham`
- **Preprocessing:**
  - Tokenization
  - TF-IDF or Count Vectorization
- **Handling Class Imbalance:** Used `sample_weight` to balance the 700:4800 class ratio
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 🚀 How It Works

1. Load and preprocess email data
2. Convert text to numerical features using `TfidfVectorizer` or `CountVectorizer`
3. Train the `MultinomialNB` model
4. Evaluate on test data
5. Predict whether new emails are spam or ham
