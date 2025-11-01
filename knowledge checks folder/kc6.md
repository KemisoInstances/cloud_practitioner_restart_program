# AWS Security Quiz

This is a static quiz designed for GitHub. The checkboxes are for formatting purposes and are not interactive. To see the correct answers and explanations, click the "Show Answer & Explanation" text below each question.

---

### Question 1

Which two resources can AWS WAF protect? (Choose 2)

- [ ] a. Application Load Balancers
- [ ] b. Amazon CloudFront distributions
- [ ] c. EC2 Instances directly
- [ ] d. IAM Roles

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** a. Application Load Balancers, b. Amazon CloudFront distributions
<br><br>
**Explanation:** AWS WAF is a web application firewall that helps protect your web applications or APIs against common web exploits. It can be associated with resources that distribute traffic to your application, such as an Application Load Balancer and an Amazon CloudFront distribution. It cannot protect EC2 instances or IAM roles directly.
</details>

---

### Question 2

A system administrator wants to visualise EC2 CPU usage in near real time. Which CloudWatch component is best suited?

- [ ] a. CloudWatch Logs
- [ ] b. CloudWatch Dashboard
- [ ] c. CloudWatch Alarms
- [ ] d. CloudTrail

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. CloudWatch Dashboard
<br><br>
**Explanation:** CloudWatch Dashboards are customizable home pages in the CloudWatch console that you can use to monitor your resources in a single view. They are specifically designed for visualizing metrics, such as EC2 CPU usage, in real time. CloudWatch Logs are for log data, CloudWatch Alarms are for triggering actions based on metrics, and CloudTrail is for API activity logging.
</details>

---

### Question 3

Which two AWS services require explicit approval for penetration testing? (Choose 2)

- [ ] a. Amazon Route53
- [ ] b. AWS Lambda
- [ ] c. Amazon RDS
- [ ] d. Amazon CloudFront

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** c. Amazon RDS, d. Amazon CloudFront
<br><br>
**Explanation:** AWS generally allows penetration testing against certain services without prior approval, but some services like Amazon CloudFront and Amazon RDS require explicit permission. This is to prevent disruption to shared infrastructure.
</details>

---

### Question 4

Which two types of metrics can CloudWatch collect? (Choose 2)

- [ ] a. Billing metrics
- [ ] b. IAM policies
- [ ] c. Custom metrics from applications
- [ ] d. Security group rules

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** a. Billing metrics, c. Custom metrics from applications
<br><br>
**Explanation:** CloudWatch can collect standard metrics from AWS services and also allows you to publish your own custom metrics from your applications. It does not collect IAM policies or security group rules.
</details>

---

### Question 5

A global company wants a single service to deploy WAF rules, Shield protections, and Network Firewall policies across multiple AWS accounts. Which service is most suitable?

- [ ] a. AWS Firewall Manager
- [ ] b. Amazon Inspector
- [ ] c. AWS CloudWatch
- [ ] d. AWS Trusted Advisor

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS Firewall Manager
<br><br>
**Explanation:** AWS Firewall Manager is a security management service that centrally configures and manages firewall rules across your accounts and applications in AWS. It simplifies the administration of WAF, AWS Shield, and Network Firewall.
</details>

---

### Question 6

A security analyst needs to detect unusual API activity and potential compromised IAM credentials. Which service should they use?

- [ ] a. AWS Shield
- [ ] b. AWS GuardDuty
- [ ] c. AWS WAF
- [ ] d. AWS Inspector

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS GuardDuty
<br><br>
**Explanation:** AWS GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. It analyzes CloudTrail management and S3 data events, as well as VPC Flow Logs, for threats such as unusual API calls or compromised credentials.
</details>

---

### Question 7

An e-commerce company wants to block SQL injection and cross-site scripting attacks on its website. Which service should they use?

- [ ] a. AWS Inspector
- [ ] b. AWS Shield
- [ ] c. AWS WAF
- [ ] d. AWS GuardDuty

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. AWS WAF
<br><br>
**Explanation:** AWS WAF is designed to protect web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources. This includes attacks like SQL injection and cross-site scripting.
</details>

---

### Question 8

A company wants to apply centralised firewall policies across multiple AWS accounts. Which service should they use?

- [ ] a. AWS Firewall Manager
- [ ] b. AWS WAF
- [ ] c. AWS Network Firewall
- [ ] d. Amazon GuardDuty

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. AWS Firewall Manager
<br><br>
**Explanation:** AWS Firewall Manager is a centralized service that helps you manage and audit firewall rules across multiple accounts and resources. It allows for the application of consistent security policies across an entire organization.
</details>

