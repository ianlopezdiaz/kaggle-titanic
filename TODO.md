# TODO

---

## Exploratory Data Analysis

### Objective
Understand the structure of the dataset and identify factors influencing survival.

### Sections

- Dataset overview
- Missing values analysis
- Target distribution (Survived vs Not Survived)
- Survival by:
  - Sex
  - Passenger class (Pclass)
  - Age
  - Embarked location
- Feature correlations
- Key insights and hypotheses

---

## Feature Engineering and Data Preparation

### Objective
Transform raw data into a model-ready dataset.

### Sections

- Handling missing values
- Encoding categorical variables
- Feature creation:
  - FamilySize
  - IsAlone
  - Title extraction from Name
- Feature transformations (scaling / normalization if needed)
- Train/test consistency checks

---

## Model Development and Evaluation

### Objective
Train, compare, and evaluate multiple classification models.

### Sections

- Baseline model (Logistic Regression)
- Additional models:
  - Naive Bayes
  - KNN
  - SVM
  - Decision Tree
  - Random Forest
  - Gradient Boosting (optional)
- Cross-validation strategy
- Evaluation metrics:
  - Accuracy
  - Precision / Recall
  - F1-score
  - ROC-AUC
- Model comparison table
- Final model selection
- Kaggle submission generation