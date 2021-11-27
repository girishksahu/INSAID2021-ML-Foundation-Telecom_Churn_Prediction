# INSAID2021-ML-Foundation-Telecom_Churn_Prediction
INSAID 2021 ML Foundation Term Project
# Project Description
## Introduction
Client for this project is a Telecom Service Provider.

The company has started facing high churn rate due to rapid development in technology and the emerging new competitors in the market.
The objective is to use the model to take further actions for preventing customers to churn.

They will have to offer something to their customers so they stick around, example - a promo, discount, loyalty program etc.

## Current Scenario
Till now they have been using traditional ways which now have become a problem to handle due to human interventions.

They have a detailed history of their customers and are looking for an automated solution to identify the likeliness of customer churning from using their services.

## Problem Statement
The current process suffers from the following problems:

* Due to the boom in the telecom industry with 4G technology, it has become a pain in the neck for the company to retain their customers.
* They are in the middle of setting up more cell sites on the 4G network to improve their 4G services. It is plausible for customers to choose 4G services over 3G services due to benefits of cost, speed, latency etc.

In return, they have decided to find a more optimal way.

## Project Task
* Datasets of past customers and their status (Churn: Yes or No) are provided.
* Project task is to build a classification model using the dataset.
## Project Deliverables
* Deliverable: Predict whether a customer will churn or not.
* Machine Learning Task: Classification
* Target Variable: Churn (Yes / No)
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the Accuracy Score.
# Data Description
* Dataset contains all the necessary information about the customers like their Gender, MonthlyCharges, TotalCharges, PaymentMethod, InternetService, etc.
* Also included in the dataset is the column Churn which classifies whether the customer will churn or not.

* This is the data that we have to predict for the future customers.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 5634 rows and 21 columns.
* The last column Churn is the target variable.

## Test Set:
* The test set contains 1409 rows and 20 columns.
* The test set doesn’t contain the Churn column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **customerID**   | Customer Identity |
|02| **Gender**      | Whether the customer is a male or a female|
|03| **SeniorCitizen**        | Whether the customer is a senior citizen or not (1, 0)|
|04| **Partner**          | Whether the customer has a partner or not (Yes, No)|
|05| **Dependents**      | Whether the customer has dependents or not (Yes, No) |
|06| **Tenure**           | Number of months the customer has stayed with the company|
|07| **PhoneService**     | Whether the customer has a phone service or not (Yes, No)|
|08| **MultipleLines**        | Whether the customer has multiple lines or not (Yes, No, No phone service)  |
|09| **InternetService**          | Customer’s internet service provider (DSL, Fiber optic, No)       |
|10| **OnlineSecurity**         | Whether the customer has online security or not (Yes, No, No internet service)  |
|11| **OnlineBackup**     | Whether the customer has online backup or not (Yes, No, No internet service)  |
|12| **DeviceProtection**     | 	Whether the customer has device protection or not (Yes, No, No internet service)    |
|13| **TechSupport**     | Whether the customer has tech support or not (Yes, No, No internet service)     |
|14| **StreamingTV**     | Whether the customer has streaming TV or not (Yes, No, No internet service)           |
|15| **StreamingMovies**     | Whether the customer has streaming movies or not (Yes, No, No internet service)           |
|16| **Contract**     | The contract term of the customer (Month-to-month, One year, Two year)      |
|17| **PaperlessBilling**     | Whether the customer has paperless billing or not (Yes, No)                        |
|18| **PaymentMethod**     | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) |
|19| **MonthlyCharges**     | The amount charged to the customer monthly           |
|20| **TotalCharges**     | The total amount charged to the customer           |
|21| **Churn**     | Whether the customer churned or not (Yes or No)|
