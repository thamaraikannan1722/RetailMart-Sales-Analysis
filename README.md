🛒 RetailMart Country Sales Analysis

📊 A Data Analytics Project Using SQL, PostgreSQL & Power BI

---

📌 1. Project Overview

RetailMart Country Sales Analysis is a data analytics project that explores retail sales transactions across six countries:

 🛒 RetailMart Country Sales Analysis

📊 A Data Analytics Project Using SQL, PostgreSQL & Power BI

---

📌 1. Project Overview

RetailMart Country Sales Analysis is a data analytics project that explores retail sales transactions across six countries:

🇨🇦 Canada | 🇨🇳 China | 🇮🇳 India | 🇳🇬 Nigeria | 🇬🇧 United Kingdom | 🇺🇸 United States

The project uses SQL, PostgreSQL, and Microsoft Power BI to analyze sales performance, product trends, profitability, customer demographics, payment methods, and store locations.

🎯 Objective: Transform raw retail transaction data into meaningful business insights and interactive dashboards.

---

🎯 2. Project Objectives

- 📈 Analyze sales performance across six countries.
- 💰 Evaluate total sales and profit.
- 🛍️ Identify top-performing products and categories.
- 🌍 Compare country-wise sales performance.
- 👨‍💼 Evaluate sales representative performance.
- 🏬 Analyze store-location performance.
- 💳 Examine payment method preferences.
- 👥 Explore customer age groups and gender patterns.
- 📊 Develop interactive Power BI dashboards.

---

🛠️ 3. Tools & Technologies

🧰 Tool| 🎯 Purpose
🐘 PostgreSQL| Database storage and management
💻 SQL| Data querying and analysis
📊 Microsoft Power BI| Interactive dashboard development
📄 CSV| Source data format
🐙 GitHub| Project hosting and portfolio presentation

---

📂 4. Dataset Overview

The project contains six country-level CSV datasets.

📄 Dataset| 🌍 Country
"sales_Canada.csv"| Canada

"sales_China.csv"| China

"sales_India.csv"| India

"sales_Nigeria.csv"| Nigeria

"sales_UK.csv"| United Kingdom

"sales_US.csv"| United States

📋 Dataset Columns

The documented dataset schema contains 15 columns:

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

---

🔄 5. Project Workflow

The project follows these stages:

1. 📥 Collect the six country-level CSV datasets.
2. 🔍 Inspect the data and column structure.
3. 🗄️ Load the data into PostgreSQL.
4. 💻 Perform data analysis using SQL.
5. ✅ Validate transaction records and calculated fields.
6. 🔗 Connect the data to Power BI.
7. 📊 Create interactive reports and visualizations.
8. 💡 Interpret results and document business insights.

---

💻 6. SQL Analysis

The SQL script "RetailMart_Analysis.sql" includes queries for:

- 🔎 Inspecting transaction records.
- 🔁 Checking duplicate transaction identifiers.
- 🧮 Calculating total transaction amounts.
- 💰 Calculating profit.
- 🌍 Comparing sales and profit across countries.
- 🏆 Identifying the top five products by quantity purchased.
- 👨‍💼 Evaluating sales representative performance.
- 🏬 Comparing store-location performance.
- 📊 Generating summary statistics.

⚠️ Note: Total amount and profit calculations should be validated against the definitions of discount and cost price in the source data.

---

📊 7. Power BI Dashboard

The Power BI report provides interactive views of retail sales performance.

📑 Dashboard Pages

- 🏠 Summary
- 📋 Overview
- 📈 Sales Analysis
- 🛍️ Product Analysis
- 👥 Customer Analysis
- 🌍 Geographic Analysis
- 🧾 Transaction Analysis

These pages organize the analysis into different business perspectives.

🖼️ Dashboard Preview

<!-- Add your dashboard screenshot here after uploading it to the repository. -->---

🔍 8. Key Business Questions

This project investigates questions such as:

- 🌍 Which countries generate the highest sales?
- 🛍️ Which products have the highest purchase quantities?
- 💰 How does profitability vary across countries?
- 👨‍💼 Which sales representatives perform strongly?
- 🏬 Which store locations contribute to sales?
- 💳 Which payment methods are used?
- 👥 How do sales patterns vary across customer age groups and genders?
- 📊 How can dashboards help monitor retail performance?

📌 The answers should be interpreted from the actual SQL results and Power BI report.

---

💡 9. Business Value

This project demonstrates how retail transaction data can be used to:

- 📈 Compare sales performance across countries.
- 🏆 Identify popular products.
- 💰 Examine profitability.
- 🏬 Investigate store-level performance.
- 💳 Understand payment patterns.
- 🎯 Support data-driven business discussions.

