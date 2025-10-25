# Superstore Data Analysis

## 📌 Project Overview
This project analyzes the Superstore sales dataset to extract business intelligence and actionable insights. Several analytical approaches are implemented: SQL data analysis, Jupyter notebook exploration, and Power BI visualizations.

---

## ⚙️ How It Works
- **Dataset:** Uses sales, orders, customer, and product data from a typical retail superstore.
- **Tools:**
  - SQL for data extraction and foundational insights (`Superstore_sales_analysis_SQL_Insights.sql`)
  - Jupyter Notebook for exploratory data analysis and visualization (`SuperstoreSalesAnalysis_JupyterNotebook.ipynb`)
  - Power BI dashboard for interactive business insights (`Superstore Sales Insights.pbix` and PDF export)
- **Process:**
  - Data is cleaned and loaded using the provided SQL dump and CSV files.
  - Key business questions are addressed using SQL queries (shipping, customer value, product popularity, regional analysis, etc.).
  - Visualizations in Power BI summarize top trends, segment performances, and geographical insights.

---

## 🚧 Problems Faced
- Raw data had inconsistencies and missing values.
- Complex business logic required precise SQL queries.
- Large dataset challenged performance and needed optimization.

---

## 🛠️ How These Problems Were Overcome
- Data was cleaned using both SQL and pandas in the Jupyter Notebook.
- Used common table expressions (CTEs), window functions and optimized queries to handle business logic.
- Created aggregations and indexes to improve query speed.

---

## 💡 Insights & Findings
- **Shipping:** Found the percentage of orders shipped same-day and shipping times by segment.
- **Customers:** Identified top customers by value, frequency, and city.
- **Products & Categories:** Determined top products by average sales and most demanded sub-category in the west.
- **Regional Trends:** Revealed lowest and highest revenue-contributing cities and states.
- **Anomalies:** Found orders with the highest items or value, uncovered segments prone to first-class shipping.

---

## 📂 Files
- `Superstore_sales_analysis_SQL_Insights.sql`: Key SQL queries for all major insights
- `SuperstoreSalesAnalysis_JupyterNotebook.ipynb`: Exploratory analysis & visualizations
- `Superstore Sales Insights.pbix`: Power BI interactive dashboard
- `Superstore Sales Insights.pdf`: Exported dashboard for easy review
- `SuperstoreData_cleaned_dump_Dataset.sql`: Cleaned database dump
- CSVs: Cleaned datasets for analysis

---

## 📝 How to Run
1. Import the SQL dump into your relational database.
2. Open the notebook to replicate EDA and plots.
3. Use CSVs or SQL for Power BI dashboard import.
4. Review SQL queries for insight extraction.

---

## 🙏 Acknowledgements
- Kaggle and public Superstore dataset for the source data.



## Preview

![Screenshot 2024-03-04 005612](https://github.com/AdityaPatil100/Power-Bi-projects/assets/86911300/686ca170-2ef7-41b6-9c66-ab596f4dddfb)
![Screenshot 2024-03-04 005604](https://github.com/AdityaPatil100/Power-Bi-projects/assets/86911300/391f96a0-2f0d-4255-9eb8-ff312ffb053b)
![Screenshot 2024-03-04 005649](https://github.com/AdityaPatil100/Power-Bi-projects/assets/86911300/cb17e7f2-11f4-4249-9c18-2dbe230a2e7f)
