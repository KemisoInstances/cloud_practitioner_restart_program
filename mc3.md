# AWS Quiz Questions

This quiz is designed to be self-graded. You can "select" your answers by ticking the boxes. When you are ready to review your responses, click the "Show Correct Answer" dropdown at the end of each question.

---

## Question 1

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
You are planning to deploy a video streaming application with frequently accessed throughput-intensive workloads to your EC2 instance which requires fast, consistent throughput. What EBS volume type should you use to maximize performance as well as cost?

**Select one:**
- [ ] a. Cold HDD
- [ ] b. Provisioned IOPS SSD
- [ ] c. Throughput Optimized HDD
- [ ] d. General Purpose SSD

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Throughput Optimized HDD

**Explanation:**
Throughput Optimized HDD (st1) is designed for frequently accessed, throughput-intensive workloads such as large data sets and data warehouses. It is a good balance of performance and cost efficiency for this use case. Provisioned IOPS SSD (io1/io2) is for mission-critical, high-performance workloads, while General Purpose SSD (gp2/gp3) is for a wide variety of transactional workloads. Cold HDD (sc1) is for infrequently accessed data.
</details>

---

## Question 2

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which service in AWS protects resources from common DDoS attacks in a proactive manner?

**Select one:**
- [ ] a. AWS WAF
- [ ] b. Amazon Inspector
- [ ] c. AWS Shield
- [ ] d. Security groups

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS Shield

**Explanation:**
AWS Shield is a managed DDoS protection service that safeguards applications running on AWS. It provides always-on detection and automatic inline mitigations that minimize application downtime and latency. AWS WAF is a web application firewall that helps protect web applications from common web exploits. Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Security groups act as a virtual firewall for your EC2 instances.
</details>

---

## Question 3

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A retail company needs to run complex analytical queries on petabytes of structured sales data. The solution must support columnar storage, massively parallel query execution, and the ability to integrate with BI tools such as Amazon QuickSight for near real-time insights. Which AWS service is the most suitable for this use case?

**Select one:**
- [ ] a. Amazon S3
- [ ] b. Amazon DynamoDB
- [ ] c. Amazon Aurora
- [ ] d. Amazon Redshift

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Amazon Redshift

**Explanation:**
Amazon Redshift is a fully managed, petabyte-scale data warehouse service. It is optimized for large-scale data analytics and business intelligence, making it the most suitable service for this scenario.
</details>

---

## Question 4

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which of the following is needed to retrieve a list of Amazon EC2 instances using the AWS CLI?

**Select one:**
- [ ] a. Access Keys
- [ ] b. Username and password
- [ ] c. MFA
- [ ] d. EC2 key pairs

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Access Keys

**Explanation:**
To programmatically interact with AWS services using the AWS Command Line Interface (CLI), you need to configure it with an access key ID and a secret access key. These credentials are used to authenticate your requests.
</details>

---

## Question 5

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which of the following AWS well-architected pillars discusses the use of the right computing resources to meet demand levels even as the demand changes and technologies evolve?

**Select one:**
- [ ] a. Cost optimization
- [ ] b. Reliability
- [ ] c. Operational Excellence
- [ ] d. Performance Efficiency

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Performance Efficiency

**Explanation:**
The Performance Efficiency pillar of the Well-Architected Framework focuses on using IT and computing resources efficiently. This includes the selection of the right resource types and sizes based on workload requirements, as well as monitoring and scaling resources to meet demand.
</details>

---

## Question 6

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A Software Engineer is working on a new project for the company. The project entails creating a web application with the PHP framework and releasing it to the AWS Cloud. Given the company’s limited resources and the Software Engineer’s tight deadline, the Software Engineer must devise a plan for quickly deploying the application to AWS while avoiding the time-consuming process of setting up and configuring the infrastructure. Which of the following services will allow the Software Engineer to quickly deploy the application into the AWS Cloud without building or launching the individual resources?

**Select one:**
- [ ] a. Amazon EKS
- [ ] b. Amazon EBS
- [ ] c. AWS Elastic Beanstalk
- [ ] d. Amazon ECS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS Elastic Beanstalk

**Explanation:**
AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. It handles the deployment and management of the underlying infrastructure, including EC2 instances, load balancers, and scaling, allowing developers to focus on their code.
</details>

---

## Question 7

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following are advantages of Cloud Computing? (Select TWO.)

**Select one or more:**
- [ ] a. Trade capital expense for variable expense.
- [ ] b. Achieve lower economies of scale.
- [ ] c. Increase speed and agility.
- [ ] d. Trade variable expense for capital expense.
- [ ] e. Massive discounts for your computers, network devices and other equipment from Amazon online shopping website.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. Trade capital expense for variable expense.
- c. Increase speed and agility.

**Explanation:**
One of the key benefits of cloud computing is the ability to trade upfront capital expenditures (CAPEX) for low, pay-as-you-go variable expenses (OPEX). The cloud also allows for rapid provisioning of resources, which increases speed and agility, accelerating time-to-market.
</details>

---

## Question 8

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A startup is recently migrated its infrastructure to the AWS cloud and wants to ensure that users can access the right resources. Which IAM service is responsible for enforcing privileges and access controls in your AWS environment?

**Select one:**
- [ ] a. IAM User
- [ ] b. IAM Role
- [ ] c. IAM Group
- [ ] d. IAM Policy

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. IAM Policy

**Explanation:**
An IAM policy is a document that formally defines permissions. It is attached to an IAM identity or resource and determines what actions are allowed or denied.
</details>

---

