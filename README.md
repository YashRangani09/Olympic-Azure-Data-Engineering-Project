# Olympic-Azure-Data-Engineering-Project
Olympics-DE-Project in Azure

Welcome to the Olympics Data Engineering project on Azure! This project is designed to showcase how various Azure services can be utilized to ingest, store, transform, and analyze Olympics-related data. We have employed the following Azure services to achieve these goals:

INTRODUCTION-TO-TOOLS

•	Azure Data Factory (ADF): Used for data ingestion, Azure Data Factory allows us to efficiently collect data from various sources and move it to the desired destination. In this project, ADF is responsible for bringing in Olympic data from external sources.

•	Azure Data Lake Storage Gen2: This is where the ingested data is stored. Azure Data Lake Storage Gen2 provides a scalable and secure platform for storing large volumes of data. It enables us to manage, access, 
and analyze data effectively.

•	Azure Databricks: For data transformation, we leverage Azure Databricks with PySpark. Databricks provides a collaborative environment for data engineers and data scientists to work together on big data projects. In our project, we use PySpark to clean, reshape, and process the raw Olympics data into a more usable format.

•	Azure Synapse Analytics: To gain valuable insights from the transformed data, we utilize Azure Synapse Analytics. It allows us to run SQL queries on the data warehouse to extract meaningful information. This is where we uncover trends, patterns, and insights related to the Olympics data.

ABOUT-PROJECT
1.	To get started with this project, follow these steps:
2.	Data Ingestion: Use Azure Data Factory to configure data ingestion from your chosen data sources. Define the data movement and transformation activities required to bring the Olympics data into the Azure ecosystem.
3.	Data Storage: The ingested data will be stored in Azure Data Lake Storage Gen2. Set up the appropriate folder structure and permissions to organize and secure your data.
4.	Data Transformation: Utilize Azure Databricks with PySpark for data transformation. Cleanse, preprocess, and reshape the data as necessary to prepare it for analysis.
5.	Analytics: Write SQL queries using Azure Synapse Analytics to gain insights from the transformed data. Identify trends, statistics, and patterns related to the Olympics data.

ARCHITECTURE  
![image](https://github.com/YashRangani09/Olympic-Azure-Data-Engineering-Project/assets/84180552/9e1c7ebd-afb6-4834-b6be-94b8877d121d)

PREREQUISITES

Azure subscription: Ensure you have an active Azure subscription to provision the required services. 

Access to Azure Portal: You'll need access to the Azure portal to create and manage resources. 

Data Sources: Identify the external sources from which you'll be ingesting Olympics data.

USAGE

•	Data Ingestion: Configure and run the ADF pipelines to ingest the Olympics data into Azure Data Lake Storage Gen2.

•	Data Transformation: Execute the PySpark notebooks in Azure Databricks to perform data transformation tasks.

•	Analytics: Use Azure Synapse Analytics to execute SQL scripts in order to derive insights from the transformed data.


