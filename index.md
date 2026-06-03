# Kaggle Titanic

This is my attempt at the classic Kaggle competition
[Titanic – Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic).

The goal of this tutorial is to walk through a complete supervised **classification** workflow on a real Kaggle dataset: from exploratory data analysis, through data cleaning and feature engineering, to training and comparing multiple classification models and generating a Kaggle submission.

For installation, environment setup, and project structure, see the repository's [README](README.md).

---

## What you will learn

- How to frame a supervised classification problem using a real Kaggle competition. [web:6]
- How to explore the dataset, handle missing values, engineer useful features, and prepare data for classification models.
- How to train, evaluate, and compare a range of classifiers (logistic regression, Naive Bayes, KNN, SVM, trees, ensembles, and neural networks) and generate a Kaggle submission.

---

## Index

### 1. **[Exploratory data analysis](1_EDA.ipynb)**  
Understand the problem, inspect the raw data, and build intuition about which features are related to survival on the Titanic.

### 2. **[Data cleaning and feature engineering](2_feature_engineering.ipynb)**  
Handle missing values, encode categorical variables, create new features (e.g., family size, title from name), and prepare a modeling-ready dataset.

### 3. **[Modeling, evaluation, and submission](3_modeling.ipynb)**  
Train baseline and advanced classifiers, evaluate them with appropriate metrics (accuracy, ROC AUC, confusion matrix), and generate a Kaggle submission file.