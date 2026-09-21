# SQL Exploratory Data Analysis Project

Welcome to the SQL Exploratory Data Analysis Project repository! 🚀

This project demonstrates an end-to-end SQL data analytics workflow using Microsoft SQL Server. The project focuses on exploring, analyzing, and transforming structured sales data to uncover meaningful business insights about customers, products, sales performance, and trends.

---

## 📖 Project Overview

The project follows a structured data analysis workflow, starting from database setup and exploration and progressing through advanced analytical techniques and the creation of reusable customer and product reports.

The analysis covers:

1. **Database Exploration:** Understanding the database structure, tables, columns, and available data.
2. **Dimension Exploration:** Examining customer and product dimensions.
3. **Date Range Exploration:** Understanding the time period covered by the dataset.
4. **Measures Exploration:** Calculating key business metrics and measures.
5. **Magnitude Analysis:** Analyzing business performance across different dimensions.
6. **Ranking Analysis:** Ranking customers and products based on key performance indicators.
7. **Change Over Time Analysis:** Identifying trends and changes in business performance over time.
8. **Cumulative Analysis:** Analyzing cumulative sales and performance patterns.
9. **Performance Analysis:** Evaluating product and customer performance.
10. **Data Segmentation:** Grouping customers and products into meaningful segments.
11. **Part-to-Whole Analysis:** Understanding the contribution of individual categories to overall performance.
12. **Customer Reporting:** Creating a reusable customer-level analytical report.
13. **Product Reporting:** Creating a reusable product-level analytical report.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Explore and understand the available sales data.
- Analyze customer purchasing behavior.
- Analyze product performance.
- Identify sales trends and patterns.
- Calculate important business metrics.
- Rank customers and products based on performance.
- Segment customers based on their characteristics and behavior.
- Understand how individual products and categories contribute to overall sales.
- Create reusable analytical reports for customers and products.
- Demonstrate practical SQL skills used in data analytics.

---

## 🛠️ Tools & Technologies

- **Microsoft SQL Server**
- **SQL Server Management Studio (SSMS)**
- **SQL**
- **Git & GitHub**
- **Microsoft Excel / CSV files**
- **Draw.io**
- **Notion**

---

## 📊 Analytical Techniques

The project applies several SQL analytical techniques, including:

- Database exploration
- Data profiling
- Aggregate functions
- Date functions
- Common Table Expressions (CTEs)
- Window functions
- Ranking functions
- Running totals
- Cumulative analysis
- Time-series analysis
- Customer segmentation
- Product segmentation
- Part-to-whole analysis
- KPI calculations
- Data reporting

---

## 📂 Repository Structure

~~~text
sql-exploratory-data-analysis-project/
│
├── datasets/
│   ├── dim_customers.csv
│   ├── dim_products.csv
│   └── fact_sales.csv
│
├── docs/
│   ├── Project Roadmap.pdf
│   └── Project Roadmap.png
│
├── scripts/
│   ├── 00_init_database.sql
│   ├── 01_database_exploration.sql
│   ├── 02_dimensions_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_ranking_analysis.sql
│   ├── 07_change_over_time_analysis.sql
│   ├── 08_cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_part_to_whole_analysis.sql
│   ├── 12_report_customers.sql
│   └── 13_report_products.sql
│
├── LICENSE
└── README.md
~~~

---

## 📁 Dataset

The project uses three analytical datasets:

### [`dim_customers.csv`](datasets/dim_customers.csv)

Contains customer-level information used to analyze customer demographics, purchasing behavior, and customer performance.

### [`dim_products.csv`](datasets/dim_products.csv)

Contains product-level information used to analyze product categories, costs, and product performance.

### [`fact_sales.csv`](datasets/fact_sales.csv)

Contains sales transaction data used to calculate sales metrics and analyze business performance over time.

---

## 🔍 Analysis Workflow

The SQL scripts are organized sequentially to follow the progression of the analysis:

