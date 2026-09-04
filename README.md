<h1 align="center">Hi, I'm Aryan Rajput 👋</h1>

<p align="center">
  <b>Data Engineer - Somewhere in Pune, India</b><br/>
  Learning about pipelines and stuff
</p>

<p align="center">
  <a href="mailto:aryan.ed4200@gmail.com"><img src="https://img.shields.io/badge/Email-aryan.ed4200%40gmail.com-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/aryan-rajput-?utm_source=share_via&utm_content=profile&utm_medium=member_android"><img src="https://img.shields.io/badge/LinkedIn-Aryan%20Rajput-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
</p>

---

## Me.?

- Currently working on the **Crypto Market Microstructure Pipeline** -- real time BTC/USDT & ETH/USDT tick ingestion via Binance WebSocket streamed through Redpanda Cloud into Spark Structured Streaming, landing in Delta Lake on S3 (Bronze/Silver layers live -- gold in progress waiting for sufficient data) - VWAP and order flow imbalance (OFI) features per Cont, Kukanov & Stoikov (2014)
- Completed the **Credit Card Fraud Analytics Pipeline** -- end-to-end medallion architecture using AWS, Snowflake, dbt & Airflow, with PII tokenisation and Z-score anomaly detection
- **Indian Airspace Intelligence Platform** -- real-time ADS-B flight telemetry pipeline (OpenSky API -> S3 -> Databricks Lakeflow); currently paused after diagnosing OpenSky's hyperscaler IP blocklisting across multi-cloud testing
- Deepening expertise in **Apache Spark, Kafka/Redpanda, and real-time streaming architectures**
- Financial domain exposure spans **Ab Initio-based data migration, AML monitoring, fraud detection, and crypto market microstructure** -- fintech data is where I've accidentally ended up and I'm not mad about it
- Long game plan: **Data Engineering & Quant Finance infra**. Short game: ship the next layer before I give up
- trying to reading market microstructure papers instead of doing something "productive"

---

## Stack n Stuff

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Data Engineering & Processing**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Boto3](https://img.shields.io/badge/Boto3-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle%20SQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)

**Tools & Version Control**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ab Initio](https://img.shields.io/badge/Ab%20Initio-002D62?style=flat-square&logoColor=white)

---

## 🚀 Things I've Actually Built (mostly)

### 📈 [Crypto Market Microstructure Pipeline](https://github.com/Aryan-Rajput/crypto-market-pipeline)
> Real-time market microstructure feature engineering pipeline for BTC/USDT and ETH/USDT — *nearly done*

- **Stack:** Binance WebSocket - Redpanda Cloud - Spark Structured Streaming - AWS S3 Delta Lake
- **Highlights:** VWAP & order flow imbalance (OFI) features approximated from taker-side trade flow (Cont, Kukanov & Stoikov, 2014) - Bronze/Silver layers live
- **Architecture:** Streaming ingestion -> Delta Lake medallion (Bronze -> Silver -> Gold, Gold in progress)

### 🔐 [CC Fraud Analytics Pipeline](https://github.com/Aryan-Rajput/cc_fraud_pipeline)
> End-to-end data pipeline for credit card fraud detection using a medallion architecture (Bronze -> Silver -> Gold)

- **Stack:** AWS S3 - AWS Glue - Snowflake - dbt - Apache Airflow - GitHub Actions - Power BI
- **Highlights:** 1.85M+ rows processed - PII masking - automated CI/CD - full data lineage via dbt
- **Architecture:** Medallion (raw -> cleansed -> aggregated) on cloud-native infrastructure

### ✈️ [Indian Airspace Intelligence Platform](https://github.com/Aryan-Rajput/indian-airspace-intelligence)
> Real-time ADS-B flight telemetry ingestion for Indian airspace — *in progress*

- **Stack:** OpenSky Network API - AWS S3 - Terraform - Databricks Lakeflow
- **Highlights:** 25,000+ partitioned flight records ingested - diagnosed OpenSky's hyperscaler IP blocklisting via multi-cloud (GCP/EC2) testing
- **Status:** On hold after hitting cloud ingestion blockers; Bronze Lakeflow pipeline built on Databricks Community Edition

---

<p align="center">
  <i>open to DE roles - perpetually mid-project - send help (or opportunities) :)</i>
</p>
