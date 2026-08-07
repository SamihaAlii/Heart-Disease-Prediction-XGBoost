# Heart-Disease-Prediction-XGBoost
# ❤️ Heart Disease Prediction using XGBoost

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-green)
![License](https://img.shields.io/badge/License-MIT-blue)


## 📌 Overview

This project predicts whether a patient has heart disease using the XGBoost classifier. It demonstrates a complete machine learning workflow from preprocessing to model evaluation.

## 📊 Model Performance

| Metric | Score |
|--------|------:|
| Accuracy | 75.93% |
| Precision | 74.19% |
| Recall | 85.19% |
| F1 Score | 79.31% |
| ROC-AUC | 0.92 |

## Workflow

1. Load Dataset
2. Data Preprocessing
3. Target Encoding
4. Train-Test Split
5. Build Scikit-Learn Pipeline
6. Train XGBoost Model
7. Evaluate Model
8. Visualize Results
9. Interpret Feature Importance
## 📂 Dataset

- Heart Disease Dataset
- Source: Kaggle (UCI Heart Disease Dataset)


## 🚀 Features

- Data preprocessing
- Target encoding
- Train-test split
- Scikit-Learn Pipeline
- XGBoost Classifier
- Feature Importance Analysis
- ROC Curve
- Confusion Matrix Heatmap

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn


## ROC Curve

![ROC Curve](images/roc_curve.png)

## Feature Importance

![Feature Importance](images/feature_importance.png)

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

## 📁 Files

- `Heart_Disease_Prediction_XGBoost.ipynb`
- `heart_disease.csv`
- `requirements.txt`

- ## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow for predicting heart disease using XGBoost.

The model achieved a **ROC-AUC score of 0.92**, indicating excellent discriminative performance. Feature importance analysis showed that **Chest Pain Type**, **Thallium**, and **Number of Vessels Fluoroscopy** were among the most influential predictors.

Future improvements include hyperparameter tuning, cross-validation, model explainability using SHAP, and deployment with Streamlit.