### 1. Database Exploration

The initial scripts establish the database and explore the available tables, columns, and data.

- [`00_init_database.sql`](scripts/00_init_database.sql)
- [`01_database_exploration.sql`](scripts/01_database_exploration.sql)

### 2. Dimensions and Date Exploration

The analysis examines customer and product dimensions and identifies the date range covered by the sales data.

- [`02_dimensions_exploration.sql`](scripts/02_dimensions_exploration.sql)
- [`03_date_range_exploration.sql`](scripts/03_date_range_exploration.sql)

### 3. Measures and Magnitude Analysis

Key business metrics are calculated and analyzed across different dimensions.

- [`04_measures_exploration.sql`](scripts/04_measures_exploration.sql)
- [`05_magnitude_analysis.sql`](scripts/05_magnitude_analysis.sql)

### 4. Ranking and Trend Analysis

Customers and products are ranked based on performance, while changes in sales and business metrics are analyzed over time.

- [`06_ranking_analysis.sql`](scripts/06_ranking_analysis.sql)
- [`07_change_over_time_analysis.sql`](scripts/07_change_over_time_analysis.sql)

### 5. Advanced Analysis

The project applies cumulative analysis, performance analysis, segmentation, and part-to-whole analysis to obtain deeper business insights.

- [`08_cumulative_analysis.sql`](scripts/08_cumulative_analysis.sql)
- [`09_performance_analysis.sql`](scripts/09_performance_analysis.sql)
- [`10_data_segmentation.sql`](scripts/10_data_segmentation.sql)
- [`11_part_to_whole_analysis.sql`](scripts/11_part_to_whole_analysis.sql)

### 6. Analytical Reports

The final scripts create reusable reports focused on customer and product analysis.

- [`12_report_customers.sql`](scripts/12_report_customers.sql)
- [`13_report_products.sql`](scripts/13_report_products.sql)

---

## 📈 Customer Report

The customer report consolidates customer-level information and key performance metrics to support customer analysis.

The report includes information and metrics related to:

- Customer demographics
- Customer age
- Customer orders
- Sales
- Quantity purchased
- Product activity
- Customer recency
- Average order value
- Average monthly spending
- Customer lifespan
- Customer segmentation

The customer report is available in [`12_report_customers.sql`](scripts/12_report_customers.sql).

---

## 📦 Product Report

The product report consolidates product-level information and performance metrics to support product analysis.

The report includes analysis related to:

- Product categories
- Product costs
- Sales
- Quantity sold
- Orders
- Revenue
- Product performance
- Product lifespan
- Product segmentation

The product report is available in [`13_report_products.sql`](scripts/13_report_products.sql).

---

## 📚 Documentation

The `docs/` directory contains the project roadmap and supporting project documentation.

- [Project Roadmap](docs/Project%20Roadmap.pdf)
- [Project Roadmap Image](docs/Project%20Roadmap.png)

---

## 🚀 How to Use This Project

1. Clone or download the repository.
2. Open SQL Server Management Studio.
3. Create or connect to a SQL Server database.
4. Run [`00_init_database.sql`](scripts/00_init_database.sql) to initialize the database.
5. Execute the remaining scripts in numerical order.
6. Review the analytical queries and their results.
7. Explore the [Customer Report](scripts/12_report_customers.sql) and [Product Report](scripts/13_report_products.sql).

---

## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

---

## 👨‍💻 About Me

Hi there! I'm **Denilson Pius**, an aspiring Data Engineer passionate about data engineering, data analytics, SQL, and data warehousing.

I'm continuously developing my skills through practical projects and hands-on learning with technologies such as Microsoft SQL Server, SQL, data modeling, ETL, and data analytics.

Let's stay in touch! Feel free to connect with me on the following platforms:

- [LinkedIn](https://www.linkedin.com/in/denilsonpius/)
- [GitHub](https://github.com/Denilson47)
