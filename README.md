# Crime Type Prediction using Machine Learning

## Overview
This project demonstrates the use of Machine Learning to predict the type of crime based on structured case-related data. The model uses features such as location, evidence type, case status, and date-based attributes to analyze patterns and perform classification.

The primary objective of this project is to understand and implement an end-to-end data science workflow, from data preparation to model evaluation and interpretation.

The goal is to demonstrate an end-to-end Data Science workflow:
- Data cleaning
- Feature engineering
- Encoding categorical variables
- Model training and evaluation
- Feature importance analysis

## Dataset
The dataset contains fictional crime case records with the following fields:
- Case ID
- Crime Type (target variable)
- Location
- Date
- Evidence Type
- Case Status

## Machine Learning Model
- Algorithm: Random Forest Classifier
- Features:
  - Location (encoded)
  - Evidence Type (encoded)
  - Case Status (encoded)
  - Day, Month, Weekday (from date)

## Results
- Accuracy achieved on test set (small dataset)
- Feature importance visualization used to interpret the model

> Note: This dataset is small and used for learning purposes. High accuracy
does not indicate a production-ready model.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Author
Rahat Khan
