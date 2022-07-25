# lambda-dev
AWS Lambda development information collections and code snippet.

# AWS Lambda
AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you. These events may include changes in state or an update, such as a user placing an item in a shopping cart on an ecommerce website. You can use AWS Lambda to extend other AWS services with custom logic, or create your own backend services that operate at AWS scale, performance, and security. AWS Lambda automatically runs code in response to multiple events, such as HTTP requests via Amazon API Gateway, modifications to objects in Amazon Simple Storage Service (Amazon S3) buckets, table updates in Amazon DynamoDB, and state transitions in AWS Step Functions.

Lambda runs your code on high availability compute infrastructure and performs all the administration of your compute resources. This includes server and operating system maintenance, capacity provisioning and automatic scaling, code and security patch deployment, and code monitoring and logging. All you need to do is supply the code.

# Contents
- [Docs](#docs)
- [Related Services](#related-products)
- [Developer Tools](#developer-tools)
- [Web App Dvelopment](#web-app-dvelopment)
- [Data Processing](#data-processing)
- [Mobile Backend Development](#mobile-backend-development)
- [Edge Computing](#edge-computing)
- [Open Source Repository](#open-source-repository)

# Docs

-[AWS Lambda Developer Guide](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

# Related Products

## Amazon API Gateway

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services. Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications. API Gateway supports containerized and serverless workloads, as well as web applications.

[Docs](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)


## Amazon S3

Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize data, and configure fine-tuned access controls to meet specific business, organizational, and compliance requirements. 

[Docs](http://docs.aws.amazon.com/AmazonS3/latest/dev/)

## Amazon DynamoDB

Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data export tools. 

[Docs](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/)

## AWS Step Functions

AWS Step Functions is a low-code, visual workflow service that developers use to build distributed applications, automate IT and business processes, and build data and machine learning pipelines using AWS services. Workflows manage failures, retries, parallelization, service integrations, and observability so developers can focus on higher-value business logic.

[Docs](http://docs.aws.amazon.com/step-functions/latest/dg/welcome.html)

## Amazon Simple Notification Service (Amazon SNS)

Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.

[Docs](https://aws.amazon.com/documentation/sns/)

## Amazon EventBridge

Amazon EventBridge is a serverless event bus that makes it easier to build event-driven applications at scale using events generated from your applications, integrated Software-as-a-Service (SaaS) applications, and AWS services. EventBridge delivers a stream of real-time data from event sources such as Zendesk or Shopify to targets like AWS Lambda and other SaaS applications. You can set up routing rules to determine where to send your data to build application architectures that react in real-time to your data sources with event publisher and consumer completely decoupled.

[Docs](https://docs.aws.amazon.com/eventbridge/latest/userguide/index.html)

## Amazon Simple Queue Service (Amazon SQS)

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates the complexity and overhead associated with managing and operating message-oriented middleware, and empowers developers to focus on differentiating work. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available. Get started with SQS in minutes using the AWS Management Console, Command Line Interface or SDK of your choice, and three simple commands.

[Docs](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)

# Developer Tools

## AWS Serverless Application Model (SAM)

The AWS Serverless Application Model (SAM) is an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines per resource, you can define the application you want and model it using YAML. During deployment, SAM transforms and expands the SAM syntax into AWS CloudFormation syntax, enabling you to build serverless applications faster.

AWS Serverless Application Model (AWS SAM) is an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings.

[Docs](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html)

-[SAM CLI Command Reference](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-command-reference.html)

-[SAM Repository](https://github.com/aws/serverless-application-model)

-[SAM CLI Repository](https://github.com/aws/aws-sam-cli)

## AWS Cloud Development Kit (AWS CDK)

The AWS Cloud Development Kit (AWS CDK) is an open-source software development framework to define your cloud application resources using familiar programming languages.

AWS Cloud Development Kit (AWS CDK) is an open source software development framework to define your cloud application resources using familiar programming languages.

[Docs](https://docs.aws.amazon.com/cdk/latest/guide/home.html)

-[CDK Repository](https://github.com/aws/aws-cdk)

-[Construct Hub](https://constructs.dev/packages/aws-cdk-lib/v/2.33.0?lang=python)

 # Web App Dvelopment
 Combine AWS Lambda with other AWS services to build powerful web applications that automatically scale up and down and run in a highly available configuration across multiple data centers.
 
## Chalice
 Chalice is a framework for writing serverless apps in Python. It allows you to quickly create and deploy applications that use AWS Lambda.

 [Docs](https://aws.github.io/chalice/?badge=latest)

-[Chalice Repository](https://github.com/aws/chalice)
 
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