# 📦 FutureCart CRM Data Mart

A **Lambda Architecture**–based Data Warehouse solution for managing and analyzing customer cases and survey feedback in **real-time and batch modes** using AWS.

---

## 🚀 Project Summary

FutureCart CRM Data Mart is designed to help businesses like **FutureCart Inc.** track customer support and satisfaction **KPIs** using both **historical batch data** and **real-time streams**.

- 🔁 **Lambda Architecture** combining batch (Hive) and streaming (Kinesis)
- 🧩 **Multiple AWS services**: MySQL, Hive, Spark, Kinesis, Redshift, Quicksight
- 📊 **KPI dashboards** for open/closed cases, sentiment analysis, and daily trends

---

## 🧰 Tech Stack

| Service | Role |
|--------|------|
| **MySQL (EC2)** | Source for dimension tables |
| **Apache Hive** | Stores historical case & survey data |
| **Apache Spark on EMR** | Batch processing and real-time streaming |
| **Amazon Kinesis** | Real-time ingestion |
| **Amazon S3** | Data lake |
| **Amazon Redshift Serverless** | Central data warehouse |
| **Amazon Quicksight** | Dashboards & analytics |
| **Airflow + AWS Lambda** | Workflow orchestration & scheduling |

---

## 🗂️ Architecture Overview

