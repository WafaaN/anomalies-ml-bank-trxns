# Project README 

## 📝 Project Overview

Detect anomalies in financial transactions dataset using unsupervised machine learning algorithms. Started with an ensemble-based method: Isolation Forest.

## 📊 Dataset
- Data set used [Bank Transaction Dataset for Fraud Detection](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection). 
- This dataset provides a detailed look into transactional behavior and financial activity patterns, ideal for exploring fraud detection and anomaly identification. 
- It contains 2,512 samples of transaction data, covering various transaction attributes, customer demographics, and usage patterns. Each entry offers comprehensive insights into transaction behavior, enabling analysis for financial security and fraud detection applications.

## ⚙️ Methodology – Bank Transaction Anomaly Detection

1. **Data Reading** Load structured data from CSV/Excel and inspect the structure and types.
2. **Data Cleaning & Profiling**  Handle missing values, duplicates, incorrect types, and detect outliers.
3. **Exploratory Data Analysis (EDA)**  Visualize distributions, analyze categorical counts, examine correlations, and detect anomalies.
4. **Feature Engineering & Preprocessing**  Encode categorical variables and scale numeric features.  
5. **Model Selection & Training**  Train unsupervised anomaly detection models (Isolation Forest, One-Class SVM, DBSCAN, and LOFgit init).
6. **Model Evaluation** Assess performance using number of anomalies detected, visualizations anomaly points.
7. **Conclusion & Future Work**  suggest improvements, retraining strategies, and analysis of discrepancies between model results.

