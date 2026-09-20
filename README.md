# Sales Data Analysis 2026

## Overview
This project analyzes retail sales transactions from January to June 2026 to identify top-performing products, regions, and sales channels, and to surface actionable recommendations for the business.

## Data
The dataset contains 180 sales orders with the following fields:

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date the order was placed |
| Region | Giza, Cairo, Alexandria, Mansoura, etc. |
| Channel | Store, Online, or other sales channel |
| Product | Product name (e.g. Office Chair, Desk, Laptop) |
| Category | Product category (Furniture, Electronics, Stationery, etc.) |
| Quantity | Units sold |
| Unit_Price_EGP | Price per unit (EGP) |
| Discount | Discount rate applied |
| Sales_EGP | Total sale value (EGP) |
| Customer_ID | Unique customer identifier |

Located in [data/raw/Sales_Data_Analysis_2026.xlsx](data/raw/Sales_Data_Analysis_2026.xlsx).

## Analysis
Performed in Excel, including:
- Data cleaning (added a `month` field for time-based analysis)
- Pivot tables and a summary dashboard
- Breakdown of sales by month, region, channel, category, and product

See [analysis/Sales_Data_Analysis_2026.xlsx](analysis/Sales_Data_Analysis_2026.xlsx).

## Key Findings
- **Laptops drove the highest total sales** despite receiving the lowest promotional discount, indicating strong demand and low price sensitivity for that product.
- **Alexandria was the top-performing region**, while Mansoura recorded the lowest sales volume, pointing to a notable geographic performance gap.
- **The Online channel outperformed all other channels**, reflecting a strong customer preference for digital purchasing.
- **Electronics led all categories in revenue**, while Stationery lagged behind; at the product level, Laptops led and Notebooks underperformed.
- **May was the peak sales month** of the year, with sales more than tripling the lowest month (EGP 685,139 vs. roughly EGP 201,000–225,000 in other months).

## Recommendations
- Avoid unnecessary discounting on Laptops to protect margins, and maintain strong stock levels to meet organic demand.
- Investigate Mansoura's underperformance and consider targeted regional promotions or supply chain fixes.
- Invest further in the Online channel (UX improvements, ad spend) while auditing bottlenecks in offline channels.
- Re-evaluate pricing and placement for Stationery and Notebooks to understand low demand.
- Study what drove May's spike and look to replicate those tactics during slower months.

## Tools
Excel (pivot tables, data cleaning, dashboard, trend analysis)
