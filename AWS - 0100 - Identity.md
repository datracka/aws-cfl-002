## Zero Trust Model.

it augments the old network centric approach based in firewalls and VPNs with an identity centric model where security is based in improved KYC / MFA techniques or providing provisional access

in AWS

- AWS Identity and access management
	- IAM Policies
	- Permission Boundaries
	- Service Control Policies (Organization-wide policies)
	- IAM Policy Conditions
		- Ex restrict IP Address, restrict on region, if MFA is turned off or based in hour of the day (not allow during the night for example)

## Directory Service
It maps names of the network resources to their network addresses

- DNS
- Microsoft Active Directory
	- Azure Active Directory
- Apache Directory Service
- Oracle Internet Directory (OID)

## Identity Provider

- Identity Providers: OpenID, OAuth 2.0 and **SAML** (**SSO** through browser)

**LDAP** is protocol for accessing and maintaining a distributed directory of information services. LDAP is commonly used as a central place to store usernames and password, (a place for querying them)

- SSO is based commonly in LDAP
- MFA
- Security keys (Yubikey)

## IAM
- IAM Policies. JSON to grant permission for uses / groups /roles. Policies are Attached to IAM identities
- IAM Permission 

IAM Identities: 

- IAM Users
- IAM Groups
- IAM Roles

## IAM Policy
- Version
- Statement
	- SID (optional)
	- Effect: allow deny
	- Action: what you are allowing / denying
	- Principal; account user or role which you'd like to allow / deny access
	- Resource. to which action applies

# Principle of least privilege

To provide the least amount o permissions to perform an operation or action. 

JEA: Just enough access 
JIT: Just in time

Risk based adaptive policies: Each access generates a score, based in many factors. Not supported by AWS IAM.

## Users

## Root User 
Special user that can not be deleted
Full permissions
Only one Root users by AWS account

Tasks
- Changing account settings
- Restore IAM user permissions
- Close your AWS account
- Change or cancel AWS support plan

## User

for common tasks that is assigned with permissions.

AWS Single-sign on

![[aws-single-signon.png]]