# WGL Expenses Power BI Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

# Overview

The WGL Expenses Dashboard is a comprehensive Power BI project developed to analyze and monitor expense data related to the WGL (Work Group Ledger). It provides insights into various spending categories, departmental usage, monthly trends, and helps in budget vs. actual comparison.

# Data Sources

Internal Excel or SQL-based datasets related to:

Expense Categories

Departmental Budgets

Monthly Expenditures

Vendor Details (if applicable)

# Data Model

Fact Table: Expenses

Dimension Tables:

Department

Category

Date

Vendors

Relationships built on keys like DepartmentID, CategoryID, DateKey.

# DAX Measures

Sample DAX measures:

Total Expenses = SUM(Expenses[Amount])
Monthly Average = AVERAGEX(VALUES(Date[Month]), [Total Expenses])
Budget Variance = [Budgeted Amount] - [Total Expenses]

# Key Visuals

Bar chart: Expense by Department

Line chart: Monthly Expense Trend

Pie chart: Expense Breakdown by Category

Card: Total Expenses / Average Monthly Expense

Matrix Table: Department vs. Monthly Expense Comparison

# Use Case

This dashboard is useful for:

Finance teams to monitor department-wise expenses

Auditing and controlling excessive or unplanned spending

Visualizing spending trends and making data-driven decisions

# How to Use

Open the .pbix file in Power BI Desktop.

Use filters to slice data by:

Year

Department

Expense Category

Hover over visuals for tooltips and insights.

