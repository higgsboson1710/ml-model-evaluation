# Logistic Regression ROC & Threshold Analysis

## 📌 Overview
This project demonstrates ROC curve analysis and optimal threshold
selection for a binary classification problem using Logistic Regression.

The Pima Indians Diabetes dataset is used to evaluate model performance
beyond simple accuracy.

## 📊 What This Notebook Covers
- Train-test split of the dataset
- Logistic Regression model training
- ROC curve computation using predicted probabilities
- Visualization of ROC curve with threshold markers
- Optimal threshold selection using Youden’s J statistic (TPR − FPR)

## 🧪 Model Used
- Logistic Regression

## 📈 Key Insight
Instead of relying on the default 0.5 threshold, the notebook identifies
a better decision threshold by maximizing the difference between true
positive rate and false positive rate.

## 🛠 Libraries Used
- pandas
- numpy
- scikit-learn
- plotly

## 📂 File
- `logistic_regression_roc_threshold_analysis.ipynb`
