 # Telecom Customer Churn Analysis

📈 Predicting customer churn and identifying the key factors which will influence to retain customers in future

## Project Overview
In the telecom industry, customer churn (when customers leave the service) is a major challenge. This project analyzes customer data to identify the major factors contributing to customer churn and builds a predictive model to help telecom companies retain customers.

## Motivation
In the telecom industry, customers frequently switch providers, leading to an average annual churn rate of 15-25%. Since acquiring a new customer costs 5-25 times more than retaining one, customer retention is now a top priority.
![What-stops-customer-churn-Having-a-centralized-data-hub-does-and-heres-why](https://github.com/user-attachments/assets/212e3035-3120-4149-8978-e8e54677672f)


## Business Aspects of Telecom Customer Churn Analysis
### Business Goals

* Reduce Churn Rate: Identify key factors influencing customer churn and implement strategies to retain customers.

* Increase Customer Lifetime Value (CLV): Enhance loyalty programs, offer personalized discounts, and improve service quality.

* Optimize Marketing Efforts: Target high-risk customers with proactive retention campaigns.

* Improve Customer Service: Analyze customer support interactions to detect dissatisfaction early.

* Enhance Profitability: Reduce revenue loss by improving customer satisfaction and engagement.

### How This Dataset Helps?

* Usage Analysis: Understanding customer call and data usage patterns.

* Service Plan Impact: Evaluating how international plans and voicemail services affect retention.

* Customer Support Influence: Examining the effect of customer service calls on churn likelihood.

* High-Risk Customer Identification: Predicting customers most likely to leave and taking preventive actions.

## Techniques used in this project:
## 📊 Data Exploration & Preprocessing
### Data Loading: 
The dataset is imported using pandas, providing a structured format for analysis.

### Exploratory Data Analysis (EDA): 
Initial analysis includes checking for null values, understanding data types, and summarizing statistical properties.

### Data Cleaning: 
Drop unnecessary columns that don’t contribute to analysis and correcting data types and addressing inconsistencies to prepare the data.

## 🎯 Target Variable Analysis: churn
To understand the distribution of the target variable churn, the following steps were performed:

![Screenshot (1)](https://github.com/user-attachments/assets/3d0d802a-9c8c-4acb-b041-fc88db99b4a7)

## 📊 Output:
This provides both the raw counts and the percentages of customers who churned vs. those who did not. It helps identify if the dataset is imbalanced, which is critical when building classification models.

Understanding this distribution allows us to:

* Detect potential class imbalance
* Decide on the need for resampling techniques (like SMOTE or undersampling)
* Adjust class weights in models for better performance on the minority class

## 📈 Data Visualization
Analysis of the target variable: A pie chart is used in this kind of project to visualize the class distribution of the target variable — in this case, churn (e.g., Yes vs. No).

Univariate Analysis: Visualizations such as histograms and bar plots are used to understand the distribution of individual features.

Correlation Analysis: Heatmaps and correlation matrices identify relationships between numerical variables, aiding in feature selection.
 
## Source of dataset:
The dataset used in this project is sourced from Kaggle. You can access and download it from csv file folder
