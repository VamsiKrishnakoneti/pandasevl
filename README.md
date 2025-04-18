This project is a simple data analysis workflow that extracts, processes, and visualizes sales data stored in an SQLite database. The final output is a bar chart showing revenue per product.
Using Python, we:

1. **Connect to a SQLite database** (`sales_data.db`) that contains sales records.
2. **Run a SQL query** to calculate total quantity sold and total revenue per product.
3. **Load the result into a Pandas DataFrame** for further analysis.
4. **Visualize the data** using a bar chart (with Matplotlib) showing the revenue by product.
5. **Save the chart as an image** (`sales_chart.png`) for easy sharing or reporting.
