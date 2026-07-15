# Task-8--Simple-Sales-Performance-Dashboard
## Objective
This task involved building an interactive Power BI dashboard to analyze sales performance using the Sample Superstore dataset.

## Dataset
Sample Superstore dataset

## Tools Used
- Power BI Desktop

## Steps Performed
   - Imported the Superstore dataset
   - Fixed data types (Order Date, Sales as Decimal Number)
   - Created a 'Month-Year' custom column for time-based grouping
   - Created a 'month-yeaer sort' numeric helper column (Year×100+Month) to enable correct chronological sorting of the text-based Month-Year field
  -Dashboard Visuals(Sales Over Month,Sales by Category, Sales by Region)
  - Added slicers for Region and **Category** to allow dynamic filtering across all visuals.

## Key Insights
1. Sales are volatile month-to-month rather than trending steadily up or down, with sharp spikes suggesting seasonal demand or bulk orders.
2. Technology is the top-performing category (36.4% of sales), closely followed by Furniture (32.3%) and Office Supplies (31.3%).
3. The West region leads in total sales, followed by East, with Central and South trailing behind.
4. No single category or region dominates overwhelmingly — sales are fairly diversified across segments.

## Files in this Repository
- `Sales_Performance_Dashboard.pdf` – Final dashboard export including visuals and key insights
- `README.md` – This file
