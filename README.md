# SQL-_PROJECT
<h1 align="center">📊 SQL Project — Sales Data Analysis</h1>

<p align="center">
  🚀 A beginner-friendly SQL project to explore <b>real-world sales data</b> through queries and analysis.<br>
  🧠 Focus: Data Exploration | Aggregation | Joins | Business Insights
</p>

---

### 📌 **Project Overview**
This project focuses on analyzing sales data using SQL to answer real-world business questions.  
It includes queries related to:
- 🥇 Top-selling products  
- 📅 Sales trends over time  
- 🧾 Order values and quantities  
- 🏷️ Brand-wise revenue analysis  
- ⏱️ Time-based filtering

---

### 🛠️ **Tech Stack**
- 🧮 **Database:** MySQL  
- 💻 **Tool:** MySQL Workbench / VS Code  
- 🗂️ **Data:** Orders, Products, Order Lines, Brands, Invoices

---

### 🧠 **Key SQL Concepts Used**
- `GROUP BY` & `ORDER BY`  
- `JOIN` (INNER JOIN)  
- `LIMIT`  
- Date & time functions (`MONTH`, `MINUTE`)  
- Aggregate functions (`SUM`, `AVG`)

---

### 🧪 **Sample Query**
```sql
-- ✅ Top 3 products based on total quantity sold
SELECT product_id 
FROM order_lines 
GROUP BY product_id 
ORDER BY SUM(quantity) DESC 
LIMIT 3;
📈 Business Questions Solved

Top 3 product IDs based on the quantity sold

Orders where quantity sold was in multiples of 2

Brand name, order value & product name for each product

Average order value for orders placed after half an hour

Total quantity & price per brand per month

🚀 How to Run

Download the .sql file from this repo

Import it into MySQL (Workbench or CLI)

Run the queries one by one to see results

🙌 Author

Shruti Awasthi
📧 [Shrutiavasthi77@gmail.com]

🔗 LinkedIn[ https://www.linkedin.com/in/shruti-awasthi-139b10206]

⭐ If you like this project, don't forget to star it!




