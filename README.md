# Loan-Eligibility-Prediction
Internship Task 1 — Loan Eligibility Prediction  
**Author:** Ibadoo

## Overview
Predict whether an applicant's loan will be approved using EDA, Logistic Regression and Random Forest.

## Files
- `notebook.ipynb` — main notebook with EDA, modeling, visuals.
- `loan.csv` — dataset (download separately from Kaggle).
- `requirements.txt`

## Dataset
Download from Kaggle: [Loan Predication / Loan Prediction dataset (Kaggle)](https://www.kaggle.com/datasets/ninzaami/loan-predication). :contentReference[oaicite:1]{index=1}

## How to run
1. Create a conda/venv with `pip install -r requirements.txt`  
2. Place `loan.csv` in the notebook folder.  
3. Open `notebook.ipynb` and run cells top-to-bottom.

## Notes
- I compared Logistic Regression and Random Forest; Random Forest performed best.
- Next improvements: SMOTE for imbalance, LightGBM, model explainability (SHAP).