## Question 9

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What service allows you to create alarms that notify you when EC2 CPU Utilization thresholds are breached?

**Select one:**
- [ ] a. AWS Config
- [ ] b. AWS Auto Scaling
- [ ] c. Amazon SNS
- [ ] d. Amazon CloudWatch

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Amazon CloudWatch

**Explanation:**
Amazon CloudWatch is a monitoring service that collects and tracks metrics, logs, and events from your AWS resources and applications. You can use it to set alarms that trigger actions when specific thresholds are breached, such as an EC2 instance's CPU utilization exceeding a certain percentage.
</details>

---

## Question 10

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following actions does not affect costs when using Amazon S3?

**Select one:**
- [ ] a. Moving objects out of your S3 bucket to another bucket
- [ ] b. Making GET requests to your S3 objects
- [ ] c. Data transfer costs for uploading objects into your S3 bucket.
- [ ] d. Choosing S3 Standard IA rather than One Zone IA

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Data transfer costs for uploading objects into your S3 bucket.

**Explanation:**
There are no data transfer costs for uploading objects into an S3 bucket. You are charged for data transfer out, requests made against your objects, and the storage itself, but not for data transfer in.
</details>

---

## Question 11

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
What action can be taken to strengthen the security of an AWS root account in the event of suspected unauthorized usage?

**Select one:**
- [ ] a. Enable CloudTrail to monitor for suspicious logins
- [ ] b. Disable root account credentials and use an IAM user with admin privileges instead
- [ ] c. Configure MFA for your root account
- [ ] d. Change the root account password often

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Configure MFA for your root account

**Explanation:**
Multi-Factor Authentication (MFA) adds an extra layer of security to your AWS account by requiring a second authentication factor in addition to your password. This makes it significantly harder for unauthorized users to gain access, even if they have your password. While the other options are good practices, MFA is the primary way to strengthen the root account's security.
</details>

---

## Question 12

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A company has a customized EC2 instance running in their latest web application. How can they create an exact copy of this instance in another region?

**Select one:**
- [ ] a. Create a golden AMI of the instance and copy it to the other region.
- [ ] b. Create backups of all EBS volumes and copy them to another region.
- [ ] c. There is no way to do this in AWS. You will have to perform the transfer manually.
- [ ] d. Create a load balancer with an auto scaling group that is linked between two regions. Scale up to have another instance running in the other region.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Create a golden AMI of the instance and copy it to the other region.

**Explanation:**
An Amazon Machine Image (AMI) provides the information required to launch an instance, including the operating system, a template for the root volume, launch permissions, and block device mappings. You can create an AMI from a running EC2 instance and then copy it to other regions, allowing you to launch an identical instance there.
</details>

---

## Question 13

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Your web servers are showing relatively poor performance in delivering content. How can you improve its performance and cost efficiency?

**Select one:**
- [ ] a. Use HTTP protocol instead to decrease the time consumed in decrypting content
- [ ] b. Request AWS to use faster network cables for your servers
- [ ] c. Apply a caching mechanism that stores frequently accessed content
- [ ] d. Run more web servers to distribute the workload

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Apply a caching mechanism that stores frequently accessed content

**Explanation:**
Using a caching mechanism, such as Amazon CloudFront, can significantly improve web server performance and reduce costs. By caching frequently accessed content at edge locations closer to users, it reduces the load on the web servers and decreases latency, leading to better performance.
</details>

---

## Question 14

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A customer is choosing the best AWS support-plan which includes a designated Technical Account Manager. Which of the following should they choose?

**Select one:**
- [ ] a. Developer
- [ ] b. Business
- [ ] c. Enterprise On-Ramp
- [ ] d. Enterprise

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Enterprise

**Explanation:**
The Enterprise support plan is the only one that includes a designated Technical Account Manager (TAM) to provide proactive guidance and assistance for your AWS environment.
</details>

---

## Question 15

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following is an example of having a highly available application in AWS?

**Select one:**
- [ ] a. Running spot instances for your EC2 workloads
- [ ] b. Running your RDS instance with multi-AZ enabled
- [ ] c. Running CloudFront for the static website in your S3 bucket
- [ ] d. Using Amazon SQS to decouple messages between a sender and a receiver

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Running your RDS instance with multi-AZ enabled

**Explanation:**
Multi-AZ deployment for Amazon RDS creates a standby replica of your database in a different Availability Zone. This provides high availability and automatic failover in case of a zone outage, making your application highly available. The other options address cost savings, performance, or decoupling, but not high availability in this manner.
</details>

---

## Question 16

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
When is using Amazon RDS a better choice than using a local database?

**Select one:**
- [ ] a. When you want to offload administration responsibilities from yourself
- [ ] b. When you need a fast network connection to your local web servers
- [ ] c. When you need full control of your SQL database
- [ ] d. When you need a free Enterprise license for your Enterprise databases

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. When you want to offload administration responsibilities from yourself

**Explanation:**
Amazon RDS is a managed service, which means AWS handles the patching, backups, and maintenance of the database software. This offloads the administrative burden from the customer, allowing them to focus on the application.
</details>

---

## Question 17

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following instances is it better to use IAM roles rather than IAM users? (Select TWO.)

**Select one or more:**
- [ ] a. When you need an administrator to handle the AWS account for you
- [ ] b. When you have outside entities that need to perform specific actions in your AWS account
- [ ] c. When you want to provide AWS services permissions to do certain actions
- [ ] d. When you need a GUI to interact with your AWS environment
- [ ] e. If you have employees who will constantly need access to your AWS resources

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- b. When you have outside entities that need to perform specific actions in your AWS account
- c. When you want to provide AWS services permissions to do certain actions

