# Default Credit Card Prediction

## Project Overview

This project aims to assess the payment behavior of credit card customers in Taiwan and predict the likelihood of default. We use logistic regression techniques to create machine learning models for classifying customers as reliable or unreliable based on their payment history.

## Dataset

The dataset used in this project is the 'Default of Credit Card Clients Dataset' from the UCI Machine Learning Repository. It contains information on Taiwanese credit card users' behavior between April and September 2005, including:

- Credit limit
- Gender
- Education level
- Marital status
- Age
- Payment history
- Bill amounts
- Payment amounts

## Methodology

1. **Exploratory Data Analysis (EDA)**: Thorough analysis of the dataset to uncover patterns and insights.
2. **Data Preprocessing**: 
   - Outlier detection and evaluation
   - Feature selection
   - Data standardization
   - Handling class imbalance using SMOTE and Undersampling
3. **Dimensionality Reduction**: Principal Component Analysis (PCA)
4. **Model Implementation**: Custom Logistic Regression with Regularization
5. **Hyperparameter Tuning**: Grid search for optimal learning rate, lambda parameter, and regularization technique
6. **Model Evaluation**: Using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC

## Key Findings

- The model trained on the SMOTE-balanced dataset generally showed higher accuracy across different regularization techniques and learning rates.
- Ridge regularization with a learning rate of 0.1 demonstrated better generalization across different lambda values.
- The bias-variance tradeoff was more pronounced in the SMOTE-balanced dataset compared to the undersampled dataset.

## Files in the Repository

- `Stats_Learning_Project_Report.pdf`: Detailed project report
- `README.md`: This file, providing an overview of the project
- `Credit Card Default Prediction.ipynb` : Project Exectuion

## Acknowledgments

This project was completed as part of the IE7300: Statistical Learning for Engineering course, Spring 2024.
