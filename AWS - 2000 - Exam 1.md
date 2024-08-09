Question 1

An enterprise is evaluating whether to adopt AWS to offload most of their on-premise Virtual Machines to Ec2. The enterprise does not have much domain expertise, and they need a point of contact that will help proactively manage their account and connect them with AWS experts.

Which Enterprise offering does this best describe?

- Concierge Support Team: It helps with billing
- **TAM: Technical account manager. It helps with tech staff**
- AWS Technical support manager. Provides a range of service (included TAM in Enterprise level)

Question 2 (Case Study)

Considering NovaTech's need for stringent data security and compliance, which AWS service would be most appropriate for managing identity access and ensuring secure sign-on processes?

- AWS Directory Service - NO it is Active Directory
- AWS Cognito - Sistem of autentication
- AWS Key Management Service (KMS) - Create and control Cryptographic keys
- **AWS Identity Management Service (IAM)**

NovaTech is concerned about unexpected costs in AWS. What tool would you recommend they use to monitor and control their AWS spending?

- AWS Price List API: lista de precios 
- AWS Trusted Advisor: helps to optimize costs
- Amazon CloudWatch: Monitoriing for DevOps
- **Budgets and AWS Cost Explorer**

Given NovaTech's extensive data storage needs for AI model training, which AWS storage service would you recommend that balances performance, scalability, and cost?

- AWS Storage GateWay: Hybrid cloud storage service, connects on-premises with AWS cloud storage -> it offers 4 types of storage!
- **Amazon Elastic File System (EFS): For Data, ML, based in files**
- Amazon S3: used for unestructured data
- Amazon Elastic Block Store (EBS): For DB, Blocks

How would you ensure high performance and low latency for NovaTech's AI applications, considering their global expansion plans?

- AWS lambda
- Amazon Elastic Cache (cache like of Redis)
- AWS Global Accelerator (Networking) - 2 static public IPs
- **Amazon EC2 Auto Scaling: It scales EC2 to the proper number of instances you need**

Suggest a disaster recovery plan for NovaTech's critical AI applications and data on AWS.
- 
- Amazon S3 Glacier. For Data Achieving
- Amazon RDS Multi-AZ Deployments:  Databases multi regions
- **AWS Elastic Disaster Recovery**


Question 3

Which AWS billing services are capable of forecasting cost and usage?

 -  **Amazon Costs**
 - **AWS Budgets**

QUestion 6

What are three key factors from the twelve-factor app pattern methodology that play a role in designing for failure? 

(I don't know)

An organization wants to download a compliance report to attest that AWS meets regulatory compliance before they decide to adopt AWS as their primary cloud service provider.

Question 7 


- AWS inspector: look for vulnerabilities
- **AWS Artifact: Security compliance management**
- AWS Customer Compliance Center: Resources
- Amazon Regulatory Reporter: Antitrust / Government Relations / Regulatory Compliance / Public affairs

Question 7 

A company has an existing on-premise relational database. They want to migrate this database to the cloud and are willing to adopt a NoSQL database in order to gain managed sharding and provisioned throughput with a guarantee of performance at any scale.

- DynamoDB: NoSL
- Amazon Aurora: MySQL / PostgresSQL self managed
- RDS: Relational DB
- Document DB: MongoDB
- Amazon Neptune: graphDB

Question 8

A developer wants to gain remote access to an EC2 Instance running Linux without the need of managing a key pair.

What EC2 feature will meet this requirement?

- Sessions Manager: to Manage EC2, edge, on-premises o VM
- IAM ROLE
- AWS Key Management Service (KMS)
- EC2 key pairs: credentials to connect to your EC2 machine

Question 9

A Canadian company needs to meet regulatory compliance where the data must reside within Canada. Their CIO has experience with maintaining and trusting on-premise infrastructure because it provides a guarantee of Data sovereignty. However, they would like to use an AWS service to take care of this for them.

Which AWS service provides a guarantee of Data sovereignty?

- **AWS Outposts: it is about brining AWS to onpremise**
- AWS Data Sovereignty
- AWS Data Lake
- AWS Security Hub: view of security
- AWS Artifact: compliance

Question 10

Which AWS security services are capable of detecting publicly accessible S3 buckets in an organization where multiple departments manage their own AWS accounts?

**AWS IAM Access Analyzer**
Amazon Detector: fraud
S3 Bucket Scanner
**Amazon GuardDuty: Thread detection**
Amazon Macie: sensitive data

Question 11

An AWS customer believes that one of their accounts has been comprised and it has resources running compute workloads performing illegal activities.

What action should the AWS customer take?

- **Contact [abuse@amazonaws.com](mailto:abuse@amazonaws.com)**
- AWS access analyzer: IAM Access Analyzer helps you identify the resources in your organization and accounts, such as Amazon S3 buckets or IAM roles, shared with an external entity
- AWS Technical Support
- AWS Account Suppo9rt




## Notes

AMaon LightSail
AWS Global Accelerator / AWS Direct Connect / AWS CloudFront
Amazon Storage options. Glacier / Infrequent Access... / SnowBall

AWS Aurora
AWS cloudformation
Trusted Advisors

Kinesis / SQS / SNS / SES 
AWS Direct Connect

Disaster Recovery! 

 Data sovereignty?
 AWS WAF

AWS Key Management Service (KMS) / Sessions Manager

AWS Managed Rules / AWS Security Hub

Amazon GuardDuty

AWS Service Catalog / AWS Organizations / AWS System Manager / AWS Stack List

Amazon Regulatory Reporter / AWS Artifact / AWS customer compliance Center / Amazon Inspector

AWS Managed Job Function

Amazon Macie

Amazon Quicksight
AWS Tableau

Cost Allocation Tasks / AWS Costs and Usage Reports

Capital Expenses (CAPEX)?