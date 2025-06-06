# SQL-DataWarehouse

# 📊 Data Warehouse & Analytics Portfolio Project
Welcome to the Data Warehouse & Analytics Project! 🚀

This  project presents a complete, end-to-end data solution, covering everything from raw data ingestion to delivering insightful, business-ready analytics. It reflects best practices in data architecture, engineering, and analytics, designed to showcase practical skills and technical proficiency.

---
## 🏗️ Data Architecture
The project leverages the Medallion Architecture, a layered approach widely adopted in modern data platforms, consisting of:

![Data Architecture](Docs/Data%20Architecture%20Design.png)

**Bronze Layer** – Raw data is ingested from source systems (CSV files) and stored as-is in a SQL Server database.

**Silver Layer** – Data is cleansed, transformed, and standardized for further use, ensuring quality and consistency.

**Gold Layer** – This layer contains business-ready, analytics-optimized data modeled in a star schema for reporting and decision-making.

---
## 📖 Project Highlights
The key components of this project include:

1. **Data Architecture Design**: Implementation of a scalable Medallion architecture to organize and streamline data flow.

2. **ETL Pipelines**: Development of robust Extract, Transform, Load (ETL) processes to move and refine data from source to warehouse.

3. **Data Modeling**: Creation of well-structured fact and dimension tables tailored for analytical workloads.

4. **Analytics & Reporting**: Generation of SQL-based reports and dashboards to uncover trends and support business decisions.

## 💼 Skills Demonstrated
This repository serves as a strong demonstration of capabilities in:

✅ SQL Development

✅ Data Architecture & Modeling

✅ ETL Pipeline Development

✅ Data Engineering Best Practices

✅ Analytics & Reporting


## 🚀 Project Requirements

### 🎯 Objective
Design and implement a modern data warehouse using SQL Server to consolidate sales-related data, supporting analytics and business intelligence.

### 📌 Key Requirements

- **Data Sources**: Load data from two independent systems—ERP and CRM—provided in CSV format.

- **Data Quality**: Identify and resolve data inconsistencies to ensure reliable analysis.

- **Data Integration**: Merge both datasets into a unified, analysis-friendly model.

- **Scope**: Focus only on the latest available data; historical tracking is out of scope.

- **Documentation**: Provide clear, structured documentation of the data model to support business and technical users alike.

---

## 📊 Analytics & Reporting (Data Analysis)

### 🎯 Objective
Use SQL to develop insightful analytics that drive data-informed decision-making. The analysis focuses on:

**Customer Behavior**
**Product Performance**
**Sales Trends**

These insights enable stakeholders to monitor key metrics, discover trends, and optimize strategy.

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw source data (ERP and CRM CSV files)
│
├── docs/                               # Project documentation and design assets
│   ├── etl.drawio                      # Visual representation of ETL logic and techniques
│   ├── data_architecture.drawio        # Diagram of the Medallion architecture
│   ├── data_catalog.md                 # Dataset descriptions, metadata, and field definitions
│   ├── data_flow.drawio                # End-to-end data flow diagram
│   ├── data_models.drawio              # Star schema model diagram
│   ├── naming-conventions.md           # Standard naming guidelines for database objects
│
├── scripts/                            # SQL scripts organized by data processing stage
│   ├── bronze/                         # Scripts for raw data ingestion
│   ├── silver/                         # Scripts for data transformation and cleansing
│   ├── gold/                           # Scripts for building analytical data models
│
├── tests/                              # Data validation and quality checks
│
├── README.md                           # Project introduction and usage instructions
├── LICENSE                             # Licensing information
├── .gitignore                          # Git ignore rules
└── requirements.txt                    # Required tools, libraries, or dependencies
```

---