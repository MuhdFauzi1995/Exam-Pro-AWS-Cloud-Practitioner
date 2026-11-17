
# Introduction
- The process of letting 2 independent applications to communicate and work with each other, commonly facilitated by an intermediate system
- Cloud workloads encourage systems and services to be loosely coupled so AWS has many services for the specific purpose of application integration
![[Pasted image 20261116142342.png]]

# Queueing and SQS
- Messaging system
	- used to provide asynchronous communication and decouple processes via messages/events from a sender and receiver (producer and consumer)
- Queuing System
	- A messaging system that generally deletes messages once they are consumed
		- Simple communication
		- Not Real0time
		- Have to pull
		- Not reactive
![[Pasted image 20261116142521.png]]
# Streaming and Kinesis
- Multiple consumers can react to events (messages)
- Events live in the stream for lonf periods of time so complex operations can be applied in real time
![[Pasted image 20261116142825.png]]
# Pub-Sub and SNS
- Publish-Subscribe pattern commonly implemented in messaging systems
- Sender of messages (publishers) do not send their messages directly to receivers but to an event bus
- The event bus categorizes their messages into groups, allowing receivers of messages (subscribers) to subscribe to these groups
- Any new messages within their subscription are immediately delivered to them
![[Pasted image 20261116143021.png]]
# API Gateway and Amazon API Gateway
- A program that sits between a single-entry point and multiple backends
- Allows for throttling, logging, routing logic or formatting of the request and response
![[Pasted image 20261116143348.png]]
# State Machines and AWS Step Functions
- State machine
	- An abstract model which decides how one state moves to another based on a series of conditions
	- Can be treated like a flowchart
![[Pasted image 20261116143457.png]]
# Event Bus and Amazon Event Bridge
- An event bus receives events from a source and route events to a target based on riles
![[Pasted image 20261116143606.png]]

![[Pasted image 20261116143721.png]]
# Application Integration Services
![[Pasted image 20261116143956.png]]

# AWS Amplify
- An opinionated framework and fully-managed infrastructure to allow developers to focus on building web and mobile applications
- Not easy to understand
![[Pasted image 20261116144209.png]]

![[Pasted image 20261116144243.png]]
# AppSync
- A fully managed GraphQL service
![[Pasted image 20261116144438.png]]

![[Pasted image 20261116144556.png]]

![[Pasted image 20261116144641.png]]









