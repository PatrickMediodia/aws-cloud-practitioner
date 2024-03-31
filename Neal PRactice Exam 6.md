Top-Level Container to hold objects within S3?
- Bucket

User Data --> script to be run on EC2 Instance Launch

You can't nest IAM groups

Which AWS support plans provide 24x7 access to customer service?
- All Plans
- But if via phone or chat?
	- Business and Enterprise only

if through VPC public subnet to internet --> Internet Gateway
if through VPC private subnet to internet --> NAT Gateway

When an organization leverages the AWS Cloud Adoption Framework for migrating to the cloud, which two of the following would most likely be the primary stakeholders involved in the process? (Select TWO.)
- CIO
- IT Architects

Comprehend -> NLP, Lex -> NLP

Subnet Level -> NACL, Instance Level -> Security Groups

Which AWS service or feature helps restrict the AWS service, resources, and individual API actions the users and roles in each member account can access?
- AWS Organizations

Athena
- S3 and SQL
- Operational Analytics

Which AWS Glacier data access option retrieves data from an archive in 1-5 minutes?

EBS Snapshots are stored in S3 Buckets

Which AWS security tool uses an agent installed in EC2 instances and assesses applications for vulnerabilities and deviations from best practices?
- Amazon Inspector

Step Functions
- Which AWS service makes it easy to coordinate the components of distributed applications as a series of steps in a visual workflow?

Redshift
- ideally suited to analytics using SQL queries

Amazon Simple Workflow Service (SWF) 
- is a web service that makes it easy to coordinate work across distributed application components. 
- SWF enables applications for a range of use cases, including media processing, web application back-ends, business process workflows, and analytics pipelines, to be designed as a coordination of tasks.

Which of the authentication options below can be used to authenticate using AWS APIs? (Select TWO.)
- Access Keys
	- for programatic access
- Server Certificates SSL/TLS

Amazon Elasticsearch Service is involved with operational analytics such as application monitoring, log analytics and clickstream analytics. Amazon Elasticsearch Service allows you to search, explore, filter, aggregate, and visualize your data in near real-time.

Which AWS Glacier data access option retrieves data from an archive in 1-5 minutes?
- Expedited retrievals allow you to quickly access your data when occasional urgent requests for a subset of archives are required. For all but the largest archives (250 MB+), data accessed using Expedited retrievals are typically made available within 1–5 minutes.
- Standard --> 3-5 hour

AWS Inspector
- is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. 
- inspector automatically assesses applications for vulnerabilities or deviations from best practices
- Inspector uses an agent installed on EC2 instances.

Things to Study
- AWS Cloud Adoption Framework
- AWS Cost Management Tool
- CloudWatch vs CloudTrail
	- Metrics vs Logs?
- Textract
- S3 Costs
	- If standard
		- data egress and per gb/month
	- If others
		- retrieval free
- AWS Resource Groups
- AWS VPN vs VPC vs Direct Connect vs Site-to-Site VPN

Links to study
https://aws.amazon.com/cloud-adoption-framework/
https://aws.amazon.com/architecture/well-architected/
https://aws.amazon.com/athena/
https://aws.amazon.com/premiumsupport/plans/
https://aws.amazon.com/s3/storage-classes/glacier/
https://aws.amazon.com/about-aws/whats-new/2016/12/introducing-aws-personal-health-dashboard/
https://docs.aws.amazon.com/inspector/v1/userguide/inspector_introduction.html


[https://digitalcloud.training/aws-identity-and-access-management/](https://digitalcloud.training/aws-identity-and-access-management/)
https://digitalcloud.training/aws-billing-and-pricing/
https://digitalcloud.training/aws-shared-responsibility-model/

https://docs.aws.amazon.com/amazonswf/latest/developerguide/swf-welcome.html