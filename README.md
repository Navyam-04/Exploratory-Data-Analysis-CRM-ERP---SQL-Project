

# 🧪 Exploratory Data Analysis of CRM & ERP Data using SQL

This project showcases **Exploratory Data Analysis (EDA)** on CRM and ERP datasets using **SQL Server**, following structured query scripts and a layered dataset approach inspired by the **Medallion Architecture** (Bronze → Silver → Gold). The focus is on understanding, analyzing, and generating insights from enterprise-level business data.

---

## 📁 Project Structure

```
📦 Exploratory-Data-Analysis-CRM-ERP---SQL-Project
├── datasets/              # All CSV files (bronze, silver, gold layers)
├── scripts/               # SQL scripts for database setup & EDA
├── LICENSE                # MIT License
└── README.md              # Project overview
```

---

## 🧠 Objective

To perform comprehensive EDA on integrated **CRM and ERP data** using structured **SQL queries**, enabling insight extraction across sales, customer, product, and performance metrics.

---

## 🗂️ Dataset Layers

Your data is split into the following Medallion-inspired layers:

- **🟫 Bronze Layer:** Raw CRM and ERP input data  
- **🟪 Silver Layer:** Cleaned and structured data ready for analysis  
- **🟨 Gold Layer:** Final analytical tables including dimensions, facts, and reporting outputs

---

## 📊 SQL Scripts Overview (`scripts/`)

Each file performs a specific EDA task. Scripts are named with a numeric prefix for proper execution order:

| Script No. | Purpose |
|------------|---------|
| `init_database.sql` | Restore / create DB schema |
| `database_exploration.sql` | Metadata and schema inspection |
| `dimensions_exploration.sql` | Explore dimension attributes |
| `date_range_exploration.sql` | Check date completeness and range |
| `measures_exploration.sql` | Measure distribution and outliers |
| `magnitude_analysis.sql` | High-value customers/products |
| `ranking_analysis.sql` | Top N and bottom N queries |
| `change_over_time_analysis.sql` | Trend analysis |
| `cumulative_analysis.sql` | Cumulative aggregations |
| `performance_analysis.sql` | Efficiency, performance over time |
| `data_segmentation.sql` | Group-wise insights |
| `part_to_whole_analysis.sql` | Proportions and market share |
| `report_customers.sql` | Final customer-level insights |
| `report_products.sql` | Final product-level insights |

---



## 💡 Key Insights

- Identified top-performing products and customers.
- Performed temporal sales trend analysis.
- Built final report-level summary tables from cleaned datasets.
- Used multi-level joins, aggregations, and window functions.

---

## 🧰 Tech Stack

- **SQL Server (T-SQL)**
- **SSMS (SQL Server Management Studio)**
- **CSV / Excel (Datasets)**
- **GitHub for Version Control**

---




## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🔗 Connect with Me  
👋 Hi, I'm **Mangali Navya**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/navya-mangali/)  
[![Email](https://img.shields.io/badge/Email-Send%20Mail-red?logo=gmail)](mailto:middenavya51@gmail.com)  
[![GitHub](https://img.shields.io/badge/GitHub-Navyam--04-black?logo=github)](https://github.com/Navyam-04)  
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-purple?logo=internet-explorer)](https://mangalinavya.my.canva.site)


_"Learn deeply. Build boldly. Share generously."_ Navya

