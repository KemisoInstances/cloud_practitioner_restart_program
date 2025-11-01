# AWS Services Quiz

This is a static quiz designed for GitHub. The checkboxes are for formatting purposes and are not interactive. To see the correct answers and explanations, click the "Show Answer & Explanation" text below each question.

---

### Question 1

A development team is building an application that needs database credentials. They want automatic rotation and avoid storing credentials in code. Which AWS service fits this scenario?

- [ ] a. AWS Systems Manager Parameter Store can store parameters but requires extra steps for rotation.
- [ ] b. AWS KMS manages encryption keys but does not automatically rotate application secrets.
- [ ] c. AWS Secrets Manager securely stores, retrieves, and automatically rotates database credentials without embedding them in code.
- [ ] d. AWS CloudFormation deploys resources but does not handle credential rotation automatically.

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. AWS Secrets Manager
<br><br>
**Explanation:** **AWS Secrets Manager** is specifically designed for this use case. It securely stores and automatically rotates secrets like database credentials, API keys, and other sensitive information, which prevents the need to hardcode them in applications.
</details>

---

### Question 2

You must manage encryption keys and application secrets. Which TWO services are relevant?

- [ ] a. AWS CloudTrail
- [ ] b. AWS KMS for managing encryption keys.
- [ ] c. AWS Secrets Manager for storing and rotating secrets.
- [ ] d. AWS CloudFormation
- [ ] e. Amazon Macie

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** b. AWS KMS, c. AWS Secrets Manager
<br><br>
**Explanation:** **AWS KMS** (**Key Management Service**) is for creating and managing cryptographic keys. **AWS Secrets Manager** is used to store, manage, and automatically rotate application secrets. These two services complement each other for comprehensive key and secret management.
</details>

---

### Question 3

Automate governance and account setup for multiple AWS accounts. Which service is primary?

- [ ] a. AWS Control Tower
- [ ] b. AWS Systems Manager
- [ ] c. AWS CloudFormation
- [ ] d. AWS Service Catalog

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS Control Tower
<br><br>
**Explanation:** **AWS Control Tower** is the primary service for setting up and governing a secure, multi-account AWS environment. It automates the setup of a landing zone with best-practice blueprints and enables guardrails to enforce governance rules.
</details>

---

### Question 4

A multinational company must continuously monitor AWS accounts for compliance and generate audit-ready reports. Which TWO AWS services can help achieve this goal?

- [ ] a. AWS Config records resource configuration but doesn’t generate full audit reports automatically.
- [ ] b. AWS Security Hub centralizes security alerts and compliance checks across multiple AWS accounts.
- [ ] c. AWS CloudFormation deploys infrastructure but does not evaluate compliance.
- [ ] d. AWS CloudTrail logs API activity but is not a compliance evaluation service.
- [ ] e. AWS Audit Manager continuously evaluates controls and generates audit-ready reports.

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** b. AWS Security Hub, e. AWS Audit Manager
<br><br>
**Explanation:** **AWS Security Hub** provides a comprehensive view of security alerts and compliance status across your accounts. **AWS Audit Manager** helps you continuously audit your AWS usage and simplifies the process of generating audit-ready reports.
</details>

---

### Question 5

Automate application deployment and configuration using Chef or Puppet. Which AWS service?

- [ ] a. AWS CloudFormation
- [ ] b. AWS OpsWorks
- [ ] c. AWS Systems Manager
- [ ] d. AWS Control Tower

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS OpsWorks
<br><br>
**Explanation:** **AWS OpsWorks** is a configuration management service that provides managed instances of Chef and Puppet. It automates application deployment and configuration for a wide range of application architectures.
</details>

---

### Question 6

Your team needs to provision and manage SSL/TLS certificates for a public website. Which service should they use?

- [ ] a. AWS Certificate Manager (ACM)
- [ ] b. AWS KMS
- [ ] c. Amazon Macie
- [ ] d. AWS Secrets Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS Certificate Manager (ACM)
<br><br>
**Explanation:** **AWS Certificate Manager (ACM)** is the service for provisioning, managing, and deploying SSL/TLS certificates for use with AWS services like Elastic Load Balancers and CloudFront distributions.
</details>

---

### Question 7

