# Bank Turnover Prediction

This project aims to predict the level of a customer’s account turnover based on the provided attributes. The prediction is performed on the basis of the following customer attributes: 
 - CreditScore 
 - Geography 
 - Gender 
 - Age 
 - Tenure 
 - Balance 
 - NumOfProducts 
 - HasCrCard 
 - IsActiveMember 
 - EstimatedSalary 
 
 Whereas "Exited" column is our target variable


## Project Overview

The project focuses on predicting customer turnover for a bank dataset using an Artificial Neural Network (ANN). The dataset is imbalanced, with more customers maintaining higher turnover than those with lower activity. To address this issue, several techniques for handling imbalanced data have been applied.

## Steps Involved

### 1. Data Cleaning
The data has been cleaned and preprocessed, including:
- Encoding categorical variables
- Scaling numerical features
- Removing any irrelevant columns or features

### 2. Model Implementation
**ANN** is used to predict customer churn.

### 3. Handling Imbalanced Data
The dataset is imbalanced, which can lead to biased model predictions. Several techniques were applied to address this issue:
- **Undersampling Majority Class**: Reduces the number of customers in the majority class (retained customers).
- **Over-sampling Minority Class (Duplication)**: Increases the number of customers in the minority class (churned customers) by duplicating entries.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Generates synthetic samples of the minority class to balance the dataset.
- **Ensemble Method**: Combines multiple models to improve the prediction performance and robustness.

### 4. Model Evaluation
The model performance is evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

These metrics are essential in evaluating how well the model handles imbalanced data and its ability to predict customer turnover.
