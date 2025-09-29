# Heart Disease Prediction (Cleveland Dataset)

This repository contains my CSCA 5622 Supervised Learning Final Project.  
It uses the **Cleveland Heart Disease dataset** from the UCI Machine Learning Repository to predict the presence of heart disease using various supervised learning models.

## Contents
- `CSCA5622_heart_cleveland.ipynb` — Jupyter notebook with full analysis, EDA, model building, tuning, and evaluation.

## Dataset
- **Source:** [UCI ML Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Subset used:** Cleveland Clinic (303 records, 14 attributes).
- **License:** CC BY 4.0.

## Project Summary
1. **Problem:** Predict whether a patient has heart disease (binary classification).
2. **Data Cleaning:** Converted `?` to NaN, coerced types, binarized target.
3. **EDA:** Histograms, correlations, and boxplots to identify important features.
4. **Modeling:** Compared Logistic Regression, SVC (RBF), Random Forest, Gradient Boosting using pipelines.
5. **Tuning:** Grid-searched SVC hyperparameters for optimal ROC AUC.
6. **Evaluation:** Reported metrics and plotted confusion matrix and ROC curve on a held-out test set.

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/heart-disease-prediction.git
   cd heart-disease-prediction
2. pip install -r requirements.txt
3. jupyter notebook CSCA5622_heart_cleveland.ipynb
