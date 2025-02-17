# Credit-Card-Fraud-Detection-Using-Machine-Learning-
Project Overview

This project explores machine learning techniques to detect fraudulent credit card transactions. Given the highly imbalanced nature of fraud data, we used Logistic Regression, Random Forest, and Multiple Regression models to classify transactions as fraudulent or non-fraudulent.
Dataset

The dataset used in this project contains real anonymized credit card transactions. The major challenge in fraud detection is class imbalance, as fraudulent transactions represent a very small portion of total transactions.
Data Preprocessing

✅ Handling Imbalanced Data: We applied under-sampling techniques to create a more balanced dataset.

✅ Feature Selection: We used correlation analysis and Random Forest feature importance to remove redundant features and improve efficiency.

✅ Feature Scaling & Encoding: Standardized numerical features and encoded categorical variables for better model performance.

Models Implemented & Performance

Model	Accuracy	AUC Score	Precision	Recall
Logistic Regression	X%	0.97	Y%	Z%
Random Forest	X%	X%	X%	X%
Multiple Regression	X%	X%	X%	X%
Evaluation Metrics


📈 ROC Curve: The AUC score of 0.97 indicates strong predictive power.

📊 Precision-Recall Curve: Ensured that fraud cases were not missed while minimizing false positives.
Challenges & Improvements


⚡ Class imbalance required careful handling to avoid misleading accuracy scores.

⚡ Logistic Regression performed well but has limitations in capturing complex fraud patterns.

⚡ Next steps involve ensemble methods and deep learning techniques to enhance performance.

How to Use

Clone this repository:
git clone [GitHub Link]

Install dependencies:
pip install -r requirements.txt

Run the model:
python fraud_detection.py

Contributors
👨‍💻 Abhishek Shrivas – www.linkedin.com/in/abhishek-shrivas-bb35bb239
⭐ Star this repo if you found it helpful!
#MachineLearning #CreditCardFraud #FraudDetection #LogisticRegression #Python #DataScience #AI
