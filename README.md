# Data Warehouse and Analytics Project

This repository presents a complete data warehousing and analytics solution using SQL Server. It follows a structured approach—from raw data ingestion to building analytical models and generating business insights—adopting best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

This project uses the **Medallion Architecture** model with three layers:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Ingests raw data from CSV files into SQL Server.
2. **Silver Layer**: Performs data cleansing, standardization, and transformations.
3. **Gold Layer**: Structures business-ready data into a star schema for analytics.

---

## 📖 Project Overview

This project involves:

* **Data Architecture**: Implementing Bronze, Silver, and Gold layers.
* **ETL Pipelines**: Extracting, transforming, and loading data into the warehouse.
* **Data Modeling**: Designing fact and dimension tables.
* **Analytics & Reporting**: Writing SQL-based reports and insights.

Skills demonstrated:

* SQL Development
* Data Engineering
* ETL Development
* Dimensional Modeling
* Analytical Reporting

---

## 🛠️ Tools & Resources

* **Datasets**: Provided in CSV format
* **SQL Server Express**: Database engine
* **SQL Server Management Studio (SSMS)**: Database GUI
* **DrawIO**: For architecture and data flow diagrams
* **Notion**: Project planning templates and steps

---

## 🚀 Project Requirements

### Data Engineering

**Objective**:
Build a modern data warehouse to consolidate ERP and CRM data for analytics.

**Key Components**:

* Import raw data from CSV files
* Clean and integrate datasets
* Build a unified star schema
* Document schema for analytics use

---

### Data Analytics

**Objective**:
Create SQL queries and reports to analyze:

* Customer behavior
* Product performance
* Sales trends

Refer to [`docs/requirements.md`](docs/requirements.md) for more details.

---

## 📂 Repository Structure

```
data-warehouse-project/
├── datasets/                # Raw ERP and CRM datasets
├── docs/                    # Project documentation and architecture
│   ├── *.drawio            # Architecture and data flow diagrams
│   ├── *.md                # Metadata and documentation files
├── scripts/                 # SQL scripts for each layer
│   ├── bronze/             # Raw data ingestion
│   ├── silver/             # Cleaning and transformation
│   ├── gold/               # Analytical modeling
├── tests/                   # Quality checks and validation
├── README.md                # Project overview
├── LICENSE                  # Licensing info
└── requirements.txt         # Project dependencies
```

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). Free to use, modify, and distribute with appropriate attribution.

---
