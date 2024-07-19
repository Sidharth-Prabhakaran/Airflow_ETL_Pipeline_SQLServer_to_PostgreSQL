# Airflow_ETL_Pipeline

## Project Overview

This project demonstrates the creation of an ETL (Extract, Transform, Load) pipeline using Apache Airflow. The pipeline extracts data from a SQL Server database, transforms it using Pandas, and loads it into a PostgreSQL database. The primary objective is to automate and optimize data workflows, ensuring efficient and scalable data processing operations.

## Features

- **Data Extraction**: Extracts data from specified tables in a SQL Server database.
- **Data Transformation**: Utilizes Pandas for data transformation, including column selection, null value handling, and column renaming.
- **Data Loading**: Loads the transformed data into a PostgreSQL database using SQLAlchemy.
- **Task Orchestration**: Manages task dependencies and execution order using Apache Airflow TaskGroups.
- **Automation**: Schedules the ETL process to run automatically at specified intervals.

## Project Structure

- **DAGs**: Contains the Airflow DAG definition and task groups.
- **Tasks**: Defines individual tasks for data extraction, transformation, and loading.
- **Connections**: Uses Airflow's connection management to securely connect to SQL Server and PostgreSQL.