**Explanation:**
IAM roles are a secure way to delegate permissions without sharing long-term access keys. They are temporary and can be assumed by a trusted entity. This is ideal for giving permissions to other AWS services (like an EC2 instance needing S3 access) or to external parties or services.
</details>

---

## Question 18

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company has game servers hosted in the US East (N. Virginia) Region. However, players from Europe and Asia experience high latency, impacting their gaming experience. How can the company reduce latency and improve the gaming experience for players in these regions?

**Select one:**
- [ ] a. Implement Amazon CloudFront as a content delivery solution.
- [ ] b. Utilize AWS Direct Connect to establish dedicated network connectivity.
- [ ] c. Use autoscaling for the game servers in the US East (N. Virginia) Region.
- [ ] d. Deploy additional game servers in Europe and Asia

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Deploy additional game servers in Europe and Asia

**Explanation:**
The best way to reduce latency for a real-time application like gaming is to deploy the servers closer to the end users. Deploying additional servers in AWS Regions in Europe and Asia would directly address the high-latency problem for players in those locations.
</details>

---

## Question 19

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
You have an Amazon Linux EC2 instance running for an hour and thirty minutes. How will AWS bill you in terms of usage?

**Select one:**
- [ ] a. You will only be billed for an hour according to the hourly billing rule
- [ ] b. You will be billed for an hour and thirty minutes according to the per-second billing rule
- [ ] c. You will be billed for one hour and thirty minutes according to the hourly billing rule
- [ ] d. You will be billed for an hour and twenty-nine minutes according to the per second billing rule

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. You will be billed for an hour and thirty minutes according to the per-second billing rule

**Explanation:**
Most Linux-based EC2 instances are billed per second, with a one-minute minimum charge. An hour and thirty minutes (90 minutes or 5400 seconds) would be billed for the exact duration of use. The one-hour minimum charge is for older EC2 instances.
</details>

---

## Question 20

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A startup is migrating its on-premises infrastructure to AWS. They want full control over the operating system, installed software, and network configurations while AWS manages the physical servers, storage, and networking. They decide to launch Amazon EC2 instances to meet these requirements. Which cloud computing model does this represent?

**Select one:**
- [ ] a. DBaaS
- [ ] b. SaaS
- [ ] c. PaaS
- [ ] d. IaaS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. IaaS

**Explanation:**
Infrastructure as a Service (IaaS) provides the fundamental building blocks of cloud computing, such as virtual machines (EC2 instances), storage, and networking. The customer has control over the operating system and applications, while the cloud provider manages the underlying infrastructure.
</details>

---

## Question 21

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following is true regarding the AWS Cost and Usage report? (Select TWO.)

**Select one or more:**
- [ ] a. Provides you with granular data about your AWS costs and usage
- [ ] b. Helps you visualize, understand, and manage your AWS costs and usage over time via an intuitive interface that enables you to quickly create custom reports
- [ ] c. Provides you a dashboard that lets you view the status of your month-to-date AWS expenditure and provides access to a number of other cost management products that can help you dig deeper into your AWS costs and usage
- [ ] d. Allows you to load your cost and usage information into Amazon Athena, Amazon Redshift, and AWS QuickSight
- [ ] e. Lets you set custom cost and usage budgets that alert you when those thresholds are exceeded

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. Provides you with granular data about your AWS costs and usage
- d. Allows you to load your cost and usage information into Amazon Athena, Amazon Redshift, and AWS QuickSight

**Explanation:**
The AWS Cost and Usage Report (CUR) provides the most granular data available about your costs and usage. You can load this report into other AWS services like Amazon Athena, Amazon Redshift, or Amazon QuickSight to analyze your spending. Options b, c, and e describe AWS Cost Explorer, the Billing Dashboard, and AWS Budgets, respectively.
</details>

---

## Question 22

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
An e-commerce company is considering migrating its website to the AWS Cloud to improve its scalability and reduce costs. Which statements explain the business value of migration to the AWS Cloud? (Select TWO.)

**Select one or more:**
- [ ] a. Companies that migrate to the AWS Cloud reduce IT costs related to infrastructure, freeing the budget for reinvestment in other areas.
- [ ] b. Companies migrating to AWS Cloud can benefit from improving service level agreements (SLAs) while reducing risk and unplanned outages.
- [ ] c. Applications are modernized because migration to the AWS Cloud requires companies to rearchitect and rewrite all enterprise applications.
- [ ] d. Migrating to AWS Cloud offers the e-commerce company access to advanced analytics and machine learning capabilities.
- [ ] e. The migration of enterprise applications to the AWS Cloud makes these applications automatically available on mobile devices.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. Companies that migrate to the AWS Cloud reduce IT costs related to infrastructure, freeing the budget for reinvestment in other areas.
- b. Companies migrating to AWS Cloud can benefit from improving service level agreements (SLAs) while reducing risk and unplanned outages.

**Explanation:**
Migrating to the cloud allows companies to trade capital expenses for variable costs, reducing the overall IT costs. AWS also provides high availability and reliability, which leads to better SLAs and reduced risk of unplanned outages compared to on-premises solutions. The other options are not always true; for example, rearchitecting applications is an option, not a requirement.
</details>

---

## Question 23

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company stores sensitive customer data in Amazon S3 and wants to automatically detect personally identifiable information (PII), monitor access patterns, and receive alerts about suspicious activity to help meet compliance requirements. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon GuardDuty
- [ ] b. AWS CloudTrail
- [ ] c. Amazon Detective
- [ ] d. AWS Macie

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS Macie

