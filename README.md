# Logistic Regression Project

## Problem Statement
Predict whether a person's income is >50K or <=50K using classification techniques.

## Dataset
Adult Income Dataset

## Techniques Used
- Data preprocessing
- Encoding & scaling
- SMOTE (handling class imbalance)
- Threshold tuning
- Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- RFE (feature selection experiment)

## Results
- Multiple models (Logistic Regression, Decision Tree, Random Forest) were evaluated
- All models showed similar performance with F1-score around ~0.69–0.70
- Threshold tuning affected precision-recall tradeoff but did not significantly improve overall performance
- No single model significantly outperformed others
- This indicates that model performance is constrained by the dataset rather than the choice of algorithm

## Conclusion
Model performance plateaued across models and thresholds, indicating that further improvement depends on feature engineering rather than model selection.
