# mlflow_experiments

This repository contains hands-on experiments using **MLflow** to demonstrate **Supervised Learning** with both **Classification** and **Regression** models, along with **hyperparameter tuning** and **experiment tracking**.

---

## 📘 Experiment 1: Supervised Learning - RandomForestClassifier

**Experiment Name:**  
`mlflow_1st_exp_SupervisedL_RandomForestClassifier`

### ✅ Details
- **Learning Type:** Supervised Learning (Classification)
- **Algorithm:** RandomForestClassifier
- **Hyperparameters Tuned:**
  - `n_estimators` → Number of trees in the forest
  - `max_depth` → Maximum depth of each tree

### 🎯 Goal
- Train multiple models with different hyperparameter settings  
- Track and compare results using **MLflow**  
- Select the **best-performing model** based on accuracy  

---

## 📘 Experiment 2: Supervised Learning - XGBoost Regressor

**Experiment Name:**  
`mlflow_1st_exp_SupervisedL_XGBoostRegressor.ipynb`

### ✅ Details
- **Learning Type:** Supervised Learning (Regression)
- **Algorithm:** XGBoost Regressor
- **Hyperparameters Tuned:**
  - `n_estimators` → Number of trees
  - `max_depth` → Depth of each tree
  - `learning_rate` → Step size for boosting
  - `subsample` → Fraction of samples used for each tree

### 🎯 Goal
- Train multiple regression models with different hyperparameters  
- Track metrics such as **MSE** and **R²** using **MLflow**  
- Compare runs and identify the **best model**  

---

## 🧠 Understanding the Problem Types

### 📊 Classification (Predict a Category)

Examples:
- Email → Spam or Not Spam  
- Customer → Will buy or not buy  
- Image → Cat, Dog, or Bird  
- Flower → Setosa, Versicolor, Virginica  
- Disease → Positive or Negative  

👉 **Output is a label / class**

---

### 📈 Regression (Predict a Number)

Examples:
- House price → ₹45,00,000  
- Temperature tomorrow → 32.5°C  
- Sales next month → 1200 units  
- Salary prediction → ₹8.5 LPA  
- Stock price → ₹1,234.50  

👉 **Output is a continuous number**

---

## 🤖 Common Algorithms

### Classification Algorithms
- Logistic Regression  
- RandomForestClassifier  
- KNN Classifier  
- SVM (Classifier)  
- XGBoost Classifier  
- Neural Networks (for classification)  

### Regression Algorithms
- Linear Regression  
- RandomForestRegressor  
- XGBoost Regressor  
- Ridge / Lasso  
- SVR (Support Vector Regressor)  
- Neural Networks (for regression)  

---

## 🧭 When to Use What?

> Use **classification** when you want to predict a **category**.  
> Use **regression** when you want to predict a **number**.

---

## 🔧 Hyperparameter Tuning Guide

### For RandomForest (Classification)
Start by tuning:
- `n_estimators`
- `max_depth`
- `min_samples_leaf`

### For XGBoost (Regression)
Start by tuning:
- `n_estimators`
- `max_depth`
- `learning_rate`
- `subsample`

---

## 🚀 Summary

This repository demonstrates:
- How to run **multiple ML experiments** using MLflow  
- How to **track parameters, metrics, and models**  
- How to compare **classification vs regression** use cases  
- How to perform **hyperparameter tuning** and select the best model  
