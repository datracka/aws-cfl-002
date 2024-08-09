The  Layers of security

- Data
- Applications
- VM / Compute
- Network / Perimeter
- Identify Access
- Physical: access to a datacenter to only authorized personnel

## CIA Triad

- Confidentiality
- Integrity
- Availability

![[CIA-triad.png]]

Vulnerability is a hole or weakness in the application

## Cryptography

Cryptography key ( variable+ algorithm)

- Symmetric encryption: (AES)
- Asymmetric encryption (RSA)

Hash function. Given an input produces a deterministic output. use for passwords storing
(MD3, SHA256, Bcrypt) + salting Password

#### Digital Signature. Tamper to be sure data was modified or not. 

- Key Generation
- Signing (private key)
- Signing Verification (public key)

For example SSH with ssh- with RSA

- TLS / SSL (Encryption In-Transit)
- AES / RSA (Encryption At-Rest)

#### AWS compliance programs

ISO / IEC - 270001
HiPAA 

### PEN Testing

an authorized simulated cyberattack on a computer system performed to evaluate the security of the system.

**They are allowed to be performed in AWS** on:

- ECS
- NAT
- LB
- RDS
- CloudFront
- Aurora
- Api GateWau
- Lambda and Lambda Edge Functions

> **AWS Artifact** is the self-serve portal for on-demand access to AWS compliance reports!!


## Security Tools

- **AWS Inspector** is a service that runs a **security benchmark** against specific EC2 instances (popular is CIS with 699 checks!)
- **AWS Shield** is a managed **DDos** protection Service that safeguards applications running on AWS. 
	- **CloudFront** or **Route53** (domain redirection) are using it under the hoods.
- **AWS Guard Duty i**s a threat detection service. IDS (Intrusion detection system) / IPS (Intrusion protection system)
- **AWS VPN**. Secure & private tunnel from your network to AWS global network. Based on IPSec
	- AWS Client VPN (user to AWS network)
	- AWS site to site VPN (connect on-premise network to VPC)
- **AWS WAF**: you write rules to ALLOW / DENY traffic of https request
	- it can be attached to CloudFront or the LB
	- **AWS Managed Rules**
- **Hardware security module (HSM)**. Its designed to store encryption keys. It holds in memory and never write to disk
	- **CloudHSM** single tenant HSM that automates HW provisioning, software patching and high availability backups.
- **AWS KMS**: Key Management Service. it makes easy to create and control the encryption keys used t encrypt your data. 
	- Envelope encryption: You can have a Master key to encrypt your operational data keys 
- **AWS Security Hub**: Provides a comprehensive view of your security 
- **AWS Guardrails:** mechanism to enforce security / compliance and operational best practices
	
  








