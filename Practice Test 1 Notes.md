34. What are the fundamental drivers of cost with AWS Cloud?
	- Compute, Storage, and Outbound Data Transfer
37. Which of the following solutions can you use to connect your on-premises network with AWS Cloud (Select two)?
	- Compute, Storage, and Outbound storage
40. What are the different gateway types supported by AWS Storage Gateway service?
	- It has something to do with tape, and volume but I'm not sure
43. AWS Compute Optimizer delivers recommendations for which of the following AWS resources? (Select two)
	- AWS Lambda functions and S3
	- EC2 and EC2 ASG
48. A photo sharing web application wants to store thumbnails of user-uploaded images on Amazon Simple Storage Service (Amazon S3). The thumbnails are rarely used but need to be immediately accessible from the web application. The thumbnails can be regenerated easily if they are lost. Which is the most cost-effective way to store these thumbnails on Amazon Simple Storage Service (Amazon S3)?
	- Im thinking S3 one zone IA since they can be easily regenerated if lost and needs to be immediately accessible
Short Notes
- AWS WAF --> web apps, sql injection, xss
- Event Bridge
- Subnets can only span one AZ, while VPCs can span multiple AZs within a region
- Athena --> analyze data from S3 buckets using SQL
- ECR vs ECS
	- ECS is actually deploying and running the docker containers
	- ECR is for storing and managing the images
- AWS Health Dashboard
	- Service Health Dashboard
		- general availability of AWS services
	- Your account health dashboard
		- specific to your account and the services that your account uses

Things I'm not sure of
- Is it only data transfer out of a region that is charged?
- Study MQ vs SNS vs SQS
- AWS Computer Optimizer
- Different gateway types supported by AWS Storage Gateway
	- Tape
	- File
	- Volume
- CAF Transformation Phases
	- AWS systems manager - session manager
- Study CAF
	- Technical
		- Platform
		- Security
		- Operations
	- Business
		- Business
		- People
		- Governance
- AWS Global Accelerator