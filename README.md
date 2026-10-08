# Hi, I'm Oliver Samwel

### Data Engineer | Python • SQL • Data Pipelines • CDC • Cloud & Data Platforms

I build data systems that move data from source to storage, transformation, and analytics.

My work spans synthetic data generation, API-based ingestion, ETL/ELT pipelines, workflow orchestration, change data capture, event streaming, data quality, containerized infrastructure, and CI/CD.

I focus on building systems that are practical, reproducible, and understandable from ingestion through to the final analytical output.

---

## Core Technologies

**Languages & Data**
- Python
- SQL
- Pandas
- PostgreSQL
- MySQL

**Data Engineering**
- ETL / ELT
- Data ingestion
- Data transformation
- Data quality & testing
- Data warehousing concepts
- Change Data Capture (CDC)
- Event-driven data pipelines
- Workflow orchestration

**Platforms & Tools**
- Apache Kafka
- Debezium
- Apache Airflow
- dbt
- MinIO
- Docker & Docker Compose
- Grafana
- Apache Superset
- Git & GitHub
- GitHub Actions / CI/CD

---

# Featured Projects

## Datagen — Synthetic Data Generation Library

[View Datagen on GitHub](https://github.com/25thOliver/Datagen)

**Datagen** is a Python package for generating localized synthetic tabular data for development, testing, analytics prototyping, and data engineering workflows.

It is the project I use to explore the engineering side of building and maintaining a reusable Python data tool.

### What it does

- Generates synthetic **Kenyan user profiles**, including local phone numbers, addresses, cities, and geographic coordinates.
- Generates **employee and salary data** across departments and experience levels.
- Generates **global business region metadata**.
- Generates **vehicle inventory data** focused on the Kenyan automotive market.
- Supports deterministic data generation through seed control.
- Supports multiple output formats including CSV, JSON, Excel, and Parquet.
- Provides a Python API and command-line workflow for generating datasets.
- Includes automated tests and CI/CD through GitHub Actions.
- Provides Docker-based development support.

### Why it matters

Synthetic data is useful when building and testing data pipelines without relying on sensitive or production datasets. Datagen provides a reusable way to create controlled datasets that can be used to seed databases, prototype ETL/ELT pipelines, test transformations, and support analytics development.

**Stack:** Python, Pandas, Faker, Docker, pytest, GitHub Actions

---

## Real-Time Earthquake CDC Pipeline

[View Real-Time Earthquake CDC on GitHub](https://github.com/25thOliver/Real-Time-Earthquake-CDC)

An end-to-end **Change Data Capture and streaming pipeline** that ingests live and revised earthquake events from the USGS FDSN API and moves them from an operational database into an analytical PostgreSQL environment.

### Architecture

`USGS API → MySQL → Debezium → Kafka → JDBC Sink → PostgreSQL → Grafana`

### What it demonstrates

- Python-based API ingestion running on a 60-second polling cycle.
- `updatedafter` watermarking to capture new and revised earthquake events.
- High-watermark recovery to reduce data gaps after ingestion downtime.
- MySQL upserts that allow revised earthquake records to produce downstream CDC events.
- MySQL row-based binary logging.
- Debezium-based Change Data Capture.
- Kafka topics for asynchronous event streaming.
- JDBC Sink delivery into PostgreSQL.
- Grafana dashboards for real-time seismic activity and trends.
- Docker Compose orchestration of the multi-service environment.
- Automated tests with pytest.
- GitHub Actions CI/CD for automated test execution.

**Stack:** Python, MySQL, PostgreSQL, Kafka, Debezium, Kafka Connect, Docker Compose, Grafana, pytest, GitHub Actions

---

## Kenya Economic & Weather Intelligence Pipeline

[View Kenya Economic & Weather Pipeline on GitHub](https://github.com/25thOliver/Kenya-Weather-Economic-Pipeline)

A Dockerized data engineering pipeline that brings together **economic indicators and weather data for Kenya**, taking the data through ingestion, raw storage, transformation, validation, database loading, and analytics.

### Pipeline components

- **World Bank API** — economic indicators for Kenya.
- **Open-Meteo API** — weather observations for selected Kenyan locations.
- **Python ingestion services** — collect and process source data.
- **MinIO** — object storage for raw pipeline data.
- **PostgreSQL** — relational storage for analytical datasets.
- **Apache Airflow** — workflow orchestration.
- **dbt** — transformation and data quality testing.
- **Apache Superset** — analytical visualization.
- **Docker Compose** — containerized infrastructure.

### What it demonstrates

- API-based data ingestion from multiple external sources.
- Raw-data storage before transformation.
- ETL/ELT pipeline design.
- Workflow orchestration.
- Data transformation and validation with dbt.
- PostgreSQL data modeling and constraints.
- Data quality testing.
- Object storage using an S3-compatible storage layer.
- Multi-service containerized development.
- Git/GitHub-based incremental engineering workflow.

**Stack:** Python, PostgreSQL, MinIO, Apache Airflow, dbt, Docker, Apache Superset, World Bank API, Open-Meteo API

---

# Engineering Focus

Across these projects, I work primarily around:

- Building and maintaining data ingestion pipelines
- Designing ETL/ELT workflows
- Working with relational and analytical databases
- Data transformation and quality validation
- Workflow orchestration
- Streaming and Change Data Capture
- Containerizing data infrastructure
- Automated testing and CI/CD
- Building systems that can be inspected, reproduced, and extended

I am particularly interested in data engineering roles where I can work on real data platforms, pipelines, and infrastructure while continuing to deepen my experience with production-scale systems.

---

# GitHub Activity

I use GitHub to build, document, and track the systems I work on.

![Oliver's GitHub stats](https://github-readme-stats.vercel.app/api?username=25thOliver&show_icons=true&theme=dark)

[![GitHub Streak](https://streak-stats.demolab.com/?user=25thOliver&theme=default)](https://git.io/streak-stats)

---

# Connect

- Portfolio: [25oliver-web-portfolio.vercel.app](https://25oliver-web-portfolio.vercel.app/)
- LinkedIn: [Samwel Oliver](https://www.linkedin.com/in/samwel-oliver)
- GitHub: [25thOliver](https://github.com/25thOliver)
- X: [@bug_alchemist](https://x.com/bug_alchemist)

---
