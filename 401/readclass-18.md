# Readings: AWS: API, Dynamo and Lambda

## AWS API Gateway Overview

### What is Amazon API Gateway?
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic.

(So basically it condenses backend work and simplifies the process of a backend.)

### Why is Amazon API Gateway an important part of the Serverless ecosystem?

Having the ability to execute a serverless function directly in response to an HTTP request is the selling point of API Gateway

### How does API Gateway integrate with other AWS services?

AWS Lambda: run Lambda functions to generate HTTP API responses.

AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.

Amazon Cognito: provide authentication and authorization for your HTTP APIs.


## AWS API Gateway

### What are the some benefits of using Amazon API Gateway?\

Ones that matter to me as a student dev.

-Easy monitoring
-RESTful API options
-Efficient API development

### What two API types might you choose from?

https://rapidapi.com/carapi/api/car-api2/

https://developer.spotify.com/documentation/web-api/


# AWS DynamoDB Guide

### What is DynamoDB?

is a hosted NoSQL database offered by AWS

### Under what circumstances would you recommend DynamoDB over MongoDB?

Applications that require fast and large scalabity in small succession time. Serverless application support and simple datas ets with access patterns. 

# AWS DynamoDB

## Explain to a non-technical friend how DynamoDB works.

serverless, key-value NoSQL database designed to run that is highly scalabe.

# Dynamoose

## What is Dynamoose?

It is a modeling tool for Amazon's DynamoDb.

## What are some key features of Dynamoose?

Ability to transform data before saving or retrieving items
Strict data modeling (validation, required attributes, and more)
Support for DynamoDB Transactions
Powerful Conditional/Filtering Support