SyriaTel Customer Churn Prediction

Project Overview

This project aims to predict customer churn for SyriaTel, a telecommunications company. The primary goal is to help the company identify customers who are likely to leave (churn) so they can take proactive steps to retain them.

Business Problem

Customer churn significantly affects profitability in the telecom industry. Understanding and predicting churn allows SyriaTel to:

Reduce customer acquisition costs

Increase customer lifetime value

Improve customer satisfaction with targeted interventions

Objective

Use classification models to predict whether a customer will churn based on behavioral and service-related features.

Dataset
'bigml_59c28831336c6604c800002a.csv'

Key Features:

Number of customer service calls

International plan subscription

Total day, evening, night call minutes and charges

Voicemail plan

methods and Models

Exploratory Data Analysis (EDA):


Modeling:

Logistic Regression (tuned using GridSearchCV)

Decision Tree Classifier (tuned using GridSearchCV)

Evaluation Metrics:

Accuracy

Precision, Recall, F1-Score (especially for churn class)


Best Model: Decision Tree (Tuned)

Business Recommendations

- Customers with high day-time charges, international plans, and frequent support calls are more likely to churn.
- SyriaTel should:
  - Offer loyalty programs or bundle plans to high-risk segments.
  - Reduce churn by proactively reaching out to users with frequent service issues.
  - Consider offering discounts to users with high charges during the day or night periods.