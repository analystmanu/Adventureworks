# Azure End-to-End Data Engineering Pipeline

This repository demonstrates a **scalable cloud data pipeline** using **Azure Data Factory, Databricks, Azure Data Lake, and Synapse Analytics**, processing **GitHub API JSON data** and visualizing it in **Power BI**.

---

## Project Overview
- **Dataset:** Adventure Works
-AdventureWorks is a Microsoft database simulating a retail company selling bicycles and accessories. It’s widely used for SQL practice, ETL pipelines, data analysis, and BI projects.

- **Data Included:**

Sales: Orders, salespersons, sales territories, customers
Production: Products, categories, product models
Human Resources: Employees, departments, jobs
Person: Customers, addresses, contact info
- **Data Source:** GitHub API (repositories, commits, contributors)  
- **Pipeline Orchestration:** **Azure Data Factory**  
- **Data Storage:** **Azure Data Lake Storage** with **Parquet format**  
- **Data Transformation:** **PySpark notebooks** in Databricks  
- **Data Warehouse:** **Azure Synapse Analytics** using **CETAS (Create External Table As Select)**  
- **Analytics:** **Power BI dashboards** for repository activity and top contributors  
- **Architecture:** Medallion Architecture (**Bronze → Silver → Gold**)  

---

## Repo Structure
