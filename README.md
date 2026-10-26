# NovaMart Retail — Data Studio Dashboard

## Project Overview

This project presents an interactive retail sales and inventory dashboard created using Google Data Studio (Looker Studio). It builds on the NovaMart Retail Sales & Inventory Performance Analysis project and reuses its synthetic dataset and documented business analysis.

The dashboard is designed to help business stakeholders review sales performance, profitability, store comparisons, product sales, and inventory distribution.

## Tools Used

- Google Data Studio (Looker Studio) — dashboard development and visualisation
- Google Sheets — data source preparation
- SQL and Excel — supporting analysis completed in the broader NovaMart portfolio project

## Business Questions

1. What are the overall sales and profit totals?
2. How does sales performance vary by store?
3. Which products generate the highest sales?
4. How is the recorded inventory distributed across stock-status categories?

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | ₹4,508,300 |
| Total Profit | ₹1,783,900 |
| Profit Margin | 39.57% |
| Average Order Value | ₹4,508.30 |
| Transactions | 1,000 |
| Units Sold | 3,000 |

## Dashboard Components

- KPI scorecards for overall business performance
- Bar chart comparing sales across stores
- Bar chart ranking products by sales
- Pie chart showing inventory status distribution

## Key Findings

- Total recorded sales are ₹4,508,300, with total profit of ₹1,783,900.
- Lucknow Central records the highest sales among the stores in the dataset.
- Pune Central records the lowest sales among the stores in the dataset.
- Vacuum Cleaner, Air Fryer, and Food Processor are the top three products by recorded sales.
- The inventory snapshot contains 393 healthy-stock records and 107 overstock records, with no low-stock records.

## Data and Methodology

The project uses a synthetic retail dataset created for portfolio and analytical practice. The sales analysis contains 1,000 transactions, and the inventory analysis contains 500 inventory records.

Sales and profit KPIs are aggregated from the cleaned orders dataset. Inventory status is analysed separately using the provided inventory snapshot.

## Limitations

- The data is synthetic and does not represent a real retailer.
- The inventory snapshot is generated separately from the sales transactions and is not reconciled with order-level sales.
- Observed differences between stores and products should not be interpreted as causal business relationships.
- Inventory status reflects the supplied snapshot and does not establish actual demand, stockout risk, or product movement over time.

## Business Recommendations

- Investigate differences in store sales and profitability before making operational decisions.
- Review stock policies for products with repeated overstock classifications.
- Validate inventory records against actual sales and replenishment data.
- Introduce time-based sales and inventory tracking to improve trend analysis and forecasting.

## Dashboard Link

[https://datastudio.google.com/reporting/79034c1b-840c-4bed-82e9-368cda6cbff2]

## Related Project

GitHub repository: https://github.com/NishaK03/retail-sales-inventory-analysis
