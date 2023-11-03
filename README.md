
# AWS ETL Pipeline Using Python

## Business Overview
Over 2.6 billion individuals worldwide use YouTube monthly, making it one of the top-most visited websites. Now, imagine your company will launch a new data-driven campaign, and you are in charge of the campaign advertisements. Which platform do you think will be ideal for the advertisement? None other than YouTube! This means the company will have to analyze large volumes of YouTube data using various tools and metrics to effectively understand how to advertise its new campaign on the platform. The company might want to find answers to questions such as ‘how to categorize videos based on the number of comments and statistics’, ‘what factors affect how popular a YouTube video will be’, etc.

This project aims to securely manage data, streamline, and analyze the structured and semi-structured YouTube video data based on the video categories and trending metrics.

## Aim Of the Project:
This big data project aims to build an ETL pipeline using Python and various AWS tools and services, including Athena, Lambda, and Glue, on a Youtube video dataset from Kaggle.

## Dataset
This Python ETL pipeline big data analytics project uses the Youtube dataset from Kaggle that contains statistics (CSV and JSON files) on popular daily YouTube videos over many months.
The data for each region is in its file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment_count are among the items included in the data. A category_id field, which differs by area/region, is also included in the JSON file linked to the region.

## Tech Stack
➔ Languages- SQL, Python3
➔ Services- AWS S3, AWS Glue, QuickSight, AWS Lambda, AWS Athena, AWS IAM

## Key Concepts In AWS ETL Pipeline Python Project
Some key concepts, tools, and technologies used in this AWS ETL Pipeline Example Using Python project are discussed below-

## Data Pipeline:
Data pipeline is similar to a conveyor belt for transferring raw data from one system to another. Depending on the situation, it can handle data from various sources in real-time or in batches. The pipeline includes everything from collecting and storing data to data analytics and transforming it into a format ready to be queried. It shows key performance indicators (KPIs) and manages the ETL process.

## Amazon S3:
Amazon S3 (AWS Simple Storage Service) is a highly scalable object storage service offered by AWS, which provides secure and durable storage for various data types, such as documents, images, videos, etc. With S3, you can easily store and retrieve data anywhere online. It offers high availability, scalability, and cost-effective storage options.

## AWS IAM:
Uisng AWS Identity and Access Management (IAM), a popular service by Amazon Web Services (AWS), enables users to manage access and permissions to their AWS resources securely. Using IAM, users can create and manage user accounts, assign granular permissions, and control who can access your AWS services and resources. IAM allows you to set up policies to define fine-grained access controls, ensuring that only authorized users or services can interact with your AWS environment. It's a crucial tool for maintaining security and ensuring compliance within your AWS infrastructure.

## AWS QuickSight 
I used Amazon QuickSight being a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud. It is the first BI service to offer pay-per-session pricing, where you only pay when your users access their dashboards or reports, making it cost-effective for large-scale deployments. It can connect to your data from various sources like Redshift, S3, Dynamo, RDS, files like JSON, text, CSV, TSV, Jira, Salesforce, and on-premises Oracle SQL-server.

## AWS Glue 
AWS Glue is a serverless data integration service that makes it easy to collect, process/repare, and combine data for data analytics, machine learning, and application development. It runs Spark/Python code without managing Infrastructure at a nominal cost. You pay only during the run time of the job. Also, you pay storage costs for Data Catalog objects. Tables may be added to the AWS Glue Data Catalog using a crawler. The majority of AWS Glue users employ this strategy. A crawler can crawl multiple data sources and repositories in a single run. The crawler adds or modifies one or more tables in your Data Catalog after it's finished.

## AWS Lambda
Lambda is a computing service that allows data engineers and programmers to run code without creating or managing servers. Lambda executes the code on high-availability computing infrastructure and manages all aspects, including server and operating system maintenance, capacity provisioning and automated scaling, code monitoring, and logging. Lambda allows you to run code for almost any application or backend service.

## AWS Athena
AWS Athena is a serverless query service offered by AWS that allows you to analyze data stored in Amazon S3 using standard SQL queries without needing to manage infrastructure. With Athena, you can quickly extract insights from your data by querying both structured data and unstructured data formats. It offers on-demand scalability and cost-effectiveness, making it an efficient tool for ad-hoc data analysis and exploration.

## Approach
    1. Dataset Understanding.
    2. Setting Up The Environment For Building A Python Data Pipeline
    3. Creating An AWS S3 Bucket For The ETL Pipeline.
    4. Creating AWS Glue Catalog For The AWS ETL Pipeline.
    5. AWS Lambda Data Pipeline.
    6. Python ETL Pipeline Project- Data Processing Using AWS Glue.
    7. Data Materialization Using AWS Glue Studio.
    8. Data Visualization Using AWS QuickSight.
    

## Architecture Diagram:
![Logo](https://project-architecture0102.s3.eu-west-2.amazonaws.com/youtube_data_engineering_architectural+diagram.jpg)










    




