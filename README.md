# Elevate-labs-task-7
# 📊 Task 7 - Basic Sales Summary using SQLite and Python

This project demonstrates how to connect Python with a SQLite database, run basic SQL queries to summarize sales data, and visualize the results using a bar chart.

---

## ✅ Objective

- Connect to a SQLite database (`sales_data.db`)
- Run SQL to get total quantity and revenue per product
- Display results using print statements and a matplotlib bar chart

---

## 🧰 Tools Used

- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib

---

## 📁 Files in this Repo

- `sales_data.db` – SQLite database with a simple `sales` table
- `Task7_Sales_Summary.ipynb` – Jupyter Notebook with complete code
- `sales_chart.png` – Output bar chart showing revenue by product
- `README.md` – This file

---

## 🔍 What the Script Does

1. Creates a database and inserts sample sales data
2. Runs a SQL query to get:
   - Total quantity sold per product
   - Total revenue per product (`quantity * price`)
3. Loads data into pandas
4. Prints the summary
5. Plots a bar chart of revenue by product

---

## 📈 Sample Output

```plaintext
  product  total_qty  revenue
0   Apple         15      7.5
1  Banana         30      6.0
2  Orange         20      6.0
