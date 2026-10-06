# Customer Churn Prediction

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning classification project that predicts whether a customer is likely to stop using a company's service.

This project uses a telecom customer dataset and applies Machine Learning techniques to identify customers who are likely to churn.

The project focuses on data preprocessing, exploratory data analysis, feature engineering, classification models, and model evaluation.

---

## 🎯 Objectives

- Predict whether a customer will churn or not.
- Clean and preprocess the customer dataset.
- Handle missing values and categorical variables.
- Perform Exploratory Data Analysis (EDA).
- Analyze relationships between customer features and churn.
- Train classification models.
- Compare model performance using different evaluation metrics.
- Identify important features affecting customer churn.

---

## 📊 Dataset

The dataset used in this project is the **Telco Customer Churn Dataset** from Kaggle.

**Dataset Source:**  
https://www.kaggle.com/blastchar/telco-customer-churn

### Target Variable

- `Churn = 0` → Customer stays
- `Churn = 1` → Customer churns

### Important Features

- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- PhoneService
- InternetService
- Contract
- PaymentMethod
- MonthlyCharges
- TotalCharges

---

## 🔍 Exploratory Data Analysis

The project performs EDA to understand:

- Customer demographics
- Contract types
- Monthly and total charges
- Customer tenure
- Internet services
- Payment methods
- Relationship between customer features and churn

Visualizations are used to identify patterns and factors associated with customer churn.

---

## ⚙️ Project Workflow

```text
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Categorical Encoding
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Model Evaluation
     ↓
ROC Curve Analysis
     ↓
Feature Importance
     ↓
Model Comparison
     ↓
Conclusion
