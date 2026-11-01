# Payroll Analysis Dashboard

## Project Overview

The Payroll Analysis Dashboard is a data analytics project developed using Microsoft Power BI.

The purpose of this project is to analyse employee payroll data and understand salary expenses, deductions, and net payroll distribution.

This dashboard helps users monitor payroll information and gain meaningful insights into employee compensation.

## Business Objectives

The main objectives of this project are:

- Analyse total gross payroll and net payroll.
- Understand total employee deductions.
- Calculate average employee salary.
- Monitor employee headcount.
- Analyse payroll expenses across departments.
- Identify patterns and trends in employee compensation.
- Present payroll information through interactive visualizations.

- ## Tools & Technologies Used

- **Microsoft Power BI:** Used to create the interactive payroll dashboard.
- **Power Query:** Used for data cleaning and transformation.
- **DAX (Data Analysis Expressions):** Used to create calculated measures and perform payroll calculations.
- **Microsoft Excel:** Used as the source of payroll and employee data.

- ## Dataset Description

This project uses employee and payroll-related data organised into three tables:

### 1. Employees Table
Contains employee-related information such as:
- Employee ID
- Employee Name
- Department

### 2. Payroll Table
Contains payroll and salary-related information such as:
- Gross Pay
- Net Pay
- Deductions

### 3. Department Table
Contains department-related information used for analysing payroll across different departments.

These tables are used together to analyse employee compensation and payroll expenses.

## Data Cleaning & Transformation

Data cleaning and transformation were performed using Power Query in Microsoft Power BI.

The following steps were carried out:

- Checked column names and corrected inconsistencies.
- Verified and corrected data types.
- Identified and handled missing values.
- Removed unnecessary columns where required.
- Checked for duplicate records.
- Used Trim and Clean transformations to remove unwanted spaces and characters.
- Ensured numerical columns had appropriate data types.
- Applied the transformations before loading the data into Power BI.

These steps helped improve data quality and prepare the dataset for analysis.

## Data Modelling

Data modelling was performed in Power BI to establish relationships between the three tables.

- Connected the Employees, Payroll, and Department tables.
- Created relationships using the relevant employee and department keys.
- Used the data model to combine information from multiple tables.
- Ensured the relationships supported accurate payroll analysis and reporting.

The data model helped organise the data and enabled analysis across different departments and employees.

## DAX Measures

DAX (Data Analysis Expressions) was used in Power BI to create measures for payroll calculations and business analysis.

The following measures were created:

- **Total Gross Payroll:** Calculates the total gross salary paid to employees.
- **Total Net Payroll:** Calculates the total net salary received by employees.
- **Total Deductions:** Calculates the total deductions from employee salaries.
- **Average Gross Salary:** Calculates the average gross salary of employees.
- **Total Employees:** Calculates the total employee headcount.

These measures were used to display key payroll metrics and support interactive data analysis.

## Dashboard Pages

The Power BI dashboard consists of three interactive pages:

### 1. Payroll Overview
Provides a summary of overall payroll performance using key performance indicators (KPIs), including:
- Total Gross Payroll
- Total Net Payroll
- Total Deductions
- Average Gross Salary
- Total Employees

### 2. Department Analysis
Focuses on analysing payroll distribution across different departments. It helps compare salary expenses and understand departmental payroll patterns.

### 3. Employee Analysis
Provides an employee-level view of payroll information to support analysis of individual employee compensation and salary distribution.

## Key Insights

The dashboard enables users to:

- Monitor overall gross and net payroll expenses.
- Understand the total deductions from employee salaries.
- Evaluate average gross salary and employee headcount.
- Compare payroll distribution across departments.
- Explore employee-level compensation details.
- Identify payroll patterns through interactive visualizations.
- Use slicers to filter and analyse payroll information from different perspectives.




