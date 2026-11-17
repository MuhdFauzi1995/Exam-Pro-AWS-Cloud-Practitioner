# Defense-In-Depth
![[Pasted image 20261117171706.png]]

# CIA (Confidentiality, Integrity and Availability) Triad
- A model describing the foundation to security principles and their trade-off relationship
![[Pasted image 20261117171909.png]]
# Vulnerabilities
- A hole or weakness in the application, which can be a design flaw or an implementation bug that allows an attacker to cause harm to the stakeholders of an application
![[Pasted image 20261117172018.png]]

# Encryption
- Cryptography
	- The practice and study of techniques for secure communication in the presence of third parties called adversaries
- Encryption
	- The process of encoding (scrabbling) information using a key and a cypher to store sensitive data in an unintelligible format as protection
	- Takes in plain text and produces ciphertext

# Cyphers
- Cypher
	- An algorithm that performs encryption of decryption
	- Synonymous with code
- Ciphertext
	- The result of encryption performed on plaintext via an algorithm
- Codebook
	- A type of document used for gathering and storing cryptography codes

# Cryptographic Keys
- A variable used in conjunction with an encryption algorithm in order to encrypt or decrypt data
- Comes in 2 forms
	- Symmetric encryption
		- Used for encoding and decoding
			- e.g Advanced Encryption Standard (AES)
	- Asymmetric encryption
		- 2 keys are used; One to encode and the other to decode
			- e.g. Rivest-Shamir-Adleman (RSA)
![[Pasted image 20261117173059.png]]
# Hashing and Salting
- Hashing
	- A one-way process and is deterministic
		- Deterministic functions always return the same output for the same input
![[Pasted image 20261117173317.png]]
# Digital Signatures and Signing
- A mathematical scheme for verifying the authenticity of digital messages or documents
![[Pasted image 20261117173526.png]]
# In-Transit vs At-Rest Encryption
- In-Transit
	- Data that is secure when moving between locations
	- Algorithms: TLS, SSL
- At-Rest
	- Data that is secure when residing on storage or within a database
	- Algorithms: AES, RSA
![[Pasted image 20261117173709.png]]
# Compliance Programs
- A set of internal policies and procedures of a company to comply with laws,  rules and regulations or to uphold business reputation
![[Pasted image 20261117173857.png]]

![[Pasted image 20261117173958.png]]

![[Pasted image 20261117174021.png]]

![[Pasted image 20261117174049.png]]

![[Pasted image 20261117174122.png]]

![[Pasted image 20261117174219.png]]
# Pen Testing
- An authorized simulated cyberattack on a computer system performed to evaluate the security of the system
- Allowed to be performed on AWS
![[Pasted image 20261117174406.png]]
# AWS Artifact
- A self-serve portal for on-demand access to AWS compliance reports
![[Pasted image 20261117174456.png]]
# AWS Inspector
- Hardening
	- The act of eliminating as many security risks as possible
	- Common for Virtual Machines where you run a collection of security checks known as a security benchmark
![[Pasted image 20261117174626.png]]
# DDoS (Distributed Denial of Service)
- A malicious attempt to disrupt normal traffic by flooding a website with large amounts of fake traffic
![[Pasted image 20261117174815.png]]
# AWS Shield
- A managed DDos protection service that safeguards applications running on AWS
![[Pasted image 20261117174944.png]]

![[Pasted image 20261117175114.png]]


# AWS Guard Duty
- A threat detection service that continuously monitors for malicious, suspicious activity and unauthorized behavior
- It uses Machine Learning and analyzes using these AWS Logs
	- CloudTrail Logs
	- VPC Flow Logs
	- DNS Logs
- Alerts you of findings which you can automate an incident response via CloudWatch Events or with 3rd party Services
- IDS (Intrusion Detection System)/ IPS (Intrusion Protection System)
	- A device or software application that monitors a network or systems for malicious activity or policy violations
![[Pasted image 20261117185429.png|404]]

![[Pasted image 20261117185449.png]]

# AWS VPN (Virtual Private Network)
- Lets you establish a secure and private tunnel from your network or device to the AWS global network
- 2 options
	- AWS Site-to-Site VPN
		- Securely connect on-premises network or branch office site to VPC
	- AWS Client VPN
		- Securely connect users to AWS or on-premises networks

![[Pasted image 20261117185622.png]]
# AWS WAF (Web Application Firewall)
- Protects your web applications from common web exploits
![[Pasted image 20261117185959.png]]
# Hardware Security Module
- A piece of hardware designed to store encryption keys
- Holds keys in memory and never write them to disk
![[Pasted image 20261117190239.png]]
# AWS KMS (Key Management Service)
- A managed service that makes it easy for you to create and control the encryption keys used to encrypt your data
![[Pasted image 20261117192610.png]]
# CloudHSM
- A single-tenant HSM as a service that automates hardware provisioning, software patching, high availability and backups
![[Pasted image 20261117192837.png]]
# AWS Security Hub
- A cloud security posture management (CSPM)
- CSPMs allows you to generate a security score to determine your security posture
![[Pasted image 20261117193645.png]]
# AWS Audit Manager
- Continuously audits your AWS Usage to simplify risk and compliance assessment
- You can
	- create assessments to review evidence collected and generate an assessment report
	- continuously collect evidence by directly integrating AWS Config and AWS Security Hub
![[Pasted image 20261117193452.png]]

# AWS Firewall Manager
- Allows you to centrally configure and manage firewall rules across accounts and applications
![[Pasted image 20261117194531.png]]








