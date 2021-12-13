# Credit Card Fraud Detection
IEE-CIS Fraud Detection, create machine learning model to detect the anomaly in transaction in order to improve the efficacy of fraudulent transaction alerts.

**Tools Used** : Python, Pandas, Matplotlib, Seaborn, Scikit-Learn

**Category** : Machine learning, Clustering and Classification, Anomaly Detection

**Year** : December 2021

**Dataset source** : https://www.kaggle.com/c/ieee-fraud-detection/data

**Features** : Transaction Date, Transaction Amount, and a very wide range (hundreds) of features

**Feature Engineering** : Feature Importance (from RandomForest), LabelEncoder, StandardScaler

**Model Algorithms** : Isolation Forest, Gaussian Naive Bayes, Random Forest, GridSearchCV for cross-validation and parameter tuning

**Result** : The RandomForest model with default parameter achieved the highest f1-score (100%) but we assumed that it overfits, so we decided to use the tuned model of Gaussian Naive Bayes (it achieved 95% of f1-score).
