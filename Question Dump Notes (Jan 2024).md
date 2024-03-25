AWS Systems Manager - Session Manager

SNS vs SQS
    SNS
		- one to many
		- pubsub
    SQS
	    - many to many
	    - message queuing 

identify measurable business outcomes

NAT Gateway

Which AWS service or component allow inbound traffic from the internet to access a VPC?
	NOT NAT Gateway - this only allows traffic from one of your services to access the public internet
	ANSWER Internet Gateway - allows both ways, from internet to VPC, and VPC to public internet

Well Architected Framework Pillars
- Performance Efficiency
- Operational Excellence
- Security
- Sustainability
- Reliability
- Cost Optimization
https://aws.amazon.com/blogs/apn/the-6-pillars-of-the-aws-well-architected-framework/

Global Accelerator
- service to service connection through the AWS network

AWS Savings Plans
- EC2
- Compute
- SageMaker

Local Zones
- extension of AWS infrastructure to provide low latency, close to customer office
- only available in certain areas

Dedicated Hosts vs Dedicated Instances
	Instances
		- hardware dedicated to a single customer but does not give you access to the underlying physical server
		- does not allow you to use existing software licenses
	Hots
		- per-socket, per-core, or per-virtual machine softwar licenses for MS windows server

Reserved Instances
	- note, your reservation can only be accessed in one zone

AWS Storage Gateway
	- on-premise access to aws cloud data
	- fast and low latency



CodeGuru
- code reivews and code quality

Fargate
- serverless contanerization

Quicksight
- business intelligence dashboards

S3 Transfer Acceleration
- uses AWS backbone network and edge locations to reduce latencies from the end user to amazon s3

CloudWatch
- monitor and troubleshoot

AWS Step Functions
- orchestration for multiple AWS services
- run this after this, basically you write the steps on what to do with a GUI

Study
- Route 53 vs RouteTables vs Global Accelerator
- CloudWatch vs TrustedAdvisor vs CloudTrail vs GuardDuty
- Compute Optimizer
- AWS Systems Manager
	- automatically collect software inventory, apply OS patches, create system images, and configure linux and windows operating systems
- Service Catalog
- AWS Resource Groups
- AWS Migration Hub (?)
- AWS Application Discovery and Migration Services