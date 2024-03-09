Legend:
- **Bold** --> answer for that question
- *Italicized* --> take a look at this service/concept

1. Security Pillar Well-Architected Framework
	- **KMS** to encrypt data
	- *AWS Cloud Formation to automate security best practices*
		- not used to automate security best practices, amazon inspector can be used for that
	- Should be KMS, I was wrong
2. Which AWS service can inspect Amazon CloudFront distributions running on any HTTP web server?
	- Inspector is EC2 specific
	- **GuardDuty** can do that I think
	- WAF is the correct answer, if HTTP then it is WAF
1. Which types of monitoring can be provided by Amazon CloudWatch? (Select TWO)
	- Account Management
	- Performance and availability of AWS services
	- **Resource utilization**
	- API access
	- **Application performance**
2. Which AWS tool/service will help you define your cloud infrastructure using popular programming languages such as Python and JavaScript?
	- *CDK vs SDK*
3. A company would like to define a set of rules to manage objects cost-effectively between Amazon Simple Storage Service (Amazon S3) storage classes. As a Cloud Practitioner, which Amazon S3 feature would you use?
	- S3 lifecycle configuration
	- bucket policies
4. Which AWS tool can provide best practice recommendations for performance, service limits, and cost optimization?
	- Trusted Advisor
	- *AWS Health Dashboard
5. A start-up would like to quickly deploy a popular technology on AWS. As a Cloud Practitioner, which AWS tool would you use for this task?
	- AWS CodeDeploy
	- **AWS Partner Solutions (Quick Starts)**
6. A company needs to use a secure online data transfer tool/service that can automate the ongoing transfers from on-premises systems into AWS while providing support for incremental data backups. Which AWS tool/service is an optimal fit for this requirement?
	- **AWS DataSync**
	- *AWS Storage Gateway*
7. A company is planning to implement Chaos Engineering to expose any blind spots that can disrupt the resiliency of the application. Which AWS service will help implement this requirement with the least effort?
	- ***AWS Fault Injection Simulator (AWS FIS)***
8. Which security control tool can be used to deny traffic from a specific IP address?
	- **NACL** (allow and deny, stateless)
	- **Security group** (allow only)
9. A start-up would like to monitor its cost on the AWS Cloud and would like to choose an optimal Savings Plan. As a Cloud Practitioner, which AWS service would you use?
	- **AWS cost explorer** is for finding the optimal savings plan
10. Which of the following services are provided by Amazon Route 53? (Select Two)
	- **Domain Registration**
	- **Health checks and monitoring**
	- it is only a DNS, so it does not provide IP routing, load balancing, or transfer acceleration
11. An e-commerce company would like to build a chatbot for its customer service using Natural Language Understanding (NLU). As a Cloud Practitioner, which AWS service would you use?
	- Amazon Comprehend (NLP)
	- **Amazon Lex (NLU)**
12. Which of the following options is NOT a feature of Amazon Inspector?
	- it does not **track configuration changes**
	- automates security assessments
	- analyzes the network for unintended accessibility
	- and inspect running OS against vulnerabilities
13. Which of the following AWS services can be used to generate, use, and manage encryption keys on the AWS Cloud?
	- **CloudHSM** (hardware)
	- *AWS secrets manager*
		- *I don't think this allows you to generate encryption keys (?)*
14. A company based in Sydney hosts its application on an Amazon Elastic Compute Cloud (Amazon EC2) instance in ap-southeast-2. They would like to deploy the same Amazon EC2 instances in eu-south-1. Which of the following AWS entities can address this use case?
	- **AMI (Amazon Machine Image)**
	 - *EBS Elastic Volume snapshots (can't you create a snapshot which means you could restore than in another region?)* 
15. A company would like to separate cost for AWS services by the department for cost allocation. Which of the following is the simplest way to achieve this task?
	- **Create tags for each department**
		- since this is only for cost allocation, tags can be used
	- *Create different accounts for different departments*
		- this is more for separating the billing stuff
16. An organization would like to copy data across different Availability Zones (AZs) using Amazon EBS snapshots. Where are Amazon EBS snapshots stored in the AWS Cloud?
	- **EFS** but im not sure why
17. A company would like to move its infrastructure to AWS Cloud. Which of the following should be included in the Total Cost of Ownership (TCO) estimate? (Select TWO)
	- I remember that it was the ff, but im not sure why
		 - ***electronic equipment at office***
		- ***power/cooling* **

Things I'm not sure of
- AWS Secrets Manager
- Amazon Connect
- IAM Identity Center
- Amazon Guard Duty
	- threat detection service that continuously monitors for malicious or unauthorized behaviors to protect AWS accounts and workloads

Short Notes
- Hadoop, big data --> Amazon EMR
- ETL, Prepare for data analytics --> Amazon Glue
- AWS OpsWorks --> Chef and Puppet
- EC2
	- windows and linux are pay per second (a minimum of 60 seconds)
	- anything else pay per minute/hour
- Secondary backups --> S3 One Zone-IA
- Temporary Credentials --> STS
- CodeGuru --> automated code reviews
- X-ray --> analyze and debug production, distributed, and microservices
	- basically a debugging tool
- Cost Explorer --> costs and usage over time, for forecasting