# HR-Analytics--Power-BI
A Power BI dashboard analyzing key HR metrics to identify and understand factors driving employee attrition.

# HR Attrition Analysis Dashboard

This repository contains a Power BI dashboard designed to analyze HR data for understanding employee attrition trends and identifying key factors influencing turnover. The dashboard leverages various employee attributes to provide comprehensive insights into workforce dynamics, enabling HR and management teams to make informed decisions about retention strategies.

## Features
- **Attrition Overview**: Visualizes the overall attrition rate and trends over time.
- **Demographic Breakdown**: Provides insights by Age, Age Group, Gender, and Marital Status, allowing users to identify demographic groups with higher attrition risk.
- **Job and Compensation Analysis**: Examines the impact of attributes such as Job Level, Monthly Income, Salary Slab, Stock Option Level, and Percent Salary Hike on attrition.
- **Workplace Satisfaction & Engagement**: Analyzes factors like Environment Satisfaction, Job Satisfaction, Relationship Satisfaction, and Work-Life Balance to determine their influence on employee turnover.
- **Performance & Tenure Analysis**: Evaluates the correlation of Performance Rating, Total Working Years, Years at Company, Years in Current Role, and Years with Current Manager with attrition.
- **Training & Development**: Includes metrics such as Training Times Last Year and Num Companies Worked to understand how career development impacts employee retention.
- **Interactive Filters**: Allows users to drill down into specific departments, roles, or groups for targeted insights.

## Data Columns
The dataset includes a range of attributes providing insights into employee demographics, compensation, job satisfaction, and engagement. Key columns include:

- **Employee Details**: 
  - `EmpID`, `Age`, `AgeGroup`, `Gender`, `MaritalStatus`
  
- **Work and Compensation**: 
  - `Department`, `JobRole`, `JobLevel`, `MonthlyIncome`, `SalarySlab`, `HourlyRate`, `DailyRate`, `MonthlyRate`, `StockOptionLevel`, `StandardHours`
  
- **Engagement and Satisfaction**: 
  - `EnvironmentSatisfaction`, `JobInvolvement`, `JobSatisfaction`, `RelationshipSatisfaction`, `WorkLifeBalance`
  
- **Performance & Tenure**: 
  - `YearsAtCompany`, `YearsInCurrentRole`, `YearsSinceLastPromotion`, `YearsWithCurrManager`, `PerformanceRating`, `TotalWorkingYears`
  
- **Additional Factors**: 
  - `BusinessTravel`, `DistanceFromHome`, `OverTime`, `PercentSalaryHike`, `NumCompaniesWorked`, `TrainingTimesLastYear`

## Usage
1. **Clone** the repository and open the Power BI file.
2. **Connect** to your HR data source, if needed, and refresh the visuals.
3. Use the **interactive dashboard** features to explore trends in attrition, analyze factors driving turnover, and identify high-risk employee groups.
4. Utilize **filters** to focus on specific attributes like Job Role, Department, or Age Group for deeper insights.

## Purpose
This dashboard serves as a powerful tool for HR teams to analyze attrition trends, understand key drivers, and design strategies for improving employee retention and engagement.

---

# HR Attrition Analysis Dashboard

This Power BI dashboard provides an in-depth analysis of employee attrition, helping HR teams and management understand key factors influencing turnover and design data-driven retention strategies.

## Dashboard Overview

- **Attrition Rate Overview**: Visualizes overall attrition rate and trends over time to monitor changes in turnover.
- **Demographic Breakdown**: Analyzes attrition by Age, Gender, Marital Status, and other demographics, identifying high-risk groups.
- **Job and Compensation Analysis**: Examines the impact of Job Level, Monthly Income, Salary Slab, and other compensation factors on attrition.
- **Satisfaction & Engagement**: Evaluates Environment Satisfaction, Job Satisfaction, Work-Life Balance, and other engagement metrics to understand their effect on retention.
- **Performance & Tenure Analysis**: Assesses relationships between Performance Rating, Years at Company, and other tenure metrics with attrition risk.
- **Training & Development**: Highlights the role of Training and Num Companies Worked in influencing employee retention.
- **Interactive Filters**: Enables filtering by Department, Job Role, Age Group, etc., for targeted analysis of specific employee segments.

## Key Data Columns

The dashboard leverages various employee attributes, including:
- **Employee Details**: `EmpID`, `Age`, `Gender`, `MaritalStatus`
- **Work & Compensation**: `Department`, `JobRole`, `MonthlyIncome`, `StockOptionLevel`
- **Engagement & Satisfaction**: `EnvironmentSatisfaction`, `JobSatisfaction`, `WorkLifeBalance`
- **Performance & Tenure**: `YearsAtCompany`, `PerformanceRating`
- **Additional Factors**: `BusinessTravel`, `DistanceFromHome`, `OverTime`

## Usage

1. **Clone** the repository and open the Power BI file.
2. **Connect** to your HR data source if necessary.
3. Explore the dashboard to analyze attrition trends and key drivers using interactive filters for in-depth insights.

---

This dashboard equips HR teams with actionable insights for proactive retention and engagement strategies.

