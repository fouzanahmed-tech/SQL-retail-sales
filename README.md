# SQL-retail-sales
SQL project covering table creation, data cleaning, exploratory queries, and business-driven analytics (top customers, category sales, monthly trends, and shift-based ordering).
A beginner-friendly SQL portfolio project using **PostgreSQL** to clean, explore, and analyze retail sales transactions.  
The goal is to practice real-world SQL skills: table setup, data quality checks, and business-focused analysis queries.

---

# What’s Inside

### 1) Database & Table Setup
- Creates the `retail_sales` table with transaction, customer, product category, pricing, and total sale fields.

### 2) Data Cleaning
- Identifies rows with missing values (NULLs) across key columns.
- Removes incomplete records to keep analysis consistent.

### 3) Exploratory Data Analysis (EDA)
- Total number of sales (rows)
- Number of unique customers
- Distinct product categories

### 4) Business Analytics Queries
Includes queries to answer questions like:
- Sales made on a specific date
- Clothing transactions with quantity thresholds in Nov 2022
- Total sales and total orders by category
- Average age of customers in the Beauty category
- High-value transactions (total_sale > 1000)
- Transactions by gender and category
- Best-selling month (by average sale) in each year using window functions
- Top 5 customers by total sales
- Unique customers per category
- Orders by shift (Morning/Afternoon/Evening) based on sale_time

---

## Tech Stack
- **PostgreSQL**
- **pgAdmin 4** (or any PostgreSQL client)

---

## How to Run
1. Open pgAdmin (or your SQL client) and connect to your PostgreSQL server.
2. Run the script sections in order:
   - Create table
   - (Optional) Load/insert data
   - Cleaning queries
   - Analysis queries

> Note: This repo focuses on SQL querying. If you are using a CSV dataset, you can import it into PostgreSQL using pgAdmin’s Import/Export tool or `COPY`.

---

## Project Structure (Suggested)
- `sql/retail_sales_analysis.sql` → All SQL queries
- `README.md` → Project overview
