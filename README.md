

                                                📊 HR Attrition Analysis
📌 Project Overview

Employee attrition is a major challenge for organizations as it directly impacts productivity, hiring costs, and team stability.
This project analyzes HR data to identify key factors influencing employee attrition and provides actionable insights to help reduce turnover.

The analysis was performed using Python, MySQL, and Power BI, following a structured data pipeline approach.

🎯 Objective

The main goal of this project is to:

Calculate overall attrition rate

Identify high-risk departments and job roles

Analyze the impact of job satisfaction, salary, tenure, and commute distance

Provide HR-focused recommendations to improve employee retention

🛠 Tools & Technologies Used

Python – Data cleaning and preprocessing

MySQL – Data storage and SQL-based analysis

Power BI – Interactive dashboard and visualization

Pandas & SQLAlchemy – Data manipulation and database connectivity

🔄 Project Workflow

Data Collection

HR dataset containing employee demographics, satisfaction metrics, salary details, and attrition status.

Data Storage

Raw data stored in MySQL database.

Data Cleaning (Python)

Removed unnecessary columns (IDs, constant values, redundant salary fields)

Handled missing values

Created new features:

AgeGroup

SalaryBucket

DistanceGroup

Saved cleaned dataset back to MySQL and exported as CSV

Exploratory Data Analysis (SQL & Python)

Calculated attrition rate

Department-wise attrition

Job role-based analysis

Satisfaction and overtime impact

Dashboard Creation (Power BI)

Designed an interactive HR Attrition dashboard

Added KPIs, trend analysis, and filtering options

Highlighted key insights and HR recommendations

📊 Dashboard Highlights

The dashboard includes:

✔ Total Employees

✔ Attrition Count

✔ Attrition Rate (%)

✔ Attrition by Job Role

✔ Attrition by Department

✔ Attrition by Years at Company

✔ Job Satisfaction Analysis

✔ Age Group & Distance Impact

✔ Key Insights Section

The layout is structured to allow HR managers to quickly understand turnover patterns and drill down using filters.
<img width="1165" height="649" alt="image" src="https://github.com/user-attachments/assets/7ec79bc7-35bf-4582-9a54-2a680cbfffed" />


🔍 Key Insights

Sales Representatives show the highest attrition.

Most employee exits occur within the first 5 years.

Low job satisfaction strongly correlates with attrition.

Adult age group and longer commute distance show higher exit trends.

💡 HR Recommendations

Implement targeted retention programs for high-risk job roles.

Strengthen onboarding and early career engagement initiatives.

Improve job satisfaction through feedback and engagement strategies.

Consider flexible work policies for employees with longer commute distances.

📁 Repository Structure
|
│── hr_attrition_cleaned.csv
├
│── data_cleaning.py
├
│── analysis_queries.sql
├
│── HR_Attrition_Dashboard.pbix
└── README.md

📈 Business Impact

This dashboard transforms raw HR data into a decision-support tool.
Instead of just reporting attrition numbers, it identifies patterns and actionable drivers of employee turnover.

It enables HR teams to move from reactive hiring to proactive retention planning.

🚀 Future Improvements

Predictive attrition modeling using machine learning

Department-level deep-dive dashboards

Integration with real-time HR systems

Automated reporting pipeline

👤 Author

Md Zulkar Nain
B.Tech CSE (AI & ML)
Focused on Data Analytics and Business Intelligence

