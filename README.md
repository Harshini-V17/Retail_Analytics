Retail Sales Alaytics Data Engineering Project

Overview:
    This project demonstrates a data engineering workflow using Python, PySpark, Azure Databricks, and Power BI to ingest, transform, analyze, and visualize retail sales data.
Project Workflow
Task 1 – Data Ingestion & Transformation
    1. Created datasets: stores.csv, products.csv, store_sales.csv.
    2. Loaded and cleaned data in Databricks using PySpark, joined into final_df.
    3. Derived metrics: gross_amount, net_amount, profit.
    4. Exported cleaned data as cleaned_sales.csv.

Task 2 – ETL Pipeline & Logging
    1. Simulated an ETL pipeline with stages: Ingestion, Transformation, Storage.
    2. Implemented logging to track each stage and verify execution.

Task 3 – Power BI Dashboard
    1. Imported cleaned_sales.csv into Power BI.
    2. Created DAX measures: Total Revenue, Profit Margin.
    3. Built an interactive dashboard with:
          * Total Revenue & Profit by Store (Bar Chart)
          * Top 5 Products by Sales (Bar Chart)
          * Sales Trend by Date (Line Chart)
          * Region-wise Performance (Pie Chart)
          * Slicers for Region, Store, and Date Range
          
Tools & Technologies:
Python, PySpark, Azure Databricks, Power BI
