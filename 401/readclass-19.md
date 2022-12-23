## Readings: AWS: Events



## AWS SQS vs SNS

## What is the difference betweeen SQS and SNS?

SNS is a distributed publish-subscribe service

SQS is distributed queuing service.

## What are some use cases for both SNS and SQS?

SQS : Pull Mechanism — Consumers poll messages from SQS.
SNS : Push Mechanism — SNS pushes messages to consumers.

SQS : Messages are persisted for some duration is no consumer available. The retention period value is from 1 minute to 14 days. The default is 4 days.

SNS : No persistence. Whichever consumer is present at the time of message arrival, get the message and the message is deleted. If no consumers available then the message is lost.


# AWS SNS and SQS

## Describe how to use SQS and SNS in a “fanout” pattern.

In a fanout pattern, using SNS you can send messages yo multiple subscribers and endpoints. This is also a reliable method.



## Explain how “push notifications” work, using SNS.

It sends multiple notifications to different devices. It can leverge off of other services to deliever the notification. 





# SQS and SNS Basics

## How might a large scale, distributed application make use of a Queue system like SQS?

It uses the First in First Out queue system to make a priority chain based off of the incoming traffic. 

