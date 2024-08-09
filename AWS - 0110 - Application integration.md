Is the process of communicate 2 independent applications

- Queueing
- Streaming
- pub/sub
- API Gateways
- State Machine ??
- Event Bus ??

## SNS ~ (pub / Sub)

Fully managed messaging service. It allows you to send messages to a large number of subscribers at once.

Pub / Sub
topic. or Event Bus

**Events, messages are lost**

Use Case 

- Chat System or Web Hook
- Push notifications for mobile applications.
- Sending notifications to users (e.g., SMS, email alerts).
- Fan-out messages to multiple subscribers.
- Distributing event updates to micro services.


Publisher does not know who the subscriber are
Subscriber DO NOT PULL the messages
messages == events
send directly once they happen
you can not re-read messages

Useful to connect micro-services. 

## SQS
Fully managed message queuing service. Standard and FIFO queue types.

**Amazon SQS** is great for decoupling and buffering between distributed system components, ensuring reliable and scalable message delivery.

Use Cases:

- Ensuring reliable message delivery with guaranteed ordering (FIFO queues). 
- transactional emails

## Kinesis ~ Streaming
Real time Data ingestion.

**Messages are retained!!** 

> ~ its like Kafka 
![[aws-kinesis.png]]

Use Cases: 
- **Real-time analytics and monitoring (e.g., analyzing log and event data).**
- Real-time data streaming for IoT devices.
- Live data dashboards and monitoring systems.
- Processing event data, like gaming data feeds or social media streams.

and also you have: 

- Amazon Kinesis **Firehouse** (serverless Kinesis).
- Amazon Kinesis Video Streams.

## AWS Gateway. 

Allows to create secure apis from any scale

## States Machines (AWS Step Functions)

Defines kind of a workflow (like Airflow)

## Event Bus (EventBridge)

AWS EventBridge is a serverless event bus service

Ideal for integrating with third-party services in an event-driven architecture.

Source -> [ Rules ] -> Target

**Use Cases:**

- Building event-driven applications.
- Integrating third-party SaaS applications with your AWS environment.
- Decoupling services through an event-based model.
- Handling complex event routing and processing.

>Based in events (similar to SNS)


## Others
- Amazon MQ (Active MQ) managed message broker service
- Managed Kafka Service (MSK)
- AppSync (graphQL)