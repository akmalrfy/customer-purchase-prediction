Customer Purchase Prediction using Logistic Regression
📌 Overview

This project simulates a real-world marketing analytics use case to predict whether an individual is a potential customer based on demographic and financial attributes.

The objective is to support data-driven customer targeting using an interpretable machine learning model.

🧠 Business Problem

Marketing teams need to identify high-potential customers efficiently in order to:

Optimize acquisition costs

Improve conversion rates

Reduce ineffective marketing efforts

This problem is formulated as a binary classification task.

📊 Dataset

The dataset contains customer demographic and financial information:

Feature	Description
Usia	Age of the individual
Status	Marital or social status (encoded)
Kelamin	Gender (binary encoded)
Memiliki_Mobil	Car ownership (0/1)
Penghasilan	Income level

Target Variable

Purchase decision (0 = No, 1 = Yes)

🛠️ Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

🔍 Methodology

Data loading and validation

Missing value analysis

Feature and target separation

Train-test split

Logistic Regression modeling

Model evaluation using classification metrics

📈 Model Evaluation

The model performance was evaluated using classification analysis on the test dataset.

Logistic Regression was selected due to its interpretability, making it suitable for business-facing predictive analytics.

🔑 Key Insights

Income and asset ownership show strong influence on purchase probability

Interpretable model coefficients help explain customer behavior

The model serves as a strong baseline for customer targeting strategies

🚀 Business Impact

This model enables organizations to:

Identify high-potential customers

Optimize marketing resource allocation

Support strategic decision-making using data

📌 Future Improvements

ROC-AUC and threshold optimization

Feature scaling and normalization

Model comparison with tree-based algorithms

Hyperparameter tuning

👤 Author

Akmal
Aspiring Data Scientist
