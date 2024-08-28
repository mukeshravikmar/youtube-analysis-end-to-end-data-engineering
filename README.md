# youtube-analysis-end-to-end-data-engineering

## Overview

The objective of this project is to handle structured and semi-structured YouTube video data in a secure manner, optimize it, and do analysis on it using trending metrics and video categories.

## Project Goals
1. Data Ingestion: Construct a system to take in data from various sources.
2. ETL System: Data is being received in raw format; we are converting it to the appropriate format.
3. Data lake: To store the data that we will be receiving from various sources, we need a centralized repository.
4. Scalability – We must ensure that our system can grow as our data grows in size.
5. Cloud – Because large volumes of data cannot be processed on a local computer, we must use the cloud; in this instance, AWS
6. Reporting – Create a dashboard to obtain the responses to the previous query.


## Services we will be using
1. Amazon S3: Offering manufacturing scalability, data availability, security, and performance, Amazon S3 is an object storage service.
2. AWS IAM: This is essentially identity and access management, which lets us securely control who has access to AWS resources and services.
3. QuickSight: Designed for the cloud, Amazon QuickSight is a machine learning-powered, scalable, serverless, embeddable business intelligence (BI) service.
4. AWS Glue: With this serverless data integration tool, you can easily find, prepare, and integrate data for application development, analytics, and machine learning.
5. AWS Lambda: This computing service enables coders to execute programs without setting up or maintaining servers.
6. AWS Athena: Athena is an interactive query service for S3 that allows data to remain in S3 without the need to be loaded.


## Dataset Used
This Kaggle dataset includes statistics (CSV files) on the most popular YouTube videos every day for a number of months. Every day, up to 200 popular videos are released for various areas. Every region's data is contained in a separate file. Among the details in the data are the title of the video, the channel name, the publishing time, tags, views, likes and dislikes, description, and the number of comments. In the JSON file associated with the region, there is also a category_id field, which varies by area.

https://www.kaggle.com/datasets/datasnaek/youtube-new
