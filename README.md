**Azure ETL Pipeline – Beginner Practice Project**
This project marks my first hands-on implementation of a cloud-based ETL pipeline using Microsoft Azure.
Starting as a complete beginner to the Azure Portal, I built this project step by step to understand real-world data engineering fundamentals.

**Project Overview**
Built an end-to-end ETL pipeline using Azure Data Factory
Ingested flat-file (CSV) data into Azure Data Lake Storage Gen2
Implemented a Bronze data layer following modern data lake architecture
Learned Azure resource setup, datasets, pipelines, publishing, and execution

**Technologies Used**
Azure Data Factory (ADF)
Azure Data Lake Storage Gen2 (ADLS)
Azure Portal
CSV flat-file data

**Architecture (Current Phase)**
Source CSV → Azure Data Factory → ADLS Gen2 (Bronze Layer)

**Folder structure:**
datalake/
 └── bronze/
     └── source=manual/
         └── entity=orders/
             └── dt=2026-01-17/
                 └── orders.csv

