# Adventure Works 2022 Data Analysis & Dashboards
A complete Excel data analysis project using the Adventure Works 2022 dataset (7 files).

### 📅 Project Timeline
* **Development Period:** October 2026 .
* **Note:** This project was developed locally and later migrated to GitHub .

This project is an in-depth data analysis built in Microsoft Excel, using the Adventure Works 2022 dataset. The dataset was spread across 7 different files, requiring robust data preparation before building out the final visualizations. The end result is a dual-dashboard setup tailored to different analytical needs.

## Tools I Used
- Microsoft Excel
- Power Query
- Power Pivot

## Project Workflow
Here is a look at my process from raw data to the final dashboards:

1. Data Import and Cleaning
The first challenge was handling the raw data, which came in 7 separate files. I used Power Query to import, clean, and shape the data, ensuring all tables were consistent and ready to be joined.

2. Defining the Analysis Scope
With a dataset this large, it was important to set clear goals. I decided to split the analysis into two main scopes: tracking the performance of the sales team and analyzing product sales trends.

3. Data Modeling and DAX
Because the data came from multiple sources, building a solid relational data model in Power Pivot was crucial. I connected the tables (like Sales, Product, Reseller, Salesperson, and Region) and created custom DAX measures to calculate KPIs such as Total Sales, Total Profit, Total COGS, and Quantity Sold.

4. Dashboard Design
I designed two distinct dashboards using Pivot Tables to address the two different scopes:

- **Sales Team Performance & Reseller Analytics:** This dashboard focuses on the human element of sales. It highlights the best and worst-performing salespeople, tracks total sales and profit by employee across 2017-2022, and breaks down the quantity sold to different business types (like Value Added Resellers vs. Specialty Bike Shops).
- **Product Analytics & Sales Trends Overview:** This dashboard is all about the products. It provides a detailed look at total sales and profit by sub-categories (like Jerseys and Shorts), identifies the top 5 and worst 5 selling products, and visualizes overall sales trends across different regions (with Canada leading) and timeframes.
