🎬 Movie Data Engineering Project with Apache Airflow
📌 Overview

This project is a Data Engineering learning project built with Apache Airflow, designed to help me become familiar with Airflow concepts and common data engineering workflows.

The main focus of this repository is understanding how to create, schedule, send, and receive DAGs that interact with SQL databases containing information about movies and actors.

Rather than being a production-ready system, this project serves as a hands-on exploration of orchestration, pipelines, and database-driven workflows.

🎯 Project Goals

Learn and practice Apache Airflow fundamentals

Understand how DAGs are structured and executed

Work with SQL-based databases inside Airflow pipelines

Apply core Data Engineering concepts, such as:

ETL / ELT workflows

Task dependencies

Scheduling and retries

Data validation

Build confidence designing orchestrated data pipelines

🏗️ Project Description

The project revolves around movie-related data, specifically:

Movies

Actors

Relationships between movies and actors

Airflow DAGs are used to:

Extract data from SQL databases

Transform and clean data

Load or sync data between different database tables

Trigger workflows related to movie and actor datasets

Each DAG represents a specific data pipeline and is designed to reinforce different Airflow and data engineering concepts.

🎬 Movie Data Engineering Project with Apache Airflow & Airbyte
📌 Overview

This repository contains a Data Engineering learning project built with Apache Airflow, Airbyte, and Docker, created with the goal of becoming familiar with modern data engineering tools and orchestration concepts.

The project focuses on orchestrating data pipelines that interact with SQL databases containing information about movies and actors, combining data ingestion (Airbyte) with workflow orchestration (Airflow).

This is a hands-on, educational project, designed to simulate real-world data platform architectures.

🎯 Project Objectives

Learn and practice Apache Airflow fundamentals

Understand how Airbyte handles data ingestion

Orchestrate end-to-end data pipelines

Work with SQL-based movie and actor databases

Use Dockerized environments for reproducibility

Apply key Data Engineering concepts, including:

Data ingestion

ELT workflows

Task dependencies

Database initialization

Pipeline orchestration and monitoring

🏗️ Project Description

This project simulates a modern data stack:

Airbyte is used to ingest data from source SQL databases

Apache Airflow orchestrates transformations, validations, and downstream tasks

PostgreSQL databases store movie and actor data

The pipelines manage:

Movie datasets

Actor datasets

Relationships between movies and actors

Each DAG represents a specific step in the data lifecycle, reinforcing best practices in Data Engineering.

📁 Project Structure
.
├── airflow/
│   └── dags
│       ├── etl_dag.py
│
├── airbyte/
│   └── Airbyte configuration and setup
│
├── custom-postgres/
│   └── Docker configuration for custom PostgreSQL images
│
├── custom_postgres/
│   └── Additional PostgreSQL customization and scripts
│
├── source_db_init/
│   └── SQL scripts to initialize source movie and actor databases
│
├── elt/
│   └── ELT / transformation-related scripts
│
├── docker-compose.yml
├── Dockerfile
├── start.sh
└── README.md

🧠 Concepts Covered

Apache Airflow DAGs

Airbyte data ingestion

End-to-end ELT pipelines

SQL database orchestration

Docker-based environments

Task dependencies and scheduling

Observability via Airflow UI

🛠️ Tech Stack

Apache Airflow

Airbyte

Python

PostgreSQL

SQL

Docker & Docker Compose

Bash scripting

🚀 How to Run the Project
Prerequisites

Docker

Docker Compose

Steps

Clone the repository:

git clone https://github.com/your-username/airflow-movie-data-engineering.git
cd airflow-movie-data-engineering


Start the full stack:

docker-compose up --build


Access the tools:

Airflow UI: http://localhost:8080

Airbyte UI: http://localhost:8000

Configure Airbyte connections (if not preconfigured) and enable DAGs in Airflow.

📚 Learning Outcomes

How Airbyte and Airflow complement each other

Designing ingestion + orchestration pipelines

Managing SQL-based data sources

Running data platforms locally with Docker

Understanding modern Data Engineering stacks

⚠️ Disclaimer

This project is intended for learning and portfolio purposes only.
It is not production-ready but reflects real-world Data Engineering workflows and tooling.

👤 Author

Omar Alejandro Martínez Cisneros
Aspiring Data Engineer | Data Science & Automation Enthusiast