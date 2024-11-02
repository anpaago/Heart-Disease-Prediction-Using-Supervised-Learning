# HEART DISEASE PREDICTION
![image](https://github.com/user-attachments/assets/e1104644-5a63-4d35-aedd-d4dbef8286f0)


## Table of Contents
   - [Project Overview](#project-overview)
   - [Project Objective](#project-objective)
   - [Data sources](#data-sources)
   - [Data Preprocessing](#data-preprocessing)
   - [Machine Learning Model](#machine-learning-model)
   - [Evaluation Metrics](#evaluation-metrics)
   - [Key Insights](#key-insights)
   - [Conclusion](#conclusion)

## Project Overview
The "Heart Disease Prediction using Supervised Learning" aims to develop an intelligent system that is capable of analyzing certain features, such as blood pressure, cholesterol level, presence of chest pain, etc. to detect the possibility of a person having a heart attack.

## Project Objective
The primary aim of this project is to build and train a robust machine learning model that can accurately predict the likelihood of a person coming down with a heart attack based on certain features.

## Data Source
The dataset used in this project was provided by 10Alytics.
 

## Data Preprocessing
The following preprocessing steps were used before feeding the data into the machine learning model.
1. Handling missing values
2. Scaling the numerical variables


## Machine Learning Model
The machine learning model was built using the supervised learning approach. Data was split into training and test datasets. Logistic regression and random forest classifier were used to build the model.


## Evaluation Metrics
To access the performance of the machine learning model, the following evaluation metrics were used:

- **Precision:** The proportion of correctly predicted likelihood of a heart attack among all cases predicted as having a heart attack.
- **Recall:** The proportion of correctly predicted likelihood of a heart attack among all actual cases of heart attack.
- **Accuracy:** The overall proportion of correctly predicted likelihood of heart attack.
- **F1 Score:** The harmonic mean of precision and recall, providing a balanced metric for model evaluation.


## Key Insights
- The purpose of the project is to predict the event of a heart attack
- The best model that predicts with lesser error is to be chosen, subjecting them to the different evaluation metrics including k-fold cross-validation(accuracy, precision, recall)
- The confusion matrix displays the error value for each model in terms of False Positive ( where the model predicts the event of a heart attack when there is not - Precision) and False Negative (where the model predicts there is no heart attack when there is - Recall) 
- After cross-validation, the model with the highest recall will be deployed. 


## Conclusion
The "Heart Disease Prediction Model" demonstrates the effectiveness of a machine learning algorithm in predicting the event of a heart attack using certain features. By accurately predicting these scenarios, intervention methods can immediately be conducted to prevent the actual occurrence or further damage. 
