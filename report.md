## Overview of the Analysis

The analysis aimed to develop machine learning models to predict loan risk from financial data, focusing on identifying 'healthy' and 'high-risk' loans. We analyzed variables like loan size and borrower information to predict loan risk. The process involved data preprocessing, oversampling imbalanced classes with `RandomOverSampler`, fitting models like `LogisticRegression`, and evaluating performance metrics.

## Results

Results are summarized with key metrics for each model:

- **Logistic Regression:**
  - **Balanced Accuracy Score:** High accuracy, indicating strong overall performance.
  - **Precision for `0` (Healthy Loans):** Perfect, suggesting no healthy loans were misclassified as high-risk.
  - **Precision for `1` (High-Risk Loans):** Good, indicating a low false positive rate for high-risk loans.
  - **Recall for `1` (High-Risk Loans):** High, demonstrating the model's ability to identify most high-risk loans.

## Summary

The Logistic Regression model with oversampled data shows excellent capability in predicting both healthy and high-risk loans, achieving high precision and recall rates. It stands out for its accuracy and ability to distinguish between loan types effectively, making it a recommended choice for predicting loan risk. The performance underscores the importance of addressing class imbalance and the effectiveness of Logistic Regression in handling binary classification tasks in financial contexts.

