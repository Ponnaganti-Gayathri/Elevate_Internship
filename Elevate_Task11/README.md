# Task 11: SVM – Breast Cancer Classification

## Objective
To classify breast cancer tumors as malignant or benign using Support Vector Machine (SVM).

## Dataset
- Sklearn Breast Cancer Dataset (`load_breast_cancer()`)

## Steps Performed
- Loaded and explored dataset
- Applied StandardScaler for feature normalization
- Trained SVM with linear and RBF kernels
- Tuned hyperparameters using GridSearchCV
- Evaluated model using accuracy, confusion matrix, and classification report
- Plotted ROC curve and calculated AUC score
- Saved trained model pipeline

## Tools Used
- Python
- Scikit-learn
- Matplotlib
- Seaborn

## Output
- ROC Curve with AUC score
- Confusion Matrix
- Saved model file (`svm_breast_cancer_model.pkl`)

## Result
Achieved high classification accuracy using tuned RBF SVM.
