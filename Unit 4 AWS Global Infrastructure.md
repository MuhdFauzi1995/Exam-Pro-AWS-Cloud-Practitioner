# Overview
![[Pasted image 20261112201414.png]]

# Regions
- Geographically distinct locations consisting of one or more Availability zones
- Each region is physically isolated from and independent of every other region in terms of location, power and water supply
![[Pasted image 20261113185740.png]]
![[Pasted image 20261113185810.png]]

- Each region has 3 availability zones
	- Some new users are limited to 2
- New services are almost always available first in US-EAST
- Not all AWS services are available in all regions
- All billing information appears in US-EAST-1 at North Virginia
- Cost of AWS services vary per region

![[Pasted image 20261113190159.png]]

## 4 factors to consider
1. What regulatory Compliance does this region meet?
2. What is the cost of AWS services in this region?
3. What  AWS services are available in this region?
4. What is the distance/latency to my end-users?

# Regional vs Global Services

## Regional services
- AWS scopes their AWS Management Console on a selected Region
- This determines where an AWS service will be launched and what will be seen within an AWS Service's console
- You don't explicitly set the region for a service at the time of creation
![[Pasted image 20261113192435.png]]
## Global Services
- Some AWS Services operate across multiple regions and the region will be fixed to Global
- For these global services at the time of creation:
	- There is no concept of region (e.g. IAM User)
	- A single region must be explicitly chosen (e.g. S3 Bucket)
	- A group of regions are chosen (e.g. CloudFront Distribution)
![[Pasted image 20261113192637.png]]

# Availability Zones
- A physical location made up of one or more data centers
![[Pasted image 20261113192913.png]]

![[Pasted image 20261113193345.png]]
![[Pasted image 20261113193402.png]]

# Regions and Availability zones
- A region has multiple Availability zones
	- Each Availability zone is made up of at least 1 data center
- All AZs in an AWS region are 
	- interconnected with high-bandwidth, low-latency networking, 
		- over fully redundant, dedicated metro fiber, 
	- providing high-throughput, low-latency networking between
- All traffic between AZs are encrypted
- AZs are within 100km of each other.

![[Pasted image 20261113193914.png]]

# Fault Tolerance
- A fault domain is a section of a network that is vulnerable to damage if a critical device or system fails
- Fault domains ensure that failures do not cascade outside that domain to limit possible damage
- A fault level is a collection of fault domains
![[Pasted image 20261113200706.png]]
- Each Amazon region is designed to be completely isolated from other Amazon Regions
	- achieving the greatest possible fault tolerance and stability
- Each Availability zone
	- is isolated, but those in a Region are connected through low-latency links
	- is designed as an independent failure zone
## Failure zones
![[Pasted image 20261113201858.png]]
![[Pasted image 20261113201914.png]]

# AWS Global Network
- Represents the interconnections between the AWS Global Infrastructure
	- Commonly referred to as the 'Backbone of the AWS'
	- Treated like a private expressway where things can be moved very fast between datacenters
![[Pasted image 20261113205111.png]]
# Points of Presence (PoP)
- An intermediate location between an AWS region and the end user
	- This location could be a datacenter ot collection of hardware
- For AWS, 
	- a PoP is a datacenter owned by AWS or a trusted partner 
	- that is utilized by AWS services 
		- related to content delivery or expediated upload
![[Pasted image 20261114103452.png]]
# Tier 1
- 
![[Pasted image 20261114103614.png]]
# AWS Services using PoPs
- These services are used for content delivery or expediated uploadds
## Amazon Cloudfront
- A Content Delivery Network (CDN) service that:
	- Lets you choose your website to CloudFront so that it can route requests to the nearest Edge Location Cache
	- Allows you to choose an origin that will be the source of cached data
	- Caches contents of what origin would be returned to various Edge Locations around the world
## Amazon S3 Transfer Acceleration
- Enables you to generate a special URL that can be used by end users to upload files to a nearby Edge Location
- Files uploaded there move much faster within AWS Network to reach S3
## Amazon Global Accelerator
- Finds the optimal path from the end user to your web-server.
- Deployed within Edge Locations so you send traffic to an Edge Location instead of directly to your web-application
![[Pasted image 20261114105544.png]]

# AWS Direct Connect
- A private/dedicated connection between your datacenter, office co-location and AWS
- Direct Connect options:
	- Lower Bandwidth: 50 MBps - 500 MBps
	- Higher Bandwidth: 1 GBps or 10 GBps
![[Pasted image 20261114110525.png]]

# Direct Connect Locations
- Trusted partnered datacenters that you can establish a dedicated high speed, low latency connection from your on-premise to AWS.
![[Pasted image 20261114111317.png]]
# AWS Local Zones
- Datacenters located very close to a densely populated ares to provide single-digit millisecond low latency performance (e.g 7ms) for that area
![[Pasted image 20261114112005.png]]
# Wavelength zones
- Allows for edge-computing on 5G networks
- Applications will have ultra-low latency being as close as possible to users
![[Pasted image 20261114112257.png]]
# Data Residency
- Data Residnecy
	- Physical or geographic location of 
		- where an organization or cloud resources reside
- Compliance Boundaries
	- A regulatory compliance (legal requirement) by a government or organization 
		- that describes where fata and cloud resources are allowed to reside
- Data Sovereignty
	- The jurisdictional control or legal authority that 
		- can be asserted over data because 
			- its physical location is within jurisdictional boundaries
![[Pasted image 20261114112603.png]]


# AWS for government
- Public sector
	- Includes public goods and governmental services as listed here
![[Pasted image 20261114113142.png]]

- AWS can be utilized by public sector or organizations developing cloud workloads for the public sector
- AWS achieves this by meeting regulatory compliance programs along with specific governance and security controls
![[Pasted image 20261114113405.png]]

# GovCloud
![[Pasted image 20261114115731.png]]

# AWS in China
- AWS in China is completely isolated from the global version to meet regulatory compliance for Mainland China with its own domain (amazonaws.cn)
![[Pasted image 20261114125017.png]]

# Sustainability
- Amazon co-founded the Climate Pledge to acheive Net-Zero Carbon Emissions by 2040 across all of its businesses, including AWS

## 3 parts of sustainability goals
1. Renewable energy
2. Cloud Efficiency
3. Water Stewardship
![[Pasted image 20261114125516.png]]
# AWS Ground Station
- A fully managed service that lets you control satellite communications, process data and scale operations without the worry of building or managing own ground station infrastructure
![[Pasted image 20261114130207.png]]
# AWS Outposts
- A fully managed service that offers the same AWS Infrastructure, services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience
![[Pasted image 20261114155130.png]]

- Comes in 3 form factors: 42U, 1U and 2U
![[Pasted image 20261114155534.png]]













