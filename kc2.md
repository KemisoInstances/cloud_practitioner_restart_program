# AWS Quiz on EC2, Compute, and Storage

This quiz is for self-study. You can click on the checkboxes to select your answers. To see the correct answer and an explanation, expand the "Show Correct Answer" dropdown.

---

### Question 1: EC2 Purchasing Options
Which of the following Amazon EC2 instance purchasing options can help you address compliance requirements and reduce costs by allowing you to use your existing server-bound software licenses?

- [ ] a. Dedicated Instance
- [ ] b. Dedicated Host
- [ ] c. On-Demand Instance
- [ ] d. Reserved Instance

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Dedicated Host
  
  **Explanation:** A **Dedicated Host** is a physical server with EC2 instance capacity dedicated for your exclusive use. This allows you to meet strict compliance and regulatory requirements while using existing server-bound software licenses, which are often tied to physical cores, sockets, or a server.
</details>

---

### Question 2: AWS Services
A startup plans to host a simple WordPress site on AWS. However, due to its developers’ limited knowledge on AWS, they seek the easiest method of deploying the site. Which AWS service should the startup use?

- [ ] a. Amazon Elastic Beanstalk
- [ ] b. Amazon Lightsail
- [ ] c. Amazon Elastic Compute Cloud (EC2)
- [ ] d. AWS Glue

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Amazon Lightsail
  
  **Explanation:** **Amazon Lightsail** is the easiest way to get started with AWS for simple workloads like a WordPress site. It provides a simple-to-use virtual private server (VPS) with pre-configured plans and a single dashboard for managing instances, databases, and networking.
</details>

---

### Question 3: EC2 Instance Information
A customer needs to retrieve the instance ID, instance profile permissions, and kernel information of their EC2 instance. Where can they find this info?

- [ ] a. Instance user data
- [ ] b. Amazon Machine Image
- [ ] c. Instance metadata
- [ ] d. Resource tag

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. Instance metadata
  
  **Explanation:** **Instance metadata** is data about your running EC2 instance. It can be used to configure or manage the running instance and includes information such as the instance ID, public IP address, security groups, and IAM role details. You can access it from the instance itself.
</details>

---

### Question 4: EC2 Purchasing Options
What is the best type of instance purchasing option to choose if you will run an EC2 instance for 3 months to perform a job that is uninterruptible?

- [ ] a. Reserved Instance
- [ ] b. Spot Instance
- [ ] c. On-Demand Instance
- [ ] d. Dedicated Instance

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. On-Demand Instance
  
  **Explanation:** An **On-Demand Instance** is the best choice for this scenario. It is a pay-as-you-go option with no long-term commitment. Reserved Instances require a 1-year or 3-year commitment, and Spot Instances can be interrupted, making them unsuitable for an uninterruptible job.
</details>

---

### Question 5: Container Orchestration
Your team is planning to containerize a microservices-based application. You need to manage the container orchestration, including scheduling, networking, and scaling, but without managing the underlying server infrastructure. Which AWS compute option should you choose?

- [ ] a. Amazon EC2 with Docker installed manually
- [ ] b. AWS Fargate with Amazon ECS
- [ ] c. AWS Lambda with Docker images
- [ ] d. Amazon Lightsail Containers

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. AWS Fargate with Amazon ECS
  
  **Explanation:** **AWS Fargate** is a serverless compute engine for containers that works with both Amazon ECS and Amazon EKS. It allows you to run containers without managing servers or clusters. You simply define your application's resource requirements, and Fargate handles the scaling and management of the underlying infrastructure.
</details>

---

### Question 6: Elastic Load Balancing
Which of the following is true regarding Elastic Load Balancing?

- [ ] a. It distributes traffic across multiple targets in multiple AZs
- [ ] b. It translates domain names into IP addresses
- [ ] c. It runs applications in the cloud
- [ ] d. It automatically scales instances

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** a. It distributes traffic across multiple targets in multiple AZs
  
  **Explanation:** **Elastic Load Balancing (ELB)** automatically distributes incoming application traffic across multiple targets, such as EC2 instances, in multiple Availability Zones. This increases the availability and fault tolerance of your applications.
</details>

---

### Question 7: EC2 Reserved Instances
What are the valid contract lengths for EC2 Reserved Instances? (Select TWO)

- [ ] a. 5 years
- [ ] b. 4 years
- [ ] c. 2 years
- [ ] d. 3 years
- [ ] e. 1 year

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** d. 3 years and e. 1 year
  
  **Explanation:** EC2 Reserved Instances are purchased for a 1-year or 3-year term. They provide a significant discount compared to On-Demand pricing in exchange for a commitment to use a specific instance type.
</details>

---

### Question 8: Container Services
Which service is used to store and manage Docker container images in AWS?

