
# Zero-Trust Model
- A security model of 'trust on one, verify everything'
![[Pasted image 20261116091531.png]]
# Zero-Trust on AWS
- Identity Security Controls you can implement on AWS to meet the Zero Trust Model
![[Pasted image 20261116092932.png]]

![[Pasted image 20261116092952.png]]
# Zero-Trust on AWS with Third-Parties
- AWS technically implements a Zero Trust Model but does not allow for intelligent identity security controls
![[Pasted image 20261116101224.png]]

![[Pasted image 20261116101244.png]]

# Directory Service
- A service that maps the names of network resources to their network addresses
![[Pasted image 20261116101346.png]]

![[Pasted image 20261116101425.png]]

# Active Directory
- Microsoft introduced Active Directory Domain services in Windows 2000 to give organizations the ability to manage multiple on-premises infrastructure components and systems using a single identity per user

![[Pasted image 20261116101709.png]]
# Identity Providers (IdPs)
- A system, entity that creates, maintains and manages identity information for principals and provides authentication services to applications within a federation or distributed network
- A trusted provider of your user identity that lets you use authenticate  to access other services
- Identity Providers could be
	- Facebook, Amazon, Google, Twitter, GitHun and LinkedIN
![[Pasted image 20261116102236.png]]
# Single-Sign-On (SSO)
- An authenthication scheme that allows a user to log in with a single ID and password to different systems and software
- SSO allows IT departments to administrate a single identity that can access many machines and cloud services
![[Pasted image 20261116102337.png]]
# LDAP (Lightweight Directory Access Protocol)
- On open vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network
- A Common use of LDAP is to provide a central place to store usernames and passwords
- LDAP allows for the same sign on
	- which allows users to a single ID and password
		- but they have to enter it each time they want to login
![[Pasted image 20261116102608.png]]
# Multi-Factor-Authentication
- A security control where after you fill in your username/email and password , you have to use a second device such as a phone to confirm it is you logging in
- Protects against people who have stolen your password
- An option in most cloud providers and social media websites

![[Pasted image 20261116103445.png]]
# Security Keys
![[Pasted image 20261116103704.png]]

# AWS IAM (Identity and Access Management)
- You can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources
![[Pasted image 20261116103826.png]]

![[Pasted image 20261116103849.png]]
# Anatomy of an IAM Policy
- IAM Policies are written in JSON and contain permissions which determine what API actions are allowed or denied
![[Pasted image 20261116104043.png]]
# Principle-of-Least-Privilege (PoLP)
- The computer security concept of providing a user, role or application the least amount of permissions to perform an operation or action
![[Pasted image 20261116104401.png]]

# AWS Account Root User
- A special user who is created at the time of AWS account creation
![[Pasted image 20261116104635.png]]

![[Pasted image 20261116104738.png]]
# AWS IAM Identity Center
- You can create, or connect, your workforce identities in AWS once and manage access across your AWS organization
![[Pasted image 20261116104932.png]]
















































