![[networking services.png]]

# Enterprise / Hybrid

![[networking_hybrid.png]]

- Direct Connection (not encrypted)
- VPN
- PrivateLinks - No over the internet

# Private Cloud

CIDR: 10.0.0.0/16 (VPC)
	- public subnet 10.0.0.0/24
	- private subnet 10.0.0.0/24

## Security Groups vs NACLs

NACLs: Network Access Controllers. Virtual Firewall as subnet level
	- Block IP
	- **Allow and Deny** Rules

Security Groups: Firewall at the instance VPC level
	- You can create **Allow** rules. 
	- Not possible to block a single IP for example