**Explanation:**
Amazon Macie is a data security and data privacy service that uses machine learning and pattern matching to discover and protect your sensitive data in AWS, such as PII in S3 buckets. The other services are for threat detection (GuardDuty), API activity logging (CloudTrail), and investigation (Detective).
</details>

---

## Question 24

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following is a serverless compute service of AWS?

**Select one:**
- [ ] a. Amazon DynamoDB
- [ ] b. Amazon Athena
- [ ] c. Amazon Aurora
- [ ] d. AWS Lambda

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS Lambda

**Explanation:**
AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers. It automatically scales and manages the underlying infrastructure. The other services listed are a NoSQL database (DynamoDB), a query service (Athena), and a relational database (Aurora).
</details>

---

## Question 25

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A customer has recently experienced an SQL injection attack on their web application’s database hosted in EC2. They submitted a complaint ticket to AWS. What should be the response from AWS?

**Select one:**
- [ ] a. AWS should reiterate that the customer is responsible for the security of their applications in the Cloud.
- [ ] b. AWS should secure their infrastructure better to reduce these kinds of incidents.
- [ ] c. AWS and the customer should contact a third party auditor to verify the incident.
- [ ] d. AWS should not be liable for the damages since the customer should have properly patched the EC2 instance.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. AWS should reiterate that the customer is responsible for the security of their applications in the Cloud.

**Explanation:**
This scenario is an example of the AWS Shared Responsibility Model. AWS is responsible for the security OF the cloud (the infrastructure), while the customer is responsible for the security IN the cloud (the data, applications, and operating systems running on EC2). An SQL injection attack is a vulnerability in the customer's application, for which they are responsible.
</details>

---

## Question 26

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company is planning to use AWS Cloud to augment the resources of their on-premises data center to better serve their customers around the world. How does a company benefit from using AWS?

**Select one:**
- [ ] a. Benefit from massive discounts from the Amazon.com shopping website
- [ ] b. Replace low variable costs with upfront capital infrastructure expenses
- [ ] c. Benefit from massive economies of scale
- [ ] d. Replace high variable costs with upfront capital infrastructure expenses

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Benefit from massive economies of scale

**Explanation:**
By aggregating usage from millions of customers, AWS can achieve massive economies of scale, which translates to lower prices for everyone. The cost savings from this is a major benefit of using the cloud.
</details>

---

## Question 27

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following do you need to programmatically interact with your AWS environment? (Select TWO.)

**Select one or more:**
- [ ] a. Access keys
- [ ] b. AWS SDK
- [ ] c. AWS Lambda
- [ ] d. AWS Management Console
- [ ] e. Account username and password

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. Access keys
- b. AWS SDK

**Explanation:**
Access keys are a set of credentials (Access key ID and Secret access key) used to sign programmatic requests to AWS. The AWS SDK (Software Development Kit) provides APIs in various programming languages to interact with AWS services. These two components work together to allow programmatic access.
</details>

---

## Question 28

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which AWS service will allow you to serve your dynamic web content to users globally?

**Select one:**
- [ ] a. Amazon CloudFront
- [ ] b. Amazon Route53
- [ ] c. AWS Elastic Load Balancer
- [ ] d. Amazon S3

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Amazon CloudFront

**Explanation:**
Amazon CloudFront is a content delivery network (CDN) that accelerates the delivery of both static and dynamic web content to users worldwide by caching content at edge locations.
</details>

---

## Question 29

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A customer is using Amazon S3 to store sprites of game characters. When players retrieve these sprites, they are temporarily stored on the player’s computer. The sprites are currently stored in the S3 Standard storage class. Which of the following options would you recommend to optimize storage costs?

**Select one:**
- [ ] a. Add a lifecycle policy to move sprites to S3 Glacier Flexible Retrieval after the customer uploads them.
- [ ] b. Have the customer compress the sprites to reduce storage consumption.
- [ ] c. Add a lifecycle policy to move sprites to S3 Standard – Infrequent Access after the customer uploads them.
- [ ] d. Have the customer directly upload the sprites to S3 Standard – Infrequent Access.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Have the customer compress the sprites to reduce storage consumption.

**Explanation:**
Compressing the sprites before uploading them to S3 directly reduces the total storage volume, thereby lowering the monthly storage cost. A lifecycle policy to move objects to Infrequent Access is also a good option, but compressing the files first would lead to an immediate and direct reduction in the storage consumed, which is the best first step for cost optimization. Glacier is not suitable as the data needs to be retrieved frequently.
</details>

---

## Question 30

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A media company needs to store massive amounts of unstructured data, such as videos and images, that must be highly durable, cost-efficient, and automatically scalable. They also want easy integration with other AWS analytics and machine learning services. Which AWS service is the most suitable choice?

**Select one:**
- [ ] a. AWS Storage Gateway
- [ ] b. Amazon EFS
- [ ] c. Amazon S3
- [ ] d. Amazon EBS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Amazon S3

**Explanation:**
Amazon Simple Storage Service (S3) is an object storage service that offers scalability, data availability, security, and performance. It is ideal for storing unstructured data, such as videos and images, and is highly durable and scalable. It also has deep integration with a wide range of other AWS services.
</details>

---

## Question 31

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
As an AWS customer, what offering do you naturally inherit from AWS after you sign up?

