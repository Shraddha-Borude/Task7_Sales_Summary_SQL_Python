# Task 7: Basic Sales Summary using SQLite and Python

## Objective

The goal of this task is to:
- Create a small SQLite database containing simple sales data.
- Use SQL queries within Python to pull sales insights such as total quantity sold and total revenue per product.
- Visualize the results using a simple bar chart.

---

## Tools & Libraries Used

- Python (Google Colab)
- SQLite (via `sqlite3`)
- pandas
- matplotlib

---

## What This Project Does

- Creates a SQLite database file named `sales_data.db` with a table called `sales`.
- Inserts sample sales records (product, quantity, price).
- Executes an SQL query to get:
  - Total quantity sold
  - Total revenue per product
- Loads the query result into a pandas DataFrame.
- Prints the summary using `print(df)`.
- Displays a bar chart of revenue by product using matplotlib.
- Optionally saves the chart as `sales_chart.png`.

---

## Files in this Repository

| File Name           | Description                                  |
|---------------------|----------------------------------------------|
| `sales_data.db`     | SQLite database with sample sales data       |
| `sales_summary.ipynb` | Python notebook that performs the analysis  |
| `sales_chart.png`   | (Optional) Bar chart showing revenue summary |
| `README.md`         | You are here! Explains the project           |

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/) or locally using Jupyter Notebook.
2. Run all cells in order.
3. The notebook will create a database, insert data, query the summary, and plot the chart.
4. The bar chart will be displayed within the notebook and saved as an image (optional).

---

## Sample Output
