# Titanic Dataset

My attempt at the classic Kaggle competition
[Titanic – Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic).

## About the competition 
- [Overview](https://www.kaggle.com/competitions/titanic/overview)
- [About the data](https://www.kaggle.com/competitions/titanic/data)

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

# Step by step instructions

After you have all requirements or environment up and running you should

### 1. Create your notebooks

However many you want. Use an old project. Just get some notebooks.

### 2. Create a "_quarto.yml" file
Adapt the structure of [this file](_quarto.yml) according to your notebooks.

### 3. Create an "index.md" file
It will be your page's index.
Adapt the structure of [this file](index.md) according to your notebooks.

### 4. Install Quarto (if you haven't already done it)

```bash
pip install quarto-cli
```

### 5. Render the site locally

```bash
quarto render
```

### 6. Commit

```bash
git add .
git commit -m "some message"
git push origin
```

### 7. Publish the site

```bash
quarto publish gh-pages
```

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