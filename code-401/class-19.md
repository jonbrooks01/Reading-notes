# Class 19 Reading Notes

## AWS SQS vs SNS

1) The main differences between SQS and SNS is that SNS sends messages to a subscribed system whereas SQS is a polling system that receives messages

2) Use cases for SNS and SQS: SNS you can send messages on different platforms, send out batch messages. Use cases for SQS: its a simple queue without any additional requirements, you can perform asynchronous processing with decoupled applications

## AWS SNS and SQS

1) SNS and SQS can work together in order to send messages to the consumer, one case might be a transaction event, that one event sends the signal to the consumer and then to several different systems validating and analyzing the topic that was sent.

2) with SNS the messages will be pushed to the account that was subscribed to the service via email or application this ensures the customer receives the notification for the event

## SQS and SNS Basics

1) A large scale business would be able to use SQS in there system because it can scale to the needs of the business and it is able to handle increased workloads without lag in there system.