A healthcare application requires dedicated Hardware Security Modules (HSMs) to meet strict compliance standards. Which AWS service should be used?

- [ ] a. AWS KMS uses multi-tenant HSMs and may not meet strict compliance requirements.
- [ ] b. AWS Secrets Manager stores secrets but does not provide dedicated HSMs.
- [ ] c. Amazon Macie is for data classification, not key management.
- [ ] d. AWS CloudHSM provides single-tenant HSM appliances in the cloud for regulatory-compliant key management.

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS CloudHSM
<br><br>
**Explanation:** **AWS CloudHSM** provides single-tenant, dedicated **Hardware Security Modules** (HSMs) in the cloud. This meets stringent compliance requirements for key management that may not be met by a multi-tenant service like AWS KMS.
</details>

---

### Question 8

The compliance team wants to detect and protect personally identifiable information (PII) stored in Amazon S3. Which AWS service should they use?

- [ ] a. AWS Control Tower
- [ ] b. AWS Security Hub
- [ ] c. Amazon Macie
- [ ] d. AWS Secrets Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. Amazon Macie
<br><br>
**Explanation:** **Amazon Macie** is a data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS. It can automatically detect personally identifiable information (PII) in Amazon S3.
</details>

---

### Question 9

You notice suspicious activity from an AWS-hosted resource. Who should you contact to report this abuse?

- [ ] a. AWS Support
- [ ] b. AWS Abuse team
- [ ] c. AWS Security Hub
- [ ] d. AWS Audit Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Abuse team
<br><br>
**Explanation:** The **AWS Abuse team** is the correct point of contact for reporting suspicious or malicious activity originating from an AWS resource, such as spam, malware, or other abusive behavior.
</details>

---

### Question 10

A company wants to set up new AWS accounts with preconfigured guardrails and governance best practices. Which TWO AWS services are appropriate?

- [ ] a. AWS Service Catalog deploys templates but does not enforce guardrails.
- [ ] b. AWS Systems Manager manages resources, not account setup governance.
- [ ] c. AWS Organizations centrally manages multiple AWS accounts.
- [ ] d. AWS Control Tower sets up accounts with best-practice guardrails automatically.
- [ ] e. AWS OpsWorks manages application stacks, not account governance.

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** c. AWS Organizations, d. AWS Control Tower
<br><br>
**Explanation:** **AWS Organizations** allows you to centrally manage and consolidate multiple AWS accounts. **AWS Control Tower** builds on top of Organizations to provide a landing zone and automated guardrails, ensuring new accounts adhere to governance rules from the start.
</details>

---

### Question 11

A DevOps engineer wants to run AWS CLI commands directly in a browser without local installation. Which service should they use?

- [ ] a. AWS Systems Manager
- [ ] b. AWS CloudFormation
- [ ] c. AWS CloudShell
- [ ] d. AWS OpsWorks

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. AWS CloudShell
<br><br>
**Explanation:** **AWS CloudShell** is a browser-based shell that comes pre-authenticated with your AWS credentials. It provides a command-line interface for managing AWS resources directly from the console without needing a local installation.
</details>

---

### Question 12

Your team wants to automate application deployment and configuration management using Chef or Puppet. Which AWS service is most suitable?

- [ ] a. AWS OpsWorks
- [ ] b. AWS CloudFormation
- [ ] c. AWS Systems Manager
- [ ] d. AWS Service Catalog

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS OpsWorks
<br><br>
**Explanation:** **AWS OpsWorks** is a configuration management service that provides a fully managed platform for using Chef and Puppet to automate the deployment of applications and manage server configurations.
</details>

---

### Question 13

A system administrator wants to automate patching and run commands across thousands of EC2 instances. Which service should they use?

- [ ] a. AWS OpsWorks
- [ ] b. AWS Control Tower
- [ ] c. AWS CloudFormation
- [ ] d. AWS Systems Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Systems Manager
<br><br>
**Explanation:** **AWS Systems Manager** provides a unified interface to automate operational tasks across your AWS infrastructure. The Run Command and Patch Manager features are perfect for automating command execution and patching on a large scale across thousands of instances.
</details>

---

### Question 14

A company wants to offer pre-approved products/templates to internal teams for self-service provisioning. Which AWS service helps achieve this?

