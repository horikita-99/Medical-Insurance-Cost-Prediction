# Medical-Insurance-Cost-Prediction

This project aims to predict medical insurance charges based on an individual’s demographic and lifestyle attributes. Using regression techniques, we analyze how factors like age, BMI, smoking status, and region influence healthcare costs.

The project also compares linear and tree-based models to evaluate performance and understand non-linear relationships in the data.

---
## Objective

To build and compare regression models that accurately predict medical insurance costs and identify key factors that significantly impact charges.

---
## Dataset Information

Source: Kaggle – Medical Cost Personal Dataset

Target Variable: charges (medical insurance cost)

---
## Features:

- age – Age of the individual

- sex – Gender

- bmi – Body Mass Index

- children – Number of dependents

- smoker – Smoking status

- region – Residential region
---
## Project Workflow

1. Exploratory Data Analysis (EDA)

2. Handling categorical variables using One-Hot Encoding

3. Feature scaling for numerical features

4. Train-test split

5. Model training

6. Hyperparameter tuning

7. Model evaluation

---
## Models Implemented

- Linear Regression

- Decision Tree Regressor (Untuned & Tuned)

- Random Forest Regressor (Tuned using GridSearchCV)

---
## Evaluation Metrics

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

Models were compared based on prediction accuracy and generalization performance.

---
## Key Insights

Smoking status has a significant impact on insurance charges.

Tree-based models capture non-linear relationships better than linear regression.

Hyperparameter tuning improves Random Forest performance and reduces overfitting.

---
## Tech Stack

Python (Jupyter Notebook)

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

---
## Conclusion

This project demonstrates practical regression modeling, feature engineering, and model comparison techniques to solve a real-world cost prediction problem.
