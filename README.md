<h1 align="center">Hi, I'm Phuc 👋</h1>
<h3 align="center">Data Engineer · Lakehouse · Streaming · Modern Data Stack</h3>

<p align="center">
  <a href="https://linkedin.com/in/phuclhde/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:phuclhde@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.credly.com/badges/524bdfd2-5a72-4b78-8be7-43689fee7961/public_url"><img src="https://img.shields.io/badge/AWS_Certified-Data_Engineer_Associate-FF9900?style=for-the-badge" alt="AWS Certified Data Engineer Associate" /></a>
</p>

## About me

I'm a Data Engineer based in Ho Chi Minh City with 3+ years of building data platforms on AWS and Google Cloud.
I like pipelines that are boring in production: idempotent, observable and easy to replay.

- 🔭 Working on ingestion that feeds a permission-aware RAG knowledge base on Amazon Bedrock
- 🌱 Exploring the modern data stack: Snowflake, dbt contracts, semantic layers
- 💬 Ask me about Kafka, Apache Iceberg, SCD Type 2 and Kimball modeling

## Highlights

- ⚡ Exactly-once streaming on Kafka and Apache Iceberg, safe under failure and replay
- 🚀 Cut a BigQuery pipeline from 5 to 3 minutes (40% faster)
- 🔎 Cut Elasticsearch search latency from 200 ms to 150 ms (25% lower)
- 🗂️ Built a 3-layer S3 Lakehouse with incremental, deduplicated ingestion

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,bash,linux,aws,gcp,kafka,elasticsearch,docker,githubactions,git&perline=11" alt="Tech stack" />
</p>

| Area | Tools |
| :-- | :-- |
| Warehouse & formats | Snowflake, BigQuery, Apache Iceberg, AWS Glue, Athena |
| Transform & orchestrate | dbt, MetricFlow, Airflow, Dagster, NiFi, dlt |
| Processing | PySpark, Spark Streaming, Kafka |
| Quality & governance | Great Expectations, dbt tests, OpenMetadata |
| Delivery | Docker, GitHub Actions, ArgoCD, AWS CDK |

## Featured project

### 🛒 [RetailPulse](https://github.com/whtbl3/retail-pulse)

End-to-end retail analytics: **PostgreSQL → dlt → Snowflake → dbt → Preset**, orchestrated by **Dagster**.

- SCD Type 2 dimensions in dbt, so every sale uses the product cost valid at that moment
- Metrics defined once in a MetricFlow semantic layer
- Great Expectations checks, retries, freshness warnings and Slack alerts
- Slim CI on per-PR Snowflake schemas and dbt contracts on every mart

## GitHub stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=whtbl3&theme=dark&hide_border=true&background=0D1117&ring=29B5E8&fire=FF694B&currStreakNum=29B5E8&currStreakLabel=29B5E8&sideNums=FFFFFF&sideLabels=8B949E&dates=8B949E" alt="GitHub streak" />
</p>
