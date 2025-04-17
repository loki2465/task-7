# task-7

# 📊 Sales Summary from SQLite using Python

This project demonstrates how to use Python with SQLite and basic data visualization tools to generate a sales summary from a simple database.

---

## ✅ Objective

- Connect to an SQLite database (`sales_data.db`)
- Use SQL to retrieve total quantity sold and total revenue by product
- Display the results using:
  - `print()` statements
  - A basic bar chart using `matplotlib`

---

## 🛠️ Tools Used

- Python 3
- SQLite (via `sqlite3` module)
- pandas
- matplotlib

> No external database setup is required! SQLite is lightweight and built into Python.

---

## 📂 Project Structure

```
sales-summary-project/
│
├── sales_summary.py        # Main Python script
├── sales_data.db           # SQLite database (auto-created by script if not exists)
├── sales_chart.png         # Output revenue chart (auto-generated)
└── README.md               # Project documentation
```

---

## 📦 Requirements

Install the required libraries using pip:

```bash
pip install pandas matplotlib
```

---

## ▶️ How to Run

1. Open a terminal and navigate to the project folder.
2. Run the script:

```bash
python sales_summary.py
```

3. The script will:
   - Create the database and table if they don’t exist
   - Insert some sample data
   - Run an SQL query to compute total quantity and revenue
   - Print the summary
   - Plot a bar chart of revenue by product
   - Save the chart as `sales_chart.png`

---

## 📊 Sample Output

**Console Output:**
```
Sales Summary:
  product  total_qty  revenue
0   Apple         15      7.5
1  Banana         30      9.0
2  Grapes          8      8.0
3  Orange         20     14.0
```

**Bar Chart Output:**

A bar chart showing revenue per product will be displayed and saved as `sales_chart.png`.

---

## 📚 What You'll Learn

- Writing basic SQL queries inside Python
- Reading SQL results into pandas
- Summarizing and visualizing data using bar charts
- Using SQLite without the need for a database server

---

## 📬 Contact

For questions or improvements, feel free to reach out or fork this project!
