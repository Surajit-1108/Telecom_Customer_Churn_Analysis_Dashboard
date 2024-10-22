# Telecom_Customer_Churn_Analysis
MySQL | Python (Jupyter Notebook) | Power BI

Project Objectives:
1. Analyze Customer Churn: Identify the key factors contributing to customer churn in the telecom industry by examining various customer demographics, contract types, and services.
2. Predict Customer Churn: Use historical data to predict which customers are most likely to churn and determine actionable insights to reduce churn.
3. Understand Churn Patterns: Investigate churn patterns across different segments such as age, tenure, and payment methods to assist in targeted retention strategies.

Steps:
1. Data Preparation:
   . Cleaned the dataset by handling missing values.
   . Encoded categorical variables and removed columns not essential for churn prediction.
2. Exploratory Data Analysis:
   . Visualized the distribution of customers across age groups, states, and tenure groups.
   . Identified churn rates by contract type, payment method, and internet service type using Power BI visuals.
3. Churn Prediction Model:
   . Applied machine learning techniques to predict the likelihood of churn.
   . Trained a model using Random Forest, evaluating it on test data to ensure accurate predictions.
4. Churn Rate Insights:
   . Analyzed customer churn by gender, age group, tenure, and service features to discover key drivers of churn.
   . Identified high-risk churn segments, such as customers with month-to-month contracts or specific states with higher churn rates.

Tools Used:
1. MySQL: For initial data cleaning, handling missing values, and creating views for model training.
2. Python (Jupyter Notebook): Used for machine learning model implementation, primarily Random Forest, for churn prediction.
3. Power BI: For data visualization and creating an interactive dashboard for presenting insights and key findings.

Insights Generated:
1. Overall Churn Rate: The churn rate was identified at 27%, with 1,732 customers having churned out of 6,418 total customers​.
2. Gender and Churn: The churn is significantly higher among female customers (65.45%) compared to male customers (34.54%)​.
3. Age and Churn: The highest churn rates are observed among the 20-40 age group and the 41-60 age group, indicating potential dissatisfaction or competition within these age groups.
4. Contract Type: Month-to-month contract holders had a significantly higher churn rate (46.5%) compared to customers with one or two-year contracts, suggesting long-term contracts reduce churn.
5. Payment Method: Customers using mailed checks or bank withdrawal methods showed higher churn rates compared to those using credit cards, suggesting a need for promoting more convenient payment options.
6. Service Impact: Fiber optic users experience the highest churn rate at 41.1%, followed by Cable at 25.7%, while DSL users show a much lower churn rate at 19.4%.
7. Churn by Region: Regional analysis shows that Jammu & Kashmir has the highest churn rate at 57.2%, followed by states like Assam and Jharkhand, indicating potential regional service issues or competitive pressures​.

. These insights suggest targeted interventions are necessary to reduce churn among younger customers, improve long-term contract adoption, and focus on regions and payment methods with higher churn risks.

