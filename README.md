# Loan Default Prediction

This project predicts the probability of loan default using machine learning. It combines financial domain knowledge with data analytics to provide actionable insights for lenders and fintechs.

## Objective
To build a predictive model that identifies high-risk borrowers early, helping lenders reduce losses and improve credit-risk management.

## Dataset
Dataset: [Kaggle Loan Dataset](https://www.kaggle.com/datasets/nikhil1e9/loan-default)
- Key features include:
  - Borrower demographics
  - Payment history
  - Loan-to-income ratio
  - Cash-flow variability

## Approach
1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering (ratios, interaction terms)
   - Encoding categorical variables

2. **Modeling**
   - XGBoost classifier
   - Hyperparameter tuning
   - Train-validation split

3. **Evaluation**
   - ROC-AUC as primary metric
   - SHAP values for feature importance and interpretability

4. **Key Findings**
   - Most important predictors: past delinquencies, loan-to-income ratio, cash-flow variability
   - Model AUC: 0.75
   - Insights can guide better risk management

