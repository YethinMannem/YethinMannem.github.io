---
name: WorkMap - Labour Trend Analysis
tools: [ETL, Azure, Spark, Azure Data Dactory, Databricks, SQL, PowerBI]
image: https://teleportmanpower.com/wp-content/uploads/2023/10/Market-job-Analysis-1024x576.webp    
description: Designed and implemented a scalable data engineering pipeline integrating NAICS and BLS datasets to analyze labor market trends. Developed insights on employment, wage growth, and industry performance, enabling data-driven decision-making for policymakers and businesses. Focused on automation, real-time updates, and high-performance data processing for actionable insights.
--- 

# WorkMap - Labour Trend Analysis

Project Overview
Designed the Work Map Project, a comprehensive data engineering solution to analyze labor market trends across industries by integrating data from NAICS (North American Industry Classification System) and BLS (Bureau of Labor Statistics).
Enabled stakeholders, including policymakers and businesses, to derive actionable insights on employment, wage growth, and industry performance.

Data Ingestion:
Automated the retrieval of NAICS data from the U.S. Census Bureau and BLS employment data using APIs and custom Python scripts.
Stored raw datasets securely in Azure Data Lake Storage (ADLS) to ensure scalability and efficient data handling.
Utilized Databricks and Apache Spark for distributed processing and efficient handling of large datasets.
Data Transformation:
Implemented ETL processes to clean, standardize, and preprocess data using pandas and Spark for optimal querying and analysis.
Parsed and formatted JSON responses from APIs into structured formats like CSV for further analysis.
Transformed data into Spark DataFrames for distributed processing, ensuring compatibility with downstream analytics workflows.
Data Serving:
Designed a structured data storage system in ADLS to support easy retrieval and querying for analysis and visualization.
Integrated processed data with advanced analytics tools in Databricks and prepared it for dashboards and reports.
Visualization and Insights:
Conducted exploratory data analysis (EDA) to uncover trends in employment, wages, and industry performance.
Created meaningful visualizations using matplotlib, seaborn, and plotly to represent key insights.
Prepared summary reports and visualizations to highlight trends such as high-growth industries and wage disparities.
Azure Integration:
Leveraged Azure Key Vault for secure storage and management of API credentials.
Set up role-based access control (RBAC) to ensure secure handling of data.
Optimized the cost and performance of Azure resources, including ADLS and Databricks clusters.