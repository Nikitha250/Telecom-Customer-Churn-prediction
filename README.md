# Telecom-Customer-Churn-prediction


# Overview

This project aims to predict customer churn in the telecom industry using machine learning techniques. Identifying customers likely to leave can help businesses improve retention strategies and reduce revenue loss.

# Dataset

The dataset includes customer details such as:

Services (phone, internet, tech support, etc.)

Account details (contract type, billing method, etc.)

Demographics (age, gender, family details)



# Objectives

Analyze key factors influencing customer churn

Build and evaluate various machine learning models

Identify strategies to improve customer retention

# Key Insights

Customers with month-to-month contracts are more likely to churn.

Users with electronic check payments have higher churn rates.

Customers lacking online security and tech support tend to leave more frequently.

# Implementation

Libraries Used

Pandas - Data manipulation

Seaborn & Matplotlib - Data visualization

Scikit-learn - Machine learning model building

Machine Learning Models Tested

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Decision Tree

Random Forest

AdaBoost

Gradient Boosting

Voting Classifier (Final Model)

Final Model: Voting Classifier

The Voting Classifier combines Gradient Boosting, Logistic Regression, and AdaBoost for improved accuracy.

Final Accuracy: 84.6%

# Recommendations

Offer discounts or incentives to month-to-month customers to increase retention.

Encourage users to switch to automatic payment methods to reduce churn.

Improve tech support and online security services to enhance customer satisfaction.

# How to Run

Clone this repository.

Install the required libraries using pip install -r requirements.txt.

Run the Jupyter Notebook or Python script to train and evaluate the model
