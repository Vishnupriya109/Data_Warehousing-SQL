# Data_Warehousing-SQL
Data warehousing project, which is done using SQL with developing 3 layers: silver layer, bronze layer, gold layer.
Data_architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

Project Overview

Design the architecture: a modern data warehouse with three layers, bronze, silver and gold.
Build the ETL pipelines: load the source files and move the data through the layers.
Model the data: facts and dimensions, ready for reports.
Analyze it: answer business questions with SQL.

 Project Requirements
Building the Data Warehouse (Data Engineering)

Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
