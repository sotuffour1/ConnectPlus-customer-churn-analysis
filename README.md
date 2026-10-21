# ConnectPlus-customer-churn-analysis
Telecom customer churn analysis and Power BI dashboard examining customer behaviour, revenue, and churn pattern



## Project Overview

ConnectPlus Mobile Customer Churn Analysis is a data analytics project
focused on understanding customer churn, customer behaviour, and revenue
performance within a telecommunications customer base.

The project transformed raw subscriber data into an interactive Power BI
dashboard designed to help identify customer segments associated with
higher churn and evaluate their potential business impact.

## Business Problem

Customer churn can negatively affect recurring revenue and long-term
customer value.

The objective of this analysis was to:

- Measure the overall customer churn rate
- Identify customer segments with higher churn
- Examine the relationship between complaints and churn
- Analyse customer behaviour and service usage
- Identify major revenue-generating customer segments
- Provide recommendations to support customer retention

## Dataset

The dataset contains 700 unique subscribers and includes information such as:

- Subscriber ID
- Region
- Plan
- Account Type
- Tenure
- Data Usage
- Voice Minutes
- SMS Count
- Complaints
- Monthly Bill
- Churn Status
- Payment Method

## Tools Used

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization

## Data Preparation

The raw data was cleaned and prepared using Power Query.

The preparation process included:

- Removing duplicate subscriber records
- Cleaning inconsistent text values
- Standardizing categorical fields
- Validating data types
- Checking missing and invalid values
- Validating plan and region references
- Preparing the dataset for analysis

## Power BI Dashboard

The dashboard contains four analytical pages:

### 1. Overview
Provides a high-level view of the customer base, including subscribers,
customer status, revenue, plans, and regions.

### 2. Customer Behaviour
Examines data usage, voice usage, SMS activity, complaints, and payment
methods across customer segments.

### 3. Revenue
Analyses monthly revenue, ARPU, revenue by plan, account type,
region, and customer tenure.

### 4. Churn
Examines churn rates by tenure, plan, region, complaints, account type,
and payment method.

## Key Findings

- The customer base contains 700 subscribers.
- 33 subscribers were recorded as churned.
- Overall churn rate was 4.71%.
- Customers in earlier tenure groups showed higher observed churn.
- Higher complaint frequency was associated with higher observed churn.
- The Business plan generated the highest monthly revenue.
- Business customers also recorded the highest ARPU.
- Churn varied considerably across regions and plans.
- Data usage differed substantially between customer plans.

## Recommendations

Based on the analysis, the following actions are recommended:

1. Strengthen retention initiatives for early-tenure customers.
2. Introduce proactive follow-up for customers with repeated complaints.
3. Investigate regions with comparatively high churn.
4. Prioritize retention of high-value Business customers.
5. Investigate the reasons behind higher churn among Premium customers.
6. Monitor churn and customer behaviour regularly using the dashboard.

## Dashboard Preview

### Overview
![Overview](Dashboard_Screenshots/Overview.png)

### Customer Behaviour
![Customer Behaviour](Dashboard_Screenshots/Customer_Behaviour.png)

### Revenue
![Revenue](Dashboard_Screenshots/Revenue.png)

### Churn
![Churn](Dashboard_Screenshots/Churn.png)

## Project Documentation

The complete project documentation is available here:

[View Project Documentation](Documentation/Telecom_Customer_Churn_Analysis_Project_Report.pdf)

## Conclusion

The analysis provides a data-driven view of customer retention,
customer behaviour, and revenue performance. The findings can support
targeted retention strategies by identifying customer segments and
behavioural patterns associated with higher observed churn.
