# Microsoft Fabric - Retail Project

A retail data engineering project built in Microsoft Fabric using the Medallion architecture (Bronze, Silver, Gold).

## What this project does
- **Bronze:** A Fabric pipeline copies orders (CSV), inventory (JSON) and returns (Excel) from Azure Data Lake Storage Gen2 into the Lakehouse as Parquet files.
- **Silver:** A PySpark notebook cleans and normalizes the data (dates, text, numbers, duplicates, missing values) and saves Delta tables.
- **Gold:** The Silver tables are joined and aggregated into product-level KPIs such as total orders, returns, return rate, revenue and net profit.

## Tools used
Microsoft Fabric, Lakehouse, Data Pipeline, PySpark, Delta tables, Azure Data Lake Storage Gen2, Power BI

## Documentation
Step-by-step documentation with screenshots is in:
- Microsoft_Fabric_Retail_Project.pdf
- Microsoft_Fabric_Retail_Project.docx
