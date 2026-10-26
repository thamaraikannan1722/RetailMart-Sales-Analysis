RetailMart Country Sales Analysis

1. Project Overview

RetailMart Country Sales Analysis is a data analytics project focused on evaluating retail sales transactions across six countries: Canada, China, India, Nigeria, the United Kingdom, and the United States.

The project uses SQL, PostgreSQL, and Microsoft Power BI to analyze sales performance, product trends, profitability, customer demographics, payment methods, and store locations.

The objective is to transform raw retail transaction data into meaningful insights that support business analysis and decision-making.

2. Business Problem

Retail businesses need to understand how sales performance varies across countries, products, stores, and customer segments.

Without structured analysis, it can be difficult to identify top-performing products, compare regional performance, understand payment preferences, and evaluate profitability.

This project addresses these needs by organizing transaction data, analyzing it with SQL, and presenting the results through interactive Power BI dashboards.

3. Project Objectives

- Analyze sales performance across six countries.
- Evaluate total sales and profit.
- Identify top-performing products and categories.
- Compare country-wise sales performance.
- Analyze sales representative performance.
- Examine store-location performance.
- Understand payment method preferences.
- Explore customer age-group and gender patterns.
- Present findings using interactive Power BI reports.

4. Tools and Technologies

Tool| Purpose
PostgreSQL| Database storage and management
SQL| Data querying and analysis
Microsoft Power BI| Interactive dashboard development
CSV| Source data format
GitHub| Project version control and portfolio presentation

5. Dataset Overview

The project contains six country-level CSV datasets.

Dataset| Country
"sales_Canada.csv"| Canada
"sales_China.csv"| China
"sales_India.csv"| India
"sales_Nigeria.csv"| Nigeria
"sales_UK.csv"| United Kingdom
"sales_US.csv"| United States

The documented source schema contains 15 columns:

1. "Transaction_ID"
2. "Date"
3. "Country"
4. "Product_ID"
5. "Product_Name"
6. "Category"
7. "Price_per_Unit"
8. "Quantity_Purchased"
9. "Cost_Price"
10. "Discount_Applied"
11. "Payment_Method"
12. "Customer_Age_Group"
13. "Customer_Gender"
14. "Store_Location"
15. "Sales_Rep"

6. Project Workflow

The project workflow consists of the following stages:

1. Collect the six country-level CSV datasets.
2. Inspect the data and identify relevant columns.
3. Load the data into PostgreSQL.
4. Execute SQL queries to investigate sales performance.
5. Validate transaction records and calculated fields.
6. Connect the data to Power BI.
7. Create interactive report pages and visualizations.
8. Review the results and document business findings.

7. SQL Analysis

The SQL script "RetailMart_Analysis.sql" supports the following types of analysis:

- Inspecting transaction records.
- Checking for duplicate transaction identifiers.
- Examining and updating selected records where required.
- Calculating total transaction amounts.
- Calculating profit.
- Comparing sales and profit across countries.
- Identifying the top five products by quantity purchased.
- Evaluating sales representative performance.
- Comparing store-location performance.
- Generating summary statistics.

The SQL queries are included in this repository for review and learning.

Calculation note: Total amount and profit calculations must be validated against the definitions of discount and cost price in the source data before interpreting the results.

8. Power BI Dashboard

The Power BI report provides interactive views of retail sales performance.

The report contains the following pages:

- Summary
- Overview
- Sales Analysis
- Product Analysis
- Customer Analysis
- Geographic Analysis
- Transaction Analysis

These pages organize the analysis into different business perspectives.

9. Key Business Questions

The project is designed to investigate questions such as:

- Which countries generate the highest sales?
- Which products have the highest purchase quantities?
- How does profitability vary across countries?
- Which sales representatives perform strongly?
- Which store locations contribute to sales?
- What payment methods are used in transactions?
- How do sales patterns vary across customer age groups and genders?
- How can management use dashboards to monitor retail performance?

The answers should be interpreted from the actual query results and Power BI report.

10. Business Value

This project demonstrates how retail transaction data can be used to:

- Compare sales performance across countries.
- Identify popular products.
- Examine profitability.
- Investigate regional and store-level performance.
- Understand transaction and payment patterns.
- Support data-driven business discussions.

11. How to Run the Project

Step 1: Download the repository

Download or clone this GitHub repository to your computer.

Step 2: Prepare the data

Review the six CSV files and confirm their column names and data types.

Step 3: Load the data into PostgreSQL

Import the data into PostgreSQL and configure the table names and column names to match those used in the SQL script.

Step 4: Run the SQL queries

Open "RetailMart_Analysis.sql" in your SQL environment and execute the queries as appropriate for your database.

Step 5: Open the Power BI report

Open "RetailMart Sales Analysis PBI.pbix" in Microsoft Power BI Desktop.

Step 6: Configure the data connection

Update the source paths or PostgreSQL connection settings if required, then refresh the report.

12. Project Limitations

- The documented dataset schema does not include a dedicated Customer ID or Customer Name.
- Unique customer counts cannot be reliably calculated without a suitable customer identifier.
- Sales and profit results depend on the definitions and units of the source financial columns.
- Power BI refresh may require configuring the database connection on another computer.

13. Skills Demonstrated

- SQL querying
- PostgreSQL database operations
- Retail sales analysis
- Data validation
- Power BI report development
- Data visualization
- Business intelligence
- Business requirements documentation
- GitHub portfolio management

14. Repository Contents

File| Description
"README.md"| Project overview and documentation
"RetailMart_Analysis.sql"| SQL analysis script
"RetailMart Sales Analysis PBI.pbix"| Power BI report
"sales_Canada.csv"| Canada dataset
"sales_China.csv"| China dataset
"sales_India.csv"| India dataset
"sales_Nigeria.csv"| Nigeria dataset
"sales_UK.csv"| United Kingdom dataset
"sales_US.csv"| United States dataset

15. Conclusion

RetailMart Country Sales Analysis demonstrates a complete analytics workflow involving retail datasets, SQL-based investigation, PostgreSQL, and Power BI visualization.

The project showcases practical skills in data analysis, database querying, dashboard development, and business intelligence.

---

Project: RetailMart Country Sales Analysis
Domain: Retail Analytics
Technologies: SQL, PostgreSQL, Microsoft Power BI
Datasets: Six country-level CSV files
