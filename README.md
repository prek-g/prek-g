# Portfolio & Project Showcase

Hello! My name is Prek Gjonikaj. I'm passionate about data, analytics, and building scalable ETL pipelines that turn raw data into actionable insights. I specialize in data engineering and analytics with Python, PySpark, and Delta Lake.

---

## Featured Project: Finance ETL Pipeline

This project demonstrates a full ETL pipeline built in **Databricks**, ingesting raw JSON data,prioritising idempotency, transforming it across Bronze, Silver, and Gold layers, and implementing SCD1/SCD2 for dimensions with a star schema design.  

Key highlights:
- **Bronze Layer:** Raw ingestion and flattening of JSON files, basic type casting, delta logs, checkpoint, idempotency.  
- **Silver Layer:** Transformation, deduplication, SCD1, and CDC on dimension tables.  
- **Gold Layer:** SCD2 for dimensions, surrogate key assignment, and append-only fact table integration.  
- **Fact Table:** Transactions table with millions of rows, linked to dimension tables via surrogate keys in a star schema design.  

Here is the **architecture diagram** of the pipeline:  
![](https://raw.githubusercontent.com/prek-g/databricks-pipeline-architecture/refs/heads/main/displaying_images/databricks_architecture.png)

### You can check the full Databricks repository [here](https://github.com/prek-g/databricks-pipeline-architecture).

---

## About Me

I enjoy working at the intersection of mathematics, economics, and programming, which naturally led me to data engineering and data science. My goal is to build robust, efficient, and scalable data pipelines and help organizations turn data into value.

---