**Select one:**
- [ ] a. All the best practices of AWS policies, architecture, and operational processes built to satisfy your requirements
- [ ] b. All the responsibilities in enforcing security and compliance policies of your organization
- [ ] c. All the hardware and software that you provision in the AWS cloud
- [ ] d. All the data you store in and retrieve from AWS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. All the best practices of AWS policies, architecture, and operational processes built to satisfy your requirements

**Explanation:**
When you use AWS, you inherit the security and compliance controls that AWS operates as part of the shared responsibility model. This includes the best practices for physical security, network infrastructure, and foundational services.
</details>

---

## Question 32

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following does AWS automatically handle for you? (Select TWO.)

**Select one or more:**
- [ ] a. Provide web application firewall protection to your public endpoints.
- [ ] b. Makes sure your data is safely kept and replicated between AZs
- [ ] c. Introduce updates and patches to EC2 hypervisors
- [ ] d. Introduce updates and patches to EC2 guest operating systems
- [ ] e. Secure AWS data centers from environmental hazards

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- c. Introduce updates and patches to EC2 hypervisors
- e. Secure AWS data centers from environmental hazards

**Explanation:**
In the shared responsibility model, AWS is responsible for the security OF the cloud. This includes the underlying infrastructure, such as the hypervisor and the physical security of the data centers. The customer is responsible for security IN the cloud, such as patching their EC2 guest OS and providing their own web application firewalls.
</details>

---

## Question 33

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
What does AWS do when a storage device reaches the end of its lifespan?

**Select one:**
- [ ] a. AWS simply wipes the device and disposes it
- [ ] b. AWS archives the device in case customers request their data again
- [ ] c. AWS follows a strict decommissioning process as described in compliance procedures
- [ ] d. AWS wipes the drives and sends it back to the manufacturer to procure a new one

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS follows a strict decommissioning process as described in compliance procedures

**Explanation:**
AWS follows a strict decommissioning process that ensures customer data is completely destroyed when a storage device reaches the end of its life. This process is documented in their security and compliance whitepapers to ensure data integrity and security.
</details>

---

## Question 34

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
You are planning to create point-in-time backups of your Amazon EBS volumes. Which of the following are correct statements? (Select TWO.)

**Select one or more:**
- [ ] a. You can create point-in-time backups through EBS snapshots
- [ ] b. You can take EBS backups by creating Amazon Machine Images (AMIs)
- [ ] c. Instances will have to be stopped first to start the EBS backup
- [ ] d. EBS backups are stored durably in Amazon S3
- [ ] e. Backing up the same EBS volume will create a new back up of the whole volume

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. You can create point-in-time backups through EBS snapshots
- d. EBS backups are stored durably in Amazon S3

**Explanation:**
Amazon EBS snapshots are point-in-time backups of your EBS volumes. These snapshots are stored in Amazon S3, leveraging its high durability. Snapshots are incremental, meaning only the blocks that have changed since the last snapshot are stored, which is not what option e says.
</details>

---

## Question 35

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
An employee is asking for access to your S3 buckets. What should be the level of access that you should provide to him?

**Select one:**
- [ ] a. Give him administrator access levels
- [ ] b. Give him S3 full access
- [ ] c. Give him read-only access
- [ ] d. Ask what type of access he requires and only provide him those permissions

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Ask what type of access he requires and only provide him those permissions

**Explanation:**
This is an example of the principle of least privilege. You should only grant the minimum permissions required for an identity to perform a task. By asking the employee what access they need, you can provide a more secure, granular policy.
</details>

---

## Question 36

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company used to experience delays in developing new services due to the time it took to procure and set up on-premises servers. They recently migrated their infrastructure to the AWS Cloud. This change has allowed them to spin up testing environments in just days, accelerating the time to market for their services.

Which of the following AWS Cloud benefits is showcased in this particular scenario?

**Select one:**
- [ ] a. Deploy globally in minutes
- [ ] b. Elasticity
- [ ] c. Cost savings
- [ ] d. Agility

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Agility

**Explanation:**
Cloud computing provides agility by giving you the ability to provision resources quickly and easily, without the need for manual procurement and setup. This accelerates the development and deployment of new services, leading to a faster time-to-market.
</details>

---

## Question 37

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A Software Engineer is having trouble migrating and configuring a licensed application on an EC2 instance. Which of the following options would you recommend to quickly get the applications up and running in AWS?

**Select one:**
- [ ] a. Setup a VPN connection from her local network to her AWS VPC, which essentially means that her work is now running in the Cloud.
- [ ] b. Use AWS Application Discovery Service to create an exact copy of the application in EC2.
- [ ] c. Create a Docker image of the application and launch Docker in the EC2 instances.
- [ ] d. Try to look for an AMI in the AWS Marketplace that provides a similar setup to her application stack.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Try to look for an AMI in the AWS Marketplace that provides a similar setup to her application stack.

**Explanation:**
The AWS Marketplace is a curated digital catalog that makes it easy for customers to find, buy, and deploy third-party software and services that run on AWS. Many pre-configured AMIs are available that can save time and effort in setting up complex applications.
</details>

---

## Question 38

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Availability Zones are physically separated by a meaningful distance from any other AZ, although all are within 100 km or 60 miles of each other. What is the primary reason why Availability Zones are set up the way they are now?

**Select one:**
- [ ] a. To maximize area coverage in a Region
- [ ] b. To achieve better network connectivity to users in the location
- [ ] c. To keep them as far apart from each other in case of a disaster
- [ ] d. Price of the land is cheaper in those locations

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. To keep them as far apart from each other in case of a disaster

**Explanation:**
Availability Zones are designed to be independent of each other in a region. They are physically separated to protect against a single disaster, like a flood or earthquake, impacting multiple zones, but are close enough to have low-latency network connections between them.
</details>

