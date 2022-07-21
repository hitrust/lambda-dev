# lambda-dev
AWS Lambda development information collections and code snippet.

# AWS Lambda
AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you. These events may include changes in state or an update, such as a user placing an item in a shopping cart on an ecommerce website. You can use AWS Lambda to extend other AWS services with custom logic, or create your own backend services that operate at AWS scale, performance, and security. AWS Lambda automatically runs code in response to multiple events, such as HTTP requests via Amazon API Gateway, modifications to objects in Amazon Simple Storage Service (Amazon S3) buckets, table updates in Amazon DynamoDB, and state transitions in AWS Step Functions.

Lambda runs your code on high availability compute infrastructure and performs all the administration of your compute resources. This includes server and operating system maintenance, capacity provisioning and automatic scaling, code and security patch deployment, and code monitoring and logging. All you need to do is supply the code.

# Contents
- [Features](#features)
- [Related Services](#related-products)
- [Developer Tools](#developer-tools)
- [Web App Dvelopment](#web-app-dvelopment)
- [Data Processing](#data-processing)
- [Mobile Backend Development](#mobile-backend-development)
- [Edge Computing](#edge-computing)
- [Open Source Repository](#open-source-repository)

# Features

# Related Products

## Amazon API Gateway

## Amazon S3

## Amazon DynamoDB

## AWS Step Functions

## Amazon Simple Notification Service (Amazon SNS)

## Amazon EventBridge

## Amazon Simple Queue Service (Amazon SQS)

# Developer Tools

## AWS Serverless Application Model (SAM)
AWS Serverless Application Model (AWS SAM) is an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings.

-[serverless-application-model](https://github.com/aws/serverless-application-model)

-[aws-sam-cli](https://github.com/aws/aws-sam-cli)

## AWS Cloud Development Kit (AWS CDK)
AWS Cloud Development Kit (AWS CDK) is an open source software development framework to define your cloud application resources using familiar programming languages.

 # Web App Dvelopment
 Combine AWS Lambda with other AWS services to build powerful web applications that automatically scale up and down and run in a highly available configuration across multiple data centers.
 
## Chalice
 Chalice is a framework for writing serverless apps in Python. It allows you to quickly create and deploy applications that use AWS Lambda.
 
 # Data Processing

## File processing
 Use Amazon Simple Storage Service (Amazon S3) to trigger AWS Lambda data processing in real time after an upload, or connect to an existing Amazon EFS file system to enable massively parallel shared access for large-scale file processing.

## Stream processing
 Use AWS Lambda and Amazon Kinesis to process real-time streaming data for application activity tracking, transaction order processing, clickstream analysis, data cleansing, log filtering, indexing, social media analysis, IoT device data telemetry, and metering.
 
 # Mobile Backend Development
 Build backends using AWS Lambda and Amazon API Gateway to authenticate and process API requests. Use AWS Amplify to easily integrate your backend with your iOS, Android, Web, and React Native frontends.

 # Edge Computing
 ## IoT backends
Build serverless backends using AWS Lambda to handle web, mobile, Internet of Things (IoT), and third-party API requests.

# Open Source Repository
## Cloud Custodian
Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources.
-[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)

## AWS Data Wrangler
Pandas on AWS - Easy integration with Athena, Glue, Redshift, Timestream, Neptune, OpenSearch, QuickSight, Chime, CloudWatchLogs, DynamoDB, EMR, SecretManager, PostgreSQL, MySQL, SQLServer and S3 (Parquet, CSV, JSON and EXCEL). 
-[AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler)

## StreamAlert
StreamAlert is a serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define.  
-[StreamAlert](https://github.com/airbnb/streamalert)

## AWS Lambda Powertools for Python
A suite of utilities for AWS Lambda Functions that makes tracing with AWS X-Ray, structured logging and creating custom metrics asynchronously easier.  
-[AWS Lambda Powertools for Python](https://github.com/awslabs/aws-lambda-powertools-python)

## AWS Serverless Ecommerce Platform
Serverless Ecommerce Platform is a sample implementation of a serverless backend for an e-commerce website. This sample is not meant to be used as an e-commerce platform as-is, but as an inspiration on how to build event-driven serverless microservices on AWS.  
-[AWS Serverless Ecommerce Platform](https://github.com/aws-samples/aws-serverless-ecommerce-platform)

## Real-time File Processing
Serverless Reference Architecture for Real-time File Processing .  
-[Real-time File Processing](https://github.com/aws-samples/lambda-refarch-fileprocessing)