# Capstone 3: Analysis with Power BI
**Year Up United Data Analytics Training Academy — Week 12**

## Project Overview
This project analyzes four years of sales data (2022–2025) for EmporiUm, 
a virtual student bookstore offering in-store and online sales. The report 
was built for the East Region, covering New York and Connecticut.

## Report Highlights
- **Total East Region Sales:** $10.73M across 4 years
- **Top Category:** Technology & Accessories leads all product categories
- **State Split:** New York accounts for ~70% of regional revenue
- **Top Book:** Meditations by Marcus Aurelius

## Report Pages
1. **Sales Overview** — Monthly sales trend (2022–2025), sales by category, 
   KPI cards, and year slicer
2. **Regional Insights** — Sales by state (donut chart) and top-selling 
   general audience books with authors

## Data Cleaning Summary
- Resolved 53,000+ null category values by merging Products table on Prod Num
- Combined split date columns (Year, Month, Day) into a single Date field
- Standardized state abbreviations in Store Locations (MA, ME, NY, CT)
- Appended Store Sales and Online Sales into unified Fact_Sales table
- Merged book author data from external text file into Products table

## Tools Used
- Power BI Desktop
- Power Query (M Language)
- DAX
- GitHub

## Video Walkthrough
https://yearuptemp-my.sharepoint.com/:v:/g/personal/lalicea_my_yearupunited_org/IQDX6zXnl9BVTI61DOItu4kWAXM6tZowpVZ7zE7iJpNg0Zw?e=WMSRlv&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

## Data Sources
- Capstone3_Sample_Sales.xlsx
- book_list.txt