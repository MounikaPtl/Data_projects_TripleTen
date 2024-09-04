# Analyzing High Return Rates at Superstore

### Description

In this project, we aim to analyze and understand the high volume of returned orders at Superstore using Tableau. The goal is to identify factors contributing to returns and propose strategies to reduce their frequency. This analysis will be presented through interactive dashboards, which will be accompanied by a detailed story and recommendations for the CEO of Superstore.

Tableau Public Share Link: [here](https://public.tableau.com/app/profile/mounika.patlolla6755/viz/Sprint5Project-MounikaPatlolla/Dashboard1?publish=yes).

## Table of Contents

| File Number | Title                                               | Description                                                                                                     |
|-------------|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| 1           | [DataSet_superstore.xlsx](DataSet_superstore.xlsx)  | The original data file provided by TripleTen that was used in this project's analysis.                          |
| 2           | [README.md](README.md)                              | This current page with all relevant information about the project, just past the Table of contents.             |
| 3           | [Requirements.txt](Requirements.txt)                | A simple .txt file with the provided project requirements as provided by TripleTen.                             |

## Section Titles and Descriptions

| Section Title | Description                                                                                                                                               |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Describes the source of data, included files, tables, and fields.                                                                                         |
| Description   | Describes the final product's purpose, software, format, and included visuals.                                                                            |
| Assumptions   | Describes assumptions to include given by TripleTen and assumptions made based on the data and task.                                                      |
| Process       | A general outline of how this project formed from start to finish.                                                                                        |
| Findings      | Insights learned from the data analysis.                                                                                                                  |
| Notes         | Notes sent with project to the reviewer for more context about presentation choices.                                                                      |

### Data

The data was one Excel spreadsheet file provided by TripleTen:

- **Superstore.xls**: each row corresponds to one product sold; sheets were LEFT JOIN'd
  - `orders`: details all fields for each ordered item
  - `returns`: details all fields for each returned item


### Assumptions

- **Data Accuracy**: The dataset is accurate and includes up-to-date return and shipment information.
- **Consistent Definitions**: Return statuses and shipment modes are consistently categorized.
- **Complete Dataset**: All relevant orders and returns are included, with no significant missing data.
- **Calculation Method**: Return rates are consistently calculated as total returns divided by total shipments/orders.
- **Geographic Accuracy**: Geographic data (e.g., states and regions) is accurate and correctly assigned.
- **Sample Representativeness**: The dataset represents overall business operations adequately.
- **Temporal Consistency**: Time-related data is consistent and reflects true trends.
- **No External Influences**: The analysis assumes no major external factors have impacted return rates.

### Process

- I combined data sheets, analyzed return causes through visualizations, and summarized findings in a Tableau story, creating a comprehensive overview of return patterns and insights.

  
| Section                                        | Deliverables                                                                                                                                                   |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Scatter plot Sales Vs Returns                  | **Objective**: Determine if higher sales correlate                                                                                                             |
| Bar Chart of Return Rate by Product Category   | **Objective**: Identify which product categories have higher return rates.                                                                                     | 
| Return Rate by Customer                        | **Objective**: Find customers who return more frequently.                                                                                                      |
| Map of Return Rate by Geographic Measure       | **Objective**: Explore if there is a geographic pattern in returns.                                                                                            |
| Return Rate by Time Measure                    | **Objective**: Identify any seasonal patterns in returns.                                                                                                      |
| Return Rate by Shipment Mode                   | **Objective**: Determine if different shipment methods (e.g., Standard, Express) affect                                                                        |
| Return Rate by Region and State                | **Objective**: Identify if return rates vary by geographic location (region and state).                                                                        |

### Findings

 - **Return Rates by Shipping Method**: The states with the highest number of returns exhibit varying rates of return depending on the shipping method. Standard shipping sees consistent returns, while first class experiences the highest return rate in the 4th quarter.
 - **Product Categories**: Binders lead in sales and returns, while the Phones subcategory also has a significant return volume. The Technology category shows the highest return rate at 27.09%.
 - **Geographical Trends**: Utah has the highest average order count, while California has the highest return rate.
 - **Quarterly Trends**: Return rates peak in Q3 and Q4, with August in Q3 having the highest returns. Return rates remain elevated from August onward, except for a dip in November.
 - **Shipping Class**: "Standard class" shipping records the most orders and returns, but "same day" delivery has the highest return percentage at 44.62%.
 - **Regional Trends**: The West region registers the highest order volume, primarily from one city, followed by the East region.
