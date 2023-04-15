# 📗 Study Guide for the Exam AWS Certified Cloud Practitioner

This guide is intended to provide a list of pre-selected materials to help anyone starting in the cloud computing career and/or discovering AWS be ready to the AWS Certified Cloud Practitioner Exam

*Last update on April 7, 2023*

## 📝 Skills Measured - [Obtained from the official link](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

### 💡 Cloud Concepts (26%)

#### Define the AWS Cloud and its value proposition
* Define the benefits of the AWS cloud including:
  * Security
  * Reliability
  * High Availability
  * Elasticity
  * Agility
  * Pay-as-you go pricing
  * Scalability
  * Global Reach
  * Economy of scale
* Explain how the AWS cloud allows users to focus on business value
  * Shifting technical resources to revenue-generating activities as opposed to managing
infrastructure

####  Identify aspects of AWS Cloud economics
* Define items that would be part of a Total Cost of Ownership proposal
  * Understand the role of operational expenses (OpEx)
  * Understand the role of capital expenses (CapEx)
  * Understand labor costs associated with on-premises operations
  * Understand the impact of software licensing costs when moving to the cloud
* Identify which operations will reduce costs by moving to the cloud
  * Right-sized infrastructure
  * Benefits of automation
  * Reduce compliance scope (for example, reporting)
  * Managed services (for example, RDS, ECS, EKS, DynamoDB)

#### Explain the different cloud architecture design principles
* Explain the design principles
  * Design for failure
  * Decouple components versus monolithic architecture
  * Implement elasticity in the cloud versus on-premises
  * Think parallel

### 💡 Security and Compliance (25%)

#### Define the AWS shared responsibility model
* Recognize the elements of the Shared Responsibility Model
* Describe the customer’s responsibly on AWS
  * Describe how the customer’s responsibilities may shift depending on the service used
(for example with RDS, Lambda, or EC2)
* Describe AWS responsibilities
#### Define AWS Cloud security and compliance concepts
* Identify where to find AWS compliance information
  * Locations of lists of recognized available compliance controls (for example, HIPPA,
SOCs)
  * Recognize that compliance requirements vary among AWS services
* At a high level, describe how customers achieve compliance on AWS
  * Identify different encryption options on AWS (for example, In transit, At rest)
* Describe who enables encryption on AWS for a given service
* Recognize there are services that will aid in auditing and reporting
  * Recognize that logs exist for auditing and monitoring (do not have to understand the
logs)
  * Define Amazon CloudWatch, AWS Config, and AWS CloudTrail
* Explain the concept of least privileged access

#### Identify AWS access management capabilities
* Understand the purpose of User and Identity Management
  * Access keys and password policies (rotation, complexity)
  * Multi-Factor Authentication (MFA)
  * AWS Identity and Access Management (IAM)
    * Groups/users
    * Roles
    * Policies, managed policies compared to custom policies
  * Tasks that require use of root accounts
  * Protection of root accounts

#### Identify resources for security support
* Recognize there are different network security capabilities
  * Native AWS services (for example, security groups, Network ACLs, AWS WAF)
  * 3rd party security products from the AWS Marketplace
* Recognize there is documentation and where to find it (for example, best practices, whitepapers, official documents)
  * AWS Knowledge Center, Security Center, security forum, and security blogs
  * Partner Systems Integrators
* Know that security checks are a component of AWS Trusted Advisor


### 💡 Technology (33%)

#### Define methods of deploying and operating in the AWS Cloud
* Identify at a high level different ways of provisioning and operating in the AWS cloud
  * Programmatic access, APIs, SDKs, AWS Management Console, CLI, Infrastructure as
Code
* Identify different types of cloud deployment models
  * All in with cloud/cloud native
  * Hybrid
  * On-premises
* Identify connectivity options
  * VPN
  * AWS Direct Connect
  * Public internet

#### Define the AWS global infrastructure
* Describe the relationships among Regions, Availability Zones, and Edge Locations
* Describe how to achieve high availability through the use of multiple Availability Zones
  * Recall that high availability is achieved by using multiple Availability Zones
  * Recognize that Availability Zones do not share single points of failure
* Describe when to consider the use of multiple AWS Regions
  * Disaster recovery/business continuity
  * Low latency for end-users
  * Data sovereignty
* Describe at a high level the benefits of Edge Locations
  * Amazon CloudFront
  * AWS Global Accelerator

#### Identify the core AWS services
* Describe the categories of services on AWS (compute, storage, network, database)
* Identify AWS compute services
  * Recognize there are different compute families
  * Recognize the different services that provide compute (for example, AWS Lambda
compared to Amazon Elastic Container Service (Amazon ECS), or Amazon EC2, etc.)
  * Recognize that elasticity is achieved through Auto Scaling
  * Identify the purpose of load balancers
* Identify different AWS storage services
  * Describe Amazon S3
  * Describe Amazon Elastic Block Store (Amazon EBS)
  * Describe Amazon S3 Glacier
  * Describe AWS Snowball
  * Describe Amazon Elastic File System (Amazon EFS)
  * Describe AWS Storage Gateway
* Identify AWS networking services
  * Identify VPC
  * Identify security groups
  * Identify the purpose of Amazon Route 53
  * Identify VPN, AWS Direct Connect
* Identify different AWS database services
  * Install databases on Amazon EC2 compared to AWS managed databases
  * Identify Amazon RDS
  * Identify Amazon DynamoDB
  * Identify Amazon Redshift

#### Identify resources for technology support
* Recognize there is documentation (best practices, whitepapers, AWS Knowledge Center,
forums, blogs)
* Identify the various levels and scope of AWS support
  * AWS Abuse
  * AWS support cases
  * Premium support
  * Technical Account Managers
* Recognize there is a partner network (marketplace, third-party) including Independent
Software Vendors and System Integrators
* Identify sources of AWS technical assistance and knowledge including professional services,
solution architects, training and certification, and the Amazon Partner Network
* Identify the benefits of using AWS Trusted Advisor

### 💡 Billing and Pricing (16%)

## Extras

* [AZ-900 Overview](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)
* [Certification poster](http://aka.ms/traincertposter)
* [Free Azure account sign-up](https://azure.microsoft.com/en-us/free/)
* [Exam environment simulation](https://aka.ms/examdemo)
* [Azure Infrastructure Map](http://infrastructuremap.microsoft.com/)
* [Cloud administration basics](https://docs.microsoft.com/en-us/learn/paths/cmu-admin/)
  * [Foundations of cloud computing for administrators](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-admin-overview/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Provision and manage cloud services](https://docs.microsoft.com/en-us/learn/modules/cmu-provision-cloud-services/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Secure your cloud resources with access control](https://docs.microsoft.com/en-us/learn/modules/cmu-secure-cloud-resources/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Virtualize resources in the cloud](https://docs.microsoft.com/en-us/learn/modules/cmu-virtualization/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Scale your cloud resources with elasticity](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-elasticity/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Automate cloud resource management](https://docs.microsoft.com/en-us/learn/modules/cmu-orchestration/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)
  * [Monitor cloud resources](https://docs.microsoft.com/en-us/learn/modules/cmu-monitor-cloud-resources/?ns-enrollment-type=LearningPath&ns-enrollment-id=learn.cmu-cloud-admin.cloud-admin)

## Show your support
Give the project's GitHub repository a ⭐️ if this content helped you!
