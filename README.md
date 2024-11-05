# SQL-Project---Atliq-Hardware


# Project 
Dataset Size: Approximately 1.5 million records.
Goal: To deliver actionable insights on gross and net sales, market segmentation, and top-performing customers, products, and regions.
Key Components
User-Defined Functions:

# Created functions to align dates with Atliq’s fiscal year (September 1 to August 31), crucial for generating accurate year-over-year comparisons in sales reports.
Stored Procedures:

# Developed stored procedures to assign market badges based on sales volume:
Gold Badge: Markets with over 5 million units sold.
Silver Badge: Markets with fewer than 5 million units sold.
This classification helps Atliq assess market performance quickly and adjust strategies accordingly.
Views for Sales Calculations:

Designed views to handle complex calculations of net sales by integrating pre- and post-invoice discounts.
# Views created:
sale_preinv_discount: Computes pre-invoice discounts.
sale_postinv_discount: Calculates post-invoice discounts.
These views simplify repeated calculations, ensuring efficient and readable queries.
Sales Reports:

# Generated various reports to support business strategy:
Top 5 markets, customers, and products by net sales for fiscal year 2021.
Monthly gross sales reports for clients such as Croma India.
Regional market performance: Lists top-performing markets by gross sales for targeted regions.
SQL Techniques and Optimization
Aggregation and Joins: Optimized joins and aggregations to handle large datasets efficiently, allowing for scalable report generation.
Data Transformation: Used views and functions to pre-process data, reducing complexity in main queries.
Performance Optimization: Leveraged stored procedures and views to streamline calculations, minimizing redundant code and improving execution time for large datasets.



# Results and Insights
Top Performers: Identified top markets, customers, and products by net sales, providing insights into revenue-generating entities.
Customer-Specific Sales: Tracked monthly gross sales for major clients like Croma India, aiding in customer relationship management.
Region-Specific Strategies: Pinpointed high-performing markets in each region, allowing for focused sales and marketing strategies.
Future Work
Expand reports to cover additional fiscal years and further improve query optimization.
Integrate more stored procedures for automated report generation.
