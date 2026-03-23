## Customer Churn Analysis & Retention Strategy (Python + Power BI)
# Overview

This project performs an end-to-end analysis of customer churn using the IBM Telco dataset, with a primary focus on Python-based data analysis, feature engineering, and business logic development.

The project identifies key churn drivers, high-risk customer segments, and revenue at risk, and implements a rule-based retention strategy framework, with insights visualized through a Power BI dashboard.

# Objective
Analyze customer churn using Python
Perform feature engineering to uncover behavioral patterns
Identify high-risk customer segments
Quantify revenue impact
Design actionable retention strategies

# Tools & Technologies
Python – Data analysis and logic building
Libraries – Pandas, NumPy, Matplotlib, Seaborn
Power BI – Dashboard visualization

 # Dataset
Source: IBM Telco Customer Churn Dataset
Records: ~7,000 customers
Features: Demographics, services, billing, tenure, and churn status

# Python Analysis
🔹 Data Cleaning
Handled missing values in TotalCharges
Converted data types for numerical analysis
Standardized categorical variables
🔹 Exploratory Data Analysis (EDA)
Analyzed churn distribution across contract types, tenure, and services
Identified early churn trends and high-risk segments
Visualized patterns using Matplotlib and Seaborn
🔹 Feature Engineering
num_services → Total services subscribed per customer (engagement metric)
High Value Customers → Identified using monthly charges threshold
Tenure Groups → Segmented customers by lifecycle stage
Customer Segments → Combined churn and value classification
🔹 Action Framework (Key Highlight)

Implemented a rule-based retention strategy:

High-value customers → VIP Support
Early tenure customers → Onboarding Engagement
Month-to-month customers → Contract Conversion Offers
Low engagement customers → Service Bundling
Customers without tech support → Support Upsell

# Key Insights
Month-to-month contracts have the highest churn rates
Customers within the first 6 months are most likely to churn
Low service adoption strongly increases churn probability
High-value customers contribute the most to revenue loss
Lack of tech support is strongly associated with churn

# Power BI Dashboard

A 4-page interactive dashboard was created to present insights:

Executive Summary
Customer Lifecycle Analysis
Churn Drivers
Financial Impact

 Focus: Translating Python-based analysis into business insights

# Repository Structure
Customer-Churn-Analysis
 ┣ telco_analysis.ipynb
 ┣ dashboard.pbix
 ┣ images/
 ┗ README.md

 # How to Use
Run the Jupyter Notebook to explore the analysis
Open the .pbix file in Power BI Desktop to view the dashboard

 #Business Impact

This project demonstrates how Python-driven analysis can:

Identify churn drivers
Segment customers effectively
Enable targeted retention strategies
Quantify revenue risk

 # Key Learnings
Feature engineering for behavioral analysis
Translating data into actionable insights
Combining Python analysis with business-focused visualization
# Final Note

This project highlights the use of Python not just for analysis, but for:

Building business logic
Creating actionable frameworks
Driving data-informed decision making
