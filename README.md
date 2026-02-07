# YouTube ETL Pipeline

A production-style ETL pipeline that extracts YouTube data, transforms it for analytics, and loads it into a PostgreSQL database. Built with Python and Apache Airflow, and fully containerized using Docker.


## Tech Stack

- Python
- Apache Airflow
- Docker & Docker Compose
- PostgreSQL
- Pytest (unit testing)



## Project Overview

This project implements a standard ETL workflow:

1. Extract YouTube data from the API  
2. Transform raw data into an analytics-ready format  
3. Load the processed data into PostgreSQL
4. Goes through data quality pipelines

Apache Airflow is used to orchestrate and schedule the pipeline, while Docker ensures consistent local development and deployment.



## Key Features

- Automated ETL workflows with Apache Airflow  
- Containerized setup for easy and reproducible execution  
- Modular Python codebase following data engineering best practices  
- Unit tests to validate transformation logic  



## Getting Started

```bash
git clone https://github.com/Sommie09/youtube_ETL.git
cd youtube_ETL
docker-compose up --build
