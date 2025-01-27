# nyc_caps_project

# PROJECT INTRODUCTION
- nyc_caps_project is project to integrate payroll data across all agencies in the cities of New York. I am tasked with the duty to develop a Data Analytics platform to accomplish two primary objectives: 
- Financial Resource Allocation Analysis: To analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
- Transparency and Public Accessibility: To make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees

# OBJECTIVES
- Design a Data Warehouse for NYC 
- Develop a scalable and automated ETL Pipeline to load the payroll data NYC data warehouse 
- Develop aggregate table(s) in the Data warehouse for easy analysis of the key business questions 
- Ensure quality and consistency of data in the pipeline 
- Create a public user with limited privileges to enable public access to the NYC Data warehouse.
- Properly document all  processes for reproducibility – version control 
- Maintain a cloud hosted repository of your codebase to facilitate collaboration with team members.

# Tech Stack
- PostgreSQL
- Azure
- GitHub
- VSCode
- Power BI

# Dimensional model image of the Data warehouse![nyc _model drawio 2-Page-2 drawio](https://github.com/user-attachments/assets/9c161713-0071-41c3-9db8-d61e3568d2fb)

# Data Architecture image of the pipeline ![nyc drawio](https://github.com/user-attachments/assets/d540d72e-8b47-44fe-8cc4-cdc7a254e7ba)

# captures within Azure portal 

- GetMetadata:The GetMetadata activity in Azure Data Factory (ADF) or Synapse is used to retrieve metadata from a dataset or file in your data store. It helps you fetch properties such as file names, file sizes, folder structure, last modified time, or schema information. This activity is especially useful for dynamic pipelines where decisions or further actions depend on file or dataset characteristics.![WhatsApp Image 2025-01-27 at 14 18 19_a353fbcf](https://github.com/user-attachments/assets/195f9d6a-3166-48a4-933a-dda5bf3a8556)


ForEach: The ForEach activity in Azure Data Factory (ADF) or Azure Synapse allows you to iterate over a collection of items and execute specific activities for each item in the collection. It is a control flow activity used for building pipelines that dynamically process multiple items, such as files, database records, or parameters.![WhatsApp Image 2025-01-27 at 14 04 02_b31bedb4](https://github.com/user-attachments/assets/a1388e59-05e0-42fb-a8f6-dad24e08b8fa)


A stored procedure in Azure is a precompiled set of SQL statements stored in a relational database, such as Azure SQL Database, Azure Synapse Analytics, or SQL Server. It allows you to encapsulate logic for querying, transforming, or manipulating data and execute it as a single unit. Stored procedures are particularly useful for tasks like data validation, transformation, and batch processing.
In the context of Azure Data Factory (ADF) or Azure Synapse Pipelines, you can call stored procedures as part of your data integration workflows.


Integration runtime:Integration Runtime (IR) in Azure Data Factory (ADF) and Azure Synapse Pipelines is the compute infrastructure used to execute your data integration workflows. It acts as the bridge between the pipeline activities and the data sources, whether they are in the cloud, on-premises, or a combination of both.![WhatsApp Image 2025-01-24 at 01 14 04_d513486f](https://github.com/user-attachments/assets/1cb5ed3b-b04b-4577-84d7-83eea4fe559c)


![WhatsApp Image 2025-01-27 at 14 04 02_db97630d](https://github.com/user-attachments/assets/5ee22bea-ecb2-4ba1-a49c-9c78275bcbfd)


