**AWS Event-Driven Architecture**

**Project Overview**

Event-driven cloud architecture built using AWS managed messaging and event services. This project demonstrates how to build scalable, loosely coupled applications through asynchronous communication.

**Project Goal**

Design an event-driven architecture using Amazon EventBridge, Amazon SNS, and Amazon SQS to demonstrate modern cloud-native messaging and event processing patterns.

**Architecture**

```text
Event Source
     │
     ▼
Amazon EventBridge
     │
     ▼
Amazon SNS
     │
     ▼
Amazon SQS
     │
     ▼
Application Consumers
```

**Technologies**

* Amazon EventBridge
* Amazon SNS
* Amazon SQS
* AWS
* Event-Driven Architecture

**Features**

* Event routing
* Publish/subscribe messaging
* Message queuing
* Asynchronous communication
* Decoupled application design

**Project Structure**

```text
eventbridge/
sns/
sqs/
diagrams/
screenshots/
```

**Key Learnings**

* Event-driven architecture patterns
* Amazon EventBridge event routing
* Amazon SNS publish/subscribe messaging
* Amazon SQS message queuing
* Designing loosely coupled cloud applications

**Status**

✅ Completed

**Future Improvements**

* Add Infrastructure as Code using Terraform
* Implement monitoring and alerting
* Add dead-letter queue (DLQ) support
* Integrate Lambda event processing
