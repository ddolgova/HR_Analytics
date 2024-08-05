# HR Analytics Report

## Interactive Power BI dashboard can be downloaded [here](https://www.microsoft.com).

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Modeling](#data-modeling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Insights](#results-and-insights)

### Project Overview

This project is an essential tool for HR professionals, providing a thorough analysis of HR data focusing on three main areas: Employee Headcount, Employee Retention, and Employee Turnover. The information included helps track patterns in the current workforce, changes over time, and other trends that can help guide HR decisions.

<img width="1274" alt="HR_Headcount" src="https://github.com/user-attachments/assets/baa70d34-2ba5-4a3f-bbad-b8238e371842">

<img width="1274" alt="HR_Retention" src="https://github.com/user-attachments/assets/a88421a7-d39c-437d-a7ab-a7df53c40a31">

<img width="1274" alt="HR_Turnover" src="https://github.com/user-attachments/assets/2fc809e9-0922-4ef0-8826-2f510661d35b">

### Data Sources

HR Analytics Data: The main datasets used for this report are the “Dates.xlsx”, "people_data.csv", and "people_employment_history.csv" files, which hold information about company employees, demographics, and employment timelines.

### Tools

- Excel: Data cleaning 
- Power Query Editor: Data cleaning, data modeling
- Power BI: Data analysis, data modeling, report building


### Data Cleaning and Preparation

In the first phase of data preparation, I went through the following procedure:

1. Loading the data and performing the initial assessment
2. Finding and treating missing and null values
3. Data formatting
4. Cleaning unnecessary special characters

### Data Modeling

In the next phase of data processing, I did the following:

1. Inspecting the source data to determine the best modeling approach
2. Referencing a clean copy of the source data to create the fact and dimension tables
3. Determining the cardinality and relationships between the fact and dimension tables
4. Creating some initial DAX measures

### Exploratory Data Analysis
EDA included investigating the housing data to answer the following questions:

How does employee headcount compare by different employee demographics
Which departments and job level have the most employees?
What is the general trend in employee retention over time?
What is the general trend in employee turnover over time?
What are the main reasons for employee turnover?
What do we know about employees who have left the company?

### Results and Insights

There are more male employees (61%) than female employees (39%).
The Software Department has the most employees (543) and Customer Service has the least employees (114). This is excluding the Executive Department, which has only 1 member.
There are more employees classified as Individual Contributor (2,094) than any other job level. The second most common job level is Team Lead (401 members).
Overall, employee retention has increased over time - 92.9% in 2013 and 97.3% in 2019.
Employee turnover has decreased over time - 5.7% in 2013 and 2.6% in 2019.
The main reason for employee turnover is better salary offer at their next position.
