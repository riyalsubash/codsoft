# CODSOFT - Task 1: Movie Genre Prediction using Machine Learning

## 📌 Internship: CodSoft (June Batch B34)
This repository contains the implementation of **Task 1** for the **Python Programming Internship** at CodSoft. The task involves predicting the genre of a movie based on its plot description using Natural Language Processing (NLP) and Machine Learning.

---

## 🎯 Project Title
**Movie Genre Prediction using Logistic Regression and TF-IDF**

---

## 📝 Objective
Build a multi-class classification model that predicts the **genre** of a movie based on its **description**. This project involves:
- Reading and cleaning data
- Text preprocessing
- Feature extraction using TF-IDF
- Model training using Logistic Regression
- Evaluation with accuracy and F1-score

---

## 🧠 Dataset Overview

### ✅ `train_data.txt`


Each entry includes either:
- Training data with labels (genres)
- Test data without genre (used for prediction)
- Ground truth labels for test data (for evaluation)

---

## 🔧 Technologies Used
- Python 3
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

---

## 🚀 Features
- Handles **imbalanced classes** using `class_weight='balanced'`
- Uses **TF-IDF** for converting text to numerical vectors
- Accepts **custom user input** to predict movie genre
- Prints evaluation metrics including:
  - Accuracy
  - Precision, Recall, F1-Score
- Displays **sample predictions**

---

## 📈 Results (After Class Balancing)

- **Accuracy:** `~49.5%`
- **Macro F1-score:** `0.37`
- ✅ Improved prediction for rare genres (e.g., `biography`, `romance`, `sci-fi`)
- ❌ Slight drop in overall accuracy due to fairer genre distribution