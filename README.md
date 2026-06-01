# Titanic Survival Prediction using Machine Learning

## Overview

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset was cleaned, preprocessed, and analyzed before training multiple classification models. The goal was to identify the factors that influenced survival and compare the performance of different machine learning algorithms.

This project was completed as part of the Pluto Academy AI & Machine Learning Internship Program.

---

## Dataset

Source: Titanic Dataset (Kaggle)

Dataset Information:

- Total Records: 891 passengers
- Features: Passenger information such as age, gender, ticket class, fare, family details, etc.
- Target Variable: Survived
  - 0 = Did Not Survive
  - 1 = Survived

---

## Objectives

- Clean and preprocess the dataset
- Handle missing values
- Perform feature engineering
- Train multiple machine learning models
- Evaluate model performance using classification metrics
- Compare models and identify the best performer
- Analyze important features affecting survival

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing values handled appropriately
- Irrelevant features removed
- Categorical variables encoded
- Feature scaling applied where necessary
- Dataset split into training and testing sets (80/20)

---

## Feature Engineering

Additional features were created to improve model performance:

### FamilySize

Represents the total number of family members traveling together.

### IsAlone

Indicates whether a passenger was traveling alone or with family.

These engineered features helped capture passenger relationships and travel patterns.

---

## Exploratory Data Analysis

The dataset was explored to understand:

- Survival distribution
- Gender-wise survival rates
- Passenger class impact on survival
- Age distribution
- Correlations between features

Visualizations were created to identify patterns and trends within the dataset.

---

## Machine Learning Models

Three machine learning algorithms were trained and evaluated:

### 1. Logistic Regression

A linear classification model commonly used as a baseline for binary classification problems.

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve predictive performance.

### 3. K-Nearest Neighbors (KNN)

A distance-based classification algorithm that predicts outcomes based on nearby data points.

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

A comparison table was created to compare model performance and identify the best-performing model.

---

## Best Model Analysis

The best-performing model was selected based on evaluation metrics.

Further analysis included:

- Confusion Matrix
- Feature Importance Analysis
- Performance Interpretation

---

## Key Findings

- Passenger gender significantly influenced survival.
- First-class passengers had higher survival rates.
- Traveling alone affected survival probability.
- Family-related features improved prediction accuracy.
- Ensemble methods such as Random Forest performed strongly on the dataset.

---

## Limitations

- The dataset contains only historical Titanic passenger records.
- Some potentially useful information was unavailable or incomplete.
- Model performance may be improved through hyperparameter tuning and additional feature engineering.

---

## Files

- `titanic_ml.ipynb` – Complete machine learning notebook
- `titanic_ml.pdf` – Exported project report
- `train.csv` – Dataset used for training and evaluation

---

## Author

**Siddharth**




