# HR Attrition & Workforce Insights Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Analysis-CC2927?logo=microsoftsqlserver&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-217346?logo=microsoftexcel&logoColor=white)

## Project Overview

This is my HR analytics portfolio project, focused on exploring employee workforce data to identify trends in attrition, department distribution, salaries, performance, hiring, and employee experience.

I am using Excel for data preparation, SQL Server for analysis, and Power BI for an interactive dashboard.

> This project began as an open-source reference project. I am personalizing the analysis, documentation, dashboard design, and business insights as part of my data-analytics portfolio.

## Business Questions

This dashboard answers the following HR questions:

- What is the overall employee attrition rate?
- Which departments and job roles have the highest attrition?
- How do salary and experience vary by department and gender?
- How has hiring changed over time?
- Which employee groups may need retention-focused attention?

## Tools Used

- Microsoft Excel — data cleaning and quality checks
- SQL Server — data analysis using queries and aggregate functions
- Power BI — dashboard development and visual storytelling
- DAX — KPI and calculated-measure creation

## Dashboard Features

The Power BI dashboard includes:

- Total employees, active employees, resigned employees, and attrition-rate KPIs
- Employee distribution by department, gender, job role, and status
- Salary and experience analysis
- Employee performance overview
- Hiring trend analysis
- Department, gender, and employee-status filters
- Employee-level detail page

## Key Insights

The current dataset contains 50 unique employee records after duplicate removal.

Initial analysis shows:

1. Employee attrition is high in the available dataset.
2. Sales has the largest employee population.
3. Salary and experience vary across job roles and departments.
4. The dashboard enables HR teams to investigate workforce patterns using interactive filters.

> These findings are based on a small sample dataset and are intended for portfolio demonstration and exploratory analysis.

## Repository Files

```text
HR_ANALYTICS/
├── HR-Data-Analysis-SQL.sql
├── HR_data.csv.xlsx
├── Hr Analytics Dashboard.pbix
├── README.md
├── page1-hr-analytics.png.png
└── page2-employee-details.png.png
```

## How to View the Project

1. Download or clone this repository.
2. Open `Hr Analytics Dashboard.pbix` with Power BI Desktop.
3. Use the slicers and filters to explore workforce segments.
4. Open `HR-Data-Analysis-SQL.sql` in SQL Server Management Studio to review the analysis queries.

## Next Improvements

- Redesign the dashboard with my own visual theme and layout
- Add department-wise attrition comparisons
- Add salary-band analysis
- Add more detailed retention recommendations
- Use a larger HR dataset for deeper analysis

## Author

**Vivek Rathan**  
B.Tech Student | Aspiring Data Analyst  
Skills: SQL, Power BI, Excel, Data Analysis