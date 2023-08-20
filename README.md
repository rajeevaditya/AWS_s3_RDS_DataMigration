# AWS_s3_RDS_DataMigration

#Overview

This project aims to use a URL that points to a zip file containing multiple JSON files. These JSON files contain various data structures with multiple documents. The goal is to download the zip file from the URL, extract the data from the JSON files, store it in Amazon S3, and load it into Amazon DocumentDB

#Project Goals

Use the requests library to download the zip file from the URL.

Use the zipfile module to extract the data from the zip file.

Use the boto3 library to store the data in Amazon S3.

Create a RDS MySQL instance and connect it with an EC2 instance in the same VPC.
Load the data from S3 into Amazon RDS (MySQL).
