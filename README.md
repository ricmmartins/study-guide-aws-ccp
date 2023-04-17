# 📗 Study Guide for the Exam AWS Certified Cloud Practitioner

This guide is intended to provide a list of pre-selected materials to help anyone starting in the cloud computing career and/or discovering AWS be ready to the AWS Certified Cloud Practitioner Exam

*Last update on April 15, 2023*

## 📝 Skills Measured - [Obtained from the official link](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

### 💡 Cloud Concepts (26%)

#### Define the AWS Cloud and its value proposition
* Define the benefits of the AWS cloud including
  * Security
    * [AWS Cloud Security](https://aws.amazon.com/security/)
    * [Security, Identity, and Compliance on AWS](https://aws.amazon.com/products/security/)
    * [Security and Compliance Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/security-and-compliance.html)
  * Reliability
    * [Definition of Reliability](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.pillar.reliability.en.html)
  * High Availability
    * [High availability and scalability on AWS](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/high-availability-and-scalability-on-aws.html)
  * Elasticity
    * [Definition of Elasticity](https://wa.aws.amazon.com/wat.concept.elasticity.en.html)
  * Agility
    * [What is Cloud Computing - Look for Agility](https://aws.amazon.com/what-is-cloud-computing/)
  * Pay-as-you go pricing
    * [How does AWS pricing work?](https://aws.amazon.com/pricing/?aws-products-pricing.sort-by=item.additionalFields.productNameLowercase&aws-products-pricing.sort-order=asc&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all#)
  * Scalability
    * [Definition of Scalability](https://wa.aws.amazon.com/wat.concept.scalability.en.html)
  * Global Reach
    * [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/?pg=cloudessentials)
  * Economy of scale
    * [Six Advantages of Cloud Computing](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html)
    * [Introduction to Cloud Economics](https://d1.awsstatic.com/whitepapers/introduction-to-aws-cloud-economics-final.pdf)
* Explain how the AWS cloud allows users to focus on business value
    * [Business value on AWS](https://aws.amazon.com/executive-insights/content/business-value-on-aws/)
    * [Realizing Business Value with AWS](https://aws.amazon.com/executive-insights/content/realizing-business-value-with-aws/)
* Shifting technical resources to revenue-generating activities as opposed to managing
infrastructure
    * [Cloud Economics Center](https://aws.amazon.com/economics/)
    * [What Is IaaS (Infrastructure as a Service)?](https://aws.amazon.com/what-is/iaas/)

####  Identify aspects of AWS Cloud economics
* Define items that would be part of a Total Cost of Ownership proposal
  * Understand the role of operational expenses (OpEx)
  * Understand the role of capital expenses (CapEx)
  * Understand labor costs associated with on-premises operations
  * Understand the impact of software licensing costs when moving to the cloud

> **_NOTE:_**  All  those items above are covered in this ebook: [AWS Cloud Economics](https://pages.awscloud.com/rs/112-TZM-766/images/Cloud%20Economics%20Ebook_October%202018.pdf)

* Identify which operations will reduce costs by moving to the cloud
  * Right-sized infrastructure
    * [Tips for Right Sizing](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-right-sizing/tips-for-right-sizing-your-workloads.html)
    * [Resize before Migrating](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-right-sizing/right-size-before-migrating.html)
  * Benefits of automation
    * [Evaluate the cost benefits of automation](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/best-practice-17-7.html)
  * Reduce compliance scope (for example, reporting)
  * Managed services (for example, RDS, ECS, EKS, DynamoDB)
    * [10 things you can do today to reduce AWS costs](https://aws.amazon.com/blogs/compute/10-things-you-can-do-today-to-reduce-aws-costs/)

#### Explain the different cloud architecture design principles
* Explain the design principles
  * Design for failure
  * Decouple components versus monolithic architecture
  * Implement elasticity in the cloud versus on-premises
  * Think parallel

> **_NOTE:_**  All  those items above are covered in this ebook: [Architecting in the Cloud](http://aws001.s3.amazonaws.com/trailhead/TrailHead_ArchitectingInTheCloud.pdf) 

### 💡 Security and Compliance (25%)

#### Define the AWS shared responsibility model
* Recognize the elements of the Shared Responsibility Model
* Describe the customer’s responsibly on AWS
  * Describe how the customer’s responsibilities may shift depending on the service used
(for example with RDS, Lambda, or EC2)
* Describe AWS responsibilities

> **_NOTE:_**  All  those items above are covered in this link: [Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/) 


#### Define AWS Cloud security and compliance concepts
* Identify where to find AWS compliance information
  * Locations of lists of recognized available compliance controls (for example, HIPPA,
SOCs)
    * [Compliance FAQ](https://aws.amazon.com/compliance/faq/)
  * Recognize that compliance requirements vary among AWS services
    * [AWS Services in Scope by Compliance Program](https://aws.amazon.com/compliance/services-in-scope/SOC/)
    * [Introduction to AWS Security - Compliance section](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/compliance.html)
    * [Introduction to AWS Security - PDF Whitepaper]([https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/compliance.html](https://d1.awsstatic.com/whitepapers/Security/Intro_to_AWS_Security.pdf))
    * (AWS Risk and Compliance E-book)[https://docs.aws.amazon.com/pdfs/whitepapers/latest/aws-risk-and-compliance/aws-risk-and-compliance.pdf)
* At a high level, describe how customers achieve compliance on AWS
  * Identify different encryption options on AWS (for example, In transit, At rest)
    * [Data encryption](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/data-encryption.html)
    * [Encrypting Data-at-Rest and -in-Transit](https://docs.aws.amazon.com/whitepapers/latest/logical-separation/encrypting-data-at-rest-and--in-transit.html)
* Describe who enables encryption on AWS for a given service
  * [The importance of encryption and how AWS can help](https://aws.amazon.com/blogs/security/importance-of-encryption-and-how-aws-can-help/)
  * [Three common cloud encryption questions and their answers on AWS](https://aws.amazon.com/blogs/security/three-common-cloud-encryption-questions-and-their-answers-on-aws/)
* Recognize there are services that will aid in auditing and reporting
  * [AWS Config](https://aws.amazon.com/config/)
  * [AWS CloudTrail](https://aws.amazon.com/cloudtrail/)
  * [AWS Audit Manager](https://aws.amazon.com/audit-manager/)
  * [AWS Artifact](https://aws.amazon.com/artifact/)
  * Recognize that logs exist for auditing and monitoring (do not have to understand the
logs)
    * [Event logging monitoring, auditing and logging](https://docs.aws.amazon.com/whitepapers/latest/architecting-hipaa-security-and-compliance-on-amazon-eks/event-logging-monitoring-auditing-and-logging.html)
  * Define Amazon CloudWatch, AWS Config, and AWS CloudTrail
    * [What is Amazon CloudWatch?](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
    * [What Is AWS Config?](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)
    * [What Is AWS CloudTrail?](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
* Explain the concept of least privileged access
  * [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#grant-least-priv)

#### Identify AWS access management capabilities
* Understand the purpose of User and Identity Management
  * [When do I use IAM?](https://docs.aws.amazon.com/IAM/latest/UserGuide/when-to-use-iam.html) 
  * [Overview of AWS identity management: Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_identity-management.html)
  * Access keys and password policies (rotation, complexity)
    * [Managing access keys for IAM users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html)
  * Multi-Factor Authentication (MFA)
    * [Multi-Factor Authentication (MFA) for IAM](https://aws.amazon.com/iam/features/mfa/)
  * AWS Identity and Access Management (IAM)
    * Groups/users
      * [IAM Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html)
      * [IAM user groups](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html)
    * Roles
      * [IAM roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)
    * Policies, managed policies compared to custom policies
      * [Policies and permissions in IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
      * [Overview of access management: Permissions and policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_access-management.html)
      * [What are AWS managed policies?](https://docs.aws.amazon.com/aws-managed-policy/latest/reference/about-managed-policy-reference.html)
      * [Creating IAM policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_create.html)
  * Tasks that require use of root accounts
    * [Tasks that require root user credentials](https://docs.aws.amazon.com/accounts/latest/reference/root-user-tasks.html)
  * Protection of root accounts
    * [Best practices to protect your account's root user](https://docs.aws.amazon.com/accounts/latest/reference/best-practices-root-user.html)

#### Identify resources for security support
* Recognize there are different network security capabilities
  * Native AWS services (for example, security groups, Network ACLs, AWS WAF)
    * [Network and Application Protection on AWS](https://aws.amazon.com/products/security/network-application-protection/) 
  * 3rd party security products from the AWS Marketplace
    * [Security Products in AWS Marketplace](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/security-products-in-aws-marketplace.html)
* Recognize there is documentation and where to find it (for example, best practices, whitepapers, official documents)
  * AWS Knowledge Center, Security Center, security forum, and security blogs
    * [AWS Knowledge Center](https://repost.aws/knowledge-center)
    * [AWS Security](https://aws.amazon.com/security/)
    * [Security Blogs](https://aws.amazon.com/security/blogs/)
  * Partner Systems Integrators
    * [AWS Partner Network Blog](https://aws.amazon.com/blogs/apn/)
* Know that security checks are a component of AWS Trusted Advisor
  * [AWS Trusted Avisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/)
  * [Documentation - Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)
  * [AWS Trusted Advisor check reference](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor-check-reference.html)
  * [Amazon Trusted Advisor Best Practices (Checks)](https://www.amazonaws.cn/en/support/trustedadvisor/best-practices/)

### 💡 Technology (33%)

#### Define methods of deploying and operating in the AWS Cloud
* Identify at a high level different ways of provisioning and operating in the AWS cloud
  * Programmatic access, APIs, SDKs, AWS Management Console, CLI, Infrastructure as
Code
    * [What is an API?](https://aws.amazon.com/what-is/api/)
    * [What is an SDK?](https://aws.amazon.com/what-is/sdk/)
    * [What is the AWS Management Console?](https://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/learn-whats-new.html)
    * [What is the AWS CLI?](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
* Identify different types of cloud deployment models
  * All in with cloud/cloud native
    *  [What is Cloud Native?](https://aws.amazon.com/what-is/cloud-native/)
  * Hybrid
    * [What is Hybrid Cloud?](https://aws.amazon.com/what-is/hybrid-cloud/)
  * On-premises
    * [On-premises definition under "Cloud computing deployment model"](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/types-of-cloud-computing.html)
* Identify connectivity options
  * VPN
    * [AWS VPN](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-vpn)
  * AWS Direct Connect
    * [AWS Direct Connect](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-direct-connect)
  * Public internet

#### Define the AWS global infrastructure
* Describe the relationships among Regions, Availability Zones, and Edge Locations
  * [AWS Global Infrastructure](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/global-infrastructure.html)
  * [Regions and Zones](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
* Describe how to achieve high availability through the use of multiple Availability Zones
  * Recall that high availability is achieved by using multiple Availability Zones
    * [Use multiple Availability Zones](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/use-multiple-availability-zones.html)
  * Recognize that Availability Zones do not share single points of failure
    * [High availability and scalability on AWS](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/high-availability-and-scalability-on-aws.html)
* Describe when to consider the use of multiple AWS Regions
  * Disaster recovery/business continuity
    * [Disaster recovery options in the cloud](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html)
    * [Business Continuity Plan (BCP)](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/business-continuity-plan-bcp.html)
    * [Disaster Recovery (DR) Architecture on AWS, Part I: Strategies for Recovery in the Cloud](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-i-strategies-for-recovery-in-the-cloud/)
    * [Disaster Recovery (DR) Architecture on AWS, Part II: Backup and Restore with Rapid Recovery](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-ii-backup-and-restore-with-rapid-recovery/)
    * [Disaster Recovery (DR) Architecture on AWS, Part III: Pilot Light and Warm Standby](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iii-pilot-light-and-warm-standby/)
    * [Disaster Recovery (DR) Architecture on AWS, Part IV: Multi-site Active/Active](https://aws.amazon.com/blogs/architecture/disaster-recovery-dr-architecture-on-aws-part-iv-multi-site-active-active/)
  * Low latency for end-users
    * [How can AWS help you reduce latency?](https://aws.amazon.com/whatis/latency/#:~:text=AWS%20Global%20Accelerator%20is%20a,jitter%2C%20and%20latency%20consistently%20low.) 
  * Data sovereignty
    * [AWS Digital Sovereignty Pledge: Control without compromise](https://aws.amazon.com/blogs/security/aws-digital-sovereignty-pledge-control-without-compromise/)
    * [Digital Sovereignty at AWS](https://aws.amazon.com/compliance/digital-sovereignty/)
* Describe at a high level the benefits of Edge Locations
  * Amazon CloudFront
    *  [What is Amazon CloudFront?](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
  * AWS Global Accelerator
    * [What is AWS Global Accelerator?](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html)

#### Identify the core AWS services
* Describe the categories of services on AWS (compute, storage, network, database)
  * [Compute on AWS](https://aws.amazon.com/products/compute/)
  * [Storage on AWS](https://aws.amazon.com/products/storage/)
  * [Databases on AWS](https://aws.amazon.com/products/databases/)
  * [Networking on AWS](https://aws.amazon.com/products/networking/) 
* Identify AWS compute services
  * Recognize there are different compute families
    * [Instance Types](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
  * Recognize the different services that provide compute (for example, AWS Lambda
compared to Amazon Elastic Container Service (Amazon ECS), or Amazon EC2, etc.)
    * [Compute Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html)
  * Recognize that elasticity is achieved through Auto Scaling
    * [What is Amazon EC2 Auto Scaling?](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
  * Identify the purpose of load balancers
    * [What is Load Balancing?](https://aws.amazon.com/what-is/load-balancing/)
* Identify different AWS storage services
  * Describe Amazon S3
    * [What is Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
  * Describe Amazon Elastic Block Store (Amazon EBS)
    * [Amazon Elastic Block Store](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
  * Describe Amazon S3 Glacier
    * [What Is Amazon S3 Glacier?](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html)
  * Describe AWS Snowball
    * [What is an AWS Snowball device?](https://docs.aws.amazon.com/snowball/latest/ug/whatissnowball.html)
  * Describe Amazon Elastic File System (Amazon EFS)
    * [What is Amazon Elastic File System?](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
  * Describe AWS Storage Gateway
    * [AWS Storage Gateway](https://docs.aws.amazon.com/storagegateway/index.html)
* Identify AWS networking services
  * Identify VPC
    * [What is Amazon VPC?](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
  * Identify security groups
    * [Control traffic to resources using security groups](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html)
  * Identify the purpose of Amazon Route 53
    * [What is Amazon Route 53?](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
  * Identify VPN, AWS Direct Connect
    *  [AWS VPN](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-vpn)
    * [AWS Direct Connect](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/networking-services.html#aws-direct-connect)
* Identify different AWS database services
  * Install databases on Amazon EC2 compared to AWS managed databases
    * [Choosing between Amazon EC2 and Amazon RDS](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/comparison.html)
  * Identify Amazon RDS
    * [What is Amazon Relational Database Service (Amazon RDS)?](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
  * Identify Amazon DynamoDB
    * [What is Amazon DynamoDB?](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
  * Identify Amazon Redshift
    * [What is Amazon Redshift?](https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html)

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

#### Compare and contrast the various pricing models for AWS (for example, On-Demand Instances,
Reserved Instances, and Spot Instance pricing)
* Identify scenarios/best fit for On-Demand Instance pricing
* Identify scenarios/best fit for Reserved-Instance pricing
  * Describe Reserved-Instances flexibility
  * Describe Reserved-Instances behavior in AWS Organizations
* Identify scenarios/best fit for Spot Instance pricing

#### Recognize the various account structures in relation to AWS billing and pricing
* Recognize that consolidated billing is a feature of AWS Organizations
* Identify how multiple accounts aid in allocating costs across departments

#### Identify resources available for billing support
* Identify ways to get billing support and information
  * Cost Explorer, AWS Cost and Usage Report, Amazon QuickSight, third-party partners,
and AWS Marketplace tools
  * Open a billing support case
  * The role of the Concierge for AWS Enterprise Support Plan customers
* Identify where to find pricing information on AWS services
  * AWS Simple Monthly Calculator
  * AWS Services product pages
  * AWS Pricing API
* Recognize that alarms/alerts exist
* Identify how tags are used in cost allocation

## Extras

* [Overview of Amazon Web Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html)
* [AWS Cloud Essentials - Getting Started Guide](https://aws.amazon.com/getting-started/cloud-essentials/)
* [AWS Security Essentials - Getting Started Guide](https://aws.amazon.com/getting-started/aws-security-essentials/)
* [AWS Billing and Cost Optimizations Essentials - Getting Started Guide](https://aws.amazon.com/getting-started/cost-optimization-essentials/)
* [AWS Networking Essentials - Getting Started Guide](https://aws.amazon.com/getting-started/aws-networking-essentials/)

## Show your support
Give the project's GitHub repository a ⭐️ if this content helped you!
