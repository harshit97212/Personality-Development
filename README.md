# Personality-Development
# 🧠 MBTI Personality Prediction Using NLP

This project predicts a user's MBTI (Myers-Briggs Type Indicator) personality type based on their written text using Natural Language Processing (NLP) and Machine Learning.

---

## 🚀 Project Overview

- Goal: Classify users into 1 of 16 MBTI personality types based on text input.
- Dataset: [mbti_1.csv from Kaggle](https://www.kaggle.com/datasets/datasnaek/mbti-type)
- Tech Stack: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 🧩 MBTI Types

Each personality type is represented by a 4-letter code:
- I/E – Introversion / Extraversion
- N/S – Intuition / Sensing
- T/F – Thinking / Feeling
- J/P – Judging / Perceiving

Examples: INTJ, ENFP, ISTP, etc.

---

## 📁 Dataset

- File: mbti_1.csv
- Columns:
  - type: MBTI personality type
  - posts: Combined social media posts from the user

---

## ⚙ How It Works

1. Data Preprocessing
   - Text cleaning: lowercasing, removing URLs and punctuation
   - TF-IDF vectorization for feature extraction

2. Model Training
   - Logistic Regression model is trained to classify MBTI types

3. User Interaction
   - After training, the user can input custom text
   - The model predicts and prints the corresponding MBTI type

---

## 🧪 Example

User Input:

I prefer deep conversations and love exploring abstract concepts. Crowds make me feel tired.


Predicted Output:

Predicted MBTI personality type: INFJ


---

## 📊 Evaluation

- Vectorizer: TF-IDF with stopword removal
- Classifier: Logistic Regression with saga solver
- Accuracy: Displayed after model evaluation
- Confusion Matrix: Heatmap plotted for class comparison

---

## 📎 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

In Google Colab, most libraries are pre-installed.

---

## 📌 Notes

- Longer and expressive user input gives better predictions.
- For best results, input should resemble social media or blog-style text.

---
