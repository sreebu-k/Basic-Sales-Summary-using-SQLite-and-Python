Sales-Summary-using-SQLite-and-Python

Objective

To calculate total quantity and total revenue for each product using SQL inside Python, and display the results with a bar chart.

 Tools Used

Python

SQLite (built-in database)

Pandas

Matplotlib

🧱 Steps

Create a small SQLite database (sales_data.db) using Python.

Create a table named sales with columns: product, quantity, and price.

Insert sample data manually.

Run an SQL query to calculate:

Total quantity per product

Total revenue (quantity × price)

Display the results using Pandas and visualize them with Matplotlib.

(Optional) Clear old data before each run to avoid duplication.

Output Example
product	total_qty	revenue
Headphones	12	24000.0
Keyboard	10	15000.0
Laptop	5	300000.0
Monitor	8	80000.0
Mouse	20	10000.0

Bar Chart:
A simple chart showing Revenue by Product.
