# NYC Airbnb Data Project

This project was undertaken as part of the TripleTen Business Intelligence Analytics Program. It represents an independent analysis designed to demonstrate proficiency in advanced spreadsheet techniques.

Google Spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/1p_Kzi_nQm_rGAMG__Etf9QxsiY51geZq1Nq6njKEMlw/edit?gid=993121668#gid=993121668).

## Table of Contents

| File Number | Title             | Description                                                                                                     |
|-------------|-------------------|-----------------------------------------------------------------------------------------------------------------|
| 1           | [README.md](README.md)        | Overview and details of the project, located immediately following this Table of Contents.          |
| 2           | [Requirements.txt](Requirements.txt)  | A text file listing the project requirements as specified by TripleTen.                     |
| 3           | [airbnb_rental_data_analysis.xlsx](airbnb_rental_data_analysis.xlsx)  | The dataset provided by TripleTen was used for analysis in this project.   |

## Sections Overview

| Section Title | Description                                                                                |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| Data          | Details the data sources, files, tables, and fields utilized in the analysis.                                                                    |
| Description   |Outlines the purpose, software used, format, and visuals included in the final deliverable.   |
| Assumptions   |Lists assumptions based on provided data and project requirements.|
| Process       | Describes the methodology from data exploration through to final formatting.    |
| Findings      | Summarizes insights and conclusions drawn from the data analysis.    |

### Data

- `airbnb_rental_data_analysis.xlsx`:  Contains listings data for Airbnb in Manhattan for September 2022.
- `data_dictionary`: Defines field titles and data types.
- `listings`: Comprehensive data on individual listings.
- `calendar`: Details on listing availability and rental dates.

### Description

- **Spreadsheet Composition**
  - Comprises 14 pages, including raw data, processed data, analysis, pivot tables, and a bar chart.
  - The objective was to identify optimal property types for investment in the Manhattan vacation rental market based on Airbnb data.

### Assumptions

- Airbnb rental data is considered reflective of general vacation rental trends.
- Rental activity is gauged by the number of reviews over the past 12 months.
- Listings with no reviews in the past year are classified as inactive.
- The analysis is based on reviews from the past 12 months.
- Only listings with prices above $200 and ratings of 4+ stars were considered.
- Highly frequented properties are those rented 40 or more times annually.
- Listings priced below $100 or above $1000 are excluded from the analysis.

### Process

- Initial data exploration, filtering, and cleaning were performed.
- Aggregations and pivot tables were created to identify target property types.
- Calculations, pivot tables, and charts were generated to estimate occupancy and revenue.
- Final formatting was applied to enhance clarity and readability.

### Findings

- **Top Neighborhoods**: Lower East Side and Hell's Kitchen are the most popular based on guest ratings.
- **Property Sizes**: 1-bedroom properties receive the highest ratings, followed by 2-bedroom and studio units.
- **Revenue Potential**: Midtown offers the highest annual revenue: $104,462 for 0-bedroom, $95,781 for 1-bedroom, and $162,821 for 2-bedroom properties.
- **Occupancy Trends**: Occupancy rates peak on Fridays and Saturdays.
