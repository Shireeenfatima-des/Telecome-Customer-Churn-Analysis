# Customer-Churn-Analysis

## Project Objective:
The goal of this project is to analyze customer churn in a telecom company by identifying key factors that contribute to customer retention and churn. The insights from this analysis will help the company take proactive measures to reduce churn and improve customer satisfaction.

## Dataset Details:
Total Records: 7,043 customers
Total Features: 21 columns, including customer demographics, account details, service usage, and churn status.
Key Features:

## Customer Demographics:
### Customer Account Information:
Tenure (Number of months a customer has stayed)
Contract (Month-to-month, One year, Two years)
Paperless Billing (Yes/No)
Payment Method (Electronic check, Mailed check, Bank transfer, Credit card)

### Service Subscription Details:
Phone Service, Multiple Lines
Internet Service (DSL, Fiber optic, No)
Online Security, Online Backup, Device Protection, Tech Support
Streaming TV, Streaming Movies

### Financial Information:
Monthly Charges (Customer’s monthly bill)
Total Charges (Total amount billed)
Target Variable:Churn (Yes/No) - Whether the customer left the service.

## Demographic Insights
Power BI dashboard provides insights into telecom customer churn, including:
Total Customers: 7,043
Churned Customers: 1,869
Churn Rate: 26.54%
Key Visualizations:
### Total Churn and Retained Customers
* 5.2K retained (No churn)
* 1.9K churned (Yes)
### Customer Churn by Age Group
* Senior Citizens have a higher churn percentage (25.5% churn vs. 74.5% retention)
### Customer Churn by Partner Status
* Customers without a partner have a higher churn rate.
### Customer Churn by Dependents
* Customers with no dependents churn more.

## Customers Account Insights
### Key Insights from Visuals
### Churn and Retention by Tenure (Months)
* Customers with a shorter tenure (0-20 months) have the highest churn.
* Longer tenure (41-60 months) has a much lower churn rate.
### Churn and Retention by Payment Method
* Electronic Check has the highest churn rate (45.3%).
* Automatic Bank Transfer & Credit Card have the lowest churn rates (~15-17%).
### Churn and Retention by Contract Type
* Month-to-month contracts have the highest churn (88.6%).
* Two-year contracts have the lowest churn (8.9%).
### Churn and Retention by Paperless Billing
* Customers using paperless billing have a higher churn rate (74.9%).
* Non-paperless billing customers churn less (53.6%).

## Services Insights
### Key Insights from Visuals
### Churn by Internet Service
* Fiber optic: 43.96%
* DSL: 34.37%
* No Internet Service: 21.67%
#### Observation: Customers using fiber optic have the highest churn.

### Churn and Retention by Tech Support
No Tech Support: Higher churn (2.0K).
With Tech Support: Lower churn (~0.3K).
#### Observation: Lack of tech support is associated with higher churn.

### Churn and Retention by Phone Service
* With Phone Service: 4.7K retained, 1.7K churned.
* Without Phone Service: 0.5K retained, much lower churn.
#### Observation: Customers with phone service churn more.


## Project Deliverables:
* Data Cleaning & Preprocessing: Handled missing values, outliers, and formatted categorical variables.
* Exploratory Data Analysis (EDA): Visualized churn trends and key patterns in customer behavior.
* Power BI Dashboard: Interactive dashboard to present findings with dynamic filters and visuals.
