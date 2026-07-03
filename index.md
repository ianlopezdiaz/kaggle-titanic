# Titanic: End-to-End Classification Case Study

This project demonstrates a complete machine learning workflow using the famous
[Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic).
The objective is to predict passenger survival from structured tabular data
while showcasing the techniques commonly used in real-world classification
problems.

Originally introduced as a Kaggle competition, the Titanic dataset has become
one of the most widely used benchmarks for learning supervised classification.
Its combination of numerical and categorical features, missing values, and
opportunities for feature engineering makes it an excellent case study for
building and evaluating classification models.

The goal of this tutorial is to introduce the fundamental concepts of
supervised **classification** through a complete end-to-end machine learning
workflow on a real dataset. The analysis covers exploratory data analysis,
data cleaning, feature engineering, model development, model evaluation, and
the generation of a Kaggle competition submission.

For installation, environment setup, and project structure, see the repository's
[README](README.md).

---

## What you will learn

- How to frame a supervised classification problem using a real Kaggle competition.
- How to explore the dataset, handle missing values, engineer useful features, and prepare data for classification models.
- How to train, evaluate, and compare a range of classifiers, including logistic regression, Naive Bayes, k-nearest neighbors, support vector machines, decision trees, ensemble methods, and neural networks.
- How to generate predictions and create a valid Kaggle submission.

---

## Index

### 1. **[Exploratory data analysis (EDA)](01_EDA.ipynb)**
Understand the prediction task, explore the dataset, and build intuition about which passenger characteristics are associated with survival on the Titanic.

### 2. **[Data cleaning and feature engineering](02_feature_engineering.ipynb)**
Handle missing values, encode categorical variables, create new features (such as family size and passenger title), and prepare a model-ready dataset.

### 3. **[Modeling, evaluation, and submission](03_modeling.ipynb)**
Train baseline and advanced classifiers, evaluate their performance using appropriate metrics (accuracy, ROC-AUC, confusion matrix, and classification reports), compare results across models, and generate a Kaggle submission file.