---

## Question 39

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What is a good disaster recovery precaution if you are launching a dynamic web application with mission-critical workloads that need to be available all the time?

**Select one:**
- [ ] a. Launch applications in two different AWS Regions to prevent downtime during regional outages.
- [ ] b. Always keep backup data stored in two different S3 buckets.
- [ ] c. Run applications in the cloud but keep all data locally.
- [ ] d. Launch applications in two different AZs to prevent downtime during regional outages.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Launch applications in two different AWS Regions to prevent downtime during regional outages.

**Explanation:**
To protect against a regional outage, you must deploy your application across multiple AWS Regions. Deploying across multiple Availability Zones protects against a single AZ outage but not a full regional one.
</details>

---

## Question 40

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A security team wants to record all API calls made in an AWS account, including who made the call, when, and from which IP address, to help with auditing and compliance. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon CloudWatch
- [ ] b. AWS Config
- [ ] c. AWS CloudTrail
- [ ] d. Amazon S3

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS CloudTrail

**Explanation:**
AWS CloudTrail is a service that records all API calls made in your AWS account and delivers them to an S3 bucket. This provides a complete audit trail of all actions performed, which is essential for security analysis, auditing, and compliance.
</details>

---

## Question 41

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
What is the lowest support plan that allows an unlimited number of technical support cases to be opened?

**Select one:**
- [ ] a. Business
- [ ] b. Basic
- [ ] c. Developer
- [ ] d. Enterprise

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Business

**Explanation:**
The Business support plan is the lowest tier that provides unlimited technical support cases. Both the Basic and Developer plans have limitations on the number of support cases you can open.
</details>

---

## Question 42

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
How is expense shifted when moving from traditional servers to the Cloud?

**Select one:**
- [ ] a. Operational expense is traded for variable expense
- [ ] b. Capital expense is traded for variable expense
- [ ] c. Variable expense is traded for capital expense
- [ ] d. Capital expense is traded for operational expense

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Capital expense is traded for variable expense

**Explanation:**
In a traditional on-premises environment, buying hardware is an upfront capital expense (CAPEX). In the cloud, you pay for what you use, which becomes a variable operational expense (OPEX). This is a core benefit of cloud computing.
</details>

---

## Question 43

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A number of servers in your on-premises data center have been collecting dust over the past few years. What is the benefit of moving to the Cloud in this case?

**Select one:**
- [ ] a. AWS has automated services for you
- [ ] b. Physical servers are managed and maintained by AWS for you
- [ ] c. The ability to provision resources only when you need them
- [ ] d. The ability to pay for only what you use

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. The ability to pay for only what you use

**Explanation:**
The benefit of a pay-as-you-go model is that you only pay for the resources you consume. If you have on-premises servers that are idle, you are still paying for their purchase and maintenance. In the cloud, you can turn off idle resources and stop paying for them.
</details>

---

## Question 44

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company wants to control which users and services can access specific AWS resources and enforce least-privilege permissions across their account. Which AWS service should they use?

**Select one:**
- [ ] a. AWS CloudTrail
- [ ] b. Amazon SNS
- [ ] c. AWS IAM
- [ ] d. AWS KMS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS IAM

**Explanation:**
AWS Identity and Access Management (IAM) is the service that enables you to securely control access to AWS services and resources for your users. With IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.
</details>

---

## Question 45

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A customer needs to identify the IAM user who terminated their production EC2 instance in AWS. Which service should they use in this situation?

**Select one:**
- [ ] a. AWS Systems Manager
- [ ] b. AWS CloudTrail
- [ ] c. Amazon AppStream 2.0
- [ ] d. Amazon CloudWatch

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS CloudTrail

**Explanation:**
AWS CloudTrail logs all API calls made in your account, including who made the call, when, and from where. You can use CloudTrail logs to identify the specific IAM user who took an action, such as terminating an EC2 instance.
</details>

---

## Question 46

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which payment plan will give you the largest discount when purchasing EC2 reserved instances?

**Select one:**
- [ ] a. Partial upfront payment for a 3-year term purchase
- [ ] b. Partial upfront payment for a 1-year term purchase
- [ ] c. All upfront payment for a 3-year term purchase
- [ ] d. All upfront payment for a 1-year term purchase

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. All upfront payment for a 3-year term purchase

**Explanation:**
The largest discount for Reserved Instances is offered for the longest commitment (3-year term) with the highest upfront payment option (All upfront).
</details>

---

## Question 47

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A company needs to quickly and securely transfer large amounts of on-premises data to Amazon S3 with minimal management overhead. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon S3 Glacier
- [ ] b. AWS Transfer Family
- [ ] c. AWS Snowball
- [ ] d. AWS DataSync

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS DataSync

**Explanation:**
AWS DataSync is a data transfer service that simplifies, automates, and accelerates moving data between on-premises storage systems and AWS storage services. It handles the transfer process securely and efficiently with minimal management.
</details>

---

## Question 48

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A high-performance computing application requires ultra-low latency storage directly attached to an EC2 instance. The data does not need to persist after the instance is stopped or terminated. Which AWS storage option is the most suitable?

**Select one:**
- [ ] a. Instance Store
- [ ] b. EBS Throughput Optimized HDD
- [ ] c. EFS
- [ ] d. EBS Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Instance Store

**Explanation:**
An Instance Store provides temporary block-level storage for an EC2 instance. The data on an instance store persists only for the life of the instance, but it offers very low latency and high I/O performance, making it ideal for temporary, high-performance needs.
</details>

---

