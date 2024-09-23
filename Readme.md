# Streaming Data to AWS S3 With Kafka Running on EC2 Instances

This project is for learning purposes by simulating streaming data with .csv files with sample function so we can build pipeline as if the data were running in real time.

## Architecture

The architecture of this project is as follows:

- EC2 instances running Kafka
- Data were dumps into S3 Bucket Amazon AWS
- The data in the S3 Bucket is crawled by AWS Glue
