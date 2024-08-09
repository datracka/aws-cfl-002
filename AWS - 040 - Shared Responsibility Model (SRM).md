![[shared_responsability_model.png]]The type of **cloud deployment mode**l and/or the scope if the **cloud service category** can result in specialized SRM

Customer: (IN) is responsible Data and Configuration
	- Self managed services. Platform, applications and IAM
	- VM: OS, Network and FW
	- Security & Encryption: Client / Server / Network
	- Customer Data
AWS: (OF) Hardware, Operation of Managed Service and Global Infrastructure

Responsibilities:

On-Premise: You are responsible of everything
IaaS: VM, Servers, Storage, Networking out. 
	Bare Metal / EC2 / Containers (ECS)
PaaS: Only Applications and Data (Beanstalk)
SaaS or FaaS: Google Drive. Only Data Integrity or Code

Amplify
Lambda

Fargate
ECS/ EKS

Elastic Beanstalk
EC2

## Higher Performance Computing Service

Cluster of hundred of thousands of servers

- Nitro System: 
	- Nitro Cards (VPC / EBS, Instance Storage and Controller)
	- Nitro Security Chips. Protects HW resources
	- Nitro Hypervisor. Memory / CPU allocator

Bar Metal Instance: M5 and R5 instances
 - Bottle rocket: Linux OS 
 - Parallel Cluster: Cluster Management tool

## Hybrid Computing Services

AWS VPC + on premise Data Centers
- AWS Outposts: AWS Physical Servers you can run in your Data Center
- WMWare Cloud: manage on-premise VM using WMWare as EC2 Instances

## Cost Management

- EC2 Spot instances, reserved instances or saved plans
- AWS Batch
- AWS Compute optimizer
- EC2 Autoscaling groups (ASGs)
- ELB 
- EB


