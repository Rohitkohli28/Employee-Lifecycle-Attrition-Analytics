# Employee Lifecycle and Attrition Analytics

## Project Overview

An end-to-end data engineering project that processes employee lifecycle data using Azure, Databricks, Delta Lake, and Power BI.

## Architecture

Bronze → Silver → SCD Type 2 → Gold → Power BI

## Technologies

- Python
- SQL
- PySpark
- Azure Data Factory
- Azure Storage
- Azure Databricks
- Delta Lake
- Power BI

## Pipeline

Azure Data Factory
→ Databricks Bronze
→ Silver Transformation
→ SCD Type 2
→ Gold Business Analytics
→ Power BI Dashboard

## Analytics

The project provides insights into:

- Current employee count
- Employee attrition
- Average tenure
- Department-wise employee count
- Department-wise salary
- Active vs resigned employees
- Top salary employees
