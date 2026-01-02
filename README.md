# Fraud-Detection-System-ML
To detect fraudulent financial transactions using machine learning models, while handling extreme class imbalance and minimizing financial loss.
🚨 Fraud Detection System using Machine Learning
📌 Project Overview

Financial fraud causes billions in losses every year.
This project builds a robust, real-world fraud detection system using machine learning techniques that focus on class imbalance, recall optimization, and business-critical evaluation metrics.

The model predicts whether a credit card transaction is fraudulent or legitimate, prioritizing fraud recall over naive accuracy.

🎯 Objectives

Detect fraudulent credit card transactions

Handle highly imbalanced datasets

Minimize false negatives (missed frauds)

Build an industry-grade ML pipeline

📂 Dataset

Source: Public Credit Card Fraud Dataset

Features: PCA-transformed numerical features

Target:

0 → Legitimate transaction

1 → Fraudulent transaction

⚠️ Fraud cases account for <1% of data, making this a realistic and challenging ML problem.

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-Learn

Matplotlib, Seaborn

Google Colab

🔍 Project Workflow

Data Loading & Exploration

Handling Class Imbalance

Train-Test Split

Feature Scaling (StandardScaler)

Logistic Regression with:

class_weight='balanced'

Increased max_iter

Model Evaluation using:

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC Curve

📊 Model Evaluation (Key Insight)

Accuracy is NOT the main metric

Recall for fraud class is prioritized

Model successfully identifies fraudulent transactions while controlling false alarms

🚀 Key Learnings

Why fraud detection requires recall-focused evaluation

Importance of class imbalance handling

Difference between academic ML and production-ready ML

How small parameter choices impact real business outcomes

📌 Future Improvements

Threshold tuning for cost-sensitive learning

Tree-based models (Random Forest, XGBoost)

Anomaly detection approaches

Deployment using Streamlit

👤 Author

Dhivya
Aspiring Data Scientist | ML Enthusiast
