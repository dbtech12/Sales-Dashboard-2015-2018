# Sales Dashboard 2015-2018 (Power BI)

An interactive Power BI dashboard that gives an overview of sales performance by product, category, region, customer segment and month.

![Sales Dashboard: View 1](Screenshot%202026-11-20%20031140.png)

![Sales Dashboard: View 2](Screenshot%202026-11-20%20031332.png)

## The question

Where do sales come from, and which products, categories, regions and customer segments drive them?

## The data

- A practice retail sales dataset of **9,789 order lines** (`PORT.xlsx`).
- Orders from **3 January 2015 to 30 December 2018**, all in the United States.
- Fields include order date, ship date, customer, segment, region, state, city, category, sub-category, product name and sales.
- **4,916 orders**, **1,860 products** and **793 customers**.
- There are no missing values. The only repeated row is one order line that appears twice, and I kept it.
- The data is very evenly spread across groups, which suggests it is simulated. This project is about dashboard design and analysis skills, not real business conclusions.

## What I built

- **KPI cards:** Total Sales, Total Orders, Total Products, Total Customers
- **Sales by Product Name:** top-selling products
- **Sales by Category:** Technology, Furniture, Office Supplies
- **Sales by Region:** West, East, Central, South
- **Sales by Segment:** Consumer, Corporate, Home Office
- **Sales by Month:** sales for each month, with all years combined
- **Slicers:** Region, Category, Segment and an Order Date range

## Key numbers

| Measure | Value |
|---|---|
| Total sales | 2.25M |
| Total orders | 4,916 |
| Total products | 1,860 |
| Total customers | 793 |
| Average sales per order | 458.22 |

## My Findings

| Group | Result |
|---|---|
| Top category | Technology 825.86K (36.7%), then Furniture 723.54K (32.1%) and Office Supplies 703.21K (31.2%) |
| Top region | West 710.22K (31.5%), then East 660.59K, Central 492.65K and South 389.15K |
| Top segment | Consumer 1.15M (50.9%), then Corporate 682.21K (30.3%) and Home Office 423.69K (18.8%) |
| Top product | Canon imageCLASS 2200 Advanced Copier: 61.6K, more than twice the next product |
| Busiest months | November 345.04K, December 321.28K and September 300.10K (all years combined) |
| Slowest months | February 59.37K and January 91.98K (all years combined) |
| Sales by year | 2015: 479.86K, 2016: 454.32K, 2017: 597.22K, 2018: 721.21K |

- **West and East together bring in about 61% of all sales.**
- Sales dipped slightly in 2016, then grew about 31% in 2017 and about 21% in 2018.
- The Sales by Month chart adds all four years together for each month, so it shows seasonality (a strong end of year), not a trend over time.

## Recommendations

1. Prepare stock and marketing for the September to December peak.
2. Look for growth in the South and Central regions, which sell the least.
3. Keep investing in Technology, the largest category, and in Consumer customers.
4. Study the top products, such as the Canon copier, to see what makes them sell.

## How I built it

1. Loaded `PORT.xlsx` into Power BI and checked the data in Power Query (data types, empty values and duplicates).
2. Set the Sales column to a currency type so totals are correct.
3. Built the KPI cards and charts.
4. Added slicers so the whole report can be filtered by region, category, segment and date.
5. Checked the figures against the Excel data.

## Tools

Power BI, Power Query, Excel

## Files

- [MY SALES PROJECT.pbix](MY%20SALES%20PROJECT.pbix): the Power BI report
- [PORT.xlsx](PORT.xlsx): the dataset
- [Dashboard screenshot 1](Screenshot%202026-11-20%20031140.png)
- [Dashboard screenshot 2](Screenshot%202026-11-20%20031332.png)

## About me

Osavibie Deborah Edoruyi, aspiring data analyst.

[LinkedIn](https://www.linkedin.com/in/osavibie-edoruyi-1131a6329)
