# Readings: AWS: Events

* Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services.

* With Amazon SNS, you can send push notifications to Apple, Google, Fire OS, and Windows devices , as well as to Android devices in China with Baidu Cloud Push. You can use SNS to send SMS messages to mobile device users in the US or to email recipients worldwide.

* SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS.

## Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

* both Express and Serverless can be used for writing Node.js APIs, with ExpressJS Server we can set up the routes and implement the functionality for them. With AWS API Gateway, we set up the routes and then implement the functionality with lamda functions.

## List the AWS Database offerings and talk about the pros and cons of each

| Database type   | AWS service  |
| -----------  | ----------- |
|    Relational  | Amazon RDS  |
|    Key-value   | Amazon DynamoDB |
|    In-memory   | Amazon ElastiCache for Memcached  |
|    Document    | Amazon DocumentDB |
|   Wide column  | Amazon Keyspaces  |
|     Graph      | Amazon Neptune   |
|    Time series | Amazon Timestream  |
|      Ledger    | Amazon QLDB  |

* Pros :

* Automated Patching

* Automated Backups

* Integrated with the rest of the AWS ecosystem

* Cons:

* Zero data loss is not guaranteed

* No root access to the server

* Downtime required for scaling operations

## What’s the difference between a FIFO and a standard queue?

* Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it

## How can the server be assured a message was properly received?

* to get a response from the client that the message was received

## Document the following Vocabulary Terms

* Serverless API: a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.

* Triggers: resource in another service that you configure to invoke your function in response to lifecycle events

* Dynamo vs Mongo: DynamoDB is a fully managed solution. Using a fully managed service reduces the amount of time a team spends on operations; (no pager duty alerts), no servers to update, kernel patches to roll out, SSDs to replace, hardware provisioning, setup/configuration, throughput capacity planning, replication, software patching, or cluster scaling. The focus shifts to application logic where the real value lies. The general rule of thumb is to choose Dynamo for low throughput apps as writes are expensive and consistent reads are twice the cost of eventually consistent reads. MongoDB's Atlas cost comes from infrastructure availability and backups for external managed services; throughput is inclusive of the pricing

* Dynamoose vs Mongoose

>
> Dynamoose is a modeling tool for Amazon's DynamoDB
>
> Mongoose is mongodb object modeling for node.js
>