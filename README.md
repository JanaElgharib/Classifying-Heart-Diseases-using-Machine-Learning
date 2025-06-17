# Heart Disease Binary Classification Using Machine Learning

This project aims to predict the presence of heart disease in patients based on clinical data, using multiple machine learning models and evaluation strategies.

## 🩺 Project Overview

The dataset includes 12 clinical features for each patient, such as age, cholesterol, blood pressure, and chest pain type. The goal is to accurately classify whether a patient is at risk of heart disease.

## 🛠️ Key Steps

- **Data Analysis & Preprocessing**
  - Inspected data types, missing values, and feature distributions.
  - Applied normalization and feature engineering.
  - Used PCA for dimensionality reduction.

- **Model Development**
  - Trained and compared various ML models:
    - K-Nearest Neighbors (KNN)
    - Naive Bayes
    - Support Vector Machine (SVM)
    - Decision Trees
  - Developed a Deep Learning model using Keras achieving **98.95% recall**.

- **Evaluation Focus**
  - Prioritized **recall** to minimize false negatives (i.e., missed diagnoses).
  - Evaluated models using confusion matrices, recall, precision, and accuracy scores.

## 📁 Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn

## 📌 Outcome

The deep learning model achieved high recall, making it suitable for critical medical use cases where failing to detect a condition is far more dangerous than a false alert.

