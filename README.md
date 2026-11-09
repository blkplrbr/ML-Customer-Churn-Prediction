# Customer Churn Prediction Model

## Project Overview
This project builds a Machine Learning classification model to predict which customers are likely to cancel their subscription service (churn). By identifying high-risk customers, businesses can intervene with targeted retention offers, saving revenue.

## The Business Problem
Customer acquisition is expensive. Losing existing customers to competitors is a major drain on profitability. Using the IBM Sample Data Set, the goal was to analyze customer demographics, account information, and service usage to predict behavior and develop focused customer retention programs.

## Dataset Features
The dataset contains the following attributes for each customer:
*   **Target Variable:** `Churn` (Whether the customer left within the last month).
*   **Services:** Phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV/movies.
*   **Account Info:** Tenure (how long they've been a customer), contract type, payment method, paperless billing, monthly charges, and total charges.
*   **Demographics:** Gender, age range, and whether they have partners or dependents.

## Technical Stack
*   **Language:** Python
*   **Libraries:** Pandas, Scikit-Learn, Matplotlib/Seaborn

## Methodology
1.  **Exploratory Data Analysis (EDA):** Visualized the churn rate across different demographics, contract types, and tenure lengths. 
2.  **Data Preprocessing:** 
    *   Handled missing values and corrected data types (e.g., converting `TotalCharges` from a string to a float).
    *   Encoded categorical variables (using One-Hot Encoding).
    *   Scaled numerical features.
3.  **Model Building:** Trained multiple classification models, including Logistic Regression, Random Forest, and XGBoost.
4.  **Evaluation:** Evaluated models using F1-Score, ROC-AUC curves, and a Confusion Matrix to minimize false negatives (predicting a customer will stay when they actually leave).

## Business Impact
*   Provides a "Churn Probability Score" for every customer in the database.
*   Allows the marketing team to target high-value, high-risk customers with retention discounts before they cancel.

## Status
🚧 **Work in Progress:** The Jupyter Notebook containing the ML pipeline will be uploaded shortly.