- [ ] a. AWS Service Catalog
- [ ] b. AWS Systems Manager
- [ ] c. AWS CloudFormation
- [ ] d. AWS Control Tower

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS Service Catalog
<br><br>
**Explanation:** **AWS Service Catalog** allows you to create and manage catalogs of IT services that are approved for use on AWS. It enables a "self-service" model where users can provision pre-approved resources without direct access to the underlying infrastructure templates.
</details>

---

### Question 15

A company wants recommendations to reduce costs and improve performance of EC2 instances. Which AWS service provides this insight?

- [ ] a. AWS Trusted Advisor gives general best practices but not detailed EC2 recommendations.
- [ ] b. AWS CloudWatch
- [ ] c. AWS Systems Manager
- [ ] d. AWS Compute Optimizer

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Compute Optimizer
<br><br>
**Explanation:** **AWS Compute Optimizer** is a service that analyzes your EC2 workload utilization and provides actionable recommendations to reduce costs and improve performance by identifying optimal AWS resources.
</details>

---

### Question 16

Your team needs personalized alerts about AWS service events that might affect your resources. Which service provides this?

- [ ] a. AWS CloudTrail
- [ ] b. AWS Trusted Advisor
- [ ] c. AWS Health
- [ ] d. AWS Config

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. AWS Health
<br><br>
**Explanation:** **AWS Health** provides a personalized view of the health of AWS services and resources. It gives you proactive notifications about planned maintenance and real-time alerts about service events that may affect your resources.
</details>

---

### Question 17

Your company needs to track and manage software licenses used on AWS and on-premises. Which service helps manage this?

- [ ] a. AWS Service Catalog
- [ ] b. AWS License Manager
- [ ] c. AWS CloudFormation
- [ ] d. AWS Systems Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS License Manager
<br><br>
**Explanation:** **AWS License Manager** is a service that helps you manage your software licenses from vendors like Microsoft, Oracle, IBM, and SAP across AWS and on-premises environments.
</details>

---

### Question 18

A company wants to run AWS infrastructure on-premises to meet low-latency requirements. Which AWS service should they use?

- [ ] a. AWS CloudFormation
- [ ] b. AWS EC2
- [ ] c. AWS Lambda
- [ ] d. AWS Outposts

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Outposts
<br><br>
**Explanation:** **AWS Outposts** is a service that brings native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility. It's designed for workloads that require low-latency access to on-premises systems.
</details>

---

### Question 19

A team must manage encryption keys and secrets. Which TWO services are relevant, depending on whether they want key management or secret rotation?

- [ ] a. AWS KMS for encryption key management without secret rotation.
- [ ] b. AWS Macie
- [ ] c. AWS Secrets Manager for automatic secret rotation and storage.
- [ ] d. AWS Audit Manager
- [ ] e. AWS CloudFormation

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** a. AWS KMS, c. AWS Secrets Manager
<br><br>
**Explanation:** This is a restated version of question 2. **AWS KMS** is the service for managing encryption keys, while **AWS Secrets Manager** is the service for storing and automatically rotating secrets.
</details>

---

### Question 20

A security team wants a centralized view of security findings across accounts. Which service provides this dashboard?

- [ ] a. AWS Control Tower
- [ ] b. AWS Security Hub
- [ ] c. AWS Systems Manager
- [ ] d. AWS Macie

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Security Hub
<br><br>
**Explanation:** **AWS Security Hub** gives you a comprehensive view of your high-priority security alerts and compliance status across your AWS accounts. It consolidates security findings from various AWS services like GuardDuty, Inspector, and Macie.
</details>

---

### Question 21

A company wants to automatically deploy infrastructure with templates. Which AWS service do they use?

- [ ] a. AWS CloudFormation
- [ ] b. AWS Service Catalog
- [ ] c. AWS Control Tower
- [ ] d. AWS Systems Manager

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS CloudFormation
<br><br>
**Explanation:** **AWS CloudFormation** is an Infrastructure as Code (IaC) service that allows you to define and provision your AWS infrastructure in a declarative template. It automates the entire deployment process.
</details>

---

### Question 22

A company needs to provide user registration, login, and social login (Google/Facebook) for a mobile app. Which AWS service should they use?

