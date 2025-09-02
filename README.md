
## Diabetes Risk Prediction System

A production‑ready scikit‑learn pipeline that predicts diabetes risk from routinely collected clinical data (e.g., BMI, age, blood pressure) and converts model outputs into actionable Low/Medium/High risk tiers for screening, triage, and population health programs.


## Features
Problem: Supervised classification to estimate likelihood of diabetes for early detection and targeted follow‑up.

Robust preprocessing: Handle invalid zeros as missing, impute non‑zero medians, scale numerics, encode categoricals, address class imbalance with class‑weighted models.

Feature engineering: BMI category, age groups, glucose risk level, composite Risk_Score, and ratios (glucose/BMI, insulin/glucose).

Models: Logistic Regression and Random Forest in a unified pipeline; grid search for Random Forest hyperparameters.

Evaluation: Stratified split; AUC, precision, recall, F1, sensitivity/specificity, confusion matrix, and ROC‑based threshold selection.

Interpretability: Feature importance and thresholded risk tiers with recommendations for confirmatory testing.

## Results Snapshot
Reference runs show AUC around 0.83 (dataset/seed dependent).

Sensitivity/specificity trade‑offs are documented with ROC and confusion matrix.


## Real‑World Use
Primary care: Automated risk at routine visits to surface early‑stage cases.

Population health: Risk stratification for targeted outreach and preventive programs.

Clinical decision support: Standardized recommendations tied to risk tiers.
