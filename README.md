

# 💳 Credit Card Default Prediction

## 📌 Overview

This project builds a machine learning model to predict whether a customer will default on their credit card payment in the following month. The problem is formulated as a **binary classification task**, where 1 indicates default and 0 indicates non-default.

---

## ⚙️ Approach

* Performed data preprocessing and exploratory data analysis
* Trained multiple models: Logistic Regression, Decision Tree, Random Forest, KNN, SVM, Naive Bayes, and AdaBoost
* Evaluated models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix
* Applied GridSearchCV for hyperparameter tuning

---

## 🏆 Final Model

**Random Forest Classifier** was selected based on its balanced performance and superior F1-score for the minority (default) class.
Final accuracy achieved: **~82%**

---

## 🚀 Deployment

The trained model was deployed using **Streamlit**, enabling real-time prediction and probability-based credit risk scoring.

---

## 🛠️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, Streamlit, Joblib


