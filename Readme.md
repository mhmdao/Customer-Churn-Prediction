# Bank Customer Churn Prediction

## Overview
This project analyzes customer churn in a bank using machine learning techniques. The dataset, sourced from Kaggle, contains customer information and banking history, allowing us to build predictive models to identify customers likely to churn. The goal is to build a classification model that identifieds the customers at the highest risk of churn. 

## Dataset
- **Source**: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/ramyhafez/bank-customer-churn/data)
- **Description**: Account information for 10,000 customers at a European bank, including details on their credit score, balance, products, and whether they have churned. The dataset includes demographic and financial details of bank customers along with a churn indicator. 
- **Data Structure**
  - Single table
  - Number Of Records: 10,000
  - Number Of Fields: 13
- **Features**:
  - `CustomerId`: Unique ID for each customer
  - `Surname`: Customer's last name
  - `CreditScore`: Credit score of the customer
  - `Geography`: Country of residence
  - `Gender`: Gender of the customer
  - `Age`: Age of the customer
  - `Tenure`: Number of years as a customer
  - `Balance`: Account balance
  - `NumOfProducts`: Number of products held
  - `HasCrCard`: Whether the customer has a credit card (1 = Yes, 0 = No)
  - `IsActiveMember`: Whether the customer is an active member (1 = Yes, 0 = No)
  - `EstimatedSalary`: Estimated salary of the customer
  - `Exited`: Whether the customer churned (1 = Yes, 0 = No)

## 🛠️ Project Workflow

### ** Data Preprocessing and Exploratory Data Analysis (EDA)**
- Exploring data and features
- Prepare the data for modeling
- Build & Evaluate a logistic Regression
- Build & tune a random forest model

### ** Model Development**
- Tried different classification models:
  - Logistic Regression
  - Random Forest
- Evaluated using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

### ** Results **
- Models like Logistic Regression and Random Forests were tested.
- The best model achieved an accuracy of **85%** for the test dataset.