- [ ] a. AWS Security Hub
- [ ] b. Amazon Cognito
- [ ] c. AWS Systems Manager
- [ ] d. AWS IAM

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. Amazon Cognito
<br><br>
**Explanation:** **Amazon Cognito** is a service that handles user authentication and authorization for web and mobile applications. It simplifies the process of adding user sign-up, sign-in, and access control, including social identity providers like Google and Facebook.
</details>

---

### Question 23

You need to automate deployment using Chef or Puppet. Which service?

- [ ] a. AWS OpsWorks
- [ ] b. AWS Control Tower
- [ ] c. AWS Systems Manager
- [ ] d. AWS CloudFormation

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS OpsWorks
<br><br>
**Explanation:** **AWS OpsWorks** is the service that manages the Chef and Puppet platforms on AWS, providing automation for configuration management and application deployment.
</details>

---

### Question 24

Run AWS CLI in browser with no local installation. Which service?

- [ ] a. AWS Lambda
- [ ] b. AWS CloudShell
- [ ] c. AWS Systems Manager
- [ ] d. AWS EC2

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS CloudShell
<br><br>
**Explanation:** **AWS CloudShell** provides a browser-based shell that is pre-authenticated with your AWS account credentials, allowing you to run AWS CLI commands without any local setup.
</details>

---

### Question 25

Your company wants recommendations for cost optimization and performance improvements on EC2 instances. Which service provides actionable recommendations?

- [ ] a. AWS Trusted Advisor gives general best practices but not detailed EC2 recommendations.
- [ ] b. AWS Compute Optimizer analyzes your workloads and provides resource optimization recommendations.
- [ ] c. AWS Systems Manager patches instances but does not optimize costs.
- [ ] d. AWS CloudWatch monitors metrics but does not suggest optimizations.

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Compute Optimizer
<br><br>
**Explanation:** **AWS Compute Optimizer** analyzes the historical utilization of your EC2 instances and provides specific recommendations for right-sizing them to save costs and improve performance.
</details>

---

### Question 26

Receive personalized notifications about service events affecting resources. Which service?

- [ ] a. AWS CloudTrail
- [ ] b. AWS Health
- [ ] c. AWS Config
- [ ] d. AWS Trusted Advisor

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Health
<br><br>
**Explanation:** **AWS Health** is the service that provides personalized notifications and a dashboard for issues and scheduled maintenance events affecting your specific AWS resources.
</details>

---

### Question 27

Manage and track software licenses across AWS and on-premises. Which service?

- [ ] a. AWS License Manager
- [ ] b. AWS Systems Manager
- [ ] c. AWS Service Catalog
- [ ] d. AWS CloudFormation

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS License Manager
<br><br>
**Explanation:** **AWS License Manager** helps you track, manage, and enforce your software license agreements across both AWS and your on-premises environments.
</details>

---

### Question 28

Low-latency workloads need AWS infrastructure on-premises. Which service?

- [ ] a. AWS CloudFormation
- [ ] b. AWS EC2
- [ ] c. AWS Lambda
- [ ] d. AWS Outposts

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Outposts
<br><br>
**Explanation:** **AWS Outposts** extends AWS infrastructure and services to your on-premises data center, providing a consistent hybrid experience for workloads that require low-latency access to local systems or data.
</details>

---

### Question 29

Automatically detect sensitive data in S3. Which service?

- [ ] a. AWS CloudHSM
- [ ] b. AWS KMS
- [ ] c. AWS Secrets Manager
- [ ] d. Amazon Macie

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. Amazon Macie
<br><br>
**Explanation:** **Amazon Macie** is a data security service that automatically discovers and classifies sensitive data, such as PII, in your Amazon S3 buckets.
</details>

---

### Question 30

Centralized security alerts for multiple accounts and regions. Which service?

- [ ] a. AWS Config
- [ ] b. AWS Control Tower
- [ ] c. AWS Systems Manager
- [ ] d. AWS Security Hub

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Security Hub
<br><br>
**Explanation:** **AWS Security Hub** aggregates security findings from various AWS services and third-party products into a single, centralized dashboard, giving you a consolidated view of security alerts across all your accounts.
</details>
