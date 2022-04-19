# Churning out a Solution

**Authors**: Matthe Gayanelo

## Business Problem

SyriaTel is experiencing a 15% churn rate

## Data


Source: SyriaTel
Analytical Prupose: General Classification
Target Variable: Churn
Target Variable Use: Determine whether or not a customer will churn or out of the company.


***

## Methods

1. Initial Analysis of Data, exploring potential null values, statistical metrics and initial isolation of key features
2. Multi Model Analysis to determine best model to use
3. Class Imbalance Analysis
4. Model Optimization
5. Feature Importance exploration
6. Raw Data Exploration to validate Model Feature IMportance

## Results

### Random Forests were chosen due to the following metrics:

Model Test Precision: 0.8205128205128205
Model Test Recall: 0.8767123287671232
Model Test Accuracy: 0.954
Model Test F1: 0.847682119205298

### Feature Importance Exploration:

Customer Service Calls, Data Time Minutes and Day Time Charges were found to be the most important features

### Raw Data Exploration:

Mean of Customer Service Calls For Non Churners: 1.4498245614035088
Standard Deviation of Customer Service Calls: 1.3152936866709521
Mean of Customer Service Calls for Churners: 2.229813664596273

Mean of total day minutes Non Churners: 175.1757543859649
Standard Deviation of total day minutes: 54.45921766392581
Mean of total day minutes for Churners: 206.91407867494823

Churners displayed higher usage of their plans, and also a greater amount of customer service calls.

## Conclusions

### Usage Results

1. Users with higher usage during the day / charges are clearly more inclined to churn
2. This clearly shows that heavy usage users are not experiencing a satisfactory service

### Proposition

1. Provide a service that scales with usage in order to save 15% of the business
2. Specifically when a user starts exceeding 170 / 175 minutes per week offer reduce costs and a higher level of service
