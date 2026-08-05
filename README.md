#  Data Ingestion using Databricks Lakeflow Declarative Pipelines

## Overview

This project demonstrates an automated data ingestion pipeline built using **Databricks Lakeflow Declarative Pipelines (DLP)**. The pipeline continuously ingests raw sales data, applies transformations, and organizes it using the **Medallion Architecture (Bronze, Silver, Gold)** for efficient analytics.

---

## Features

- Automated data ingestion
- Incremental data processing
- Medallion Architecture implementation
- Data quality and transformation
- Scalable ETL pipeline
- Real-time data updates

---

## Architecture

```
Incoming Data
      │
      ▼
 Bronze Layer
(Raw Data Ingestion)
      │
      ▼
 Silver Layer
(Clean & Transform)
      │
      ▼
 Gold Layer
(Business Ready Data)
```

---

## Tech Stack

- Databricks
- Lakeflow Declarative Pipelines (DLP)
- PySpark
- Delta Lake
- Unity Catalog

---

## Pipeline Workflow

1. Raw sales data is ingested into the Bronze layer.
2. Data is cleaned and transformed in the Silver layer.
3. Business-ready datasets are generated in the Gold layer.
4. Incremental processing ensures only new data is processed.

---

## Repository Structure

```
Lakeflow-Data-Ingestion/
│
├── notebooks/
├── pipeline/
├── screenshots/
└── README.md
```

---

## Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Incremental Data Processing
- Delta Lake
- PySpark
- Lakeflow Declarative Pipelines
- Unity Catalog

---

## Future Enhancements

- Data quality expectations
- Pipeline monitoring
- Alerting and logging
- CI/CD integration
