# Project 3: Sales Performance Dashboard
This project presents a two-page Power BI dashboard analyzing product performance, store contribution (including online vs. physical channels), and monthly sales trends. The goal is to produce a clean, structured, and insight-driven report that highlights key patterns in the dataset while demonstrating strong dashboard design and analytical communication.

## Dataset
The dataset consists of four tables:
- Sales: Fact table containing transaction quantities, product keys, store keys, customer keys, and dates.
- Products: Dimension table with product names and related metadata.
- Stores: Dimension table containing store identifiers, country, state, square meters, and open date.
- Customers: Dimension table containing customer identifiers and demographic attributes.
- DateTable: Custom date dimension built to support time intelligence and monthly trend analysis.

## Dashboard Structure
Page 1: Overview
- High-level KPI (Total Quantity Sold)
- Total Quantity by Product
- Total Quantity by Month
- Total Quantity by Store
- Slicers: Product, Month, Store
- Consistent color hierarchy and layout alignment

Page 2: Sales Breakdown
- Top 5 Products by Quantity Sold
- Top 5 Stores by Quantity Sold
- Monthly Sales Trend
- Dedicated Key Insights section summarizing the findings

## Key Insights
- Product performance is tightly clustered, with WWI Desktop and Adventure items all selling at similar high levels, indicating that demand is concentrated within these two product families rather than spread across a wider range of products.
- Online sales (Store 0) overwhelmingly dominate, generating nearly ten times more volume than any physical store. Physical store performance is stable but significantly smaller, showing that the online channel is the primary driver of total sales.
- Monthly sales show strong seasonality, with early-year strength, a sharp decline in April, steady mid-year performance, and a major surge in December -- a pattern consistent with online-driven retail activity.

## Tools & Techniques
- Power BI Desktop
- Data modeling with fact/dimension relationships
- Custom DateTable for time intelligence
- DAX for calculated measures
- Visual formatting (colors, titles, alignment, font sizing)
- Insight writing focused on clarity and business relevance

## Project Itinerary
1. Import and review dataset
2. Model relationships across all tables (Sales, Products, Stores, Customers, DateTable)
3. Build Page 1 overview visuals and KPI
4. Format Page 1 (colors, titles, alignment)
5. Build Page 2 visuals (products, stores, monthly trend)
6. Write and refine Key Insights section
7. Finalize formatting and layout across both pages