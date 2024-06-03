Dataset link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

In this notebook, we explored the problem of credit card fraud detection using several machine learning models, including Random Forest, AdaBoost, CatBoost, XGBoost, LightGBM, and Logistic Regression. Our objective was to identify the best model for detecting fraudulent transactions with high accuracy and robustness.

## Key Findings:

### Random Forest:
- **Accuracy**: 0.9188
- **ROC AUC**: 0.9704
- **Precision, Recall, F1-Score**:
  - **Class 0 (Not Fraud)**: Precision = 0.89, Recall = 0.96, F1-Score = 0.92
  - **Class 1 (Fraud)**: Precision = 0.96, Recall = 0.88, F1-Score = 0.91

### AdaBoost:
- **Accuracy**: 0.9137
- **ROC AUC**: 0.9625
- **Precision, Recall, F1-Score**:
  - **Class 0 (Not Fraud)**: Precision = 0.86, Recall = 0.99, F1-Score = 0.92
  - **Class 1 (Fraud)**: Precision = 0.99, Recall = 0.84, F1-Score = 0.91


### XGBoost:
- **Accuracy**: 0.9188
- **ROC AUC**: 0.9727
- **Precision, Recall, F1-Score**:
  - **Class 0 (Not Fraud)**: Precision = 0.88, Recall = 0.97, F1-Score = 0.92
  - **Class 1 (Fraud)**: Precision = 0.97, Recall = 0.87, F1-Score = 0.91

### LightGBM:
- **Accuracy**: 0.9188
- **ROC AUC**: 0.9746
- **Precision, Recall, F1-Score**:
  - **Class 0 (Not Fraud)**: Precision = 0.88, Recall = 0.97, F1-Score = 0.92
  - **Class 1 (Fraud)**: Precision = 0.97, Recall = 0.87, F1-Score = 0.91

## Summary

Based on our evaluation metrics, **LightGBM** emerged as the best model for detecting credit card fraud. It achieved the highest ROC AUC score of **0.9746**, indicating a strong ability to distinguish between fraudulent and non-fraudulent transactions. Additionally, LightGBM, along with Random Forest and XGBoost, provided the highest accuracy of **0.9188**.

Each model demonstrated robust performance with slight variations in precision, recall, and F1-score. These metrics are crucial for understanding the trade-offs between identifying fraudulent transactions and minimizing false positives.
