Sales-Summary-using-SQLite-and-Python

Objective

To get basic sales information (total quantity sold and total revenue) using SQL inside Python, and display the result with a simple bar chart.

 Tools Used

Python

SQLite (built-in)

Pandas

Matplotlib


Steps

Create a small SQLite database (sales_data.db) inside Python.

Create a table named sales with columns: product, quantity, and price.

Insert some sample data manually.

Run SQL queries using Python to find total quantity and revenue per product.

Show results using print() and plot a bar chart using Matplotlib.

Output

Console Output Example:

     product     total_qty   revenue
0     Laptop           5     300000
1     Mouse           20      10000
2     Keyboard        10      15000
3     Monitor          8      80000
4     Headphones      12      24000


Bar Chart:
A simple bar chart showing revenue by product.
