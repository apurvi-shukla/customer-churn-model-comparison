# Customer Churn Prediction — Model Comparison

##  Project Overview

This project predicts whether a customer is likely to churn (leave a service) based on customer details. It explores multiple machine learning classification algorithms and provides an interactive web application built using Streamlit.

##  Objectives

- Analyze customer data to identify churn-related patterns.
- Perform data cleaning and exploratory data analysis (EDA).
- Prepare customer features for machine learning.
- Compare multiple classification algorithms.
- Build an interactive application for customer churn prediction.

##  Tech Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Machine Learning:** Scikit-learn
- **Model Serialization:** Joblib
- **Web Application:** Streamlit

##  Machine Learning Algorithms

The project explores the following classification algorithms:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

GridSearchCV is used for hyperparameter tuning of KNN and Random Forest.

##  Exploratory Data Analysis

- Customer churn distribution
- Missing values and duplicate records
- Numerical feature statistics and correlations
- Average monthly charges by churn status
- Age and tenure patterns by churn status
- Monthly charges and tenure distributions
- Contract type and average monthly charges

##  Data Preprocessing

- Handled missing values in the dataset.
- Encoded Gender into numerical values.
- Converted churn labels into binary values.
- Selected Age, Gender, Tenure, and Monthly Charges as model features.
- Applied StandardScaler for feature scaling.
- Split the dataset into training and testing sets.

##  Model Performance

- **Model Accuracy:** 89%
- **Problem Type:** Binary Classification
- **Target Variable:** Customer Churn (Yes/No)

The models are evaluated using accuracy, and KNN and Random Forest hyperparameters are tuned using GridSearchCV.

##  Streamlit Web Application

The application allows users to enter customer details:

- Age
- Tenure
- Monthly Charges
- Gender

After clicking the **Predict** button, the application displays the predicted churn result: `Yes` or `No`.

##  Key Learning Outcomes

- Practical implementation of classification algorithms
- Data cleaning and exploratory data analysis
- Feature encoding and scaling
- Hyperparameter tuning using GridSearchCV
- Saving and loading machine learning models with Joblib
- Building and deploying a machine learning application using Streamlit

##  Author

**Apurvi Shukla**

## 🔗 Live Application

Try the deployed Customer Churn Prediction application here:

https://customer-churn-model-comparison-apurvi.streamlit.app/

