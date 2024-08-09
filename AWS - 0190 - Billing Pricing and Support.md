
## Free Services

They are free forever, don't confuse with "free-tier" that are up to a point of usage or time: 

- IAM 
- VPC
- Organizations & Consolidated Billing
- AWS Cost Explorer

Also Free but they can provision automatically NOT free services.

- Autoscaling
- CloudFormation
- Elastic Beanstalk
- OpsWork: AWS managed Puppet master
- Amplify: Firebase
- AppSync: GraphQL APIs
- ~~CodeStar: to Develop, compile and implement AWS applications~~

## AWS Support Plans

- Basic
- Developer
- Business
- Enterprise

![[aws-supports-plan.png]]


### Pricing model 

based in AWS usage or a bottom line.

![[aws-support-plan-2.png]]

Basic is free (basically because there is not! :) ) 

- Technical Account Manager (TAM): Provides guidance and reactive support

## AWS Marketplace

curated list catalogue with thousands of software listings from independent software vendors. Only US.

## Consolidate Billing.

Pay multiple accounts from one **Bill**. No additional Costs.

You can use cost explorer to visualize usage for consolidated billing

## Discounts

the  More you use, the more you save

## AWS trusted advisor

Its a recommendation tool which automatically and actively monitors your AWS and provide actions recommendations.

- Cost Optimization
- Performance
- Security
	- Free security checks
		- MFA on Root Account
		- Security Groups. Specific ports of unrestricted
		- Amazon S3 Bucket Permissions
		- Amazon EBS Public Snapshots
		- Amazon RDS Public Snapshots
		- IAM Use (discourage root access)
		- Service Limits (all service limits checks are free)
- Fault Tolerance
- Service Limits

Basic and developer support plan have up to: 7 Trusted advisor checks. The rest of plans infinite. 

## SLA / SLI / SLO

**SLA:** its a formal commitment about the level of service between customer and provider. If not met, it is compensated

**SLI:** A metric about the performance a service. Uptime / Performance / 

**SLO:** Service level Objective. Target percentage over a period of time 

For Example

- DynamoDB SLA has a SLA of 99.999% (Gobal SLAs) / Standard SLA
- EC2, EBS, ECS, EKS - 99%

## Service Health Dashboard and AWS Personal Health Dashboard

**SHD** - shows the health of the services
**PHD** - Provides alerts and guidance for AWS Events that might affect your environment.

## AWS Abuse

A team that deal with abuses in AWS 

- Spam
- Port Scanning
- DDoS
- Intrusion attempts
- Hosting prohibited content
- Distributing malware

abuse@amazonws.com

## AWS Free Tier

For the first 12 months of sign up
or Free usage up to certain monthly limit forever

EC2 t2.micro 750 hours for year
RDS
ELB 750h 1 year
CloudFronts
Amazon Connect
Amazon ElasitCache / Elaistic Service /  PinPoint / SES (transactional) / AWS CodePipeline / Codebuild / 

## AWS Promotional Credits. 

As startup / Winning Hackatons / Surveys

## AWS Partner Network (APN)

- Consulting Partner / Technology Partner
- Tier (Select / Advanced / Premier)
- Annual fee commitment
- Different tiers need different knowledge requirements
	- AWS Certification
	- AWS Exclusive Certifications
- Promotional credits
- Unique speaking 
- Requirement to be a vendor Booth 

## AWS Budget  & Reports / Cost Explorer & Reports

### AWS Budgets
You can create budgets and alerts if exceed

- Costs
- Usage
- Reservation

It can **forecast** costs but is limited compared to Cost Explorer or Cost and Usage Report + BI tool. 

2 Budgets free of charge, up to 20.000 budgets in total.

### Reports

you can create and automate a report that can be sent automatically for review to the email

### The Cost and Usage Reports (deprecated)

its replaced by **Data Explorer** where you can create customized exports for multiple AWS cost management and billing datasets.

You can use **Cost allocation Tags** attached to a Resource to better allocate your data

### Billing Alarms (using CloudWatch)

Need to activate billing alerts and in CloudWatch select **billing**. There are much flexible than AWS budgets and ideal for more complex use cases

### Cost Explorer
It helps to visualize and manage your AWS costs over-time. 

### Princing API 
To get programmatically access pricing information to get latest prices offering for services. 


 