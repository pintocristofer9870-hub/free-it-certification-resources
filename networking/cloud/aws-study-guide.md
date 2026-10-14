
# AWS Certification Study Guide

A free study guide for learners preparing for Amazon Web Services (AWS) certifications. Review core cloud concepts, understand important AWS services, and test your knowledge with original practice questions.

Whether you are beginning your cloud journey or preparing for an associate-level certification, this guide can help you organize your learning.

## Table of Contents

- [What Is AWS?](#what-is-aws)
- [Core AWS Services](#core-aws-services)
- [Important Cloud Concepts](#important-cloud-concepts)
- [Study Plan](#study-plan)
- [Practice Questions](#practice-questions)
- [Answers and Explanations](#answers-and-explanations)
- [Official Learning Resources](#official-learning-resources)
- [More Practice](#more-practice)

## What Is AWS?

Amazon Web Services (AWS) is a cloud computing platform that provides services for computing, storage, networking, databases, security, analytics, and more.

Organizations use AWS to build applications, store data, run workloads, and scale infrastructure according to their needs.

Common benefits of cloud computing include:
- Flexible capacity and scalability.
- Access to managed infrastructure services.
- Global infrastructure options.
- Usage-based pricing for many services.
- Automation and infrastructure management.

Actual costs depend on the services, configuration, region, and usage.

## Core AWS Services

### 1. Compute

**Amazon EC2**

Amazon Elastic Compute Cloud (EC2) provides virtual servers called instances. It offers control over operating systems, instance types, networking, and storage configuration.

Common uses:
- Hosting applications.
- Running web servers.
- Performing compute-intensive tasks.

**AWS Lambda**

Lambda runs code in response to events without requiring you to manage the underlying servers.

Common uses:
- Event-driven automation.
- Processing uploaded files.
- Building serverless application components.

### 2. Storage

**Amazon S3**

Amazon Simple Storage Service (S3) is object storage for files and other data.

Common uses:
- Backups.
- Static website assets.
- Logs and data archives.

**Amazon EBS**

Amazon Elastic Block Store provides block storage volumes designed for use with EC2 instances.

Remember:
- S3 is object storage.
- EBS provides block storage volumes.
- These services solve different storage problems.

### 3. Networking

**Amazon VPC**

A Virtual Private Cloud (VPC) provides a logically isolated network for AWS resources.

Important concepts:
- Subnets.
- Route tables.
- Internet gateways.
- Security groups.
- Network access control lists (network ACLs).

**Amazon Route 53**

Route 53 is a scalable DNS service that can route users to applications and other supported endpoints.

### 4. Databases

**Amazon RDS**

Relational Database Service (RDS) simplifies the deployment and management of supported relational database engines.

**Amazon DynamoDB**

DynamoDB is a managed NoSQL database service designed for key-value and document data models.

A common exam-style distinction is that RDS supports relational database workloads, while DynamoDB is a NoSQL option.

### 5. Identity and Security

**AWS IAM**

Identity and Access Management (IAM) controls access to AWS resources through identities, policies, roles, and permissions.

Security best practices include:
- Grant only the permissions required.
- Prefer temporary credentials and roles when appropriate.
- Protect account credentials.
- Enable suitable monitoring and auditing.
- Review permissions regularly.

## Important Cloud Concepts

### Regions and Availability Zones

An AWS Region is a separate geographic area containing AWS infrastructure.

Availability Zones are distinct locations within a Region, designed to support workload availability and resilience.

For workloads that require higher availability, consider distributing suitable resources across multiple Availability Zones.

### Shared Responsibility Model

AWS and the customer have different security responsibilities.

AWS is responsible for security **of** the cloud, including the underlying infrastructure.

Customers are responsible for security **in** the cloud, with exact responsibilities depending on the service and deployment model.

For example, customers generally remain responsible for managing their identities and access permissions.

### Scalability and High Availability

Scalability means adjusting capacity to meet demand.

High availability means designing systems to remain operational despite certain failures.

Common AWS building blocks include load balancing, Auto Scaling, monitoring, and multi-AZ architectures.

### Pricing and Cost Management

Understand these principles:
- Many services charge according to usage.
- Storage, data transfer, and compute can have separate charges.
- Always check service-specific pricing.
- Set up budgets and cost alerts.
- Stop or remove unused resources when appropriate.

Creating resources for practice can incur charges. Review current pricing and use approved learning environments carefully.

## Study Plan

### Week 1: Cloud Fundamentals
- Learn cloud computing terminology.
- Understand Regions and Availability Zones.
- Review the AWS shared responsibility model.
- Explore the AWS global infrastructure concepts.

### Week 2: Core Services
- Study EC2, Lambda, S3, and EBS.
- Learn VPC basics and security groups.
- Compare RDS and DynamoDB.
- Review IAM policies and roles.

### Week 3: Architecture and Security
- Study scalability and high availability.
- Learn basic backup and disaster recovery concepts.
- Understand monitoring and cost management.
- Practice scenario-based questions.

### Week 4: Review and Practice
- Revisit weak topics.
- Answer original practice questions.
- Read explanations for incorrect answers.
- Review the official exam guide for your chosen certification.

This is a general study schedule. Adjust it to the certification level and your previous experience.

## Practice Questions

These are original educational questions, not actual certification exam questions.

### Question 1

Which AWS service is primarily designed for object storage?

A. Amazon EC2  
B. Amazon S3  
C. Amazon VPC  
D. AWS IAM  

### Question 2

Which AWS service lets you run code in response to events without managing the underlying servers?

A. Amazon EBS  
B. Amazon Route 53  
C. AWS Lambda  
D. Amazon RDS  

### Question 3

What is the primary purpose of AWS IAM?

A. Store objects  
B. Manage identities and access permissions  
C. Provide virtual servers  
D. Host relational databases  

### Question 4

What is an AWS Region?

A. A single virtual machine  
B. A geographic area containing AWS infrastructure  
C. An IAM permission  
D. A storage volume  

### Question 5

Which service is a managed NoSQL database?

A. Amazon DynamoDB  
B. Amazon EBS  
C. Amazon Route 53  
D. Amazon EC2  

### Question 6

Which statement best describes the AWS shared responsibility model?

A. AWS is responsible for every customer configuration.
B. Customers are responsible for the physical AWS data centers.
C. AWS and customers have different responsibilities for cloud security.
D. Customers do not need to manage access permissions.

## Answers and Explanations

**Question 1: B — Amazon S3**

S3 is AWS object storage and is commonly used for backups, media files, logs, and other objects.

**Question 2: C — AWS Lambda**

Lambda executes code in response to supported triggers without requiring customers to manage the underlying servers.

**Question 3: B — Manage identities and access permissions**

IAM supports access management using identities, roles, and policies.

**Question 4: B — A geographic area containing AWS infrastructure**

Regions contain Availability Zones and provide geographic choices for deploying AWS resources.

**Question 5: A — Amazon DynamoDB**

DynamoDB is a managed NoSQL database supporting key-value and document data models.

**Question 6: C — AWS and customers have different responsibilities for cloud security**

The exact division depends on the service and deployment. Customers retain important responsibilities such as identity management and appropriate configuration.

## Official Learning Resources

Use official AWS materials to keep your preparation aligned with current certification requirements.

- [AWS Certification](https://aws.amazon.com/certification/)
- [AWS Skill Builder](https://skillbuilder.aws/)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Architecture Center](https://aws.amazon.com/architecture/)
- [AWS Pricing](https://aws.amazon.com/pricing/)

Always check the current exam guide for the certification you intend to take. Service coverage and exam objectives can change.

## More Practice

Looking for additional IT certification practice questions and study resources?

Visit [ExamsTeacher.com](https://examsteacher.com/) to explore available preparation materials.

For best results, choose resources that match your target certification and include explanations that help you understand why an answer is correct.

## Disclaimer

This is an independent educational guide. It is not affiliated with or endorsed by Amazon Web Services.

AWS and related service names are used for educational identification. All practice questions in this guide are original and are not actual or leaked certification exam questions.

## Contributing

Suggestions, corrections, and original educational contributions are welcome. Please ensure that contributions are accurate, properly sourced, and consistent with the relevant certification provider's published objectives.
