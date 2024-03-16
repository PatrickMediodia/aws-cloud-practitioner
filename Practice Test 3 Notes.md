What is active passive configuration

What I know
- Automatic Data Encryption
	- **S3** 
	- **EFS (WRONG)**
	- Storage 
		- all data transferred between the gateway and AWS is encrypted using SSL

What I don't Know
- S3 Transfer Acceleration
	- Fast and secure transfer of files over long distances between your end user device and the s3 bucket
	- Cannot improve the performance of your static website
- Global Accelerator
	- traffic routing service that improves TCP and UDP performance
- CloudFront
	- CDN
- Difference Between
	- Inspector
	- CloudWatch
		- Events
		- Logs
	- CloudTrail
	- GuardDuty
		- protects your AWS account by monitoring malicious activity and detecting threats
- S3 Glacier 
	- Flexible Retireval
		- archive data that does not require immediate access but needs the flexibility to retrieve large sets of data at no cost, such as backup or disaster recovery use cases
	- Deep Archive
- AWS Budget Types you can create

What I learned
- EC2 instances can access files on an Amazon Elastic File System (Amazon EFS) file system across many Availability Zones (AZ), Regions and VPC
	- EFS offers high availability and durability across multiple AZs
- EBS vs EFS Costing
	- EBS Snapshots are stored incrementally which means you are billed only for the changed blocks stored
	- You will pay a fee each time you read or write data stored on the Amazon Elastic File System - IA (Check normal EFS vs IA)
- You must activate both AWS generated and user defined tags **separately** before they can appear in Cost Explorer
- A resource tag must be unique and can only have one value
- AWS Rekognition is regional by scope, and WAF is global since it can be accessed anywhere