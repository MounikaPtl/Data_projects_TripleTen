
# E-commerce Business Analyst Project

This is my third project completed as part of the TripleTen Business Intelligence Analyst Program. It is a solo project aimed at demonstrating my proficiency in Business Analytics using Google Sheets. The project involved analyzing raw transaction logs to derive meaningful business metrics.

## Google Spreadsheet
You can view the completed project [here]([link-to-your-google-sheet](https://docs.google.com/spreadsheets/d/19_AGIL8kc6Zi7fVXGLzxMUswaJSL6mAPQgPtXFQGDOs/edit?gid=38637670#gid=38637670)).

## Table of Contents

| File Number | Title                      | Description                                                                                                 |
|-------------|----------------------------|-------------------------------------------------------------------------------------------------------------|
| 1           | [README.md](README.md)     | This document, which includes an overview and details about the project.                                   |
| 2           | [Requirements.txt](Requirements.txt) | A text file detailing the project requirements as provided by TripleTen.                                    |

## Section Titles and Descriptions

### Data

The dataset provided was a Google spreadsheet with raw transaction logs:

- **Business Analyst Project.csv**: Contains raw user activity logs.
  - **raw_user_activity**: Records each activity or event by a user on the company's website.
    - `user_id`: Unique customer IDs
    - `event_type`: Type of activity by the user
    - `category_code`: Category of the product being viewed or purchased
    - `brand`: Company that manufactures the product
    - `price`: Price of the product in USD
    - `event_date`: Date of the user activity in YYYY-MM-DD format
  - **Table of Contents**: Preformatted sheet for project organization.
  - **Executive Summary**: Preformatted sheet for summarizing results and analysis.

### Description

The final product is an 8-page Google spreadsheet, which includes:

- Raw data
- Processed data
- Data analysis
- Pivot tables

The goal was to analyze the company's raw transaction logs and convert event logs into actionable business metrics.

### Assumptions

- The "raw_user_activity" sheet accurately reflects all relevant website activity.
- Any missing values or inconsistencies in the data are minimal and considered negligible.
- The dataset's format (columns and data types) is correct and consistent.

### Process

1. **Data Exploration and Cleaning**: Initial data review and preparation.
2. **Conversion Funnel Creation**: Built a funnel to understand user behavior from page views to purchases.
3. **Data Preparation for Cohort Analysis**: Filtered and organized data for cohort analysis.
4. **Retention Rate Calculation**: Analyzed retention rates across different cohorts.
5. **Finalization**: Enhanced formatting and documentation for clarity and presentation.

### Findings

| Results          | Synopsis                                                                                           |
|------------------|----------------------------------------------------------------------------------------------------|
| Conversion Funnel | The conversion rate from clicks to purchases is 10%, indicating a substantial drop-off in the purchasing process. |
| Retention Rates   | For the cohort starting in September 2020, the retention rate was 12.5% after the first month, declining to 3% by the fourth month. |

- The website’s conversion funnel reveals that while the transition from the shopping cart to purchase is relatively efficient, the overall conversion rate from initial page views to purchases is lower.
- Retention analysis shows a consistent drop in user retention over time, with notable exceptions in specific cohorts.
