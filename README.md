# 🚀🏦Kaggle Competition - Binary Classification with a Bank Churn Dataset

## Introduction

The dataset (both train and test) was generated from a deep learning model trained on the Bank Customer Churn Prediction dataset. Feature distributions are close to, but not exactly the same, as the original. 

## Prediction Task
whether a customer continues with their account or closes it (e.g., churns).

## Original Features
The dataset contains 13 columns:

- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)

## Models Used
- Logistic Regression
- Random Forest
- LGBM
- CarBoost
- XGBoost
- Voting Regressor (final choice)

## Metric
area under the ROC curve

## Public leaderboard score
0.88631

## Private leaderborad score
0.89220 (+51)
