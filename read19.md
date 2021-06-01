## Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
 Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. 

 ExpressJS Server allows you to spin up robust APIs and web servers in a much easier and cleaner way
## List the AWS Database offerings and talk about the pros and cons of each
mazon Aurora
 - Amazon Relational Database Service
  - Amazon Redshift
   - Key-value Database 
   - Amazon DynamoDBm In-memory Database 
   - Amazon ElastiCache for Memcached.

## What’s the difference between a FIFO and a standard queue?
- Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue.
- FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it ‏

## How can the server be assured a message was properly received?

client emit a “received” event back to the server upon receipt of the message.


## Serverless API
 architectures are application designs that incorporate third-party “Backend as a Service” (BaaS) services, and/or that include custom code run in manage

## Triggers
an AWS Lambda resource or resource in another service that you configure to invoke your function in response to lifecycle events, external requests or on a schedule, a function can have multiple triggers

## Dynamo vs Mongo
DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.‏‏

## Dynamoose vs Mongoose
Dynamoose is a DynamoDB API structured like Mongoose, lets us provide a schema and perform CRUD operations against a DynamoDB table, installed via node and configured based on role.


### SNS (Simple Notification Service)

- Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.
------------------------
Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services.



### SQS (Simple Queue Service)

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates the complexity and overhead associated with managing and operating message oriented middleware, and empowers developers to focus on differentiating work. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available. Get started with SQS in minutes using the AWS console, Command Line Interface or SDK of your choice, and three simple commands.


## Choose SNS if:
- You would like to be able to publish and consume batches of messages.
- You would like to allow same message to be processed in multiple ways.
- Multiple subscribers are needed.


## Choose SQS if:
- You need a simple queue with no particular additional requirements.
- Decoupling two applications and allowing parallel asynchronous processing.
- Only one subscriber is needed.











