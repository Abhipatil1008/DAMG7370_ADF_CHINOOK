# ADF Chinook Data Integration Project

## Overview
This project demonstrates an end-to-end **Azure Data Factory (ADF)** data integration pipeline using the classic **Chinook** sample database.  
It showcases core data engineering skills such as orchestration, parameterization, incremental loads, and cloud data movement.

The pipeline extracts data from a source system, applies transformations, and loads it into a target data warehouse for analytics.

---

## Tech Stack
- **Azure Data Factory**
- **Azure SQL Database / SQL Server (Chinook DB)**
- **Azure Data Lake Storage / Azure SQL (Target)**
- **GitHub (version control)**

---

## What This Project Demonstrates
- Building modular ADF pipelines
- Using Linked Services & Datasets
- Parameterized pipelines for reusability
- Controlled data movement (Copy Activities)
- End-to-end orchestration suitable for production use cases

---

## How to Run the Pipeline
1. Open **Azure Data Factory Studio**
2. Navigate to **Author** → **Pipelines**
3. Select the main pipeline (e.g. `pl_chinook_ingestion`)
4. Click **Debug** (for test run) or **Trigger Now**
5. Monitor execution in **Monitor → Pipeline Runs**
6. Validate data in the target system

> No code changes are required to run the pipeline once connections are configured.

---

## Data Flow (High Level)
Source → ADF Copy Activity → Target Storage / Database → Ready for BI & Analytics

---

## Why This Project Matters
This project reflects **real-world ETL/ELT patterns** used in enterprise environments and demonstrates readiness for:
- Data Engineer
- Analytics Engineer
- BI / ETL roles

---

## Author
**Abhishek Patil**  
MS Information Systems – Northeastern University  
Focus: Data Engineering, BI, Cloud Analytics
