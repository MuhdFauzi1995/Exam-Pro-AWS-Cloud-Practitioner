# Introduction
- 5 different ways to pay for EC2
1. On-Demand
2. Spot
3. Reserved
4. Dedicated
5. AWS Savings plan (Another way to save; can be used for more than just EC2)
![[Pasted image 20261116082234.png]]
# On Demand
- A Pay-As-You-Go (PAYG) model where you consume compute and then you pay
- When you launch an EC2 instance, it is by default using On-Demand Pricing
	- On-Demand has no up-front payment and no long-term commitment
![[Pasted image 20261116082424.png]]
# Reserved Instances (RI)
- Designed for applications that have a steady-state, predictable usage, or require reserved capacity
	- Pricing is based on ==Term== x ==Class Offering== x ==RI== x ==Attributes== x ==Payment Option==
![[Pasted image 20261116082915.png]]

![[Pasted image 20261116082936.png]]
# RI Attributes
- Limited based  on Class Offering and ca affect final price of RI instance
- 4 RI attributes
![[Pasted image 20261116083044.png]]
# Regional and Zonal RI
- Regional RI
	- Purchase for a region
- Zonal RI
	- Purchase for an Availability Zone
![[Pasted image 20261116083532.png]]
# RI Limits
- A limit to the number of Reserved Instances that you can purchase per month
- For each month you can purchase 
	- 20 Regional Instances per Region and 20 Zonal Regional Instances per AZ
![[Pasted image 20261116083711.png]]
# Capacity Reservations
- EC2 instances are backed by different kind of hardware, so there is a finite amount of servers available within an Availability Zone per instance type of family
![[Pasted image 20261116083921.png]]
# Standard vs Convertible RI
![[Pasted image 20261116084036.png]]

# RI Marketplace
- Allows you to sell your unused RI to recoup your RI spent for those you do not intend to or cannot use
![[Pasted image 20261116085654.png]]

# Spot Instances
- AWS has unused compute capacity that they want to maximize the utility of idle servers
- Spot Instances provide a 90% discount compared to On-Demand pricing
![[Pasted image 20261116085821.png]]
# Dedicated Instances
- Designed to meet regulatory requirements
- When you have strict server-bound licensing that would not support multi-tenancy or cloud deployments, you use Dedicated Hosts
![[Pasted image 20261116090016.png]]
# Savings Plan
- Offers similar discounts as Reserved Instances (RIs) with a simplified purchasing process
![[Pasted image 20261116090123.png]]

- 3 different savings types
![[Pasted image 20261116090339.png]]