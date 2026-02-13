# Titanic Model Comparison & Best Model Selection

## Task Overview
This project is part of **AI & ML Internship – Task 14**, focusing on comparing multiple machine learning models and selecting the best-performing model based on evaluation metrics.

---

## Dataset
- **Titanic Dataset**
- Loaded directly from **scikit-learn / OpenML**
- Target variable: `survived`

---

## Data Preprocessing
- Selected important features: `pclass`, `sex`, `age`, `fare`, `embarked`
- Handled missing values using **median** and **mode**
- Encoded categorical variables using **One-Hot Encoding**
- Converted target labels to integers
- Applied **Standard Scaling** for Logistic Regression and SVM

---

## Models Compared
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)

---

## Evaluation Metrics
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

All results were stored in a **model comparison table** and visualized using a **bar chart**.

---

## Best Model Selection
- **Random Forest Classifier** performed best with higher test accuracy and better generalization.
- Overfitting was checked by comparing train vs test accuracy.

---

## Saved Model
The best-performing model was saved using `joblib`:
