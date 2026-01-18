# Credit-risk-default-prediction
# Credit Risk Default Prediction (Retail Credit Lifecycle)

## Overview
This project builds a credit risk model to predict the probability of loan default using real-world Lending Club loan data. The goal is to support data-driven credit approval decisions across the retail credit lifecycle.

The project follows an end-to-end data science workflow: business understanding, exploratory data analysis, feature engineering, model development, evaluation, and interpretation.

---

## Business Problem
Financial institutions must assess the risk of loan applicants accurately to minimize defaults while maintaining profitability.

**Objective:**  
Predict whether a borrower will default on a loan using borrower and loan characteristics.

---

## Dataset
- Source: Lending Club loan data
- Target Variable: `loan_status`
  - Default (1): Charged Off / Default
  - Non-Default (0): Fully Paid

---

## Methodology
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
   - Logistic Regression (baseline credit model)
   - Random Forest
5. Model Evaluation
   - ROC-AUC
   - Precision, Recall
   - Confusion Matrix
6. Model Interpretation & Business Insights

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## Results
- Identified key drivers of loan default such as interest rate, debt-to-income ratio, and loan grade.
- Logistic Regression provided strong interpretability for credit decisions.
- Tree-based models improved predictive performance while maintaining stability.

---

## Business Impact
The model enables:
- Improved risk-based loan approval decisions
- Better identification of high-risk borrowers
- Support for data-driven credit lifecycle management

---

## Future Improvements
- Add model explainability using SHAP
- Incorporate model monitoring and drift detection
- Extend to Probability of Default (PD) scorecard development
