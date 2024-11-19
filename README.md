# Power BI Dashboard Project

## Overview
This project demonstrates a Power BI dashboard built using sales data imported from Excel files. The dashboard provides insights into sales performance, product categories, and regional trends.

## Data Sources
The project uses the following datasets:
1. *Date Calendar Sheet*: Includes date, week, month, quarter, year, day status, and season details.
2. *Raw Sales*: Contains PO date, SKU, quantity, per unit price, warehouse region, sales channel, and destination country.
3. *SKU Details*: Provides SKU, category, and type information.

## Steps Performed
1. Imported the Excel files into Power BI.
2. Established relationships between the tables:
   - Linked SKU between Raw Sales and SKU Details.
   - Linked PO Date with the Date field in the Calendar sheet.
3. Created simple visualizations to analyze the data, including:
   - Total Sales
   - Sales by Month
   - Sales by Region
   - Product Category and Type analysis
   - Seasonal and Quarterly trends

## Visualizations
The dashboard includes:
- *Cards*: Displaying total sales metrics.
- *Line Charts*: Showing trends over time.
- *Bar Charts*: Comparing sales across categories and regions.
- *Pie Charts and Tree Maps*: Representing sales distribution.

## Usage
- Open the Power BI file to explore the visualizations.
- Interact with slicers and filters for dynamic insights.

## Files in Repository
- sales_data.xlsx: The Excel file containing the raw data.
- PowerBI_Dashboard.pbix: The Power BI dashboard file.

![Dashboard](https://github.com/user-attachments/assets/0e67789c-8cb0-47d7-a9cc-054af484a194)
