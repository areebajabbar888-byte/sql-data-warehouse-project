# 🧱 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This end-to-end project demonstrates how raw source data can be transformed into a structured data warehouse using a **Bronze → Silver → Gold architecture**.

The project focuses on data ingestion, data cleaning, transformation, data modeling, data quality checks, and SQL-based analytics.

---

## 🏗️ Data Architecture: Medallion Design

This project follows the **Medallion Architecture** to organize data into three layers:

**Bronze → Silver → Gold**

### 🔄 Data Flow

![image_url](

- **Bronze Layer**: Stores raw data loaded from the source datasets.
- **Silver Layer**: Cleans, standardizes, and transforms the raw data.
- **Gold Layer**: Provides business-ready data for analytical queries and reporting.

---

## 📖 Project Overview

This project includes:

- 🧱 **Data Architecture** – Designing a structured data warehouse using Bronze, Silver, and Gold layers.
- 🔄 **Data Transformation** – Loading, cleaning, and transforming source data.
- 🧹 **Data Quality** – Performing quality checks on the transformed data.
- 🧮 **Data Modeling** – Creating business-ready structures for analytical use.
- 📊 **Analytics & Reporting** – Analyzing customer behavior, product performance, and sales trends.

---

## 🛠️ Tools & Technologies

- **MySQL Workbench** – Database development, SQL execution, testing, and management
- **CSV Files** – Source datasets
- **Draw.io / diagrams.net** – Data architecture and data modeling diagrams
- **GitHub** – Project version control and documentation

---

## 🚀 Project Requirements

### 💾 Data Warehouse

**Objective:** Build a structured data warehouse that transforms raw source data into clean and business-ready data for analysis.

### Data Processing

- Load raw source data into the Bronze layer.
- Clean and standardize data in the Silver layer.
- Perform data quality checks.
- Transform data into analytical structures.
- Create business-ready views in the Gold layer.

### Data Architecture

The warehouse is organized into:

- 🥉 **Bronze Layer** – Raw data
- 🥈 **Silver Layer** – Cleaned and transformed data
- 🥇 **Gold Layer** – Business-ready analytical data

---

## 📊 Analytics & Reporting

The Gold layer is designed to support analysis in the following areas:

### 👥 Customer Behavior

- Customer purchasing behavior
- Customer-related metrics
- Customer segmentation

### 📦 Product Performance

- Product performance
- Product-level analysis
- Product-related metrics

### 💰 Sales Trends

- Sales performance
- Sales trends
- Revenue-related analysis
- Aggregated sales metrics

---

## 📂 Repository Structure

```text
DataWarehouse/
│
├── datasets/
│   └── Source datasets
│
├── docs/
│   ├── 01-Data Flow.jpeg
│   ├── 02-Integration Model - How Tables Are Related.jpeg
│   ├── 03-Data Warehouse.jpeg
│   └── 04-Data Mart-Star Schema.jpeg
│
├── scripts/
│   ├── Silver/
│   │   ├── Silver_layer_loadingdata.sql
│   │   └── ddl_silver_layer.sql
│   │
│   ├── bronze/
│   │   └── ddl_bronze_layer.sql
│   │
│   ├── gold/
│   │   └── ...
│   │
│   └── init_database.sql
│
├── tests/
│   └── silver_layer_quality_checks.sql
│
├── LICENSE
└── README.md
