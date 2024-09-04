
# Zomato User Analysis Report

## Project Overview

This report presents an analysis of Zomato's user data, focusing on key demographic and engagement metrics. The goal is to understand user behaviors, income distribution, and educational backgrounds to refine marketing strategies and improve user engagement. By analyzing patterns in order volume, income, and education, the report aims to provide actionable insights that can help Zomato optimize its offerings and strategies to better serve its diverse user base.

## Table of Contents


| Section Title | Description                                                                                                                                               |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| `DATA`          | Describes the source of data, including files, tables, and fields.                                                                                         |
| `Description`   | Describes the final product's purpose, software, format, and included visuals.                                                                            |
| `Assumptions`   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task.                                                      |
| `Process`       | A general outline of how this project formed from start to finish.                                                                                        |
| `Findings`      | Insights learned from the data analysis.                                                                                                                  |

## Data

The analysis utilizes the following datasets provided by TripleTen:

- **`Zomato Data Orders & Users`**: The original datasets used for analysis.
- **`orders`**: Records of all orders made from various restaurants between October 4, 2017, and June 26, 2020.
- **`users`**: Demographic information of customers who placed orders during the specified period.
- **`restaurants`**: Information about the restaurants from which orders were made.

Certainly! Here’s a refined and professional GitHub User Analysis Report focusing on the **Description**, **Assumptions**, **Process**, and **Findings** sections.

---

# Zomato User Analysis Report

## Description

This repository contains the analysis of Zomato's user data, aiming to provide actionable insights into user demographics, income distribution, and engagement patterns. The analysis was conducted using the datasets provided by the TripleTen Business Intelligence Analytics Program. The main objective is to uncover trends and patterns that can help optimize marketing strategies and improve user engagement.

### Components:

1. **Zomato Data Users**: Original dataset containing user demographic information.
2. **Zomato User Analysis Report.pdf**: A comprehensive report summarizing the analysis findings and recommendations.
3. [README.md](README.md)  This file, providing an overview and instructions for the repository.
4. [Requirements.txt](Requirements.txt): A file listing the project requirements provided by TripleTen.

## Assumptions
1. **Data Accuracy**: The provided datasets are accurate and reflect real user behaviors and characteristics.
2. **Minimal Missing Values**: Any missing values or inconsistencies in the data are minimal and do not significantly impact the overall analysis.
3. **Column Descriptions**: The descriptions of columns in the datasets accurately represent the data they contain.
4. **Relevance of Tables**: The datasets provided (orders, users, and restaurants) include all necessary information for the analysis.
5. **Business Context**: The analysis considers Zomato's business context and industry trends, which may affect the interpretation of the data.

## Process

### 1. Data Preparation

- **Data Collection**: Extracted relevant data from the `orders` and `users` datasets.
- **Data Cleaning**: Addressed issues such as duplicate entries, missing values, and inconsistent formats.
- **Data Transformation**: Normalized data where necessary, created calculated fields to facilitate analysis, and merged tables based on common keys.

### 2. Data Analysis

- **Statistical Analysis**: Performed statistical analysis to identify key trends, correlations, and patterns within the data.
- **Visualization**: Created visualizations using Tableau to effectively communicate insights and trends.

### 3. Visualization

- **Tableau Dashboard**: Developed an interactive dashboard to allow users to explore key metrics and insights dynamically.

### 4. Reporting

- **Report Creation**: Compiled findings into a comprehensive report, summarizing key insights and providing actionable recommendations.
Certainly! Here's a concise and constructive summary of the findings for the Zomato User Analysis:

## Findings

1. **Age Distribution**:
   - **18-24 Years**: Dominates order volume, with many users in the "No Income" bracket. Primarily students with high engagement.
   - **25-34 Years**: Shows significant order volume, especially among higher income brackets. Greater interest in premium offerings.

2. **Income Bracket Insights**:
   - **Younger Users (18-24 Years)**: Predominantly in the "No Income" and lower income brackets.
   - **Older Users (25-34 Years)**: More evenly distributed across income brackets, with a notable presence in higher income categories.

3. **Education and Income Correlation**:
   - **Students**: Mostly in the 18-24 age group, with high "No Income" representation.
   - **Housewives**: Significant in the 25-34 age group, reflecting non-earning status.

4. **Engagement Patterns**:
   - **High Engagement**: The 18-24 age group exhibits high frequency of orders.
   - **Sales Trends**: Higher sales volumes in the 25-34 age group, with increased spending in premium categories.

## Links

- **Tableau Public Dashboard**: [View Dashboard](https://public.tableau.com/app/profile/mounika.patlolla6755/viz/ZomatoDataAnalysis_17242855444160/Dashboard1?publish=yes) 
- **User Analysis Report**: [Download PDF Report](Analysis.pdf) 
- **Project Requirements**: [View Requirements.txt](Research.pdf) 
