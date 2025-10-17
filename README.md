# sql-data-warehouse-project
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights

# 🏢 SQL Data Warehouse from Scratch

## 📘 Overview
This project demonstrates the end-to-end design and implementation of a **SQL Data Warehouse** using a **multi-layered architecture** approach.  
It follows the **Bronze–Silver–Gold** data modeling strategy to ensure scalability, maintainability, and data quality across all stages of data processing.

---

## 🏗️ Data Architecture
![Data Architecture Diagram](assest/data_architecture.png)

The Data Warehouse consists of three main layers:
### 🥉 Bronze Layer – Raw Data Storage
- **Purpose:** Landing zone for raw, unprocessed data ingested from various source systems.  
- **Data Source:** CSV files containing transactional or operational data.  
- **Implementation:**
  - Data is ingested as-is into the **SQL Server Database**.
  - No transformations applied at this stage.
  - Ensures complete data lineage and traceability.  
- **Goal:** Preserve raw data for auditing and reprocessing if required.

---

### 🥈 Silver Layer – Cleansed and Standardized Data
- **Purpose:** Focuses on cleansing, standardization, and normalization of data.  
- **Implementation:**
  - Handle missing or inconsistent values.
  - Remove duplicates and ensure referential integrity.
  - Standardize data formats, naming conventions, and data types.
  - Integrate data from multiple sources into a consistent structure.  
- **Goal:** Produce clean, structured, and analytics-ready data for downstream use.

---

### 🥇 Gold Layer – Business-Ready Data
- **Purpose:** Contains curated, business-ready data optimized for reporting and analytics.  
- **Implementation:**
  - Apply business logic and transformations.
  - Create **Star Schema** models (Fact and Dimension tables).
  - Optimize data for BI tools like **Power BI** or **Tableau**.  
- **Goal:** Deliver high-quality, analytics-friendly data to drive insights and business decisions.

---

## 📖 Project Overview

This project involves:

- **Data Architecture:** Designing a Modern Data Warehouse using **Medallion Architecture** (Bronze, Silver, and Gold layers).  
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.  
- **Data Modeling:** Developing **Fact** and **Dimension** tables optimized for analytical queries.  
- **Analytics & Reporting:** Creating **SQL-based reports and dashboards** for actionable insights.

---

🎯 **This repository is an excellent resource for professionals and students looking to showcase expertise in:**

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics

## 🚀 Project Requirements
#### 🎯 **Objective**
Develop a modern **Data Warehouse** using **SQL Server** to consolidate sales data, enabling analytical reporting and data-driven decision-making.

---

#### ⚙️ **Specifications**

- **Data Sources:** Import data from **two source systems (ERP and CRM)** provided as **CSV files**.  
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.  
- **Integration:** Combine both data sources into a single, user-friendly **data model** optimized for analytical queries.  
- **Scope:** Focus on the **latest dataset only** — historization of data is not required.  
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

## 📊 BI: Analytics & Reporting (Data Analysis)

#### 🎯 **Objective**
Develop **SQL-based analytics** to deliver detailed insights into key business areas, including:

- **Customer Behavior**  
- **Product Performance**  
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling **data-driven decisions** and **strategic planning** across the organization.
