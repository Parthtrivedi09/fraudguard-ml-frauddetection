# 🚨 FraudGuard: Detecting Credit Card Fraud using Machine Learning

FraudGuard is a machine learning project designed to detect fraudulent credit card transactions using real-world anonymized data. It employs supervised learning techniques to distinguish between genuine and fraudulent activity with high precision, even in highly imbalanced data.

---

## 📌 Features

- Preprocessing and handling of highly imbalanced datasets
- Multiple classification models (Logistic Regression, Random Forest, XGBoost)
- Evaluation using precision, recall, F1-score, and ROC-AUC
- Clean Jupyter Notebook workflow for easy understanding
- Scalable codebase, ready for advanced features like explainability & real-time alerts

---
About the dataset
📄 Dataset Description
📦 File: creditcard.csv

👥 Rows: 284,807 transactions

📊 Columns: 31

Column Name	Description
Time	Time in seconds since the first transaction (used for time-series analysis, optional).
V1 to V28	Result of a PCA transformation on original features (e.g., amount, location, device info). Real column names are hidden for privacy.
Amount	The transaction amount in USD.
Class	Target variable: 0 = legitimate, 1 = fraudulent.

🧠 Why "V1" to "V28"?
These are anonymized features — due to confidentiality and privacy concerns, the original feature names were removed.

The values are principal components created via PCA (Principal Component Analysis).

They’re combinations of the original features that capture most of the variance in the dataset while removing sensitive information.

🧪 Summary of Columns:
Type	Columns
Identifier	Time
Features	V1 to V28
Additional	Amount
Target variable	Class (0 = non-fraud, 1 = fraud)

🧯 Class Imbalance:
Legitimate (Class = 0): ~99.8%

Fraudulent (Class = 1): ~0.2%

This extreme imbalance is what makes it a challenging real-world problem.

-------------------------------------------------------------------------------------------


