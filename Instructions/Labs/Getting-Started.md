# MS Fabric Foundation for Enterprise Analytics

### Overall Estimated Duration: 8 Hours

## Overview

This lab introduces you to creating a workspace in Microsoft Fabric, a collaborative environment for organizing and managing projects, data, and resources. You will learn how to set up a workspace, create data pipelines for ETL/ELT processes, and use Apache Spark for data processing. Additionally, you will create a notebook to train a machine-learning model to predict customer churn using Scikit-Learn and MLflow. You will also explore dataflows in Microsoft Fabric to connect to various data sources, perform transformations, and define datasets for Power BI reports.

## Objective

By the end of this lab, you will be able to:

- **Create a Fabric workspace** : Learn to create and configure a collaborative workspace in Microsoft Fabric to efficiently manage projects, data, and resources.
- **Ingest data with a pipeline in Microsoft Fabric** : Implement and manage data ingestion in Microsoft Fabric using ETL/ELT pipelines and Apache Spark for scalable analytics.
- **Analyze data in a data warehouse** : Understand how Microsoft Fabric's data warehouse enables full SQL functionality, including insert, update, and delete operations, for large-scale analytics.
- **Get started with Real-Time Analytics in Microsoft Fabric** : Use Microsoft Fabric’s Kusto Query Language (KQL) for efficient storage and querying of time-series data, including real-time logs and IoT information.
- **Use notebooks to train a model in Microsoft Fabric** : Discover how to use Microsoft Fabric’s Kusto Query Language (KQL) for efficient storage and querying of time-series data, including real-time logs and IoT information.
- **Analyze data with Apache Spark** : Use Microsoft Fabric to train and track a customer churn prediction model with Scikit-Learn and MLflow.
- **Create a Dataflow (Gen2) in Microsoft Fabric** : Master Apache Spark for flexible, distributed data processing and analysis across platforms like Azure HDInsight and Databricks.
  
## Pre-requisites

- **Fundamental Knowledge of Data Engineering**: Understanding ETL/ELT and data pipelines
- **Programming Skills**: Familiarity with Python, SQL, or similar languages
- **Basic Understanding of Data Visualization**: Experience with tools like Power BI

## Architecture

In Microsoft Fabric, the workflow begins with creating a Fabric workspace to manage projects, data, and resources collaboratively. Next, ingest data with a pipeline using ETL/ELT processes and Apache Spark for scalable data integration. Once data is ingested, it is stored in the data warehouse, which supports full SQL functionality for extensive analytics. For real-time data processing, get started with Real-Time Analytics using Kusto Query Language (KQL) to handle time-series data like real-time logs and IoT information. Use notebooks to train machine learning models, such as a customer churn prediction model, using Scikit-Learn and MLflow. Finally, create a Dataflow (Gen2) to leverage Apache Spark for distributed data processing and analysis across platforms like Azure HDInsight and Databricks.

## Architecture Diagram

  ![](./Images/arch10.jpg)

## Explanation of Components

1. **Data Factory**: Handles data integration and workflow orchestration, allowing you to move and transform data from various sources into your data platform.

1. **Data Warehouse**: Provides scalable, high-performance storage and full SQL functionality for large-scale analytics. It supports complex queries, including insert, update, and delete operations, to efficiently handle extensive data sets.
   
1. **Data Engineering**: Provides tools and services for preparing and transforming data for analysis. This includes data pipelines, data flow orchestration, and data quality management.

1. **Data Science**: Offers capabilities for building, training, and deploying machine learning models. It supports various programming languages and frameworks for data science.

1. **Real-Time Analytics**: Facilitates real-time data processing and analysis, enabling insights from streaming data sources.
   
1. **Power BI**: A powerful analytics and visualization tool that allows you to create reports and dashboards, providing interactive and actionable insights from your data.

This hands-on-lab demonstrates how to create and manage a workspace in Microsoft Fabric, including setting up data pipelines and using Apache Spark. You’ll also train a machine-learning model and explore dataflows for Power BI reports.

## Happy Learning!!
