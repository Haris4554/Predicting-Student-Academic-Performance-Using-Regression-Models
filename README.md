# Student Performance Prediction Using Machine Learning

## Overview

This project predicts students' final academic performance (G3) using demographic, social, academic, and behavioral factors.

The project follows a complete Machine Learning workflow including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Feature Importance Analysis

---

## Dataset

- Dataset: Student Performance Dataset
- Records: 395 Students
- Features: 32 Input Variables
- Target Variable: G3 (Final Grade)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Models Trained

| Model | MAE | RMSE | R² |
|---------|---------|---------|---------|
| Linear Regression | 1.647 | 2.378 | 0.724 |
| Random Forest | 1.192 | 1.996 | 0.806 |
| XGBoost | 1.171 | 2.018 | 0.801 |

### Best Model

Random Forest Regressor

- MAE: 1.192
- RMSE: 1.996
- R² Score: 0.806

---

## Key Findings

- G2 was the strongest predictor of final grades.
- Previous failures negatively impacted student performance.
- Study time positively influenced grades.
- Absences showed non-linear importance.
- Parental education contributed positively to academic outcomes.

---

## Future Improvements

- Train models without G1 and G2 to avoid feature leakage.
- Hyperparameter tuning.
- Deploy using Streamlit.