- [ ] a. Amazon ECR
- [ ] b. Amazon ECS
- [ ] c. Amazon EFS
- [ ] d. AWS Lambda

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** a. Amazon ECR
  
  **Explanation:** **Amazon Elastic Container Registry (ECR)** is a fully managed Docker container registry that makes it easy to store, manage, and deploy your Docker container images. It integrates with other services like Amazon ECS.
</details>

---

### Question 9: Serverless Compute
You're building an analytics tool that will only run when new data files are uploaded to an S3 bucket. The job runs a Python script and usually finishes within 2 minutes. The team prefers to avoid managing infrastructure or provisioning compute manually. Which compute service best fits this use case?

- [ ] a. AWS Batch
- [ ] b. AWS Elastic Beanstalk
- [ ] c. Amazon EC2
- [ ] d. AWS Lambda

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** d. AWS Lambda
  
  **Explanation:** **AWS Lambda** is a serverless compute service that runs code in response to events, such as an object being uploaded to an S3 bucket. It automatically manages the underlying compute resources, allowing you to focus on your code. This is a perfect fit for event-driven, short-duration tasks.
</details>

---

### Question 10: Container Services
Which of the following services allows storing Docker images and orchestrating Docker containers in a simple and cost-effective manner? (Select TWO.)

- [ ] a. AWS Batch
- [ ] b. AWS Lambda
- [ ] c. Amazon Elastic Container Registry (Amazon ECR)
- [ ] d. AWS CodeBuild
- [ ] e. Amazon Elastic Container Service (Amazon ECS)

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** c. Amazon Elastic Container Registry (Amazon ECR) and e. Amazon Elastic Container Service (Amazon ECS)
  
  **Explanation:** **Amazon ECR** is the service used to store and manage Docker images. **Amazon ECS** is the container orchestration service that allows you to run, stop, and manage Docker containers on a cluster of EC2 instances or using AWS Fargate.
</details>

---

### Question 11: High Availability
What is High Availability primarily designed to achieve?

- [ ] a. Reduce development time
- [ ] b. Keep systems online during failures
- [ ] c. Prevent traffic spikes
- [ ] d. Increase compute power

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Keep systems online during failures
  
  **Explanation:** **High Availability** is a design principle focused on ensuring that a system or application remains operational and accessible to users even in the event of component failures, outages, or maintenance. It is often achieved by deploying resources across multiple Availability Zones.
</details>

---

### Question 12: Storage
Which AWS storage service offers faster disk read and write performance and provides temporary block-level storage for your instance?

- [ ] a. EBS Provisioned IOPS SSD
- [ ] b. Instance Store
- [ ] c. EFS
- [ ] d. EBS Throughput Optimized HDD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Instance Store
  
  **Explanation:** The **Instance Store** provides temporary, block-level storage for your EC2 instance. It is physically attached to the host computer and offers very high disk I/O performance, making it ideal for temporary data such as caches, buffers, or scratch data.
</details>

---

### Question 13: Container Orchestration
Which of the following AWS services is responsible for managing container orchestration?

- [ ] a. Amazon ECS
- [ ] b. AWS Lambda
- [ ] c. Amazon ECR
- [ ] d. Amazon S3

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** a. Amazon ECS
  
  **Explanation:** **Amazon Elastic Container Service (ECS)** is a fully managed container orchestration service. It handles the deployment, management, and scaling of containerized applications. While Amazon ECR stores the container images, ECS is the service that orchestrates their execution.
</details>

---

### Question 14: Auto Scaling
What is the main benefit of using Auto Scaling with your application?

- [ ] a. It stores backup data
- [ ] b. It adjusts capacity automatically based on demand
- [ ] c. It replaces EC2 instances with newer versions
- [ ] d. It increases instance speed

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. It adjusts capacity automatically based on demand
  
  **Explanation:** The main benefit of **Auto Scaling** is its ability to automatically add or remove EC2 instances in response to changing application demand. This ensures your application has enough capacity to handle traffic spikes and reduces costs by not running instances when they are not needed.
</details>

---

### Question 15: High Availability
What is the purpose of a Load Balancer in a highly available architecture?

- [ ] a. To convert application code into containers
- [ ] b. To auto-provision EC2 instances
- [ ] c. To route traffic across multiple healthy instances
- [ ] d. To back up data automatically

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. To route traffic across multiple healthy instances
  
  **Explanation:** A **Load Balancer** distributes incoming application traffic across a group of healthy instances. By constantly monitoring the health of the instances, it ensures that traffic is only sent to instances that are operational, thus increasing the fault tolerance of the application.
</details>

---

### Question 16: Cloud Design Principles
Which of the following cloud design principles supports growth in users, traffic, or data size with no drop-in performance?

- [ ] a. Decouple your components
- [ ] b. Design for failure
- [ ] c. Go Serverless to reduce compute footprint
- [ ] d. Scalability

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** d. Scalability
  
  **Explanation:** **Scalability** is the ability of a system to increase its capacity to handle a growing workload. In the cloud, this is achieved by adding or removing resources (like EC2 instances) as demand changes, ensuring that performance remains consistent as traffic or data size increases.
