# Data Engineering with Python and AI/LLMs

*Freecodecamp & dltHub Virtual Internship Course | Master of ELT Best Practices*

This repository contains the official project report, presentation deck, and completion credentials for the **Freecodecamp: Data Engineering with Python and AI** course conducted by **dltHub** and **freeCodeCamp** (August 2026).

---

## 👤 Student Details

| Field | Details |
| :--- | :--- |
| **Name** | Pratyush Khatri |
| **Roll Number** | 2410031011 |
| **Institute** | IILM University, Greater Noida, U.P. |
| **Programme** | B.Tech CSE, Batch 2024–2028 |
| **Internship Domain** | Data Engineering with Python & AI/LLMs |
| **Certification Earned** | Master of ELT Best Practices |

---

## 📌 About the Internship

The internship focused on moving beyond fragile, custom-written ETL scripts toward automated, self-healing data ingestion pipelines using the open-source `dlt` (Data Load Tool) framework. Learning was carried out through video tutorials and hands-on Google Colab code notebooks, covering core concepts such as REST API extraction, automatic data normalization, dynamic schema management, incremental loads (SCD2), lakehouse/warehouse loading, orchestration, and LLM-assisted pipeline generation ("vibe-coding").

* **Course Providers:** dltHub & freeCodeCamp
* **Featured Instructors:** Alexey Grigorev & Adrian Brudaru

---

## 🎯 Key Objectives

* **Batch vs. Streaming Processing:** Understand architectural trade-offs between scheduled batch and streaming pipelines.
* **REST API Ingestion:** Extract data efficiently handling authentication, rate limits, pagination, and memory-safe streaming.
* **Automated Normalization:** Flatten deeply nested JSON arrays into relational structures automatically without manual boilerplate.
* **Data Contracts & Governance:** Enforce contract modes (`evolve`, `freeze`, `discard`) and set up Slack alerting on schema drift.
* **Incremental Loading & SCD2:** Implement state tracking, cursor-based loading, backfilling, and Slowly Changing Dimensions (SCD Type 2).
* **Multi-Destination Loading:** Deploy data into DuckDB, Google BigQuery, Snowflake, Amazon Redshift, and AWS S3 (Parquet/Iceberg).
* **Pipeline Orchestration:** Deploy automated pipeline runs using GitHub Actions, Crontab, Dagster, and Apache Airflow.
* **AI-Assisted Pipelines:** Utilize OpenAI GPT models and Cursor IDE to generate prompts, write self-documenting code, and vibe-code production pipelines.

---

## 🗓️ Course Curriculum & Modules

| Module | Topic | Key Technical Focus |
| :---: | :--- | :--- |
| **1** | Introduction & Foundations | Data engineering core principles; moving from scripts to platform engineering. |
| **2** | Batch vs. Streaming Processing | Architectural trade-offs between batch loads and real-time streaming engines. |
| **3** | Extracting Data from REST APIs | Pagination, authentication, rate limits, and memory-safe generator streams. |
| **4** | Data Normalization & Schemas | Flattening nested JSON arrays into relational tables; dynamic schema evolution. |
| **5** | Loading Data into DuckDB | Transforming raw Python data structures into fast, columnar in-memory DuckDB tables. |
| **6** | Introduction to `dlt` | Configuring `dlt` resources, secret management, and automated normalization. |
| **7** | Data Contracts & Alerting | Enforcing contract modes (evolve, freeze, discard) and alerting via Slack webhooks. |
| **8** | Write Dispositions & Incremental | Append, replace, cursor tracking, state persistence, backfilling, and SCD2 tracking. |
| **9** | Performance Tuning | Parallel workers, async network execution, and memory management optimizations. |
| **10** | Lakes, Lakehouses & Warehouses | Exporting Parquet, Apache Iceberg, Delta Lake files to AWS S3, Glue, and BigQuery. |
| **11** | Deployment & Orchestration | Setting up automated workflow schedules via GitHub Actions, Cron, Dagster, and Airflow. |
| **12** | Building Pipelines with AI/LLMs | Designing prompt templates, generating docs, and vibe-coding pipelines with Cursor IDE. |

---

## 🛠️ Technologies & Tools Used

* **Languages & Core Libraries:** Python, Requests, Pandas, PyArrow, ConnectorX
* **Ingestion & ELT Framework:** `dlt` (Data Load Tool) / dltHub
* **Databases & Warehouses:** DuckDB, MySQL, Google BigQuery, Snowflake, Amazon Redshift
* **Data Lakes & Catalogs:** AWS S3, Parquet, Apache Iceberg, Delta Lake, AWS Glue Catalog, AWS Athena
* **Orchestration & Deployment:** GitHub Actions, Crontab, Dagster, Apache Airflow
* **AI & Development Tools:** OpenAI GPT Models, Cursor IDE, PyCharm / VS Code, Google Colab

---

## 🏆 Certification & Credentials

| Field | Details |
| :--- | :--- |
| **Certificate Title** | Master of ELT Best Practices |
| **Course** | Freecodecamp: Data Engineering with Python and AI |
| **Certificate ID** | `6a940a9209b7ae6ed40a49fa` |
| **Issue Date** | August 30, 2026 |
| **Issued By** | Adrian Brudaru (Co-founder & CDO, dltHub) |

---

## 📁 Repository Structure

```text
.
├── Pratyush_Internship_Report.pdf   # Full internship report 
├── Pratyush_PPT_Internship.pdf      # Presentation
├── Pratyush_Certificate.pdf            # Official Certificate
└── README.md                               # Project documentation
