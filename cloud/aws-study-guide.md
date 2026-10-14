
# AWS Cloud Computing Fundamentals: Study Guide

Welcome to this beginner-friendly AWS study guide. It introduces essential Amazon Web Services (AWS) concepts for learners preparing for cloud computing and IT certification exams.

For additional IT certification learning and practice resources, visit [Examsteacher.com](https://examsteacher.com/).

## 1. What Is Cloud Computing?

Cloud computing provides on-demand access to computing resources over a network, typically the internet.

Instead of purchasing and maintaining all computing hardware yourself, you can use cloud services to run applications, store data, and build infrastructure.

### Benefits of Cloud Computing

- **Scalability:** Increase or decrease resources as requirements change.
- **Elasticity:** Automatically or manually adjust capacity to match demand.
- **Pay-as-you-go pricing:** Pay for many resources based on usage.
- **Global reach:** Deploy applications in different geographic regions.
- **Managed services:** Reduce the operational work required for certain infrastructure tasks.
- **Availability options:** Design systems using multiple resources and locations to improve resilience.

Cloud computing does not automatically make every application secure, highly available, or inexpensive. Those outcomes depend on architecture, configuration, and management.

## 2. AWS Global Infrastructure

AWS infrastructure includes Regions, Availability Zones, and edge locations.

### AWS Regions

A Region is a separate geographic area where AWS operates infrastructure.

When choosing a Region, consider:
- User location and latency.
- Service availability.
- Regulatory and data residency requirements.
- Pricing.
- Disaster recovery requirements.

### Availability Zones

An Availability Zone (AZ) consists of one or more discrete data centers with independent infrastructure within an AWS Region.

Using multiple Availability Zones can help an application remain available when one zone experiences a problem.

### Edge Locations

Edge locations support services that deliver content or provide functionality closer to end users.

For example, Amazon CloudFront uses a global network of edge locations to deliver content with lower latency.

**Exam tip:** Regions are geographic areas; Availability Zones provide isolated infrastructure within Regions; edge locations support delivery closer to users.

## 3. Core AWS Compute Services

### Amazon EC2

Amazon Elastic Compute Cloud (EC2) provides virtual servers called instances.

Common uses include:
- Hosting web applications.
- Running application servers.
- Processing workloads.
- Supporting custom operating system configurations.

EC2 customers are responsible for configuring and maintaining many aspects of the guest operating system and software, depending on the service arrangement.

### AWS Lambda

AWS Lambda runs code in response to events without requiring you to manage the underlying servers directly.

Common uses include:
- Processing uploaded files.
- Responding to API requests.
- Automating event-driven tasks.
- Running scheduled functions.

Lambda is commonly described as a serverless compute service.

### AWS Elastic Beanstalk

Elastic Beanstalk helps deploy and manage applications while handling much of the underlying infrastructure configuration.

It is useful when developers want to deploy supported applications without manually managing every infrastructure component.

## 4. AWS Storage Services

### Amazon S3

Amazon Simple Storage Service (S3) is an object storage service.

Common uses include:
- Storing images and documents.
- Hosting static website assets.
- Retaining backups and archives.
- Storing data for analytics.

S3 stores data as objects in buckets.

### Amazon EBS

Amazon Elastic Block Store (EBS) provides block storage volumes designed for use with Amazon EC2.

Typical uses include:
- Operating system volumes.
- Application storage.
- Databases running on EC2.

### Amazon EFS

Amazon Elastic File System (EFS) provides managed file storage that can be shared by multiple supported compute resources.

**Exam tip:**
- S3: Object storage.
- EBS: Block storage commonly used with EC2.
- EFS: Shared file storage.

Choose a service according to the application's storage requirements.

## 5. AWS Networking Services

### Amazon VPC

Amazon Virtual Private Cloud (VPC) lets you define a logically isolated network for AWS resources.

A VPC can include:
- Subnets.
- Route tables.
- Network access controls.
- Security groups.
- Internet connectivity components.

### Public and Private Subnets

A public subnet is associated with routing that can provide a path to an internet gateway.

A private subnet does not have a direct route to an internet gateway. Depending on its configuration, resources in a private subnet may still reach external services through other network components, such as a NAT gateway.

A subnet's public or private status depends on its routing and resource configuration, not simply on its name.

### Security Groups

Security groups act as virtual firewalls for supported AWS resources.

They control inbound and outbound traffic using configured rules. Security groups are stateful.

### Network ACLs

Network access control lists (network ACLs) provide subnet-level traffic controls. They are stateless, so inbound and outbound rules must be considered separately.

### Amazon Route 53

Route 53 is AWS's scalable Domain Name System (DNS) service.

It can be used for domain registration, DNS routing, health checks, and supported traffic-routing policies.

## 6. AWS Database Services

### Amazon RDS

Amazon Relational Database Service (RDS) simplifies setting up, operating, and scaling supported relational databases.

Common uses include transactional applications that need relational data and SQL queries.

### Amazon DynamoDB

DynamoDB is a managed NoSQL database service designed for performance at scale.

It is useful for applications that need key-value or document data models and predictable low-latency access patterns.

### Amazon Aurora

Amazon Aurora is a relational database engine compatible with MySQL and PostgreSQL.

It is available through Amazon RDS.

**Exam tip:** RDS and Aurora support relational database workloads; DynamoDB supports NoSQL workloads.

## 7. Identity and Access Management

### AWS IAM

AWS Identity and Access Management (IAM) helps manage authentication and authorization for AWS resources.

IAM concepts include:

- **Users:** Identities for people or applications when appropriate.
- **Groups:** Collections of IAM users.
- **Roles:** Identities with permissions that can be assumed by trusted principals.
- **Policies:** Documents that define permissions.

### Least Privilege

Grant only the permissions needed for a task.

Avoid using overly broad permissions simply because they are convenient.

### Root User Security

Protect the AWS account root user carefully.

Recommended practices include:
- Enable multifactor authentication.
- Do not use the root user for routine administrative tasks.
- Secure recovery methods.
- Review account security settings regularly.

### Shared Responsibility Model

AWS and the customer share responsibility for security.

AWS is responsible for security **of** the cloud, including the underlying infrastructure it operates.

Customers are responsible for security **in** the cloud according to the services they use and the applicable responsibility model.

Customer responsibilities may include:
- Managing identities and permissions.
- Protecting data.
- Configuring network controls.
- Maintaining guest operating systems on EC2.
- Configuring applications securely.

The exact division of responsibility varies by service.

## 8. Monitoring and Management

### Amazon CloudWatch

CloudWatch collects and monitors metrics, logs, and events from supported AWS services and applications.

It can support alarms, dashboards, troubleshooting, and operational monitoring.

### AWS CloudTrail

CloudTrail records AWS account activity and API events to support auditing, security investigations, and governance.

### AWS Config

AWS Config helps assess, audit, and evaluate the configurations of supported AWS resources over time.

**Exam tip:** CloudWatch focuses on monitoring and observability; CloudTrail records account activity; AWS Config tracks resource configuration and compliance.

## 9. AWS Pricing and Cost Management

AWS offers different pricing approaches depending on the service and workload.

Common considerations include:
- On-demand pricing.
- Savings Plans and Reserved Instances where applicable.
- Spot Instances for suitable interruptible workloads.
- Storage and data transfer charges.
- Regional price differences.
- Resource utilization and idle resources.

### Cost Management Best Practices

- Set budgets and billing alerts.
- Review cost reports regularly.
- Remove unused resources.
- Right-size compute capacity.
- Select storage tiers according to access needs.
- Use pricing tools before deploying a workload.

Always review the current pricing details for the specific service and Region.

## 10. Reliability and High Availability

High availability means designing a system to remain operational despite certain failures.

Common design practices include:
- Deploying across multiple Availability Zones.
- Using load balancing where appropriate.
- Monitoring application health.
- Automating recovery.
- Creating and testing backups.
- Documenting recovery procedures.

Disaster recovery planning should consider recovery time objectives (RTO) and recovery point objectives (RPO).

- **RTO:** The target time to restore a service after a disruption.
- **RPO:** The target for how much data loss, measured in time, is acceptable.

A backup is useful only if it can be restored successfully. Test recovery procedures regularly.

## 11. A Simple AWS Study Plan

Use this four-week outline as a starting point.

### Week 1: Cloud Fundamentals

Study:
- Cloud computing concepts.
- AWS global infrastructure.
- Regions and Availability Zones.
- Shared responsibility model.

### Week 2: Core Services

Study:
- EC2 and Lambda.
- S3, EBS, and EFS.
- VPC, subnets, and security groups.
- RDS and DynamoDB.

### Week 3: Security and Operations

Study:
- IAM and least privilege.
- MFA and account protection.
- CloudWatch and CloudTrail.
- Reliability and cost management.

### Week 4: Revision and Practice

- Review the official exam objectives for your chosen certification.
- Complete practice questions.
- Review incorrect answers and their explanations.
- Practise in the AWS console using safe, budget-conscious configurations.
- Revise unfamiliar services.

This plan is a general starting point. Adjust it to the certification level and exam version you are targeting.

## 12. Practice Questions

Try to answer the following questions before checking the answer key.

### Question 1

Which AWS service provides object storage?

A. Amazon EC2  
B. Amazon S3  
C. Amazon VPC  
D. AWS IAM

### Question 2

Which AWS service runs code in response to events without requiring you to manage the underlying servers directly?

A. Amazon EBS  
B. Amazon Route 53  
C. AWS Lambda  
D. Amazon RDS

### Question 3

Which service is designed to provide virtual servers?

A. Amazon EC2  
B. Amazon S3  
C. AWS CloudTrail  
D. Amazon DynamoDB

### Question 4

Which AWS service helps manage identities and permissions?

A. Amazon CloudFront  
B. AWS IAM  
C. Amazon EFS  
D. Amazon Route 53

### Question 5

Which service is commonly used to monitor metrics and logs?

A. Amazon VPC  
B. Amazon S3  
C. Amazon CloudWatch  
D. AWS Organizations

### Question 6

What is a major benefit of deploying an application across multiple Availability Zones?

A. It removes every possible security risk.  
B. It guarantees that the application has no downtime.  
C. It can improve resilience to certain Availability Zone failures.  
D. It eliminates all data transfer costs.

## 13. Answer Key and Explanations

1. **B — Amazon S3.** S3 is AWS object storage for data such as files, backups, and application assets.
2. **C — AWS Lambda.** Lambda runs functions in response to events without requiring direct server management.
3. **A — Amazon EC2.** EC2 provides virtual server instances.
4. **B — AWS IAM.** IAM manages identities, roles, and permissions for AWS resources.
5. **C — Amazon CloudWatch.** CloudWatch supports monitoring through metrics, logs, alarms, and dashboards.
6. **C — It can improve resilience to certain Availability Zone failures.** Multi-AZ designs can reduce dependence on a single zone, but they do not guarantee zero downtime.

## 14. Official AWS Learning Resources

Use official sources to verify technical details and prepare for your chosen certification.

- [AWS Certification](https://aws.amazon.com/certification/)
- [AWS Skill Builder](https://skillbuilder.aws/)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Architecture Center](https://aws.amazon.com/architecture/)
- [AWS Pricing](https://aws.amazon.com/pricing/)

Certification objectives and service details may change. Review the official exam guide for the certification and version you plan to take.

## 15. Continue Learning

Explore additional IT certification learning and practice resources at [Examsteacher.com](https://examsteacher.com/).

## Disclaimer

This guide is for educational purposes only. It is not an official AWS certification guide and does not guarantee exam success.

This repository is independent and is not affiliated with or endorsed by Amazon Web Services (AWS). AWS service names and trademarks belong to their respective owners.
