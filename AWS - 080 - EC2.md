allows to launch a VM
You can share costs with other customers by sharing instances

AMI: Amazon Machine Image, predefined.

The Backbone of AWS

Computing Services

- EC2
- LightSail - EC2 guided (Wordpress)
- ECS: Docker, with a EC2 underlying
- ECR: store docker Images
- EKS
Serverless
- ECS Fargate: You forget to manage the underlying EC2 server. Pay on demand.
- AWS Lambda


EC2 is resizable and replicable
### How Choose OS via AMI

Instance Type: t2.nano <-> C4.8xlarge
Storage: EBS / EFS ...
Configure Instance:
	- Security Files, IAM Roles, Placement Groups

## Instance Type 

Instance size + instance family 

combinations of CPU / Memory / Storage / Network capacity

### instance Family

General Purpose: web servers
A1, T2-3, T3a, T4g M4-5, M5a, 5n, M6zn, M6g, M6i, Mac

Computer Optimized: scientific modeling, dedicated gains, server engines
C4-5, Cba, C5n, C6g, C6gn

Memory Optimized: in memory caches, in memory databases, real time big data 
R4-5, R5a, R5b, R5n, X1 X1e, Jigh memory, z1d

Accelerated Optimized: ML, computational finance, seismic analysis, speech recognition
P2-4, G3, G4ad, G4dn, F1, inf1, VT1

Storage optimized: high sequential read / write. Very large datasets on local storage
I3, i3en, D2, D3, D3en, H1

### Instance Size
t2.micro
*.metal

Usually they double capacity and Price.

### Dedicated Host vs Dedicated Instance

Both offer dedicated physical servers. You have in both dedicated HW.

They differ in control management and billing.

### Dedicated Host

A Dedicated Host can have dedicated Instances. 

They offer complete control over the physical server. You can server bound server licenses

Billing per Host regardless instances of use of it.

#### Dedicated Instance

You don't have visibility over the physical machine.

You pay by instance and can be reserved in the same way that you reserve EC2.

You don't know in which physical server it will run


