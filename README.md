# 🛒 D-Mart SQL Data Analysis

## 📌 Project Overview

This project analyzes D-Mart product data using **PostgreSQL** to generate business insights related to pricing, discounts, inventory, brands, and product categories. It demonstrates SQL skills from beginner to advanced by solving real-world retail business problems using aggregate functions, subqueries, Common Table Expressions (CTEs), and window functions.

The objective is to transform raw product data into actionable insights that support pricing strategies, inventory management, and category performance analysis.

---

# 🎯 Project Objectives

* Analyze product pricing across categories.
* Measure discount percentages and savings.
* Compare brand performance.
* Rank products by price.
* Identify premium and budget products.
* Evaluate category contribution to inventory value.
* Generate retail business insights using SQL.

---

# 🛠️ Tools & Technologies

* PostgreSQL
* SQL
* pgAdmin 4
* Git
* GitHub

---

# 📂 Repository Structure

```text
dmart-sql-data-analysis/
│
├── Dataset/
│   └── dmart_products.csv
│
├── Database/
│   ├── create_table.sql
│   └── import_data.sql
│
├── SQL Queries/
│   ├── 01_Beginner.sql
│   ├── 02_Intermediate.sql
│   ├── 03_Advanced.sql
│   ├── 04_Window_Functions.sql
│   └── 05_Business_Insights.sql
│
├── Images/
│
├── README.md
│
└── LICENSE
```

---

# 📊 Dataset Description

The dataset contains product information available in D-Mart stores.

### Columns

* Product Name
* Brand
* Price
* Discounted Price
* Category
* Sub-Category
* Quantity
* Description
* Breadcrumbs

---

# 📚 SQL Concepts Covered

## Beginner

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

## Intermediate

* GROUP BY
* HAVING
* CASE
* Subqueries
* Aggregate Functions

## Advanced

* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* Percentage Calculations
* Business KPI Analysis

---

# 📈 Business Questions Solved

* Find the total inventory value for each category.
* Find the top 5 brands with the highest average product price.
* Count the number of products available for each brand.
* Find categories whose average price is above the overall average price.
* Calculate the average discount percentage for each category.
* Rank products by price within each category.
* Find the highest-priced product for each brand.
* Calculate each category's contribution to total inventory value.
* Calculate the discount percentage for each product.
* Find duplicate product names.
* Categorize products into Budget, Mid-Range, and Premium using CASE.
* Find brands with above-average pricing.
* Find the top 5 brands by average discounted price.
* Rank sub-categories within each category by average price.
* Identify products with the largest price reduction.

---

# 📊 Key Business Insights

* Categories generating the highest inventory value.
* Brands with premium-priced products.
* Products offering the largest discounts.
* Categories with the highest average discount percentage.
* Price ranking of products within each category.
* High-value and premium product segments.
* Brand contribution to the overall product portfolio.
* Duplicate product listings for data quality checks.

---

# 💡 SQL Skills Demonstrated

* Data Exploration
* Data Cleaning
* Aggregate Functions
* GROUP BY & HAVING
* CASE Expressions
* Subqueries
* Window Functions
* Ranking Functions
* Business KPI Analysis
* Retail Data Analytics

---

# 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/dmart-sql-data-analysis.git
```

### 2. Create the Table

Run:

```sql
create_table.sql
```

### 3. Import the Dataset

Import the `dmart_products.csv` file into PostgreSQL using pgAdmin or the `COPY` command.

### 4. Execute SQL Queries

Run the SQL files in this order:

1. Beginner Queries
2. Intermediate Queries
3. Advanced Queries
4. Window Functions
5. Business Insights

---

# 📸 Project Preview

Include screenshots of:

* SQL query results
* PostgreSQL tables
* Query execution outputs
* ER Diagram (optional)
* Dashboard (Power BI or Tableau, optional)

Store screenshots inside the **Images** folder.

---

# 📖 Learning Outcomes

By completing this project, you will learn how to:

* Analyze retail product data using SQL.
* Perform pricing and discount analysis.
* Compare brand and category performance.
* Apply window functions for ranking and reporting.
* Solve real-world retail business problems using SQL.
* Generate actionable business insights from transactional data.

---

# 🔮 Future Enhancements

* Build an interactive Power BI dashboard.
* Perform Exploratory Data Analysis (EDA) using Python.
* Add sales transaction data for revenue analysis.
* Develop inventory forecasting models.
* Create executive KPI dashboards.

---

# 👨‍💻 Author

**Your Name**

Aspiring Data Analyst | SQL | PostgreSQL | Power BI | Python

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

Happy Learning and Happy Querying! 🚀