---

### Question 9

Trusted Advisor checks can help with which of the following? (Choose 2)

- [ ] a. DDoS Mitigation
- [ ] b. Identity and Access Management
- [ ] c. Cost Optimisation
- [ ] d. Real-time malware detection

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** b. Identity and Access Management, c. Cost Optimisation
<br><br>
**Explanation:** Trusted Advisor provides recommendations for cost optimization, performance, security, fault tolerance, and service limits. This includes checks related to IAM, as well as suggestions for saving costs.
</details>

---

### Question 10

Which AWS service provides fine-grained network traffic filtering at the VPC level?

- [ ] a. AWS WAF
- [ ] b. AWS Network Firewall
- [ ] c. AWS Shield
- [ ] d. CloudTrail

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Network Firewall
<br><br>
**Explanation:** AWS Network Firewall is a managed service that makes it easy to deploy and manage a network firewall at the VPC level. It provides deep packet inspection and fine-grained control over network traffic.
</details>

---

### Question 11

Which AWS service records all API calls made in your AWS account, including from the Management Console, CLI, and SDKs?

- [ ] a. Trusted Advisor
- [ ] b. Amazon CloudWatch
- [ ] c. Amazon CloudTrail
- [ ] d. Amazon GuardDuty

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. Amazon CloudTrail
<br><br>
**Explanation:** AWS CloudTrail is a service that enables governance, compliance, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure, including API calls made via the Management Console, CLI, and SDKs.
</details>

---

### Question 12

A security team wants to identify who deleted an S3 bucket. Which service should they check?

- [ ] a. AWS Shield
- [ ] b. AWS CloudTrail
- [ ] c. AWS Inspector
- [ ] d. Amazon GuardDuty

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS CloudTrail
<br><br>
**Explanation:** CloudTrail logs all API actions, including the deletion of an S3 bucket. It provides a history of API calls for an account, including the identity of the API caller.
</details>

---

### Question 13

Which IAM entity can only contain permissions but cannot directly make requests to AWS services?

- [ ] a. IAM Role
- [ ] b. IAM Group
- [ ] c. IAM Policy
- [ ] d. IAM User

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. IAM Policy
<br><br>
**Explanation:** An IAM policy is a document that defines permissions. It is an entity that you attach to an IAM user, group, or role. It does not have an identity itself and cannot directly make requests.
</details>

---

### Question 14

A developer needs temporary access keys to interact with AWS services for a few hours. Which IAM feature should be used?

- [ ] a. IAM Users
- [ ] b. IAM Roles
- [ ] c. IAM Groups
- [ ] d. IAM Policies

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. IAM Roles
<br><br>
**Explanation:** IAM roles are designed for temporary access. An IAM role is an IAM identity that you can create in your account that has specific permissions. It is similar to an IAM user, but it does not have a password or associated access keys. Instead, a user or AWS service can assume the role and get temporary credentials.
</details>

---

### Question 15

A company wants to test the resilience of their AWS applications by simulating cyberattacks. What is this process called?

- [ ] a. Penetration Testing
- [ ] b. Intrusion Prevention
- [ ] c. Security Patching
- [ ] d. GuardDuty Analysis

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. Penetration Testing
<br><br>
**Explanation:** Penetration testing is the practice of testing a computer system, network or web application to find security vulnerabilities that an attacker could exploit. It is a simulated cyberattack against your own systems.
</details>

---

### Question 16

A company wants to automatically restart an EC2 instance when CPU utilisation is below 5% for 30 minutes. Which CloudWatch feature should they use?

- [ ] a. CloudWatch Dashboards
- [ ] b. CloudWatch Alarms
- [ ] c. CloudTrail Events
- [ ] d. CloudWatch Logs

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. CloudWatch Alarms
<br><br>
**Explanation:** CloudWatch Alarms are used to automatically initiate actions based on a defined metric threshold. In this case, an alarm would be set on the EC2 CPU utilization metric to trigger a "reboot" action if the value drops below 5% for 30 minutes.
</details>

---

### Question 17

A compliance team wants to ensure EC2 instances are following security best practices. Which service provides automated security assessments?

- [ ] a. Amazon CloudWatch
- [ ] b. Amazon GuardDuty
- [ ] c. Amazon Inspector
- [ ] d. AWS Shield

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** c. Amazon Inspector
<br><br>
**Explanation:** Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It automatically assesses applications for vulnerabilities or deviations from best practices.
</details>

---

### Question 18

