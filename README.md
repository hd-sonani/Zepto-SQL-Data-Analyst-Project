# Zepto-SQL-Data-Analyst-Project
This project analyzes a Zepto-style grocery dataset using PostgreSQL. It covers data cleaning, exploratory analysis, and business-focused SQL queries to identify best-value products, high-MRP out-of-stock items, revenue by category, discount trends, and inventory insights.


🔍 Data Exploration

  - Key exploration steps performed:
 
  -Total row count check

  -Sample data preview

  -Null value detection across all columns

  -Identification of unique product categories

  -Stock vs out-of-stock product distribution

  -Detection of duplicate product names (multiple SKUs)


🧹 Data Cleaning

  -Actions taken to ensure data quality:

  -Removed products with MRP = 0

  -Converted prices from paise to rupees

  -Ensured consistency in pricing fields

  -Verified no critical NULL values remain


🛠️ Tools & Technologies

  -Database: PostgreSQL

  -Language: SQL

  -Concepts Used:

  -Aggregations (SUM, AVG, COUNT)

  -CASE statements

  -Filtering & sorting

  -Data cleaning with DELETE and UPDATE

  -Grouping & business logic
