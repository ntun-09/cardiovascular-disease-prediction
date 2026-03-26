# Cardiovascular Disease Prediction

Machine learning project for predicting cardiovascular disease risk using ensemble models.

## Problem
Cardiovascular disease is a leading cause of death worldwide.  
This project aims to build a predictive model to identify high-risk patients based on clinical features.

## Approach
- Data preprocessing & winsorization
- Feature engineering & interaction terms
- Multicollinearity analysis (VIF)
- Model training:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Ensemble learning (weighted soft voting)

## Evaluation
- ROC-AUC (primary metric)
- Brier Score (probability calibration)
- Calibration curve
- Threshold optimization (Youden’s J)

## Results
- Improved performance using ensemble methods
- Well-calibrated probability predictions
- Effective risk stratification based on clinical factors

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- Pandas, NumPy, Matplotlib

## Author
ntun-09
