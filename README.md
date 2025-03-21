# Credit-Card-Fraud-Detection
Data Analysis and Model building for Credit Card Fraud Detection
# project overview
This project focusses on detecting fraudulent credit card transactions using machine learning. The dataset is highly imbalanced, with fraud cases being rare compared to non-fraud cases. The goal is to build an effective model that minimizes false positives while maximizing fraud detection

# Dataset information
The dataset contains 284,807 transaction with 31 features, including
Time :seconds elapsed between a transaction and the first transaction in the dataset
V1 ti V28:Anonymized PCA-transformed features
Amount:The transaction amount 
Class: 0-Non-Fraudulent transaction
      1-Fraudulent Transactio
# Data source
kaggle-Credit Card Fraud Detection

# Data Preprocessing
ensure to balanced the imbalanced class
standardize the amount feature using StandardScaler()
split the data into training(80%) and testing(20%)
# Machine Learning model
implement Random Forest for better fraud detection using n_estimators=200
