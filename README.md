# TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python
Basic Sales Summary with SQLite and Python — Connect to a small SQLite database using Python, run simple SQL queries to calculate total quantity sold and revenue per product, then visualize the results with a bar chart using Matplotlib.
# Task 7: Basic Sales Summary from SQLite using Python

📌 Objective
The goal of this task is to:
- Connect to a small SQLite database (`sales_data.db`) using Python.
- Run basic SQL queries to fetch **total quantity sold** and **total revenue per product**.
- Display the results using **print statements** and a **Matplotlib bar chart**.

🛠 Tools Used
- **Python 3**
- **SQLite3** (built-in with Python)
- **Pandas** (for data handling)
- **Matplotlib** (for visualization)
- **Jupyter Notebook** or `.py` script

📂 Dataset
A small SQLite database file `sales_data.db` containing a single table:

**Table: sales**
| Column   | Type    |
|----------|---------|
| product  | TEXT    |
| quantity | INTEGER |
| price    | REAL    |
