## lambda-kinesis-to-dynamoDB

A Lambda function that ingests data from Kinesis Data Stream and writes it to DynamoDB table in batches. Add your Kinesis stream as a trigger in Lambda function. And make sure you have all IAM permissions right.

This code is from this tutorial: https://catalog.us-east-1.prod.workshops.aws/workshops/3ae476e4-e66d-4e78-b22f-6190c79ddee2/en-US/aws-services/kinesis/300-ingestion-to-dynamodb


## kinesis-data-analytics-SQL-examples
Examples of SQL commands in Apache Zeppelin notebook / Kinesis Analytics Studio

SQL is modified from this tutorial: https://aws.amazon.com/blogs/aws/introducing-amazon-kinesis-data-analytics-studio-quickly-interact-with-streaming-data-using-sql-python-or-scala/

## lambda-kinesis-to-SNS

A Lambda function that reads data from Kinesis Data Stream and publishes a message to SNS topic if current data point in stream payload is over the threshold. 
