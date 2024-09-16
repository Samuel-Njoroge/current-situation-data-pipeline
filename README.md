# Current Situation End To End Data Pipeline
## Background
Current Situation is a company that deals with analyzing data on the current job market due to the recent advancement in Artificial Intelligence. To power their job placement and talent matching pool, they are seeking a solution that integrates with their data stored in an on-premises Microsoft SQL Server database.

## Solution.
### Architecture
![](https://github.com/Samuel-Njoroge/current-situation-data-pipeline/blob/main/diagrams/AI_jobs_insights.svg)

### Technology used.
- `Spark SQL` - For data transformations
- `Databricks` - for data transformations and warehousing environment.
- `Azure Blob Storage` - Raw data storage
- `Azure Data Factory` - ETL 
- `Microsoft SQL Server` - Operational database for transactional systems.

### Skills Developed
- Data Integration - Azure Data Factory pipeline development.
- Big Data Processing - Spark SQL for data transformations.
- ETL/ELT Processes - Understanding and implementing Extract, Transform, Load (ETL) or Extract, Load, Transform (ELT) workflows
- Data Visualization - Power BI report creation and dashboard design
- SQL - T-SQL (for MS SQL Server) and Spark SQL

### Use Cases and Justifications

1. MS SQL Server - Operational database for transactional systems

*Justification*
- Robust relational database system for OLTP workloads
- Strong integration with Microsoft ecosystem

2. Azure Data Factory - Orchestration and data movement

*Justification*
- Managed ETL service in Azure
- Supports various data sources and destinations

3. Azure Blob Storage - Data lake for raw and processed data

*Justification*
- Cost-effective storage for large volumes of unstructured data
- Integrates well with other Azure services

4. Databricks - Big data processing and advanced analytics

*Justification*
- Managed Spark environment
- Collaborative notebook interface
- Supports machine learning workflows

5. Spark SQL - Data transformation and analysis

*Justification*
- SQL interface for Spark, familiar to SQL developers
- Distributed processing for large-scale data

6. Power BI - User-friendly interface for creating reports and dashboards

*Justification*
- Strong integration with Azure and Microsoft products
- Supports both self-service and enterprise BI

### Implementation steps.
1. Creating a storage account.
2. Creating a container.
3. Loading the data from MS SQL Server to Azure Blob Storage using Azure Data Factory.
4. Data transformation in Databricks.
5. Visualization in Power BI.

![](https://github.com/Samuel-Njoroge/current-situation-data-pipeline/blob/main/diagrams/dashboard.jpg)

Read the full implementation steps [here](https://medium.com/@_NjorogeSamuel/current-situation-end-to-end-data-pipeline-d74dd2d0ada9)
 
### Contributing
Contributions to improve the project are welcome!
