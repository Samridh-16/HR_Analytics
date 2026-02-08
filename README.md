# HR Analytics – Employee Attrition Analysis

## Overview

This project analyzes the IBM HR Analytics Attrition dataset sourced from Kaggle to understand workforce trends and identify factors influencing employee attrition.

The objective is to simulate how an HR department can use data analytics to monitor attrition rates, evaluate employee satisfaction, assess compensation impact, and identify high-risk employees. The project integrates Python for data preprocessing, SQL for business-focused analysis, and Power BI for dashboard visualization.

---

## Tech Stack

- **Python (Pandas)** – Data cleaning and feature engineering
- **SQL (MySQL / BigQuery syntax)** – Attrition analysis and risk modeling
- **Power BI** – Interactive HR analytics dashboard

---

## Dataset Source

**IBM HR Analytics Attrition Dataset (Kaggle):**

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## Repository Structure

### Dashboard

Contains Power BI dashboard screenshots visualizing attrition rate, department analysis, income segmentation, satisfaction scores, and employee risk categories.

### Dataset

Includes:

- Raw dataset
- Cleaned dataset used for analysis and dashboard creation

### Python

Contains preprocessing scripts used to:

- Handle missing values
- Create tenure and income segments
- Engineer attrition indicators
- Prepare structured dataset for SQL analysis

### SQL Query

Business-driven SQL queries addressing attrition rate calculation, department risk analysis, income quartile segmentation, satisfaction score impact, and employee risk scoring.

### SQL Query Results

Contains query outputs used to validate KPIs and dashboard metrics.

---

## Cleaned Dataset – Data Dictionary

The cleaned dataset (`WA_Fn-UseC_-HR-Employee-Attrition_checked.csv`) contains the following key variables:

| Column Name | Description |
|---|---|
| EmployeeNumber | Unique employee identifier |
| Age | Employee age |
| Attrition | Indicates whether employee left the company (Yes/No or Boolean) |
| BusinessTravel | Travel frequency for work |
| Department | Department of employee (Sales, HR, R&D) |
| DistanceFromHome | Distance between home and workplace |
| Education | Education level (numeric category) |
| EducationField | Field of education |
| EnvironmentSatisfaction | Satisfaction with work environment (1–4 scale) |
| Gender | Employee gender |
| JobRole | Employee job role |
| JobLevel | Job seniority level |
| JobSatisfaction | Job satisfaction rating (1–4 scale) |
| MaritalStatus | Marital status of employee |
| MonthlyIncome | Monthly salary |
| NumCompaniesWorked | Number of previous companies worked at |
| OverTime | Indicates overtime work (Yes/No) |
| PercentSalaryHike | Percentage salary increase |
| PerformanceRating | Performance rating score |
| RelationshipSatisfaction | Relationship satisfaction score |
| StockOptionLevel | Stock option level assigned |
| TotalWorkingYears | Total years of professional experience |
| TrainingTimesLastYear | Number of training sessions attended last year |
| WorkLifeBalance | Work-life balance rating (1–4 scale) |
| YearsAtCompany | Years worked at the company |
| YearsInCurrentRole | Years in current job role |
| YearsSinceLastPromotion | Years since last promotion |
| YearsWithCurrManager | Years with current manager |

---

## Analytical Scope

This project includes:

- Overall attrition rate calculation
- Department-wise attrition comparison
- Income quartile attrition analysis
- Age-group attrition segmentation
- Satisfaction score impact analysis
- Work environment risk evaluation
- High-risk employee identification logic

### Advanced SQL Techniques Applied:

- Common Table Expressions (CTEs)
- NTILE quartile segmentation
- Conditional risk scoring
- Attrition percentage calculations
- Multi-factor grouping and ranking

---

## Key Business Insights

- Attrition is higher in certain departments, particularly Sales.
- Entry-level and lower-income employees show significantly higher attrition.
- Employees with lower job satisfaction and work-life balance scores exhibit greater churn risk.
- Delayed promotions and extended stagnation periods increase attrition probability.

---

## Business Objective

To identify structural, compensation-related, and engagement-driven factors contributing to employee attrition, enabling HR teams to design targeted retention and workforce stability strategies.
