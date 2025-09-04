# ✈️ BI Analysis of Flight Delays and Airline Performance

> 📊 *A Business Intelligence project that analyzes flight delays, cancellations, and airline performance using ETL pipelines, a star-schema data warehouse, and interactive dashboards in Power BI.*  

---

## 📖 Table of Contents
- [✨ Features](#-features)
- [📊 KPIs & Insights](#-kpis--insights)
- [🛠 Tech Stack](#-tech-stack)
- [📂 Project Structure](#-project-structure)
- [⚙️ Installation and Execution Steps](#️-installation-and-execution-steps)
- [📸 Screenshots](#-screenshots)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [👨‍💻 Author](#-author)

---

## ✨ Features
✅ ETL process built using **SQL Server Integration Services (SSIS)**.  
✅ Cleaned, transformed, and loaded raw flight data into a **Data Warehouse**.  
✅ Designed a **Star Schema** for optimized BI queries.  
✅ Developed an **interactive Power BI dashboard** with KPIs and insights.  
✅ SQL scripts for data preprocessing, KPIs, and queries.  

---

## 📊 KPIs & Insights
The BI solution provides analysis of:  
- ✈️ **Delay Rate** by airline and airport  
- ⏱ **Average delay duration**  
- 🛑 **Canceled flights** by airline  
- 🏆 **Airline punctuality rankings**  
- 📉 Trends in flight delays over time  

---

## 🛠 Tech Stack
- **ETL & Data Integration:** SSIS (SQL Server Integration Services)  
- **Database:** SQL Server (staging + star schema data warehouse)  
- **Data Visualization:** Power BI (DAX, interactive reports)  
- **Languages:** SQL, DAX  

---

## 📂 Project Structure
```bash
BI-Flight-Delays/
│
├── ETL/                  # SSIS packages for data cleaning & loading
├── SQL/                  # SQL scripts for DW creation, KPIs, queries
├── PowerBI/              # Power BI dashboards (.pbix files)
├── data/                 # Raw CSV files (flight & airline datasets)
└── README.md             # Project documentation
