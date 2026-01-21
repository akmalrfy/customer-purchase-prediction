# Customer Purchase Prediction

This project builds a machine learning model to predict customer purchase likelihood using demographic and financial data. The work is framed as a real-world marketing analytics case where predictive modeling supports business decision-making.

---

## Problem Context

In customer acquisition, marketing teams must focus on prospects with the highest probability of conversion. This project formulates the problem as a binary classification task to support efficient and data-driven targeting strategies.

---

## Data Overview

The dataset consists of structured customer attributes:
- Age
- Marital or social status (encoded)
- Gender (binary encoded)
- Car ownership
- Income level

The target variable indicates whether an individual becomes a customer.

---

## Methodology

The modeling workflow includes:
- Data validation and preprocessing
- Feature and target separation
- Train–test split
- Logistic Regression modeling
- Performance evaluation on unseen data

Logistic Regression is selected for its interpretability, allowing insights to be communicated clearly to non-technical stakeholders.

---

## Evaluation and Insights

Model evaluation is performed using classification results on the test set.  
Analysis shows that income-related features and asset ownership contribute strongly to purchase probability.

Beyond prediction accuracy, the model is designed to explain *why* certain customers are more likely to convert.

---

## Business Impact

The model demonstrates how data science can:
- Improve customer targeting efficiency
- Reduce wasted marketing spend
- Support strategic acquisition decisions

---

## Future Enhancements

- ROC-AUC and threshold optimization
- Feature scaling
- Model comparison with tree-based algorithms
- Hyperparameter tuning

---

## Tools

Python, Pandas, NumPy, Scikit-learn

---

## Author

Akmal
