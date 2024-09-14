
# Earthquake Data Engineering Project with Microsoft Fabric

## Project Overview
This project aims to process real-time earthquake data from the USGS API using a structured data engineering pipeline. By leveraging Microsoft Fabric, Spark, and Python, the project implements the medallion architecture (Bronze, Silver, Gold) to ensure incremental and organized data processing. The final output is a Power BI report providing insightful visualizations of global earthquake patterns.

## Architecture and Workflow
1. **Data Source:** USGS Earthquake API
2. **Data Ingestion (Bronze Layer):** Raw data ingestion using Python and Spark.
3. **Data Transformation (Silver Layer):** Data cleansing and structuring.
4. **Data Enrichment (Gold Layer):** Business-ready data preparation.
5. **Orchestration:** Microsoft Fabric's orchestration capabilities to schedule and manage data pipelines.
6. **Visualization:** Power BI for data analysis and visualization.



## Project Highlights
- **Real-time Data Fetching:** Utilizes the USGS API to fetch up-to-date earthquake data globally.
- **Medallion Architecture:** Implements the Bronze, Silver, and Gold layers for incremental and organized data processing.
- **Microsoft Fabric Integration:** Orchestrates data processing using Microsoft Fabric for efficient scheduling and pipeline management.
- **Data Analysis with Power BI:** Provides an intuitive and interactive Power BI dashboard for global earthquake analysis.

## Technologies Used
- **Microsoft Fabric:** For orchestration and data pipeline management.
- **Apache Spark & Python:** For data ingestion, transformation, and processing.
- **USGS API:** Source for real-time earthquake data.
- **Power BI:** For building interactive visualizations and dashboards.

## Project Workflow

### 1. Data Ingestion (Bronze Layer)
- Fetches raw earthquake data from the USGS API using Python.
- Stores the raw data in the Bronze layer for historical record-keeping.

### 2. Data Transformation (Silver Layer)
- Cleanses and structures the raw data.
- Processes the data using Spark to ensure a more refined dataset.

### 3. Data Enrichment (Gold Layer)
- Aggregates and enriches the data to be business-ready.
- Prepares the data for analysis, ensuring high-quality insights.

### 4. Orchestration
- Microsoft Fabric orchestrates the data pipelines.
- Automates the incremental data processing using scheduled tasks.

### 5. Visualization
- Power BI is used to create an interactive dashboard.
- Visualizes earthquake occurrences, magnitudes, locations, and other key metrics.

## Conclusion
This project showcases a complete data engineering pipeline using Microsoft Fabric, Spark, and Python to process and visualize earthquake data. By implementing the medallion architecture, it ensures a scalable, structured approach to data processing, providing valuable insights through Power BI.