Which two data sources does GuardDuty analyse to detect threats? (Choose 2)

- [ ] a. CloudTrail Events
- [ ] b. CloudWatch Dashboards
- [ ] c. VPC Flow Logs
- [ ] d. IAM Policies

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** a. CloudTrail Events, c. VPC Flow Logs
<br><br>
**Explanation:** AWS GuardDuty analyzes continuous streams of VPC Flow Logs and AWS CloudTrail management events, along with DNS logs, to detect potential threats.
</details>

---

### Question 19

What is the main difference between AWS Shield Standard and Shield Advanced?

- [ ] a. Shield Advanced replaces GuardDuty
- [ ] b. Shield Advanced provides 24/7 DDoS response team access
- [ ] c. Shield Standard is paid, Shield Advanced is free
- [ ] d. Shield Advanced includes IAM support

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. Shield Advanced provides 24/7 DDoS response team access
<br><br>
**Explanation:** AWS Shield Standard is automatically included for free with all AWS accounts and provides basic DDoS protection. AWS Shield Advanced is a paid service that provides enhanced protection, including a 24/7 access to the AWS DDoS Response Team (DRT), and other features like cost protection.
</details>

---

### Question 20

Which AWS service provides best practice recommendations across cost, security, performance, and fault tolerance?

- [ ] a. Amazon CloudTrail
- [ ] b. Amazon GuardDuty
- [ ] c. Amazon Inspector
- [ ] d. AWS Trusted Advisor

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** d. AWS Trusted Advisor
<br><br>
**Explanation:** AWS Trusted Advisor is an online tool that acts as your custom cloud expert. It provides real-time guidance to help you provision your resources following AWS best practices across five categories: cost optimization, security, fault tolerance, performance, and service limits.
</details>

---

### Question 21

A company hosting a website on AWS wants automatic protection against DDoS attacks. Which service provides this?

- [ ] a. AWS Inspector
- [ ] b. AWS Shield Standard
- [ ] c. AWS GuardDuty
- [ ] d. AWS WAF

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** b. AWS Shield Standard
<br><br>
**Explanation:** AWS Shield Standard is automatically included with all AWS accounts at no additional cost and provides automatic protection against the most common, frequently occurring network and transport layer DDoS attacks.
</details>

---

### Question 22

An organisation wants to perform penetration testing on its AWS resources. What is the correct step before conducting the test?

- [ ] a. Contact AWS Support for authorisation
- [ ] b. Deploy GuardDuty
- [ ] c. Disable CloudTrail
- [ ] d. Run Trusted Advisor checks

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. Contact AWS Support for authorisation
<br><br>
**Explanation:** While AWS allows penetration testing on certain services, it is a best practice and often a requirement to contact AWS Support and get authorization before beginning any penetration testing activities to ensure you do not violate the AWS Acceptable Use Policy.
</details>

---

### Question 23

Which AWS service automatically scans EC2 instances for software vulnerabilities and missing patches?

- [ ] a. Amazon Inspector
- [ ] b. AWS Trusted Advisor
- [ ] c. AWS WAF
- [ ] d. AWS Shield

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answer:** a. Amazon Inspector
<br><br>
**Explanation:** Amazon Inspector is a service that performs automated security assessments of applications for vulnerabilities and deviations from best practices, including scanning for software vulnerabilities and missing patches on EC2 instances.
</details>

---

### Question 24

Which two are key benefits of CloudTrail? (Choose 2)

- [ ] a. Real-time malware scanning
- [ ] b. Protecting against DDoS attacks
- [ ] c. Compliance and auditing
- [ ] d. Monitoring API activity

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** c. Compliance and auditing, d. Monitoring API activity
<br><br>
**Explanation:** CloudTrail's primary function is to provide a detailed record of all API calls and account activity, which is crucial for security analysis, change tracking, and achieving compliance and auditing requirements.
</details>

---

### Question 25

Your organisation wants to ensure developers follow least privilege principles. Which two IAM features help achieve this? (Choose 2)

- [ ] a. IAM Access Analyzer
- [ ] b. IAM Policies
- [ ] c. Amazon GuardDuty
- [ ] d. AWS Shield

<details>
<summary>Show Answer & Explanation</summary>
<br>
**Correct Answers:** a. IAM Access Analyzer, b. IAM Policies
<br><br>
**Explanation:** The principle of least privilege is a security best practice that involves granting only the minimum permissions required for a user or service to perform its task. IAM Policies define these permissions, and IAM Access Analyzer helps you identify resource policies that grant public or cross-account access.
</details>
