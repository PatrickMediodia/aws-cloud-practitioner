Comprehend
- get or derive valuable insights from text documents

If about performance globally
- pick CloudFront or S3 Global Accelerator

if limit human error --> look to automate
- perform operations as code

CodeDeploy
- automates application deployment to EC2, on-premise, lambda, or ECS

AWS Outposts
- use AWS infrastructure and software on-premise for compliance purposes

S3 bucket creation
- they don't ask which availability zones, they ask for regions
- they automatically create copies of it in AZs within a region

Shared Responsibility
- AWS
	- anything hardware
- Customer
	- anything firewall

Elasticity
- scale out or in (adding additional instances to the group)
- scale up or down (change instance type)

Operational Excellence vs Performance Efficiency
- Ops
	- testing for failure
	- refine operational procedures
- Performance
	- testing for load times etc.

Savings Plans
- EC2
- Compute
	- EC2
	- Fargate
	- Lambda
- SageMaker

Edge Locations are only cache (CloudFront - CDN)

If DDOS --> Shield
if SQL Injection --> Web Application Firewall (Layer 7)

OpsWorks --> Chef and Puppet --> YAML ---> Infrastructure as Code
OpsHub --> graphical user interface to manage AWS snowball devices

AWS Budgets
- limit spending in AWS
- notification or alarm
	- ex if expenditure if more than 5 dollars etc.

AWS License Manager --> manage licences
EC2 Dedicated Hosts --> to be able to use your licences for compliance reasons

Amazon MQ
- managed message broker for Apache ActiveMQ and RabbitMQ
- message brokers for AWS

QuickSight
- dashboard
- reports
- analytics

Organizations
- create accounts
- groups
- consolidated billing

TrustedAdvisor
- best practices
- Cost Optimization, Performance, Security, Fault Tolerance, Service Limits

Redshift
- data warehouse

EMR
- hadoop
- big data

Outposts
- AWS services on-premises

Things to Study
- Systems Manager Types
- CloudWatch vs CloudTraill vs Inspector vs GuardDuty vs TrustedAdvisor
- Well Architected Framework
- Cloud Architecture Framework

S3 is the cheapest storage compared to Aurora, EBS, and EFS

CloudFormation
- infrastructure as code
- use YAML or JSON to define your infrastructure
- makes it easy to recreate yoru infrastructure in multiple regions