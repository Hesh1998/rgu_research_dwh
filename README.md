rgu_research_dwh-main is the source code from main GIT branch of rgu_research_dwh repository hosted on GitHub

GitHub link - https://github.com/Hesh1998/rgu_research_dwh.git
* This is the codebase for the Data Platform which was hosted on Databricks.
* To run this code please follow below steps,
  1) Create a Workspace in Databricks
  2) Clone the GitHub repository
  3) Create a SQL Warehouse Compute
  4) Run the DDL scripts in bronze, silver and gold folders using the Query Editor.ipynb file
  5) Create the Bronze Layer ETL, Silver Layer ETL, Gold Layer ETL and ETL Scheduler Pipelines on Databricks using the corresponding .yaml files.
  6) Run the ETL Scheduler Pipeline to populate the Data Lakehouse unto Gold Layer.
