is globally distributed. Distributed HW and Data Centers physically networked and connected.  

- Launched [[AWS - Region]]
- Availability Zones
- Direct Connection Locations: Used bu AWS Direct Connect
- Points Of Presence (Edge Locations, pointes between Regions and End User)
- Local Zone: DataCenters located to densely populated areas
- Wavelength Zones: Edge computing in 5G Network. Ultra low latency

## AWS Regional vs Global

Some services will operate across multiple regions and they will fixed to "Global".

Because you have already selected the scope (Region) when you create a Regional service you don't need (generally) to explicitly set the Region for this service. 

### Fault Domain

section of a network that is vulnerable to damage if a critical device or system fails. The iea is that if a failure occurs it will not cascade outside that domain. 

Ex:

Specific server in a rack 
entire rack in a datacenter



## AWS Global Network

interconnection between Regions & Data Centers. 

Communication Based on PoPs.

AWS Global Accelerator is a networking service that helps you improve the availability. 
Amazon cloufront (CDN)
VPC Endpoints

### PoPs 

Intermediate location between a AWS Region and end user. It can be owned by AWS or a trusted partner. Usually PoP are Edge Locations or Regional Edge Caches. 

## Service using PoPs

- Amazon Cloud Front. Cache apps in varios Edge locations close to end-user
- Amazon S3 Transfer Acceleration: Allows to create URLs to enable users to upload files to Edge locations
- AWS Global Accelerator. Use Edge Locations to access your Region 


## AWS Direct Connect

Allows to connect your office and co-locations directly to AWS. 
More consistent and secure that using directly internet. 

They use direct connect locations

## Data Residency

- Compliance Boundaries
- Data Sovereignty (legal authority)

You can make it happen with **AWS Outposts**. or **AWS Config** to create rules that check AWS resources configuration or **IAM Policies**

### AWS for Government (GovcCloud)

 - GovCloud
 - China


## AWS Outposts

A rack of servers running AWS infrastructure on your physical location


## AWS Ground Station

lets you control satellite communications

## AWS Sustainability

// pending

