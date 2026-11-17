# Introduction
- A cloud security framework that defines the security obligations of the customer data versa the Cloud Service Provider (CPS)
- Each CSP has their own variant of the SRM butthey are generally the same
- The type of cloud deployment model and/orscope of cloud service category can result in specialized SRMs
![[Pasted image 20261115123303.png]]

# AWS Shared Responsibility Model
![[Pasted image 20261115123546.png]]

![[Pasted image 20261115123708.png]]

# Types of Cloud responsibilities
![[Pasted image 20261115132622.png]]

# Shared Responsibility for Compute
![[Pasted image 20261115135224.png]]
![[Pasted image 20261115135413.png]] ![[Pasted image 20261115135422.png]] ![[Pasted image 20261115135443.png|214]]

![[Pasted image 20261115135603.png]]

#  Shared Responsibility Model Alternate
- The Shared Responsibility Model is a simple visualization that helps determine what the customer is responsible for and what the CSP is responsible for related to AWS
- The customer is responsible for 
	- the data and the configuration of access controls that resides in AWS
	- the configuration of cloud services and granting access to users vis permissions
- CSP is generally responsible for the underlying Infrastructure
- Responsibility IN the cloud
	- If you can configure or store it then you are responsible for it as a customer
- Responsibility OF the cloud
	- If you cannot configure it, CSP is responsible for it
![[Pasted image 20261115140722.png]]
## Minimum responsibilities of parties in ALL services
- CSP
	- Hardware, Boot, Hardened Kernel + IPC, Storage + Encryption, Network, Audit logging
- Customer
	- Content, Access Policies, Usage

#  Shared Responsibility Model Architecture
![[Pasted image 20261115143114.png]]


















