# Random Forest – Credit Card Fraud Detection

## Objective
To detect fraudulent credit card transactions using Random Forest and handle highly imbalanced data.

## Dataset
Kaggle Credit Card Fraud Dataset  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Steps Performed
- Loaded and explored dataset
- Analyzed class imbalance
- Split data using stratified sampling
- Trained Logistic Regression as baseline
- Trained Random Forest model
- Evaluated using Precision, Recall, F1-score
- Plotted feature importance
- Saved trained model using joblib

## Evaluation Metrics
Accuracy is avoided due to class imbalance.  
Used:
- Precision
- Recall
- F1-score

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Outcome
Random Forest performed better than baseline model and successfully detected fraud cases.
