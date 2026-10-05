# Power BI Sales Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-yellow)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-blue)
![DAX](https://img.shields.io/badge/DAX-Measures-purple)
![Portfolio](https://img.shields.io/badge/Portfolio-BI%20Developer-green)

## 📌 Overview

An end-to-end Business Intelligence portfolio project demonstrating how sales data can be transformed into an interactive management dashboard using **SQL, Power BI, DAX, Power Query and dimensional modeling**.

> **Important:** All data is synthetic and created for portfolio demonstration.

## 🎯 Business Objective

The solution answers:

- How much are we selling?
- How profitable are we?
- How are sales trending over time?
- Which regions and products perform best?
- Which customer segments generate the most value?
- Where should management focus?

## 🛠️ Technology Stack

- Power BI
- SQL Server / SQL
- DAX
- Power Query
- Data Modeling
- Star Schema
- Git / GitHub

## 🏗️ Architecture

```text
Synthetic CSV Data
       ↓
SQL Data Validation
       ↓
Star Schema
       ↓
Power BI Semantic Model
       ↓
DAX Measures
       ↓
Interactive Dashboard
```

## 📂 Repository Structure

```text
data/             Synthetic CSV datasets
sql/              SQL table, validation and analysis scripts
powerbi/          DAX and data-model documentation
screenshots/      Dashboard screenshots
documentation/    Project documentation
```

## 📊 Data Model

```text
DimDate ─────────┐
DimProduct ──────┤
DimCustomer ─────┼──> FactSales
DimRegion ───────┘
```

The model follows a **star-schema approach** with dimensions filtering the transaction fact table.

## 🔑 Key DAX Measures

Examples include:

- Total Sales
- Total Profit
- Profit Margin %
- Total Orders
- Units Sold
- Average Order Value
- Sales LY
- Sales YoY %
- Profit YoY %

See [`powerbi/dax_measures.md`](powerbi/dax_measures.md).

## 📈 Dashboard

Recommended pages:

1. Executive Overview
2. Sales Analysis
3. Product Analysis

Add your exported dashboard screenshots to the `screenshots/` folder and embed them here.

## 🧪 Data Quality

SQL validation scripts check:

- Duplicate transaction IDs
- Missing dimension keys
- Date ranges
- Sales/profit totals
- Referential integrity

## 💼 Business Insights

The dashboard is designed to identify:

- High-performing regions
- High-value products
- Profitability gaps
- Customer segment contribution
- Year-over-year growth opportunities

## 🚀 How to Reproduce

1. Clone/download this repository.
2. Load the CSV files into SQL Server or Power BI.
3. Execute the SQL scripts in order.
4. Build the star-schema relationships.
5. Add the DAX measures.
6. Create the three dashboard pages.
7. Capture screenshots and add them to `screenshots/`.

## 👩‍💻 Author

**Diksha Buwa**

Business Intelligence Developer  
Power BI | Qlik Sense | SQL | ETL | Data Analytics | Python

---

⭐ If you find this project useful, feel free to explore the repository.
