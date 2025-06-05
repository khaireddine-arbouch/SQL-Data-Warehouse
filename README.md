# SQL Data Warehouse & Analytics Project

Welcome to the **SQL Data Warehouse & Analytics Project** repository!  
This project presents a complete end-to-end data solution, from raw data ingestion to delivering actionable business insights. Designed to emulate real-world data engineering workflows, it follows industry best practices and showcases modern data warehousing techniques.

---

## Project Summary

This project simulates the development of a modern data warehouse using **SQL Server** and the **Medallion Architecture**—Bronze, Silver, and Gold layers. It integrates datasets from simulated ERP and CRM systems to support reporting on customer behavior, sales performance, and product trends.

Key areas of focus:

- **Data Ingestion** from raw CSV sources
- **Data Cleaning & Transformation** using SQL
- **Dimensional Data Modeling** (Star Schema)
- **Analytical Queries** for business insights

This repository is ideal for anyone interested in:
- Data Engineering
- SQL Development
- ETL Pipeline Design
- Data Modeling
- Business Intelligence & Analytics

---

## Data Architecture

The architecture leverages the Medallion Architecture pattern:

![Data Architecture](assets/Data%20Architecture.png)

- **Bronze Layer**: Raw, unprocessed data from ERP and CRM CSV files loaded into SQL Server.
  ![Bronze Layer Data Flow](assets/Bronze%20Layer%20Data%20Flow.png)
- **Silver Layer**: Cleaned, validated, and transformed data with unified formats and resolved inconsistencies.
  ![Silver Layer Data Flow](assets/Silver%20Layer%20Data%20Flow.png)
- **Gold Layer**: Final business-ready data in a star schema, optimized for analytical consumption and reporting.
  ![Gold Layer Data Flow](assets/Gold%20Layer%20Data%20Flow.png)

---

## Project Workflow

### 1. **Data Engineering**
- Import ERP and CRM datasets (CSV format) into SQL Server (Bronze).
- Clean and standardize the data (Silver).
- Build fact and dimension tables (Gold) following dimensional modeling best practices.

### 2. **Data Analytics**
- Write SQL queries to extract insights related to:
  - Customer behavior
  - Sales trends
  - Product performance
- Support executive dashboards and reporting use cases.

---

## Tools & Resources

All tools used in this project are free and accessible:

- **Datasets**: [Available here](datasets/)
- **SQL Server Express**: [Download](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- **SSMS (SQL Server Management Studio)**: [Download](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
- **Draw.io**: For ERDs, flow diagrams, and data architecture.
- **Notion**: [Project Steps](https://22khair.notion.site/SQL-Data-Warehouse-206b3e45fddb80c08d64cc88e0fd8fa0)

---

## Requirements

### Data Warehouse Development
- **Objective**: Consolidate multi-source sales data into a unified warehouse.
- **Data Sources**: ERP & CRM data in CSV format.
- **Scope**: Focus on current state data (no historization).
- **Deliverables**: Clean datasets, star schema models, and SQL scripts.

### Analytics & Insights
- **Objective**: Deliver actionable SQL insights around:
  - Customer engagement
  - Sales volume and trends
  - Product popularity
- **Tools**: SQL queries, visualizations (optional Tableau extension)

---

## Project Structure

```plaintext
SQL-Data-Warehouse/
├── datasets/                   # Raw data files (CSV)
├── docs/                       # Diagrams and documentation
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
│   ├── data_catalog.md
├── scripts/
│   ├── bronze/                 # Raw data ingestion SQL scripts
│   ├── silver/                 # Data cleansing and transformation scripts
│   ├── gold/                   # Star schema modeling and analytics scripts
├── tests/                      # Data quality and validation scripts
└── README.md                   # Project overview
```
---
## About Me

Hi there! I'm **Khaireddine Arbouch**. I’m an AI Engineering Student.

Let's stay in touch! Feel free to connect with me on the following platforms:

[![YouTube](https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@UcoursX)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khaireddine-arbouch-503477251)
