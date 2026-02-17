# Loan Approval Prediction

## Problem

The objective of this project was to predict whether a loan application would be approved based on applicant characteristics.

This is a binary classification problem with potential class imbalance.

## Approach

- Data inspection and cleaning
- Handling missing and anomalous values
- Feature engineering
- Exploratory data analysis
- Model development and comparison

Models implemented: 
- Logistic Regression (baseline, interpretable)
- Random Forest (non-linear comparison)
- XGBoost (gradient boosting model)

Evaluation metrics:
- Accuracy
- ROC-AUC
- Confusion matrix analysis

## Key Insights

Credit score (CIBIL) was indentified as a strong predictor. 

To evaluate model robustness, models were also trained without the CIBIL score to assess:

- Dependence on a dominant feature
- Performance degradation
- Generalization ability without credit score history information

This allowed comparison between full-feature and reduced-feature models.