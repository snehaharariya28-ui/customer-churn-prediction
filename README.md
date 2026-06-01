# Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn for a utility service provider using machine learning and business analytics techniques. The goal is to identify customers who are likely to leave the service and provide actionable insights to support customer retention strategies.

The project combines data cleaning, exploratory data analysis (EDA), feature engineering, machine learning, business insights, and Power BI dashboarding to deliver an end-to-end churn analysis solution.


## Dataset Source
The dataset used in this project was provided as part of the BCG X Data Science Virtual Experience Program hosted on Forage. The dataset represents customer information from a utility company (Powerco) and was used for educational and portfolio purposes.


## Problem Statement
Customer churn is a major challenge for utility companies because acquiring new customers is often more expensive than retaining existing ones. The objective of this project is to analyze customer behavior, identify key factors influencing churn, and build a machine learning model capable of predicting customers who are likely to leave the service.


## Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Machine Learning Model Development
5. Model Evaluation
6. Business Insights Generation
7. Power BI Dashboard Development


## Tools & Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn
* Jupyter Notebook
* Power BI

## Machine Learning Models

### Logistic Regression

* Accuracy: 89.6%
* Churn Recall: 0.01
* Correctly identified only 4 churn customers

### Balanced Logistic Regression

* Accuracy: 58.7%
* Churn Recall: 0.55
* Correctly identified 168 churn customers

### Final Model Selection

Balanced Logistic Regression was selected as the final model because it significantly improved churn detection despite a lower overall accuracy. In churn prediction, identifying customers at risk of leaving is more important than maximizing overall accuracy.


## Key Business Insights
* Overall churn rate is approximately 9.72%.
* Pricing-related variables were among the strongest churn indicators.
* Customer value metrics played an important role in churn prediction.
* Class imbalance significantly affected model performance.
* Balanced Logistic Regression improved churn detection substantially.


## Dashboard
The project includes an interactive Power BI dashboard featuring:

* Total Customers
* Churn Customers
* Churn Rate
* Churn Distribution
* Churn by Sales Channel
* Customer Tenure vs Churn


## Repository Structure
data/
docs/
notebooks/
outputs/
powerbi/
.gitignore
README.md
requirements.txt


## Author
Created as a portfolio project to demonstrate end-to-end data analytics and machine learning skills.
