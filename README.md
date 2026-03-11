# Spotify Azure Data Engineering Project (Azure / PySpark)

This project implements an end-to-end data engineering pipeline that ingests, processes, and transforms Spotify data using Azure Data Factory, Azure SQL Database, Azure Data Lake, and Azure Databricks.

## Tech Stack
- Azure Data Factory  
- Azure SQL Database  
- Azure Data Lake Storage  
- Azure Databricks  
- PySpark & Spark Streaming  
- Delta Live Tables  
- Unity Catalog  
- GitHub  

## Architecture
- Source data ingested from **Azure SQL Database**  
- **Azure Data Factory pipelines** perform incremental ingestion and orchestration  
- Data stored in **Azure Data Lake** using a **Medallion Architecture (Bronze, Silver, Gold)**  
- **Azure Databricks with PySpark** used for data transformation and processing  
- **Delta Live Tables** used for automated data pipelines and incremental processing  
- Final datasets structured using **Star Schema modeling** for analytics  

## Key Work
- Built incremental ingestion pipelines using Azure Data Factory  
- Implemented looping pipelines with conditional logic for CDC processing  
- Performed scalable transformations using PySpark in Azure Databricks  
- Designed Medallion architecture for structured data processing  
- Implemented Delta Live Tables for automated pipeline management  
- Built dimensional models using **Star Schema and Slowly Changing Dimensions (SCD)**  
- Integrated metadata-driven pipelines and dynamic processing logic  
- Configured CI/CD integration with GitHub and Databricks Asset Bundles  

The project demonstrates a complete modern data engineering workflow, from ingestion and orchestration to scalable transformation and analytics-ready data modeling.
