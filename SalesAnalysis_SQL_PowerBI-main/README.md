# Sales Data Analysis using SQL Server and Power BI

This project demonstrates how to clean, transform, and analyze sales data from a Data Warehouse using SQL Server and visualize the results through Power BI dashboards. It showcases end-to-end business intelligence development using AdventureWorks dataset.

---

## ⚙ Environment Setup

- Tools Required: *SQL Server (Express edition)* and *Power BI Desktop*
- Dataset: Uses backup files of *AdventureWorks Data Warehouse (DW)* and *Lightweight (LT)* versions.
- Instructions to restore the databases can be found [here](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).
- A comparison of DW and LT data is performed to highlight differences between structured and semi-structured datasets.
- SQL scripts are used to update the data warehouse. [SQL Script](https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql)

---

## 📈 Business Context

- A sample business requirement and corresponding user stories are reviewed to identify data needs and analytical goals.
- Based on the scenario, key metrics and data tables are selected for building insights and dashboards.

---

## 🛠 Data Cleaning and Transformation (T-SQL)

- Identification of relevant *fact* and *dimension* tables.
- Data transformation using SQL operations such as:
  - Renaming and combining columns
  - SQL formatting and commenting
  - Usage of WHERE, ORDER BY, LEFT JOIN, CASE, ISNULL
- Columns of interest are exported after applying necessary transformations.

---

## 📊 Power BI Dashboard Creation

- Loading cleaned data into Power BI
- Preparing table structures and defining relationships for data modeling
- Importing additional datasets like *Fact_Budget*
- Creating calculated measures and KPIs
- Designing visuals using:
  - Bar, Line, and Pie charts
  - Geo-maps
  - Top 10 and Gradient Charts
  - Custom visuals and Pivot tables
  - Customer-wise details for business analysis

---

## 📎 Dashboard Access

- 👉 [Download Power BI Report (.pbix)](https://github.com/AsifRashid01/SalesAnalysis_SQL_PowerBI/blob/main/Sales%20Report.pbix)  


---

## ✅ Summary

This project walks through a complete data analysis pipeline – from raw data cleaning with T-SQL to interactive business dashboard creation using Power BI. It reflects real-world BI practices and delivers actionable insights through compelling visuals.

---

*Note*: This is a hands-on educational project and intended for academic or portfolio use.
