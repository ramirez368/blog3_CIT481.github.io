---
layout: default
---


## [AWS Lambda](https://www.youtube.com/watch?v=97q30JjEq9Y)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

## How it works
AWS Lambda is a serverless, event-driven compute service that lets you run code for virtually any type of application or backend service without provisioning or managing servers. You can trigger Lambda from over 200 AWS services and software as a service (SaaS) applications, and only pay for what you use.


## AWS Lambda Features
AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you. These events may include changes in state or an update, such as a user placing an item in a shopping cart on an ecommerce website. You can use AWS Lambda to extend other AWS services with custom logic, or create your own backend services that operate at AWS scale, performance, and security. AWS Lambda automatically runs code in response to multiple events, such as HTTP requests via Amazon API Gateway, modifications to objects in Amazon Simple Storage Service (Amazon S3) buckets, table updates in Amazon DynamoDB, and state transitions in AWS Step Functions.

Lambda runs your code on high availability compute infrastructure and performs all the administration of your compute resources. This includes server and operating system maintenance, capacity provisioning and automatic scaling, code and security patch deployment, and code monitoring and logging. All you need to do is supply the code.
 
![](https://svg.template.creately.com/ipgs8yik1)

## Build custom backend services
You can use AWS Lambda to create new backend application services triggered on demand using the Lambda application programming interface (API) or custom API endpoints built using Amazon API Gateway. Lambda processes custom events instead of servicing these on the client, helping you avoid client platform variations, reduce battery drain, and enable easier updates.

## Bring your own code
With AWS Lambda, there are no new languages, tools, or frameworks to learn. You can use any third- party library, even native ones. You can also package any code (frameworks, SDKs, libraries, and more) as a Lambda Layer, and manage and share them easily across multiple functions. Lambda natively supports Java, Go, PowerShell, Node.js, C#, Python, and Ruby code, and provides a Runtime API allowing you to use any additional programming languages to author your functions.

## Completely automated administration
AWS Lambda manages all the infrastructure to run your code on highly available, fault tolerant infrastructure, freeing you to focus on building differentiated backend services. With Lambda, you never have to update the underlying operating system (OS) when a patch is released, or worry about resizing or adding new servers as your usage grows. AWS Lambda seamlessly deploys your code, handles all the administration, maintenance, and security patches, and provides built-in logging and monitoring through Amazon CloudWatch.

## Built-in fault tolerance
AWS Lambda maintains compute capacity across multiple Availability Zones (AZs) in each AWS Region to help protect your code against individual machine or data center facility failures. Both AWS Lambda and the functions running on the service deliver predictable and reliable operational performance. AWS Lambda is designed to provide high availability for both the service itself and the functions it operates. There are no maintenance windows or scheduled downtimes.

## Package and deploy functions as container images
AWS Lambda supports function packaging and deployment as container images, making it easy for customers to build Lambda-based applications using familiar container image tooling, workflows, and dependencies. Customers also benefit from Lambda???s operational simplicity, automatic scaling with sub-second startup times, high availability, pay-for-use billing model, and native integrations with over 200 AWS services and software-as-a service (SaaS) applications. Enterprise customers can use a consistent set of tools with both their Lambda and containerized applications, simplifying central governance requirements such as security scanning and image signing.


![](https://i.pinimg.com/originals/a8/89/82/a88982850f2d9e42472c84b6261c0bf9.png)

## Automatic scaling
AWS Lambda invokes your code only when needed, and automatically scales to support the rate of incoming requests without any manual configuration. There is no limit to the number of requests your code can handle. AWS Lambda typically starts running your code within milliseconds of an event. Since Lambda scales automatically, the performance remains consistently high as the event frequency increases. Since your code is stateless, Lambda can start as many instances as needed without lengthy deployment and configuration delays.

## Connect to relational databases
Use Amazon RDS Proxy to take advantage of fully managed connection pools for relational databases. RDS Proxy efficiently manages thousands of concurrent connections to relational databases, making it easy to build highly scalable, secure Lambda-based serverless applications interacting with relational databases. Currently, RDS Proxy offers support for MySQL and Aurora. You can use RDS Proxy for your serverless applications through the Amazon RDS console or AWS Lambda console.

## Fine-grained control over performance
Provisioned Concurrency gives you greater control over your serverless application performance. When turned on, Provisioned Concurrency keeps functions initialized and hyper-ready to respond in double-digit milliseconds. Provisioned Concurrency is ideal for any AWS Lambda application requiring greater control over function start time. Easily configure and adjust the concurrency your application needs. Scale up, down, or turn it off completely depending on demand. Take advantage of Provisioned Concurrency to achieve consistent performance for latency-sensitive applications without changing your code or managing compute resources.

## Connect to shared file systems
With Amazon Elastic File System (EFS) for AWS Lambda, you can securely read, write, and persist large volumes of data at low latency, at any scale. You don't need to write code and download data to temporary storage in order to process it. This saves time and simplifies the code, so you can focus on your business logic. EFS for Lambda is ideal for a range of use cases including processing or backing up large data amounts, and loading large reference files or models. You can also share files between serverless instances or container-based applications, and even run machine learning (ML) inference by using EFS for AWS Lambda.


## Run code in response to Amazon CloudFront requests
With Lambda@Edge, AWS Lambda can run your code across AWS locations globally in response to Amazon CloudFront events, such as content requests to or from origin servers and viewers. This makes it easier to deliver richer, more personalized content to your end users with lower latency. 

## Orchestrate multiple functions
Build AWS Step Functions workflows to coordinate multiple AWS Lambda functions for complex or long-running tasks. Step Functions lets you define workflows that trigger a collection of Lambda functions using sequential, parallel, branching, and error-handling steps. With Step Functions and Lambda, you can build stateful, long-running processes for applications and backends.

## Integrated security model
AWS Lambda's built-in software development kit (SDK) integrates with AWS Identity and Access Management (IAM) to ensure secure code access to other AWS services. AWS Lambda runs your code within an Amazon Virtual Private Cloud (VPC) by default. Optionally, you can configure AWS Lambda resource access behind your own VPC in order to leverage custom security groups and network access control lists. This provides secure Lambda function access to your resources within a VPC. AWS Lambda is SOC, HIPAA, PCI, and ISO-compliant. For the latest in Lambda certification and compliance readiness, please see the full services in scope.


### I hope this was useful as IoT get deeper and deeper in our lifes.


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
