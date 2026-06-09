# Titanic: End-to-End Classification Case Study

This project demonstrates a complete machine learning workflow using the famous
[Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic).
The objective is to predict passenger survival from structured tabular data
while showcasing the techniques commonly used in real-world classification
problems.

The goal of this tutorial is to introduce the fundamental concepts of
supervised **classification** through a complete end-to-end machine learning
workflow on a real Kaggle dataset. The analysis covers exploratory data
analysis, data cleaning, feature engineering, model development, model
evaluation, and the generation of a Kaggle competition submission.

## About the competition 
- [Overview](https://www.kaggle.com/competitions/titanic/overview)
- [About the data](https://www.kaggle.com/competitions/titanic/data)

---

# Project structure

This project is divided into Jupyter notebooks that follow a complete supervised **classification** workflow:

### 1. **[Exploratory data analysis](1_EDA.ipynb)**  
Understand the problem, inspect the raw data, and build intuition about which features are related to survival on the Titanic.

### 2. **[Data cleaning and feature engineering](2_feature_engineering.ipynb)**  
Handle missing values, encode categorical variables, create new features (e.g., family size, title from name), and prepare a modeling-ready dataset.

### 3. **[Modeling, evaluation, and submission](3_modeling.ipynb)**  
Train baseline and advanced classifiers, evaluate them with appropriate metrics (accuracy, ROC AUC, confusion matrix), and generate a Kaggle submission file.


## Algorithms I plan to cover

- Logistic Regression
- Naive Bayes
- K-Nearest Neighbours (KNN)
- Support-Vector Machine (SVM)
- Decision Tree
- Bagging Decision Tree (Ensemble Learning I)
- Boosted Decision Tree (Ensemble Learning II)
- Random Forest (Ensemble Learning III)
- Voting Classification (Ensemble Learning IV)
- Linear Discriminant Analysis
- Neural Networks (Multilayer Perceptron)

---

# Getting started to do this locally

### Install requirements:

```bash
pip install -r requirements.txt
```

or, if you prefer

### Clone my environment:

```bash
conda env create -f environment.yml
```

You can change `name` to anything you like in the `environment.yml` file
if you already have an Anaconda/Miniconda environment with this name or
you simply want to use a different name for whatever reason.

---

# Build the site with Quarto

### 1. Install [Quarto](https://quarto.org/) (if you haven't already done it)
```bash
pip install quarto-cli
```

After you have all requirements or environment up and running
and can modify the project anyway you feel like and 
to preview the site just do

```bash
quarto preview
```

After you are finished just

### 2. Render the site locally
```bash
quarto render
```

### 3. Commit/Push
```bash
git add .
git commit -m "some message"
git push origin
```

### 4. Publish the site
```bash
quarto publish gh-pages
```

---

