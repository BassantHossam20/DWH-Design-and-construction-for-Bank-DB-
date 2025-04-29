# 📊 Bank Data Warehouse (`bank_dwh`)

This project models and develops a data warehouse for a banking system using a **Snowflake Schema**. It integrates transactional data from the source `bank` database into a structured analytical model (`bank_dwh`) to support data analysis and business intelligence.

---

## 🎯 Project Objectives

### 1. Dimensional Modeling
- Design a **Snowflake schema** for the `bank_dwh` data warehouse.
- Include a central **fact table** and supporting **dimension tables** for key banking metrics.

### 2. Data Integrity Enforcement
- Develop **SQL-based methods** to check and maintain **referential integrity** between the fact table and its dimensions.

### 3. Time-based Analysis
- Introduce a **Date Dimension** to support **historical tracking** and time-series analysis.

### 4. ETL Process using SSIS
- Design and implement an **SSIS (SQL Server Integration Services)** project to:
  - Extract data from the source `bank` transactional database.
  - Transform and clean data as needed.
  - Load data into the `bank_dwh` target warehouse.

### 5. Analytical Cube with SSAS
- Build an **SSAS (SQL Server Analysis Services)** project in **Multidimensional Mode**.
- Deliverables include:
  - Predefined **measures** and **KPIs**.
  - Configured **dimension hierarchies**.
  - Cube browsing and exploration functionalities.

---

## 📦 Deliverables

- ✅ SQL scripts for schema creation and data integrity validation.  
- ✅ SSIS package(s) for ETL processing.  
- ✅ SSAS project for multidimensional cube modeling.  
- ✅ Date Dimension generation script.  

---

## 🖼️ DWH Design Screenshot

> A screenshot of the data warehouse schema is included to illustrate the Snowflake schema structure and table relationships.
![image](https://github.com/user-attachments/assets/756eae4e-6cf2-4662-bf54-4f6578162252)
