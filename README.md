# Industrial Retail Power BI Dashboard

## Project Overview
This project presents a Sales & Returns Performance Dashboard for an industrial retail dataset using Microsoft Power BI.

The dashboard was designed to analyse quarterly sales and returns performance, product categories, brands, and product-level activity.

## Tools Used
- Microsoft Power BI
- Power Query
- Data Modelling
- Microsoft Excel

## Data Preparation
The source data was transformed using Power Query.

Key transformation steps included:
- Checking and correcting data types
- Ensuring ProductID and StoreID had no blank values
- Unpivoting Q1–Q4 columns for Sales and Returns
- Renaming Attribute to Quarter
- Renaming Value to Quantity
- Adding a Type column for Sales and Returns
- Appending Sales and Returns into one fact table

## Data Model
The project uses:
- Fact Table: Retailactivities2024
- Dimension Table: tPRODUCT
- Relationship: ProductID
- Cardinality: Many-to-One

## Dashboard Visuals
The report includes:
- Clustered Column Chart – Quarterly Sales vs Returns
- Stacked Bar Chart – Sales & Returns by Category
- Pie Chart – Quantity by Brand
- Matrix – Product Sales & Returns
- Slicers – Quarter, Category and Type

## Key Results
- Total Sales: 239,714 units
- Total Returns: 36,133 units
- Total Activity: 275,847 units

## Files
- `industrial-retail-powerbi-dashboard.pbix` – Power BI dashboard
- `Industrial_Retail_PowerBI_Project_Unpivot_Append_Updated.xlsx` – Source dataset

## Author
Usamah Makmum

Retail Operations | Data Analytics | Power BI
