
# Real Estate Sales Dashboard | Power BI

## Overview

This project is an end-to-end Data Analytics dashboard built using Microsoft Power BI. The dashboard analyzes real estate sales data to provide insights into sales performance, regional trends, property prices, and year-over-year growth. The project covers the complete analytics workflow, starting from importing raw data to creating interactive visualizations and DAX measures.

---

## Objective

The objective of this project is to transform raw real estate sales data into meaningful business insights by:

- Cleaning and transforming the dataset
- Creating calculated measures using DAX
- Building an interactive dashboard
- Identifying sales trends and regional performance

---

## Dataset

- Source: Microsoft Excel (.xlsx)
- Domain: Real Estate Sales
- Imported into: Microsoft Power BI

---

## Tools & Technologies

- Microsoft Power BI
- Power Query Editor
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## Data Preparation

The dataset was imported from an Excel file into Power BI and cleaned using Power Query Editor.

The following preprocessing steps were performed:

- Imported data from Excel
- Checked column distribution
- Verified automatically assigned data types
- Enabled Data Profiling for the entire dataset (instead of the default first 1000 rows)
- Promoted the first row as column headers
- Replaced null and empty values
- Corrected data types for:
  - Inflation Rate
  - Date
  - Purchase Price
- Sorted and filtered records where required
- Replaced inconsistent values and errors
- Applied all transformations to the data model

---

## DAX Measures Created

The dashboard includes the following custom DAX measures:

- Average Square SQM
- Last 12 Month Sales
- Median Sales Price Change
- Offer to SQM Ratio
- Sales by Region
- Total YTD Sales
- Units Sold in Latest Year and Quarter
- YOY Sales Growth

---

## Dashboard Features

The dashboard provides insights such as:

- Total Year-to-Date Sales
- Last 12 Months Sales
- Year-over-Year Sales Growth
- Regional Sales Performance
- Average Property Size
- Offer to Square Meter Ratio
- Median Sales Price Analysis
- Units Sold Analysis
- Interactive filters and slicers for better exploration

---

## Project Workflow

1. Imported data from Excel into Power BI
2. Cleaned and transformed data using Power Query
3. Applied data profiling and corrected data types
4. Built the data model
5. Created custom DAX measures
6. Designed interactive dashboard visuals
7. Generated business insights from the data

---

## Key Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Profiling
- Data Modeling
- DAX Calculations
- Dashboard Design
- Business Intelligence
- Data Visualization

---

## Dashboard Preview

**Overview page:**

![Overview page](https://github.com/SarthakShaurya05/PowerBI-Real-Estate-Sales-Analysis/blob/main/Screenshot%202026-07-05%20023908.png?raw=true)

**Sales Performance:**

![Sales Performance](https://github.com/SarthakShaurya05/PowerBI-Real-Estate-Sales-Analysis/blob/main/Screenshot%202026-07-05%20023931.png?raw=true)

**House Type:**

![image alt](https://github.com/SarthakShaurya05/PowerBI-Real-Estate-Sales-Analysis/blob/main/Screenshot%202026-07-05%20023946.png?raw=true)

---

## Project Structure

```
Real-Estate-Sales-Dashboard/
│
├── PowerBI End to End Project.pbix
├── README.md
├── images/
|     ├── overview.png
|     ├── sales performance.png
|     └── House Type.png
|
|       
└── dataset.xlsx
```

---

## Future Improvements

- Add forecasting visuals
- Implement drill-through reports
- Optimize DAX measures for larger datasets
- Publish the dashboard to Power BI Service

---

## Author

Sarthak Shaurya

LinkedIn:www.linkedin.com/in/sarthak-shaurya-890279355

GitHub:https://github.com/SarthakShaurya05
