# Telecom Customer Churn Prediction Project

Author: Oun Nuqul
Date: October 4, 2025

## Project Overview

This project implements a machine learning solution to predict customer churn for telecommunications companies. We classify customers into binary categories (Churn vs No Churn) using customer demographics, service usage, and account information to enable proactive retention strategies.

## Business Objective

The goal is to predict customer churn to enable proactive retention strategies and reduce customer acquisition costs. The target variable is binary classification of churn status. Features include customer demographics, service plans, usage patterns, and account information.

## Dataset

The dataset contains telecom customer records with demographics, service subscriptions, billing information, and churn status. Key features include gender, senior citizen status, partner status, contract type, payment method, internet service type, monthly charges, and total charges.

## Models Used

Two machine learning models were implemented and compared:
1. Logistic Regression (baseline model)
2. Gradient Boosting Classifier with Grid Search hyperparameter optimization

## Methodology

1. Data loading and initial exploration
2. Data quality assessment and cleaning
3. Comprehensive exploratory data analysis
4. Feature engineering with one-hot encoding
5. Model training and evaluation
6. Performance comparison and model selection

## Key Findings

The Logistic Regression baseline model achieved strong performance across all metrics. Surprisingly, the Gradient Boosting model with Grid Search hyperparameter tuning did not improve upon the baseline performance and showed worse results.

The Logistic Regression model was selected as the optimal choice due to computational efficiency, interpretability for business stakeholders, satisfactory performance across all metrics, and cost-effectiveness for deployment.

## Evaluation Metrics

Models were evaluated using:
- Accuracy: Percentage of correct churn predictions
- Recall: Ability to identify customers who will churn
- Precision: Accuracy of churn predictions
- ROC AUC: Overall model discrimination ability

## Files

- notebook.ipynb: Main analysis notebook containing all code and documentation
- data.csv: Telecom customer dataset
- README.md: This documentation file

## Technical Requirements

Python libraries used:
- pandas for data manipulation
- numpy for numerical computations  
- matplotlib and seaborn for visualization
- scikit-learn for machine learning algorithms and evaluation


## Business Applications

The model can be used for real-time churn scoring, targeted retention campaigns, resource optimization, and proactive customer management to reduce revenue loss from customer departures.

## Future Enhancements

Potential improvements include advanced feature engineering with temporal usage patterns, experimenting with additional algorithms like XGBoost, implementing cross-validation, addressing class imbalance, and developing production deployment pipelines.