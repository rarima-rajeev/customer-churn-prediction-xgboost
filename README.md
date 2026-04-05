# Customer Churn Prediction Engine (XGBoost)

## Executive Summary
This project demonstrates a data-driven approach to identifying high-risk customers for a subscription-based business. By leveraging **XGBoost**, I built a predictive model that identifies potential churn with **77% baseline accuracy**, providing a foundation for automated retention strategies.

## The Problem
Customer churn directly impacts ARR (Annual Recurring Revenue). The goal of this project was to analyze 7,000+ customer records to find patterns behind attrition.

## Technology Stack
* **Language:** Python
* **Data Engineering:** Pandas (One-Hot Encoding, Data Validation)
* **Modeling:** XGBoost Classifier
* **Evaluation:** Scikit-Learn (Train/Test Split, Accuracy Scoring)

## Key Findings
* **Contract Type:** Customers on month-to-month contracts are significantly more likely to churn.
* **Tenure:** The first 6 months are the highest risk period for new users.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebook: `churn_predictor_v1.ipynb`
