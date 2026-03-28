# Breast Cancer Classification

## Overview
This project builds and compares Logistic Regression and Random Forest models for classifying breast cancer tumors as malignant or benign. It demonstrates a complete ML pipeline including data preprocessing, model training, hyperparameter tuning, evaluation, and visualization.

## Features
- Data preprocessing and scaling
- Train-test split with stratification
- Logistic Regression and Random Forest models
- Hyperparameter tuning for Random Forest
- Cross-validation for model reliability
- Model evaluation: Accuracy, Confusion Matrix, Classification Report, ROC-AUC
- Feature importance analysis and visualization
- Model saving using joblib

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook:
   notebooks/cancer_classification.ipynb

## Key Learnings
- Building an end-to-end ML pipeline
- Model comparison and hyperparameter tuning
- Evaluation using multiple metrics
- Feature importance analysis
- ROC curve visualization

## Future Improvements
- Test additional models (SVM, Gradient Boosting)
- Optimize hyperparameters further
- Deploy models for production predictions
