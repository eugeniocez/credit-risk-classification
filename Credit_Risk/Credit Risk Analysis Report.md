# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis is to evaluate the prediction of credit risk with machine learning models. The financial data analyzied included variables such as: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. The main goal of this analysis is to predict the loan status, which helps indicate whether a loan is healthy of high-risk.

The machine learning process involved multiple stages:

1. Preprocessing the data
2. Training the model
3. Evaluating the model

## Results

Logistic Regression Model

    - Accuracy: 99%
    - Precision:
        - Healthy Loan (0): 1.00
        - High-Risk Loan (1): 0.85

    - Recall:
        - Healthy Loan (0): 0.99
        - High-Risk Loan (1): 0.91

    - F1 Score:
        - Healthy Loan (0): 1.00
        - High-Risk Loan (1): 0.88

## Summary

The logistic regression model demonstrated high performance in predicting credit risk, especially for healthy loans (0). It had almost a perfect precision result and a very high recall score, indicating that this model can accurately identify loans that are not risky. The model overall performs well so I would in fact recommend it to be used by the company.