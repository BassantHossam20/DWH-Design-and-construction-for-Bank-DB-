#Bank Data Warehouse (bank_dwh)
This project models and develops a data warehouse for a banking system using a Star Schema approach. It integrates transactional data from the source bank database into a structured analytical model (bank_dwh) to support business intelligence and reporting.

Project Objectives
Design a Dimensional Model:
Build a star schema for the bank_dwh data warehouse, including a central fact table and related dimension tables.

Maintain Data Integrity:
Implement a robust SQL-based method to check and enforce referential integrity between fact and dimension tables.

Historical Tracking:
Add a Date Dimension to the model to facilitate historical analysis and support time-based queries.

ETL Process with SSIS:
Design and implement an SSIS (SQL Server Integration Services) project to extract data from the source bank transactional system and load it into the bank_dwh warehouse.

Multidimensional Cube with SSAS:
Develop an SSAS (SQL Server Analysis Services) project in multidimensional mode to create an analytical cube. Key deliverables include:

Measures and KPIs
Dimension hierarchies
Cube browsing capabilities

Deliverables
SQL scripts for data warehouse schema creation and integrity checks.
SSIS package(s) for ETL implementation.
SSAS cube project for multidimensional analysis.
Date Dimension table generation script.
DWH Design Diagram Screenshot included in the repository.
Screenshot
A screenshot of the data warehouse schema design is provided to visualize the star schema and table relationships.
![image](https://github.com/user-attachments/assets/447058f5-ebb2-4492-ab67-6912155a7511)