---

▶️ 10. How to Run the Project

Step 1️⃣ — Download the Repository

Download or clone this GitHub repository.

Step 2️⃣ — Prepare the Data

Review the six CSV files and verify their column names and data types.

Step 3️⃣ — Load Data into PostgreSQL

Import the datasets into PostgreSQL and configure the required tables.

Step 4️⃣ — Execute SQL Queries

Open "RetailMart_Analysis.sql" and execute the queries in your SQL environment, adjusting table and column names if necessary.

Step 5️⃣ — Open Power BI

Open "RetailMart Sales Analysis PBI.pbix" using Microsoft Power BI Desktop.

Step 6️⃣ — Configure the Data Connection

Update file paths or database connection settings if required, then refresh the report.

---

⚠️ 11. Project Limitations

- The documented dataset schema does not include a dedicated Customer ID or Customer Name.
- Unique customer counts cannot be reliably calculated without a suitable customer identifier.
- Sales and profit calculations depend on the definitions and units of the source financial columns.
- Power BI refresh may require configuring the data connection on another computer.

---

🧠 12. Skills Demonstrated

- 💻 SQL Querying
- 🐘 PostgreSQL Database Operations
- 📈 Retail Sales Analysis
- ✅ Data Validation
- 📊 Power BI Dashboard Development
- 📉 Data Visualization
- 💡 Business Intelligence
- 📝 Business Requirements Documentation
- 🐙 GitHub Portfolio Management

---

📁 13. Repository Contents

📄 File| 📝 Description
"README.md"| Project overview and documentation
"RetailMart_Analysis.sql"| SQL analysis script
"RetailMart Sales Analysis PBI.pbix"| Power BI report
"sales_Canada.csv"| Canada dataset
"sales_China.csv"| China dataset
"sales_India.csv"| India dataset
"sales_Nigeria.csv"| Nigeria dataset
"sales_UK.csv"| United Kingdom dataset
"sales_US.csv"| United States dataset

---

🏁 14. Conclusion

RetailMart Country Sales Analysis demonstrates an analytics workflow involving retail datasets, SQL-based investigation, PostgreSQL, and Power BI visualization.

The project showcases practical skills in data analysis, database querying, dashboard development, and business intelligence.

---

👨‍💻 Project Information

- 📌 Project: RetailMart Country Sales Analysis
- 🏢 Domain: Retail Analytics
- 🛠️ Technologies: SQL, PostgreSQL, Microsoft Power BI
- 📂 Datasets: Six country-level CSV files

---

⭐ Thank you for visiting my project repository!
The project uses SQL, PostgreSQL, and Microsoft Power BI to analyze sales performance, product trends, profitability, customer demographics, payment methods, and store locations.

🎯 Objective: Transform raw retail transaction data into meaningful business insights and interactive dashboards.

---

🎯 2. Project Objectives

- 📈 Analyze sales performance across six countries.
- 💰 Evaluate total sales and profit.
- 🛍️ Identify top-performing products and categories.
- 🌍 Compare country-wise sales performance.
- 👨‍💼 Evaluate sales representative performance.
- 🏬 Analyze store-location performance.
- 💳 Examine payment method preferences.
- 👥 Explore customer age groups and gender patterns.
- 📊 Develop interactive Power BI dashboards.

---

🛠️ 3. Tools & Technologies

🧰 Tool| 🎯 Purpose
🐘 PostgreSQL| Database storage and management
💻 SQL| Data querying and analysis
📊 Microsoft Power BI| Interactive dashboard development
📄 CSV| Source data format
🐙 GitHub| Project hosting and portfolio presentation

---

📂 4. Dataset Overview

The project contains six country-level CSV datasets.

📄 Dataset| 🌍 Country
"sales_Canada.csv"| 🇨🇦 Canada
"sales_China.csv"| 🇨🇳 China
"sales_India.csv"| 🇮🇳 India
"sales_Nigeria.csv"| 🇳🇬 Nigeria
"sales_UK.csv"| 🇬🇧 United Kingdom
"sales_US.csv"| 🇺🇸 United States

📋 Dataset Columns

The documented dataset schema contains 15 columns:

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

---

🔄 5. Project Workflow

The project follows these stages:

1. 📥 Collect the six country-level CSV datasets.
2. 🔍 Inspect the data and column structure.
3. 🗄️ Load the data into PostgreSQL.
4. 💻 Perform data analysis using SQL.
5. ✅ Validate transaction records and calculated fields.
6. 🔗 Connect the data to Power BI.
7. 📊 Create interactive reports and visualizations.
8. 💡 Interpret results and document business insights.

