
# Cloud-Native Networking Services
![[Pasted image 20261115215208.png]]

# Enterprise/Hybrid Networking Services
![[Pasted image 20261115215559.png]]

# Virtual Private Cloud (VPC) & Subnets
- A logically isolated section of the AWS network where you launch your AWS resources
- You choose a range of IPs using CIDR Range
	- CIDR Range of 10.0.0.0/16 = 655536 IP Addresses
![[Pasted image 20261115215752.png]]
# Security Groups vs NACLs (Network Access Control Lists)
- NACLs
	- Acts as a virtual firewall at the subnet level
	- You create Allow and Deny rules
- Security Groups
	- Acts as a virtual firewall at the instance level
	- Implicitly denies all traffic
	- You create only Allow rules
![[Pasted image 20261115223217.png]]