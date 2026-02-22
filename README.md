rgu_research_dwh-main is the source code from main GIT branch of rgu_research_dwh repository hosted on GitHub

GitHub link - https://github.com/Hesh1998/rgu_research_dwh.git
* This is the codebase for the Data Platform which was hosted on Databricks.
* To run this code please follow below steps,
- Create a Workspace in Databricks
- Close the GitHub repository
- Create a SQL Warehouse Compute
- Run the DDL scripts in bronze, silver and gold folders using the Query Editor.ipynb file
- Create the Bronze Layer ETL, Silver Layer ETL, Gold Layer ETL and ETL Scheduler Pipelines on Databricks using the corresponding .yaml files.
- Run the ETL Scheduler Pipeline to populate the Data Lakehouse unto Gold Layer.
