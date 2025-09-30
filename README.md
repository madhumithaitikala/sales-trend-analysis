# sales-trend-analysis
sales Trend Analysis Using Aggregations

This project analyzes monthly revenue and order volume from an online sales dataset. The analysis is implemented using SQL queries (compatible with PostgreSQL, MySQL, and SQLite) and executed in Google Colab using SQLite for demonstration.

Key Steps:

Data Preparation: Loaded the online_sales_dataset.csv file and converted the order date to a datetime format.

Revenue Calculation: Calculated sales revenue per order as amount or Quantity × UnitPrice.

Monthly Aggregation: Grouped data by year and month using SQL (EXTRACT() in PostgreSQL/MySQL or strftime() in SQLite).

Order Volume: Counted distinct orders per month to get order volume.

Filtering: Limited analysis to specific time periods (e.g., a particular year).

Visualization: Plotted revenue and order volume trends across months using Matplotlib.

Outcome:

Learn how to group data by time periods, compute aggregated metrics, and analyze monthly sales trends.

Gain hands-on experience combining SQL aggregation with Python data visualization.
