# Employee_churn_analytics_pipeline-
Overview

Employee attrition is a major challenge for organizations, leading to increased hiring costs, reduced productivity, and loss of experienced talent. This project develops an end-to-end analytics pipeline using the Google Cloud ecosystem to analyze employee attrition, uncover workforce trends, and support proactive retention strategies through interactive dashboards and predictive analytics.

This project demonstrates an end-to-end analytics workflow using Google's cloud ecosystem, transforming raw employee data into actionable insights through SQL, BigQuery, Python, and Looker Studio. Beyond predicting employee attrition, the solution provides interactive dashboards and business recommendations that enable HR teams to proactively identify retention risks and support data-driven workforce planning.

Business Problem

Organizations often struggle to identify employees who are likely to leave before attrition occurs.

Without timely insights:

Employee turnover increases recruitment costs.
Workforce planning becomes reactive.
Managers lack visibility into factors influencing attrition.
HR teams cannot prioritize high-risk employees effectively.

This project aims to transform raw employee data into actionable insights that support data-driven workforce planning.

Objectives
Clean and validate employee data.
Build an end-to-end analytics workflow using Google Cloud tools.
Analyze employee attrition trends.
Develop interactive dashboards for business users.
Predict employee churn using machine learning.
Generate actionable recommendations to improve employee retention.
Dataset

IBM HR Analytics Employee Attrition Dataset

Features include:

Age
Department
Job Role
Monthly Income
Years at Company
Overtime
Job Satisfaction
Work-Life Balance
Attrition Status

Total Records: 1,470

Google Sheets
      │
      ▼
Data Cleaning
      │
      ▼
Google BigQuery
      │
SQL Joins & Aggregations
      │
      ▼
Google Colab
      │
EDA + Feature Engineering
      │
      ▼
Random Forest Model
      │
Predictions written to BigQuery
      │
      ▼
Looker Studio Dashboard

Target Variable:

Employee Attrition (Yes/No)
