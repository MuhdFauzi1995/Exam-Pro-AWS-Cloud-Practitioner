
# VMs vs Containers
- Virtual Machines (VMs) do not make the best use of space
- Apps are not isolated, which could cause configuration conflicts, security problems or resource hogging
![[Pasted image 20261116145804.png]]

- Containers allow you to run multiple apps which are virtually isolated from each other
- Launch new containers and configure OS Dependencies per container
![[Pasted image 20261116150029.png]]
# Microservices
- Monolithic Architecture
	- One app is responsible for everything
	- Functionality is tightly coupled
![[Pasted image 20261116150219.png]]

- Microservices Architecture
	- Multiples apps are responsible for one thing
	- Functionality is isolated and stateless
![[Pasted image 20261116150310.png]]
# Kubernetes
- An open-source contanier orchestration system for automating deployment, scaling and management of containers
- Originally created by Google and now maintained by the Cloud Native Computing Foundation (CNCF)
![[Pasted image 20261116150443.png]]
# Docker
- A set of Platform as a Service (PaaS) products that use OS-level virtualization to deliver software in packages called containers
- The earliest popularized open-source container platform
![[Pasted image 20261116150629.png]]

![[Pasted image 20261116150707.png]]


# Podman
- A container engine thar is OCI-compliant and is a drop-in replacement for Docker
	- Daemon-less
	- Allows you to create pods such as K8
	- Replaces only 1 part of Docker
		- To be used alongside Buildah and Skopeo

![[Pasted image 20261116150842.png]]
# Container Services
- Primary Services
![[Pasted image 20261116151054.png]]

- Provisioning and Deployment
![[Pasted image 20261116151141.png]]

- Supporting Services
![[Pasted image 20261116151205.png]]
