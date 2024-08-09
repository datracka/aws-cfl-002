Solution Architect
Cloud Architect

- Availability 
	- By running workload in multiple AZ Zones
- Scalability
	- Vertical or Horizontal Scale up
- Elasticity
	- Ability to **automatically** increase / decrease capacity
- Fault Tolerance
	- Ensure that there is not single point of failure
- Disaster Recovery
	- Backup / fast backup / workable / live data 
Security
Cost

> CloudEndure Disaster Recovery. Back up. Replicates machines in a low-cost staging area for fast and reliable recovery 

## Business continuity plan (BCP)

A document that outlines how a business will continue operating during an unplanned disruption in services:

- Recovery Point Objective: Max amount data to loose
- Recovery Time Objective: Max amount of downtime

## Disaster Recovery


| Option                       | Time      | Cost           | when                       |
| ---------------------------- | --------- | -------------- | -------------------------- |
| Backup / Restore             | Hours     | Cheaper        | Low priority use cases     |
| Pilot light                  | 10 Min    | Cheap          | Core Services              |
| Warm Stand by                | Min       | Expensive      | Business Critical Services |
| Multi-site active / inactive | Real-time | More Expensive | Mission Critical Services  |

![[recovery-plan.png]]


