# 🔬 Breast Cancer Classification

A machine learning project that classifies breast cancer tumors as **malignant or benign** using the Wisconsin Breast Cancer dataset from scikit-learn.

---

## 📌 Overview

This project compares two classification models:
- **Logistic Regression** — simple, interpretable, and efficient
- **Random Forest** — ensemble method with hyperparameter tuning via GridSearchCV

Both models are evaluated using accuracy, classification reports, confusion matrices, and ROC curves.

---

## 📊 Results

| Model | Train Accuracy | Test Accuracy |
|---|---|---|
| Logistic Regression | 98.9% | 98.25% |
| Random Forest | 100% | 95.61% |

**Key finding:** Logistic Regression slightly outperforms Random Forest on the test set, suggesting the data is largely linearly separable after standardization.

---

## 🗂️ Project Structure
```
├── cancer_classification.ipynb  # Main notebook
├── requirements.txt             # Dependencies
├── models/                      # Saved model files (.pkl)
└── README.md
```

---

## 🛠️ Tech Stack

- Python 3.x
- scikit-learn
- pandas, numpy
- matplotlib
- joblib

---

## 🚀 Getting Started
```bash
git clone https://github.com/biruppal/breast-cancer-classification.git
cd breast-cancer-classification
pip install -r requirements.txt
jupyter notebook cancer_classification.ipynb
```

---

## 📉 Visualizations

- ROC Curve comparing both models
- Top 10 Feature Importances from Random Forest

---

## 🧠 Key Insights

- **Worst area**, **worst perimeter**, and **worst concave points** are the most predictive features
- Logistic Regression is a strong baseline for this dataset
- Random Forest provides feature interpretability through importance scores
