# Customer Purchase Prediction

This project focuses on building a machine learning model to predict whether an individual is likely to become a customer based on demographic and financial information. The work is framed as a marketing analytics use case where predictive modeling supports customer targeting and acquisition decisions.

---

## Problem Statement

Marketing teams often need to prioritize prospects with the highest likelihood of conversion in order to use resources efficiently. This project addresses that need by formulating the problem as a binary classification task.

---

## Dataset

The dataset contains structured customer information, including:

- Age  
- Marital or social status (encoded)  
- Gender (binary encoded)  
- Car ownership  
- Income level  

The target variable represents the purchase decision (0 = not a customer, 1 = customer).

---

## Approach

The workflow follows a standard machine learning pipeline:

1. Data loading and validation  
2. Basic exploratory checks and missing value analysis  
3. Feature and target separation  
4. Train–test split  
5. Logistic Regression modeling  
6. Evaluation using classification results  

Logistic Regression was chosen due to its interpretability and suitability for business-facing analysis.

---

## Model Evaluation

Model performance is evaluated on a hold-out test set using classification outputs.  
The results are interpreted not only from a predictive standpoint but also in terms of their implications for marketing decision-making.

---

## Key Findings

- Income level and asset ownership are strong indicators of purchase likelihood  
- An interpretable model helps explain why certain customers are more likely to convert  
- The model provides a reliable baseline for customer targeting strategies  

---

## Business Value

This project demonstrates how predictive modeling can be used to:

- Identify high-potential customers  
- Reduce ineffective marketing outreach  
- Support data-driven acquisition strategies  

---

## Future Work

Possible improvements include:

- ROC-AUC analysis and threshold tuning  
- Feature scaling  
- Comparison with tree-based models  
- Hyperparameter optimization  

---

## Tools

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Author

Akmal
