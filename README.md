# Cancer Detection: Model Selection, Tuning, and Validation

This project applies supervised machine learning techniques to predict breast cancer diagnoses using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.

## 🧪 Objective
Build and evaluate multiple classification models (Logistic Regression, k-NN, Decision Tree, SVM) using nested cross-validation and finalize the most reliable model based on predictive performance.

## 📊 Methods Used
- Data preprocessing and exploration
- Nested Cross-Validation (5x5) for model selection
- Hyperparameter tuning with GridSearchCV
- Evaluation using accuracy, recall, precision, F1 score, ROC AUC, and lift curve

## ✅ Final Model
- **Model:** Support Vector Machine (SVM) with RBF kernel
- **Hyperparameters:** `C=0.5`, `gamma=0.1`, `class_weight='balanced'`
- **Performance on Test Set:**
  - Accuracy: 92.98%
  - Recall: 96.83%
  - Precision: 85.92%
  - F1 Score: 91.04%
  - AUC: 0.99

## 📁 Files
- `Cancer_Predictions.ipynb` — Full notebook with modeling, evaluation, and interpretation
- `README.md` — Project overview and results summary

## 📦 Dataset
Wisconsin Diagnostic Breast Cancer dataset  
Available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/oliviaboe3/cancer-prediction-model.git`
2. Install dependencies (e.g., `pandas`, `sklearn`, `matplotlib`, `numpy`)
3. Open `Cancer_Predictions.ipynb` in Jupyter and run all cells

## 📬 Contact
Created by Olivia Boe – feel free to reach out!
