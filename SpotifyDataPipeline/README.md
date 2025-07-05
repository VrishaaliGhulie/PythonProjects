## Spotify_Data_Pipeline

An ETL pipeline that extracts data from the Spotify API, transforms it, and loads it into AWS. This pipeline provides a comprehensive end-to-end solution for retrieving and analyzing music data from Spotify.

![Architecture](https://github.com/user-attachments/assets/2f93f3e7-0e60-4f4f-87f8-9d472a969089)


### Services Used
Amazon S3: Amazon Simple Storage Service (S3) is a cloud-based object storage service provided by Amazon Web Services (AWS). It is designed to store and retrieve large amounts of data, such as photos, videos, and other types of files, from anywhere on the web
CloudWatch: Amazon CloudWatch is a monitoring and observability service provided by Amazon Web Services (AWS). It is designed to collect and track metrics, collect and monitor log files, and set alarms
AWS Glue Crawler: AWS Glue Crawler is a service that automatically crawls data stores, such as Amazon S3, RDS, and Redshift, to infer schemas and partition structures. It can also identify changes in schemas and update the Data Catalog accordingly.
AWS Lambda: AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). It enables developers to run code without provisioning or managing servers. Lambda runs code in response to events and automatically scales up or down to match the incoming request traffic.
AWS Athena: Amazon Athena is an interactive query service provided by Amazon Web Services (AWS) that makes it easy to analyze data stored in Amazon S3 using standard SQL. It allows users to quickly and easily query data without having to set up and manage complex infrastructure or data warehousing tools.
Data Catalog: The Data Catalog is a central repository that stores metadata about data sources, tables, and transforms, which can be queried and managed by other AWS services, such as Athena and EMR.
