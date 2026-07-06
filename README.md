# Hi, I'm Alvin David 👋

Data Engineer with 3 years of experience across Talend, AWS, and Azure — now focused on Azure Databricks Lakehouse architecture, PySpark, Delta Lake, and Azure Data Factory.

I solve data engineering problems: messy raw data, slow queries, unreliable incremental loads, and brittle pipelines. 🔧

## 🚀 Featured Projects

**🚕 [NYC Yellow Taxi — Azure Databricks Data Pipeline](https://github.com/AlvinDavid225/nyc-taxi-azure-databricks-pipeline)**
Medallion architecture pipeline processing 38.3M+ taxi trip records. Diagnosed and fixed a schema mismatch (INT64 vs INT32 across monthly files) that was silently rescuing 92% of rows; resolved data skew using 4-bucket salting; eliminated large shuffles with broadcast joins; applied Z-ORDER for query performance. Secured with Azure Key Vault, visualized in Power BI.

**🏗️ [Azure Databricks E-Commerce Lakehouse](https://github.com/AlvinDavid225/azure-databricks-ecommerce-pipeline)**
Medallion architecture (Bronze/Silver/Gold) processing 1.5M+ records, with Delta MERGE for idempotent loads, Unity Catalog governance, star schema modeling, and OPTIMIZE/ZORDER performance tuning. Orchestrated via Databricks Workflows with a Databricks AI/BI dashboard.

**⚡ [Fleet Telemetry Real-Time Streaming](https://github.com/AlvinDavid225/azure-databricks-real-time-streaming)**
Kafka producer → Azure Event Hubs → Databricks Structured Streaming pipeline processing 163K+ GPS telemetry events in real time. Built Bronze/Silver/Gold streaming layers with tumbling-window aggregation, stream-static joins, and MERGE-based upserts for live per-vehicle alerts, visualized in a Databricks AI/BI dashboard.

**🔄 [Azure Data Factory Real-World Scenarios](https://github.com/AlvinDavid225/ADF-Real-World-Scenarios)**
Production-grade ADF reference patterns: metadata-driven pipelines that scale to many tables, watermark-based incremental loading, event-driven ingestion via Storage Event Triggers, and custom error-logging frameworks.

## 🛠️ Skills

**Problem-Solving & Coding:** Python (data manipulation, debugging, production scripting) · SQL (window functions, CTEs, query optimization, incremental logic)

**Cloud & Platforms:** Azure Databricks · Azure Data Factory · ADLS Gen2 · Azure Synapse Analytics · AWS S3 · Amazon Redshift

**Engineering:** PySpark (broadcast joins, salting, partitioning) · Delta Lake · Structured Streaming · Unity Catalog · Medallion Architecture

## 📜 Certifications

- Microsoft Certified: Azure Fundamentals (AZ-900)
- Microsoft Certified: Azure Data Fundamentals (DP-900)
- Microsoft Certified: Azure AI Fundamentals (AI-900)
- AWS Certified Cloud Practitioner

## 📫 Connect

GitHub: [github.com/AlvinDavid225](https://github.com/AlvinDavid225)