</details>

---

### Question 17: Storage
Which AWS storage service offers temporary block-level storage with high performance?

- [ ] a. EFS
- [ ] b. Instance Store
- [ ] c. EBS Provisioned IOPS SSD
- [ ] d. EBS Throughput Optimized HDD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Instance Store
  
  **Explanation:** The **Instance Store** provides high-performance, temporary block storage that is physically attached to the host machine of an EC2 instance. Data on an Instance Store is lost when the instance is stopped or terminated.
</details>

---

### Question 18: Deployment
Which of the following services will allow the Software Engineer to quickly deploy the application into the AWS Cloud without building or launching the individual resources?

- [ ] a. Amazon EBS
- [ ] b. Amazon EKS
- [ ] c. AWS Elastic Beanstalk
- [ ] d. Amazon ECS

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. AWS Elastic Beanstalk
  
  **Explanation:** **AWS Elastic Beanstalk** is an easy-to-use service for deploying and scaling web applications and services. You upload your code, and Elastic Beanstalk automatically handles the deployment, from capacity provisioning and load balancing to auto-scaling and application health monitoring.
</details>

---

### Question 19: Auto Scaling
What AWS service can automatically increase or decrease EC2 instances based on demand?

- [ ] a. CloudFormation
- [ ] b. IAM
- [ ] c. Auto Scaling
- [ ] d. Route 53

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. Auto Scaling
  
  **Explanation:** **Auto Scaling** is the AWS service that monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. It ensures that you have the right number of EC2 instances available to handle traffic.
</details>

---

### Question 20: Database Services
There is a requirement to launch a new database in AWS where the customer assumes the responsibility and management of the guest operating system, including updates and security patches. Which of the following services should the customer use?

- [ ] a. Amazon DocumentDB
- [ ] b. Amazon EC2
- [ ] c. Amazon Aurora
- [ ] d. Amazon DynamoDB

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. Amazon EC2
  
  **Explanation:** When you use a database on an **Amazon EC2** instance, you are responsible for managing the operating system, database software, patching, and backups. This is in contrast to managed database services like Amazon Aurora, DynamoDB, and DocumentDB, where AWS handles the underlying infrastructure and OS management.
</details>

---

### Question 21: EC2 Purchasing Options
Which Amazon EC2 instance purchasing option allows you to take advantage of unused EC2 capacity in the AWS Cloud and provides up to a 90% discount compared to On-Demand prices?

- [ ] a. Standard Reserved Instance
- [ ] b. Convertible Reserved Instance
- [ ] c. Dedicated Host
- [ ] d. Spot Instance

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** d. Spot Instance
  
  **Explanation:** **Spot Instances** allow you to bid on unused EC2 capacity, offering a significant discount (up to 90%) off the On-Demand price. The tradeoff is that these instances can be terminated by AWS with a two-minute warning if the capacity is needed for On-Demand users.
</details>

---

### Question 22: Auto Scaling
Which AWS service allows your EC2 compute capacity to automatically scale based on the incoming traffic?

- [ ] a. Amazon Lightsail
- [ ] b. AWS Auto Scaling
- [ ] c. Amazon Macie
- [ ] d. AWS CloudTrail

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** b. AWS Auto Scaling
  
  **Explanation:** **AWS Auto Scaling** automatically adjusts your EC2 capacity to handle fluctuating traffic. You define scaling policies, and the service manages the launching and terminating of instances to match the demand.
</details>

---

### Question 23: EBS Volumes
What type of EBS volume is recommended for most workloads and is also usable as a boot volume?

- [ ] a. Throughput Optimized HDD
- [ ] b. Provisioned IOPS SSD
- [ ] c. General Purpose SSD
- [ ] d. Cold HDD

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** c. General Purpose SSD
  
  **Explanation:** **General Purpose SSD (gp2/gp3)** is the default and recommended EBS volume type for most workloads. It balances price and performance, making it suitable for a wide range of applications, including as a boot volume.
</details>

---

### Question 24: Serverless Containers
Which AWS service runs containers without managing servers?

- [ ] a. Amazon EKS
- [ ] b. ECS with EC2
- [ ] c. AWS Fargate
- [ ] d. AWS Lambda

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** c. AWS Fargate
  
  **Explanation:** **AWS Fargate** is a serverless compute engine for containers. It allows you to run containers without having to provision, manage, or scale the underlying virtual machines. This is in contrast to Amazon EKS or ECS with EC2, where you must manage the EC2 instances.
</details>

---

### Question 25: Security
What service acts as a firewall for your EC2 instances?

- [ ] a. Security Group
- [ ] b. Elastic Network Interface
- [ ] c. VPC
- [ ] d. Network ACL

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** a. Security Group
  
  **Explanation:** A **Security Group** acts as a virtual firewall for your EC2 instances. It controls inbound and outbound traffic at the instance level, allowing you to specify rules that permit or deny traffic based on protocol, port, and source/destination IP.
</details>
