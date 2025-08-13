# ADF Assignment

## Overview
This repository showcases an **end-to-end data engineering pipeline** built using:
- **Azure Data Factory (ADF)** for ingestion
- **Azure Data Lake Storage Gen2 (ADLS)** for storage
- **Azure Databricks** with **Delta Lake** for transformation and analytics

The solution is organized into three layers as per the **Medallion Architecture**:

- **Bronze Layer**: Raw data ingestion via ADF pipelines into ADLS
- **Silver Layer**: Cleansed and business-rule transformed data (customer, product, store, customer_sales)
- **Gold Layer**: Aggregated, analytics-ready output combining store, product, and sales data



## Repository Structure
src/
  - bronze_to_silver/
    drivers
  -->utils
  -  silver_to_gold/
   gold_aggregations

