#End-to-End Automobile Sales Data Pipeline & Analytics

* Engineered an automated data pipeline in Microsoft Fabric, ingesting automobile sales data from GitHub to Azure SQL Database via ADF pipelines with scheduled triggers. (Covers step 1 - Ingestion & Scheduling)

* Implemented robust initial and incremental data loading patterns in ADF pipelines to efficiently transfer data from Azure SQL to ADLS Gen2 Bronze layer in Parquet format. (Covers step 2 - Loading to Bronze, Initial/Incremental, Format, now explicitly mentions robust loading patterns)

* Orchestrated data transformation and cleansing in Azure Databricks (Unity Catalog) using PySpark & SQL within automated workflows, generating Silver layer tables. (Covers step 5 & 7 - Bronze to Silver Transformation & Workflow Execution, now explicitly mentions workflow automation)

* Developed dimensional fact and dimension tables from refined Silver layer data in Databricks notebooks, storing as optimized Delta tables in the Gold layer for analytical readiness. (Covers step 6 - Silver to Gold Dimensional Modeling & Delta, implicitly notebook usage)

* Designed and published interactive Power BI dashboards visualizing sales insights from the Gold layer Delta tables, demonstrating a complete end-to-end data solution. (Covers step 7 - Power BI Reporting, keeps end-to-end emphasis)
