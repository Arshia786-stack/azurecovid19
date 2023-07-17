# COVID-19 Data Factory Project using Azure

This project utilizes Azure technologies, including Azure Data Factory (ADF), to construct a data pipeline for gathering, transforming, and presenting COVID-19 data. The pipeline retrieves data from sources such as the European Centre for Disease Prevention and Control (ECDC) and the World Health Organization (WHO). The data is then processed and stored in Azure Data Lake Gen2. The goal is to create interactive dashboards using Power BI to visualize and analyze the data effectively.

## Technologies Used

- Azure Data Factory (ADF): A fully managed cloud-based data integration service from Microsoft Azure.
- Azure Data Lake Gen2: A cloud-based data storage solution for storing and managing large amounts of data.
- Azure Databricks: An Apache Spark-based analytics platform used for big data processing and transformation.
- Azure HDInsight: A cloud-based service for running Apache Hadoop, Spark, Hive, and other big data frameworks.
- Power BI: A business analytics service that provides interactive visualizations and dashboards.

## Project Overview

1. **Data Ingestion**: Data is sourced from various locations, such as ECDC and WHO, using Azure Data Factory. ADF retrieves the data and loads it into Azure Data Lake Gen2 for further processing.

2. **Data Transformation**: Azure Databricks is used to perform data transformation tasks. This includes cleaning, aggregating, and enriching the data to prepare it for analysis.

3. **Data Analysis**: Azure HDInsight is employed for big data processing and analytics. It provides powerful tools for analyzing large volumes of data and extracting meaningful insights.

4. **Dashboard Creation**: Power BI is utilized to create interactive and visually appealing dashboards. These dashboards provide real-time insights into COVID-19 data, enabling informed decision-making.

5. **Monitoring and Management**: Azure Data Factory, Azure Monitor, and Log Analytics are employed to continuously monitor the data pipelines. This ensures their smooth operation and allows for prompt issue resolution.

Feel free to adapt and extend the project to meet your unique needs and preferences.


