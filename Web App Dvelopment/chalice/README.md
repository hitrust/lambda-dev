# Chalice

[AWS Chalice](https://aws.github.io/chalice/) is a library for serverless Python application development using AWS Lambda. Chalice is suited for:

- Writing HTTPS APIs that wrap AWS infrastructure.
- Building libraries of Ops functions, including ChatOps.
- Managing AWS accounts programmatically.
- Creating web applications with your favorite front-end toolkit.
- Providing the web API backend layer to cross-platform desktop and mobile applications written in Qt for Python.

## Contents
- [Features](#features)


## Features

**Native python packaging**

Chalice has built-in support for python packaging tools. It will automatically package your application and install 3rd party dependencies specified in your requirements.txt file.

**AWS SAM and Terraform integration**

You can use Chalice's included deployer that's built using the AWS SDK for Python (boto3) or you can have Chalice generate packages that can be deployed with AWS CloudFormation or Terraform.

**CI/CD pipeline generation**

Automatically generate a deployment pipeline that's built with AWS CodePipeline and AWS CodeBuild. Deploy your application whenever you push changes to your Git repository.

**Local testing support**

Test your REST API using the local test server. This gives you a quicker feedback loop and let's you test your code before deploying to AWS.

**Websocket APIs**

Create Websocket APIs with API Gateway. Includes runtime APIs to send messages back to connected clients.

**Automatic policy generation**

Automatically generate policies for your application based on scanning your source code.

