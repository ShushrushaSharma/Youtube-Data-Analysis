# Youtube-Data-Analysis
This project focuses on building a data processing pipeline using AWS services. It includes setting up an AWS environment, uploading data to S3, and using Glue and Athena for data cataloging and querying. The project also covers writing ETL jobs in AWS Lambda to preprocess and clean the data.


1. Data Ingestion — Build a mechanism to ingest data from different sources.
2. ETL System — We are getting data in raw format, transforming this data into the proper format.
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them.
4. Scalability — As the size of our data increases, we need to make sure our system scales with it.
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS.
6. Reporting — Build a dashboard to get answers to the question we asked earlier.


SERVICES USED
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.


DATASET FROM KAGGLE: https://www.kaggle.com/datasets/datasnaek/youtube-new
