# Employee-Attrition-ML-Project
# Employee Attrition Prediction using Machine Learning

## Overview

This project focuses on cleaning, preprocessing, and building machine learning models on the IBM HR dataset to predict employee attrition.

## Dataset

* IBM HR Employee Attrition dataset
* 1470 employee records

## Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Jupyter Notebook

## Steps Performed

* Data cleaning and preprocessing
* Feature selection and encoding
* Train-test split using stratification
* Feature scaling using StandardScaler

## Models Used

* Logistic Regression
* Random Forest Classifier

## Results

* Logistic Regression Accuracy: ~85%
* Random Forest Accuracy: ~82%
* ROC-AUC Score: ~0.75

## Key Insights

* Monthly Income and Age are major factors influencing attrition
* Employees with overtime are more likely to leave
* Model struggles with minority class prediction (attrition cases)

## Future Improvements

* Handle class imbalance (SMOTE / class weights)
* Try advanced models (XGBoost)
* Improve recall for attrition prediction

## Author

G Suhas Kartik
