- CloudTrail: logs API Calls (SDK, CLI)
- CloudWatch
	- Logs: Place to store data or application logs
	- Metrics: Variable to monitor on time
	- EventBridge: Triggers an Event
	- Alarms: Notification based on Metrics
	- Dashboard: Create Visualization based on metrics
- AWS X-Ray. Distributed Tracing System, between Microservices. 

## AWS CloudTrail
Enables governance, compliance, operational and risk .

Identify users

Are logging for default logs for 90 days via Event History. Otherwise you have to create a Trail and it is stored in S3.

## CloudWatch Alarms

Based in Metrics triggers an alarm (Notification, Auto scaling, EC2 Action, Billing...)

States: **OK**, **ALARM**, **INSUFFICIENT_DATA**

**DataPoints Alarm** (not just breaking the Threshold but in how it is breached)

### Log Streams

An application can send a sequence of events. It is generally automatically done by the service you are using. You can also set them manually.

Its made from **Log Events** 

### Log insights
Enables to interactively search and analyze your CloudWatch log data.

- Robust filtering.
- Supports all types of logs.
- It's commonly used via the console. 
- They have his own language **Query Syntax**.

You can query up to **20 log groups**.
Queries **time out after 15 days** if they are not completed
Query result are available for **7 days**

### CloudWatch Metrics 
Cloud Watch comes with many predefined metrics that are generally name spaced by AWS Service. 

EC2 Per-Instance Metrics

- CPU