## Question 49

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A startup plans to host a simple WordPress site on AWS. However, due to its developers’ limited knowledge on AWS, they seek the easiest method of deploying the site. Which AWS service should the startup use?

**Select one:**
- [ ] a. AWS Glue
- [ ] b. Amazon Elastic Beanstalk
- [ ] c. Amazon Elastic Compute Cloud (EC2)
- [ ] d. Amazon Lightsail

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Amazon Lightsail

**Explanation:**
Amazon Lightsail is an easy-to-use cloud platform that offers pre-configured blueprints for applications like WordPress. It's designed for simple workloads and provides a very straightforward interface for deploying and managing services.
</details>

---

## Question 50

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What is the right arrangement of the AWS Global Infrastructure components according to their geographical coverage area size, in descending order?

**Select one:**
- [ ] a. Regions, Availability Zones, Edge Locations
- [ ] b. Regions, Edge Locations, Availability Zones
- [ ] c. Availability Zones, Edge Locations, Regions
- [ ] d. Edge Locations, Availability Zones, Regions

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Regions, Availability Zones, Edge Locations

**Explanation:**
An AWS Region is a physical location with multiple Availability Zones. An Availability Zone is one or more discrete data centers with redundant power, networking, and connectivity. Edge Locations are data centers owned by AWS that deliver content with low latency to end users. A Region is the largest, followed by Availability Zones, and then Edge Locations are the most widespread but cover the smallest geographical area individually.
</details>

---

## Question 51

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company wants to launch AWS resources in a private, logically isolated network where they can control subnets, IP ranges, and routing. Which AWS service provides this capability?

**Select one:**
- [ ] a. Amazon VPC
- [ ] b. Internet gateway
- [ ] c. Amazon EC
- [ ] d. AWS Elastic Beanstalk

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Amazon VPC

**Explanation:**
Amazon Virtual Private Cloud (VPC) lets you provision a private, logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define.
</details>

---

## Question 52

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company needs to simplify the migration of its databases from an on-premises server to AWS. Which service fits best for this purpose?

**Select one:**
- [ ] a. AWS Application Migration Service
- [ ] b. AWS Database Migration Service
- [ ] c. AWS DataSync
- [ ] d. AWS Snowball

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS Database Migration Service

**Explanation:**
AWS Database Migration Service (AWS DMS) is a service that helps you migrate databases to AWS quickly and securely. You can migrate databases with minimal downtime to the applications that rely on them.
</details>

---

## Question 53

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A Cloud Architect in a large e-commerce company manages the company’s AWS environment. One day, the Cloud Architect was notified that one of their EC2 instances had been running non-stop for over 30 days, and its usage costs had skyrocketed. The Cloud Architect needs to identify the root cause of the issue and find a way to reduce the usage costs of the instance. Which of the following AWS services can help the Cloud Architect identify the issue and check if their running resources conform to AWS best practices?

**Select one:**
- [ ] a. Amazon CloudWatch
- [ ] b. AWS IAM
- [ ] c. AWS Trusted Advisor
- [ ] d. AWS Config

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS Trusted Advisor

**Explanation:**
AWS Trusted Advisor is an online tool that inspects your AWS environment and provides recommendations for cost optimization, performance, security, fault tolerance, and service limits. It can identify resources that are underutilized, which would directly help with the cost issue described.
</details>

---

## Question 54

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which AWS service enables you to log, continuously monitor, and retain account activity related to actions across your AWS infrastructure?

**Select one:**
- [ ] a. Amazon CloudWatch
- [ ] b. AWS Trusted Advisor
- [ ] c. AWS CloudTrail
- [ ] d. AWS Config

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. AWS CloudTrail

**Explanation:**
AWS CloudTrail logs all API calls made in your account. This provides a record of actions taken by users and services, allowing for continuous monitoring and auditing of account activity.
</details>

---

## Question 55

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which AWS service helps you centrally manage VPN connections across multiple AWS accounts and regions?

**Select one:**
- [ ] a. AWS Site-to-Site VPN
- [ ] b. AWS Transit Gateway
- [ ] c. AWS VPN Manager
- [ ] d. AWS Direct Connect

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS Transit Gateway

**Explanation:**
AWS Transit Gateway connects your VPCs and on-premises networks to a single gateway. This simplifies your network architecture by eliminating the need for complex VPC peering relationships and multiple VPNs.
</details>

---

## Question 56

**Partially correct**
**Mark 0.50 out of 1.00**

**Question text**
A company recently migrated its e-commerce application to AWS in order to handle a surge in customer traffic. The application is hosted on Amazon EC2 instances and uses Amazon RDS to manage the product catalogue and inventory. Which of the following options provides disaster recovery solutions for Amazon EC2? (Select TWO).

**Select one or more:**
- [ ] a. AWS Security Hub
- [ ] b. Amazon EC2 AMI
- [ ] c. Amazon EBS Snapshots
- [ ] d. AWS Health Dashboard
- [ ] e. Amazon RDS Snapshots

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- b. Amazon EC2 AMI
- c. Amazon EBS Snapshots

**Explanation:**
Amazon EC2 AMIs and Amazon EBS snapshots are both key components of a disaster recovery plan for EC2 instances. An AMI provides a complete image of the EC2 instance, while EBS snapshots are point-in-time backups of the attached volumes. These can be used to restore an instance and its data in a different region or Availability Zone in the event of an outage.
</details>

---

## Question 57

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company is using Amazon S3 to store various types of documents in a single bucket, and different teams frequently access the stored objects. If the document is accidentally overwritten or deleted, the data must be recoverable. Which of the following S3 features should they use?

