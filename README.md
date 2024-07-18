## Credit Card Fraud Detection System

#### Overview
This project focuses on building a machine learning model to detect fraudulent transactions using a credit card dataset. The system leverages various outlier detection techniques such as IQR, k-NN, DBSCAN, and Isolation Forest, followed by a RandomForest classifier to predict fraud. This repository contains all related code and documentation.

#### Features
Outlier Detection: Implementation of multiple anomaly detection methods.
Machine Learning Model: RandomForest classifier enhanced with SMOTE to handle imbalanced data.
Evaluation: Detailed performance evaluation using confusion matrices and precision-recall curves.

#### Results
The RandomForest model achieves the following performance on the test data:

Precision: 87% for detecting fraud
Recall: 79% for detecting fraud
F1-Score: 83%
These metrics indicate the model's effectiveness at identifying fraudulent transactions with a balance between precision and recall.


