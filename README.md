# Bank-Customer-Churn-Analysis-Dashboard

### Dashboard Type : Power BI Desktop (Local Project)

---

## Problem Statement

This dashboard helps the bank understand customer churn behavior and identify key factors influencing customer attrition.  
It provides insights into overall churn rate, customer retention, engagement levels, and financial characteristics of customers.

Through demographic and financial analysis, the bank can identify **which customers are leaving and why**, enabling targeted retention strategies.  
The dashboard also highlights high-risk customer segments based on activity status and financial indicators.

---

## Steps followed

- Step 1 : Loaded customer churn dataset into Power BI Desktop (Excel file).
- Step 2 : Opened Power Query Editor and enabled **Column distribution**, **Column quality**, and **Column profile**.
- Step 3 : Changed profiling settings to analyze the entire dataset instead of the default 1000 rows.
- Step 4 : Cleaned and validated data, ensuring no critical null or error values impacted KPI calculations.
- Step 5 : Created calculated columns to group customers into meaningful segments such as age groups and balance ranges.
- Step 6 : Designed DAX measures for KPIs including churn rate, retention rate, total customers, active and inactive customers.
- Step 7 : Built **Page 1 – Executive Overview** with key KPIs and churn risk indicators.
- Step 8 : Built **Page 2 – Demographic Churn Analysis** focusing on age and gender-based churn patterns.
- Step 9 : Built **Page 3 – Financial Drivers of Churn** analyzing credit score and account balance impact.
- Step 10 : Applied consistent theme, layout, and formatting for professional dashboard presentation.
- Step 11 : Created slicers for interactive filtering and drill-down analysis.
- Step 12 : Validated insights across different filters to ensure accuracy and consistency.

---

## Dashboard Structure

### Page 1 : Executive Overview
- Total Customers
- Churn Rate
- Retention Rate
- Active vs Inactive Customers
- Churn Risk Overview

### Page 2 : Demographic Churn Analysis
- Churn Rate by Age Group
- Customer Distribution by Age Group
- Churn Rate by Gender
- Customer Distribution by Gender

### Page 3 : Financial Drivers of Customer Churn
- Churn Rate by Credit Score Range
- Customer Distribution by Credit Score Range
- Churn Rate by Account Balance Range
- Customer Distribution by Account Balance Range

---
## Dashboard Screenshots

### Page 1: Executive Overview
![Executive Overview](Screenshots/page1_executive_overview.png)

### Page 2: Demographic Churn Analysis
![Demographic Analysis](Screenshots/page2_demographic_analysis.png)

### Page 3: Financial Drivers of Customer Churn
![Financial Drivers](Screenshots/page3_financial_drivers.png)
