---
title: "Predicting Stroke Risk Using Machine Learning"
excerpt: "End-to-end machine learning pipeline for predicting stroke risk using demographic and clinical data."
collection: portfolio
date: 2025-05-01
---

## Overview

Developed an end-to-end machine learning pipeline to predict stroke risk using a dataset of 5,110 patients. The project evaluated multiple classification approaches and addressed the substantial class imbalance present in the data.

## Approach

- Cleaned and prepared demographic and clinical features including age, BMI, glucose level, hypertension, heart disease, and smoking status.
- Applied median imputation for missing BMI values and one-hot encoding for categorical variables.
- Compared Logistic Regression, Decision Tree, Random Forest, XGBoost, and a feedforward Neural Network.
- Used SMOTE on the training data to address the approximately 5% positive-class imbalance while keeping the test set untouched.
- Evaluated models using accuracy, precision, recall, F1 score, and ROC-AUC.
- Examined ROC and lift curves to assess model performance across different classification thresholds.

## Results

XGBoost achieved the strongest overall performance with an ROC-AUC of **0.8426**.

The analysis also examined how variables such as age, glucose level, and BMI contributed to predicted stroke risk and explored the tradeoffs between different classification thresholds.

## Tools & Technologies

**Python · Scikit-learn · XGBoost · Pandas · NumPy · SMOTE · Machine Learning · Data Visualization**

## Key Takeaway

This project demonstrates an end-to-end approach to healthcare machine learning, from data cleaning and feature engineering through model comparison, class-imbalance handling, evaluation, and interpretation.
