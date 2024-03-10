What is systems manager?

AWS OpsWorks

S3 does not have Reserved Instance Pricing

Is CloudWatch for billing alarms

Availability --> Multi AZ/Regions
Scalability --> ASG/Node Balancers

Route 53 --> Single Resource --> Simple Routing

Memorize Trusted Advisor things that it can help you with

VPC Endpoint is basically for connecting an AWS service to your VPC
    VPC Gateway --> S3 and DynamoDB
    VPC Interface --> everything else

EC2 Bootstrap script --> instance user data

S3 Pricing Models
    - if in to s3 no cost
    - if s3 to ec2 in same region no cost, if different region there is a cost
    - if s3 to cloufront no cost
S3 Storage Classes
    - no constraint of minimum storage duration for objects

AWS Budgets

Study Well Architected Framework Pillars and CAF
    Performance Efficiency vs Operational Excellence
        Performance
            - using IT and computing resources efficiently (right amount of resources)
        Operational Excellence
            - 
Study differences between different support plans

AWS Health Dashboard - Your account health vs service heatlh

Is s3 keyvalue based or flat non-hierarchal structure
    - S3 is a key value database AND a flat non-hierarchal structure

VPC vs VPN

AWS s3 Transfer Acceleration
AWS Global Accelerator (?)

Clarify CloudWatch

Disaster Recovery Strategies
    - pilot light
        - like warm standby but with additional steps
    - multi-site active-active strategy
    - backup & restore
    - warm standby
        - functional stack but decreased capacity
    - hot standby
        - functional stack with production levels of capacity

Are EBS and EFS EC2 Instance Specific?

S3 Replication vs Transfer Acceleration 

The differences between the different load balancers
    - Network --> (Layer 3 to 7_ (from layer 3 to 7)
    - Application --> Layer 7 (only http/s)

AWS Marketplace

AWS Device Farm

AWS Web Application Framework vs Subnets vs NACLs

AWS Global Accelerator

API gateway is for exposing labmda functions as REST API endpoints

Which S3 class does not charge any data retrieval fee

AWS Artifiacts --> security and compliance documents

Amazon Inspector vs guardduty
    - Inspector is security assesments for EC2
    - GuardDuty entire AWS environment for potential threats

Trusted Advisor - AWS account level recommendations(flag things not being encrypted, security groups with ports open to the public, etc.,)

Inspector - scan your EC2 and containers for vulnerabilities. The old version required an agent to be installed. The new version uses ssm. This is useful for things like, "does my ec2 use a vulnerable log4j package)

Cloudwatch - Where logs from various AWS services can be sent and viewed.

Guardduty - Monitors traffic for suspicious activity. The biggest example I see is outbound traffic to IPs known for cryptomining. This indicates that a EC2 has been hacked.

Coincidentally I just passed the AWS Security certification exam 1 hour ago, and this stuff, along with KMS came up a lot.

Redshift has a well-defined schema

EFS --> is an elastic NFS file system which can be used by both cloud and on-premise services
