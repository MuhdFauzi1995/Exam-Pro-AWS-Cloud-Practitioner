# AWS API
- API (Application Programming Interface)
	- A Software that allows 2 applications/services to talk to each other
	- Most common type: HTTP/S requests
- AWS API is used to interact by sending HTTPS requests using an application interacting with APIs like Postman
![[Pasted image 20261114193646.png]]

- Users rarely send HTTP requests directly to AWS API
- It is much easier to interact with API via Developer tools
![[Pasted image 20261114193756.png]]

# AWS Management Console
- A web-based unified console
- Builds, manages and monitors everything from simple web apps to complex cloud deployments
![[Pasted image 20261114194708.png]]

# Service Console
- AWS Services have their own customized console
- They can be accessed by searching their service names
![[Pasted image 20261114200201.png]]

# AWS Account ID
![[Pasted image 20261114200709.png]]

# AWS Tools for PowerShell
![[Pasted image 20261114200926.png]]

# Amazon Resource Names (ARNs)
- Uniquely identifies AWS Resources
- Required to specify a resource unambiguously across all of AWS
![[Pasted image 20261114201348.png]]
![[Pasted image 20261114202228.png]]

# AWS CLI
- Command Line Interface
	- Processes commands to a computer program as lines of text
- Terminal
	- Text-only interface (input/output environment)
- Console
	- Physical computer to physically input information into a terminal
- Shell
	- Command line program that users interact with in input programs
		- E.g: Bash, Zsh, PowerShell
![[Pasted image 20261114205851.png]]

![[Pasted image 20261114205959.png]]

# AWS SDK (Software Development Kit)
- A collection of software development tools in 1 installable package
- Can be used to programmatically create, modify, delete or interact with AWS resources
![[Pasted image 20261114210906.png]]

# AWS CloudShell
- A browser-based shell built into the AWS Management console
![[Pasted image 20261114211918.png]]

# Infrastructure as Code (IaC)
- A blueprint of infrastructure
- Allows to easily share, version or inventory cloud infrastructure
- You write a configuration script to automate creating, updating or destroying cloud infrastructure
![[Pasted image 20261114212413.png]]

# CloudFormation
- Allows you to write IaC either as JSON or YAML files
- YAML file as shown in this image
![[Pasted image 20261114220537.png|436]]
- Simple but can lead to large files or is limited tin some regard to creating dynamic or repeatable infrastructure compared to CDK
- Easier for DevOps Engineers with no backgroud in web programming languages
- Since CDK generates CloudFormation, it's still important to read and understand CloudFormation to debug IaC stacks

# CDK (Cloud Development Kit)
- Allows you to use your favorite programming language to write IaC
- Powered by CloudFormation
- Has a large library of reusable cloud components called CDK Construct
- Comes with its own CLI
- CDK Pipelines to quickly setup CI/CD pipelines for CDK projects
- Has a testing framework for Unit and Integration Testing
- AWS SDK looks similar but CSK ensures Idempotent of your Infrastructure
![[Pasted image 20261114220824.png]]

# AWS Toolkit for VSCode
- An open-source plugin for VSCode to create, debug and deploy AWS resources
![[Pasted image 20261114221313.png]]

# Access Keys
- A key and secret required to have programmatic access to AWS resources when interacting with AWS API outside of AWS Management Console
- Commonly referred to as AWS Credentials
![[Pasted image 20261114221710.png]]

- Access Keys are to be stored in ~/.aws/credentials and follow a TOML format
![[Pasted image 20261114221816.png]]

# AWS Documentation
- A Large collection of technical documentation on how to use AWS Services
![[Pasted image 20261114221942.png]]




























