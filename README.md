# Hotel Reservations Fulfillment Predicting Model

--------- 
An end-to-end solution for predicting hotel reservation fulfillment status. This model helps hotels optimize operations by identifying potential cancellations in advance and acting accordingly. It includes comprehensive data analysis, feature engineering, model training and business impact evaluation.

The chosen model yields a high average precision (0.81) when tested on unseen real test data, significantly better than a naive baseline consisting of a logistic regression with 2 very relevant features (which yields 0.68).

## Features

- A comprehensive analysis and data exploration of hotel-specific distributions and patterns. 
- Feature preprocessing using pipelines with optional PCA reduction. 
- Business impact analysis with customizable cost metrics. 
- Cross-validation and hyperparameter optimization using GridSearch. 

## Models Implemented (using scikit-learn)

- Logistic Regression 
- Random Forest
- Gradient Boosting
- Stochastic Gradient Descent

## Evaluation Metrics

- Standard metrics: Accuracy, Precision, Recall, F1-score
  - Business-specific metrics: Expected Cost Savings Rate, Cost per Booking, Total Savings

### Authors
**Johanna Schmucker, Tasnim El-Faghloumi and Rodrigo Sastré**

