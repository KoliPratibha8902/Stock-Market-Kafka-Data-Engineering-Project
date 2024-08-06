# My First Data Pipeline Project Let's See

## Stock Market Kafka Real Time Data Engineering Project
## Introduction
In this project, we will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka. The goal is to build a robust data pipeline that handles real-time stock market data, processes it, and stores it efficiently using various technologies.

## Architecture
The architecture of this project integrates several technologies to create a seamless data pipeline:
1. **Data Collection**: Real-time stock market data is ingested using Apache Kafka.
2. **Data Processing**: Python scripts are used to process the data.
3. **Data Storage**: Data is stored in Amazon S3.
4. **Data Cataloging**: AWS Glue Crawler and Glue Catalog are used to catalog the data.
5. **Data Querying**: AWS Athena is used to query the data stored in S3.
6. **Compute Resources**: Amazon EC2 instances are used for various processing tasks.
   
![Architecture Diagram](Architecture.jpg)

## Technology Used

- **Programming Language: Python**
  - Python is used for writing scripts and applications that process and analyze the stock market data.
- **Amazon Web Services (AWS)**:
  - **S3 (Simple Storage Service)**: Cloud storage service where the processed data is stored.
  - **Athena**: Serverless interactive query service used to run SQL queries on data stored in S3.
  - **Glue Crawler**: Automatically discovers and catalogs metadata from data stored in S3, making it available for queries in Athena.
  - **Glue Catalog**: A central repository in AWS Glue that stores metadata about data sources, used by Athena and other AWS services.
  - **EC2 (Elastic Compute Cloud)**: Virtual servers used to run the data processing applications and tasks.
- **Apache Kafka**
  - A distributed streaming platform that handles real-time data ingestion and processing by streaming stock market data into the system.

## Dataset Used
The dataset used in this project is available [here](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv). This dataset is primarily used for demonstrating the operational side of the data engineering pipeline.
You can use any dataset for your implementation, but the focus is on building and managing the data pipeline rather than the dataset itself.
