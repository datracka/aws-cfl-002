![[aws-ec2-pricing-models.png]]

5 different ways to pay

- On Demand
- Spot
- Reserved
- Dedicated
- AWS Saving

## On Demand (Least Commitment)
 - Low cost and flexible.
 - Only pay per hour of second.
 - Short term / unpredictable workloads.
 - For first time apps

It's the default instance, no up-front payment and no long-term commitment

Charged per second (60 seconds ) or the hour

Default running On-Demand instance purchase is 20.

## Spot

AWSy want to maximize the utility of unused servers.

They work based on On-demand

- Up 90% savings, biggest savings
- request spare computing capacity
- Interruptions
- Non critical backgrounds jobs.

If you terminate the instance you pay for partial hour of usage.

## Reserved Instance (RI)
- up to 75%, best long Term
- ready state and predictable usage
- EC2 from 1 to 3 years
- you can resell unused reserved instances

Price is base in 

Term: 1 - 3 year (more commitment, cheaper), After finishing if not renewed the switch to onDemand
Class offering (Standard 75% / Convertible 54%)
Payment Option: All upfront - partial upfront - discounted hourly rate

you can buy up to 20 RI per Region or 20 RI per AZ per Month.


RI Region accumulates with your on-demand purchases (by default 20 but you can increase it)

RI per AZ can exceed the On-Demand limit

> Standard vs Convertible differs that standard can modify their RI attributes and bought and sold in the market place. Convertible on the contrary, can only exchange attributes and they are not sellable in the market place.

#### RI Attributes
(Or Reserved Attributes)

**RIs** can be shared between multiple accounts within an AWS Organization.

Unused **RIs** can be sold in the reserve instance Market Place. 

- Instance Type. (family + size) Ex: m4.large
- Region
- Tenancy (shared o dedicated)
- Platform (windows or Linux/Unix)

#### Regional or Zonal Reserved Instance
You need to determined when buying a RI but it does not affect the price. 

what a f\*k is this!?

##### Market Place

You can sell in the market place reserved Instance after they have been paid and after they have been active at least 30 days. 

You need at least to have a month remaining for the term (it will be rounded down) and until it is sold and the transaction is complete you retain the pricing and the capacity benefit of your reservation

You need a US bank account and for tax purposes your name and company will be shared.

You can sell up to $20K per year.
 
 ## Dedicated

#### Capacity reservation

You can ask for a AZ a EC2 reservation.

## Dedicated Instance

It is just a dedicated instance for you. 

- Multi tenant -> Same HW, virtual isolation (cheaper). Not suitable for large corporations with concerns about sharing the HW with other customers.

- Single Tenant -> Dedicated HW (more expensive

It can be sold on-demand, spot or 

## Saving Plans

Is similar to Reserved Instances but in exchange fr a commitment to use a specific amount of computer power (measured in hours) for a one or three-year period.

