# Azure End-to-End Data Engineering Pipeline

This repository demonstrates a **scalable cloud data pipeline** using **Azure Data Factory, Databricks, Azure Data Lake, and Synapse Analytics**, processing **GitHub API JSON data** and visualizing it in **Power BI**.

---

## Project Overview
- **Dataset:** Adventure Works
-AdventureWorks is a Microsoft database simulating a retail company selling bicycles and accessories. It’s widely used for SQL practice, ETL pipelines, data analysis, and BI projects.

[![Bronze Layer](images/bronze%20layer%20file.png)](https://github.com/analystmanu/Adventureworks/blob/main/images/Bronze%20Layer%20files.png)

**Tables**
1. **AdventureWorks_Calendar** – Dates, holidays, fiscal info
2. **AdventureWorks_Customers** – Customer details, demographics
3. **AdventureWorks_Product_Categories** – Categories of products
4. **AdventureWorks_Products / product** – Product details, descriptions, pricing
5. **Product_Subcategories** – Subcategories of products
6. **AdventureWorks_Returns** – Returned orders, reasons
7. **AdventureWorks_Sales_2015 / 2016 / 2017** – Yearly sales data
8. **AdventureWorks_Territories** – Sales territories and regions

**TechStack**

- **Data Source:** GitHub API (repositories, commits, contributors)  
- **Pipeline Orchestration:** **Azure Data Factory**  
- **Data Storage:** **Azure Data Lake Storage** with **Parquet format**  
- **Data Transformation:** **PySpark notebooks** in Databricks  
- **Data Warehouse:** **Azure Synapse Analytics** using **CETAS (Create External Table As Select)**  
- **Analytics:** **Power BI dashboards** for repository activity and top contributors  
- **Architecture:** Medallion Architecture (**Bronze → Silver → Gold**)  

---

## Repo Structure