**Select one:**
- [ ] a. S3 Event Notifications
- [ ] b. S3 Versioning
- [ ] c. S3 Glacier Vault Lock
- [ ] d. S3 Lifecycle

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. S3 Versioning

**Explanation:**
S3 Versioning allows you to keep multiple versions of an object in the same bucket. If an object is accidentally overwritten or deleted, you can restore a previous version.
</details>

---

## Question 58

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following AWS services are considered global services, meaning they are not restricted to a single region and can operate across multiple regions? (Select TWO.)

**Select one or more:**
- [ ] a. AWS WAF
- [ ] b. AWS CloudTrail
- [ ] c. Amazon Route53
- [ ] d. AWS Lambda
- [ ] e. Amazon VPC

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- b. AWS CloudTrail
- c. Amazon Route53

**Explanation:**
Amazon Route 53 and AWS CloudTrail are global services. Route 53 manages DNS records globally, and CloudTrail can log API calls from all regions into a single log file. AWS WAF can be deployed at a regional level or globally via CloudFront. AWS Lambda and Amazon VPC are regional services.
</details>

---

## Question 59

**Partially correct**
**Mark 0.50 out of 1.00**

**Question text**
What are the benefits of using Amazon DynamoDB as your database? (Select TWO.)

**Select one or more:**
- [ ] a. Database size scales automatically so you won’t have to worry about capacity
- [ ] b. You can perform very complex queries and joins without deterioration in performance
- [ ] c. You can store different kinds of unstructured data that would normally not be suitable for relational databases
- [ ] d. DynamoDB offers 11 9’s in terms of durability, according to the SLA
- [ ] e. DynamoDB is self-healing, which means your data is scanned for errors and is repaired continuously

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- a. Database size scales automatically so you won’t have to worry about capacity
- d. DynamoDB offers 11 9’s in terms of durability, according to the SLA

**Explanation:**
Amazon DynamoDB is a fully managed NoSQL database that automatically scales to handle any amount of traffic and storage. It is also designed for 99.999999999% durability (11 nines).
</details>

---

## Question 60

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A developer is using Amazon DynamoDB and wants to improve read performance for frequently accessed items by adding an in-memory caching layer that is fully managed and integrates seamlessly with DynamoDB. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon ElastiCache
- [ ] b. Amazon DynamoDB Accelerator (DAX)
- [ ] c. Amazon Redshift
- [ ] d. Amazon Neptune

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Amazon DynamoDB Accelerator (DAX)

**Explanation:**
Amazon DynamoDB Accelerator (DAX) is a fully managed, highly available, in-memory cache for DynamoDB. It provides microsecond read performance for your DynamoDB tables, which is the perfect solution for this scenario.
</details>

---

## Question 61

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which cloud computing advantage describes how you can easily deploy your application in multiple AWS regions with just a few clicks?

**Select one:**
- [ ] a. Stop guessing capacity
- [ ] b. Benefit from massive economies of scale
- [ ] c. Stop spending money running and maintaining data centres
- [ ] d. Go global in minutes

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Go global in minutes

**Explanation:**
The ability to quickly and easily deploy your applications in multiple AWS regions is a key benefit of cloud computing. This allows you to serve a global customer base with low latency and high availability.
</details>

---

## Question 62

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company wants to visualize and analyze data stored in Amazon S3 and Amazon Redshift without managing servers, and allow business users to create interactive dashboards. Which AWS service should they use?

**Select one:**
- [ ] a. AWS Glue
- [ ] b. Amazon QuickSight
- [ ] c. Amazon Athena
- [ ] d. Amazon EMR

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Amazon QuickSight

**Explanation:**
Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence service built for the cloud. It can connect directly to data in Amazon S3 and Amazon Redshift and enables users to create dashboards without a managed server.
</details>

---

## Question 63

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A leading mobile game company has a mission-critical server that is currently down in AWS. The Systems Administrator needs to bring it back up within 15 minutes for service continuity. Which of the following support plans will allow the Administrator to contact technical support to immediately resolve the issue?

**Select one:**
- [ ] a. Enterprise On-Ramp
- [ ] b. Developer
- [ ] c. Business
- [ ] d. Enterprise

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Enterprise

**Explanation:**
For mission-critical systems and the fastest response times, the Enterprise Support plan is required. It provides a 15-minute response time for critical system down cases.
</details>

---

## Question 64

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following purchase options offers the most significant discount compared to On-Demand instance pricing to process steady-state workloads that will continuously be running for a year and also provide capacity reservation?

**Select one:**
- [ ] a. Convertible Reserved Instance
- [ ] b. Standard Reserved Instance
- [ ] c. Savings Plans
- [ ] d. Dedicated Instance

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Standard Reserved Instance

**Explanation:**
Standard Reserved Instances provide the highest discount among the EC2 Reserved Instance options for a specific instance type and are designed for steady-state workloads.
</details>

---

## Question 65

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A company wants to send automated notifications to multiple subscribers whenever a new object is uploaded to an S3 bucket. The notifications should be delivered via email, SMS, or HTTP endpoints. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon EventBridge
- [ ] b. Amazon SNS
- [ ] c. AWS Lambda
- [ ] d. Amazon SQS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Amazon SNS

**Explanation:**
Amazon Simple Notification Service (SNS) is a fully managed pub/sub messaging service. It allows you to send messages to a large number of subscribers via various protocols, including email, SMS, and HTTP endpoints, whenever an event occurs, such as a new object being uploaded to an S3 bucket.
</details>
