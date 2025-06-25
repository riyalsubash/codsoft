# CODSOFT - Task 2: Credit Card Fraud Detection using Random Forest

## 📌 Internship: CodSoft (June Batch B34)
This repository includes the implementation of **Task 2** for the **Python Programming Internship** at CodSoft. The goal of this task is to identify fraudulent credit card transactions using machine learning.

---

## 🎯 Project Title
**Credit Card Fraud Detection using Random Forest**

---

## 📝 Objective
The objective of this project is to classify credit card transactions as either **fraudulent** or **legitimate**, using a real-world dataset and a machine learning algorithm.

---

## 📊 Dataset Overview

- **Dataset Name:** `fraudTrain.csv` and `fraudTest.csv`
- **Source:** Kaggle / Real-world financial data
- **Size:** 1.2M+ transactions
- **Target Feature:** `is_fraud` (1 = Fraud, 0 = Legitimate)

---

## 🛠️ Tools & Technologies Used

- **Language:** Python 3
- **Libraries:** Pandas, Scikit-learn
- **Model Used:** Random Forest Classifier
- **Encoder:** Ordinal Encoder for categorical features

---

## ⚙️ Workflow

1. **Data Loading**
2. **Preprocessing**
   - Dropped non-informative & sensitive columns
   - Encoded categorical columns using `OrdinalEncoder`
3. **Model Training**
   - Trained `RandomForestClassifier` with 100 estimators
4. **Model Evaluation**
   - Calculated accuracy
   - Displayed prediction results

---

## 📈 Results

- ✅ **Model Used:** `RandomForestClassifier(n_estimators=100)`
- 📊 **Accuracy:** ~**99.7%** on test data
