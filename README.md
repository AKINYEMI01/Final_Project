# Final_Project
Preidicting Readmission in Dabietic Patients
# Overview
This project applies machine learning to predict 30-day readmission in diabetic patients using the Diabetes 130-US hospitals dataset
.
We compare traditional classifiers (Logistic Regression, Decision Tree, Random Forest, KNN) with boosting models (Gradient Boosting, XGBoost, LightGBM, CatBoost).

# Workflow

Preprocessing: cleaning, one-hot encoding, handling missing values.

EDA: class imbalance, demographics, inpatient visits, correlations.

Balancing: SMOTE applied to training data.

Models: train + tune 8 classifiers with RandomizedSearchCV.

Evaluation: Accuracy, Precision, Recall, F1-score, ROC, confusion matrices.

# Results

Best model: LightGBM (F1 ≈ 0.596).

Boosting models outperformed traditional classifiers.

Key predictors: inpatient visits, emergency visits, insulin use, age.