---

💻 6. SQL Analysis

The SQL script "RetailMart_Analysis.sql" includes queries for:

- 🔎 Inspecting transaction records.
- 🔁 Checking duplicate transaction identifiers.
- 🧮 Calculating total transaction amounts.
- 💰 Calculating profit.
- 🌍 Comparing sales and profit across countries.
- 🏆 Identifying the top five products by quantity purchased.
- 👨‍💼 Evaluating sales representative performance.
- 🏬 Comparing store-location performance.
- 📊 Generating summary statistics.

⚠️ Note: Total amount and profit calculations should be validated against the definitions of discount and cost price in the source data.

---

📊 7. Power BI Dashboard

The Power BI report provides interactive views of retail sales performance.

📑 Dashboard Pages

- 🏠 Summary
- 📋 Overview
- 📈 Sales Analysis
- 🛍️ Product Analysis
- 👥 Customer Analysis
- 🌍 Geographic Analysis
- 🧾 Transaction Analysis

These pages organize the analysis into different business perspectives.

🖼️ Dashboard Preview

<!-- Add your dashboard screenshot here after uploading it to the repository. -->---

🔍 8. Key Business Questions

This project investigates questions such as:

- 🌍 Which countries generate the highest sales?
- 🛍️ Which products have the highest purchase quantities?
- 💰 How does profitability vary across countries?
- 👨‍💼 Which sales representatives perform strongly?
- 🏬 Which store locations contribute to sales?
- 💳 Which payment methods are used?
- 👥 How do sales patterns vary across customer age groups and genders?
- 📊 How can dashboards help monitor retail performance?

📌 The answers should be interpreted from the actual SQL results and Power BI report.

---

💡 9. Business Value

This project demonstrates how retail transaction data can be used to:

- 📈 Compare sales performance across countries.
- 🏆 Identify popular products.
- 💰 Examine profitability.
- 🏬 Investigate store-level performance.
- 💳 Understand payment patterns.
- 🎯 Support data-driven business discussions.

---

▶️ 10. How to Run the Project

Step 1️⃣ — Download the Repository

Download or clone this GitHub repository.

Step 2️⃣ — Prepare the Data

Review the six CSV files and verify their column names and data types.

Step 3️⃣ — Load Data into PostgreSQL

Import the datasets into PostgreSQL and configure the required tables.

Step 4️⃣ — Execute SQL Queries

Open "RetailMart_Analysis.sql" and execute the queries in your SQL environment, adjusting table and column names if necessary.

Step 5️⃣ — Open Power BI

Open "RetailMart Sales Analysis PBI.pbix" using Microsoft Power BI Desktop.

Step 6️⃣ — Configure the Data Connection

Update file paths or database connection settings if required, then refresh the report.

---

⚠️ 11. Project Limitations

- The documented dataset schema does not include a dedicated Customer ID or Customer Name.
- Unique customer counts cannot be reliably calculated without a suitable customer identifier.
- Sales and profit calculations depend on the definitions and units of the source financial columns.
- Power BI refresh may require configuring the data connection on another computer.

---

🧠 12. Skills Demonstrated

- 💻 SQL Querying
- 🐘 PostgreSQL Database Operations
- 📈 Retail Sales Analysis
- ✅ Data Validation
- 📊 Power BI Dashboard Development
- 📉 Data Visualization
- 💡 Business Intelligence
- 📝 Business Requirements Documentation
- 🐙 GitHub Portfolio Management

---

📁 13. Repository Contents

📄 File| 📝 Description
"README.md"| Project overview and documentation
"RetailMart_Analysis.sql"| SQL analysis script
"RetailMart Sales Analysis PBI.pbix"| Power BI report
"sales_Canada.csv"| Canada dataset
"sales_China.csv"| China dataset
"sales_India.csv"| India dataset
"sales_Nigeria.csv"| Nigeria dataset
"sales_UK.csv"| United Kingdom dataset
"sales_US.csv"| United States dataset

---

🏁 14. Conclusion

RetailMart Country Sales Analysis demonstrates an analytics workflow involving retail datasets, SQL-based investigation, PostgreSQL, and Power BI visualization.

The project showcases practical skills in data analysis, database querying, dashboard development, and business intelligence.

---

👨‍💻 Project Information

- 📌 Project: RetailMart Country Sales Analysis
- 🏢 Domain: Retail Analytics
- 🛠️ Technologies: SQL, PostgreSQL, Microsoft Power BI
- 📂 Datasets: Six country-level CSV files
