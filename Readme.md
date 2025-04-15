# 🕵️ Crime Category Prediction using Machine Learning

This project focuses on predicting crime categories using structured data that includes incident date/time, location, victim demographics, and other related features. The aim is to develop accurate classification models to identify the type of crime that occurred based on these features.

---

## 📌 Problem Statement

The objective is to build robust machine learning models that predict the **type of crime** based on various input features, such as:

- Time and date of occurrence  
- Geographical location (latitude, longitude)  
- Victim demographic data  
- Crime descriptions and administrative classifications  
- etc.

---

## 🗂️ Project Overview

- Performed exploratory data analysis (EDA) and data visualization  
- Conducted feature engineering and preprocessing  
- Implemented multiple classification models  
- Applied hyperparameter tuning for each model to optimize performance  
- Evaluated models using appropriate metrics  
- Finalized best-performing model based on test accuracy

---

## 🔧 Data Preprocessing

- Handled missing values  
- Encoded categorical variables using `OrdinalEncoder`  
- Extracted datetime-based features (hour, weekday, etc.)  
- Applied `StandardScaler` for feature normalization  
- Balanced class distribution through stratified sampling

---

## 🤖 Models Implemented & Tuned

| Model                | Status          |
|---------------------|-----------------|
| Logistic Regression | ✅ Tuned & Tested |
| Random Forest       | ✅ Tuned & Tested |
| Gradient Boosting   | ✅ Tuned & Tested |
| XGBoost             | ✅ Tuned & Tested |
| XGBoost             | ✅ Final Model   |

> ✅ **Final accuracy** achieved: **0.88** on the test set using XGBoost with optimized parameters.

---

## ⚙️ Hyperparameter Tuning

Hyperparameter tuning was performed using techniques like:

- `GridSearchCV` and `RandomizedSearchCV`
- Manual experimentation based on feature importance and model diagnostics

Each model's key hyperparameters were tuned for optimal validation performance.

---

## 📊 Visualizations

- Class distribution and imbalance analysis  
- Feature correlation heatmaps  
- Confusion matrix for final model  
- Feature importance plots from tree-based models  
- Learning curves 

---
