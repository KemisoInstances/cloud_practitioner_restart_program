# AWS Quiz Questions

This quiz is designed to be self-graded. You can "select" your answers by ticking the boxes. When you are ready to review your responses, click the "Show Correct Answer" dropdown at the end of each question.

---

## Question 1

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which AWS service allows you to create a dedicated network connection from your on-premises environment to AWS?

**Select one:**
- [ ] a. Transit Gateway
- [ ] b. NAT Gateway
- [ ] c. VPC Peering
- [ ] d. AWS Direct Connect

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS Direct Connect
</details>

---

## Question 2

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
What is the default limit for the number of VPCs per AWS region?

**Select one:**
- [ ] a. 2
- [ ] b. 20
- [ ] c. 5
- [ ] d. 10

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. 5
</details>

---

## Question 3

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What is a VPC Peering Connection?

**Select one:**
- [ ] a. A connection to the internet
- [ ] b. A networking connection between two VPCs
- [ ] c. A VPN connection between AWS and on-premises
- [ ] d. A way to monitor network traffic

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. A networking connection between two VPCs
</details>

---

## Question 4

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
What happens if a subnet does NOT have a route to an internet gateway?

**Select one:**
- [ ] a. It is assigned a public IP
- [ ] b. It is deleted automatically
- [ ] c. It cannot be used for EC2 instances
- [ ] d. It becomes a private subnet

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. It becomes a private subnet
</details>

---

## Question 5

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which component acts as a firewall for controlling traffic in and out of your VPC subnet?

**Select one:**
- [ ] a. Route Table
- [ ] b. Network ACL
- [ ] c. Internet Gateway
- [ ] d. NAT Gateway

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Network ACL
</details>

---

## Question 6

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which AWS networking service enables you to interconnect multiple VPCs and on-premises networks through a single gateway?

**Select one:**
- [ ] a. Virtual Private Gateway
- [ ] b. AWS Transit Gateway
- [ ] c. Internet Gateway
- [ ] d. AWS Direct Connect

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS Transit Gateway
</details>

---

## Question 7

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What must you do to enable instances in a private subnet to access the internet?

**Select one:**
- [ ] a. Assign a public IP address
- [ ] b. Attach an Internet Gateway to the subnet
- [ ] c. Use a NAT Gateway or NAT Instance
- [ ] d. Create a VPC Peering connection

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Use a NAT Gateway or NAT Instance
</details>

---

## Question 8

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which of the following is required to allow internet access to resources in a public subnet?

**Select one:**
- [ ] a. Security Group
- [ ] b. VPC Peering
- [ ] c. NAT Gateway
- [ ] d. Internet Gateway

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Internet Gateway
</details>

---

## Question 9

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
You are launching a global e-commerce website with customers in Africa, Europe, and Asia. During testing, users in Asia reported slow loading times for product images and videos hosted in an S3 bucket in the US East (N. Virginia) region. Which AWS service can you use to cache and deliver content with low latency and high transfer speeds across the globe?

**Select one:**
- [ ] a. AWS Global Accelerator
- [ ] b. AWS Direct Connect
- [ ] c. Amazon CloudFront
- [ ] d. Amazon Route 53

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Amazon CloudFront
</details>

---

## Question 10

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A startup wants its domain name www.awsrestart.com to point to an application running on an EC2 instance. The app must also support health checks so that if the instance fails, traffic can be redirected to a backup server. Which AWS service provides this functionality?

**Select one:**
- [ ] a. Amazon VPC
- [ ] b. Amazon Route 53
- [ ] c. Amazon CloudFront
- [ ] d. AWS Transit Gateway

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Amazon Route 53
</details>

---

## Question 11

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A company has multiple VPCs across different AWS accounts (for development, testing, and production). They need a central way to connect and manage communication between all these VPCs without creating complex peering relationships. Which AWS service simplifies this setup?

**Select one:**
- [ ] a. AWS Direct Connect
- [ ] b. Amazon Route 53
- [ ] c. Amazon CloudFront
- [ ] d. AWS Transit Gateway

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS Transit Gateway
</details>

---

## Question 12

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
An online learning platform is running an application in two AWS Regions. They want to test a new version of the app by sending 20% of traffic to Region A and 80% of traffic to Region B. Which Route 53 routing policy should they use?

**Select one:**
- [ ] a. Failover routing
- [ ] b. Weighted routing
- [ ] c. Simple routing
- [ ] d. Latency-based routing

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Weighted routing
</details>

---

## Question 13

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which of the following allows you to privately connect your VPC to supported AWS services and VPC endpoint services powered by PrivateLink?

**Select one:**
- [ ] a. Gateway Endpoint
- [ ] b. NAT Gateway
- [ ] c. Internet Gateway
- [ ] d. Interface Endpoint

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Interface Endpoint
</details>

---

## Question 14

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
What is the main purpose of a route table in a VPC?

**Select one:**
- [ ] a. Control inbound traffic
- [ ] b. Determine where network traffic is directed
- [ ] c. Encrypt VPC communications
- [ ] d. Control outbound traffic

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Determine where network traffic is directed
</details>

---

## Question 15

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A government agency wants to connect its on-premises data center to AWS securely over the public internet. The solution must be encrypted and provide a quick way to establish hybrid connectivity without needing a dedicated line. Which AWS service should they use?

**Select one:**
- [ ] a. Amazon VPC
- [ ] b. AWS Site-to-Site VPN
- [ ] c. VPC Flow Logs
- [ ] d. Amazon Connect

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS Site-to-Site VPN
</details>

---

## Question 16

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
A security team needs to monitor and troubleshoot the IP traffic going into and out of their VPC. Which AWS service provides this visibility by capturing network flow information?

**Select one:**
- [ ] a. Amazon VPC Flow Logs
- [ ] b. Amazon CloudFront
- [ ] c. AWS Site-to-Site VPN
- [ ] d. Amazon Connect

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Amazon VPC Flow Logs
</details>

---

## Question 17

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
A company wants to enable its customer support team to handle inbound and outbound phone calls using AWS. Which service should they use?

**Select one:**
- [ ] a. AWS Site-to-Site VPN
- [ ] b. Amazon Connect
- [ ] c. AWS Direct Connect
- [ ] d. VPC Flow Logs

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Amazon Connect
</details>

---

## Question 18

**Incorrect**
**Mark 0.00 out of 1.00**

**Question text**
Which AWS service enables secure connectivity between your on-premises network and your VPC?

**Select one:**
- [ ] a. VPC Peering
- [ ] b. NAT Gateway
- [ ] c. Virtual Private Gateway
- [ ] d. Internet Gateway

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Virtual Private Gateway
</details>

---

## Question 19

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which of the following is true regarding Elastic Load Balancing?

**Select one:**
- [ ] a. It translates domain names (such as www.praesignis.com) into numeric IP addresses (such as 192.0.2.1) that Amazon EC2 instances use to connect to each other.
- [ ] b. It distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, in multiple Availability Zones.
- [ ] c. It is a virtual server that allows you to run your applications in the AWS Cloud.
- [ ] d. It automatically increases or decreases the number of instances as the demand of your application changes.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. It distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, in multiple Availability Zones.
</details>

---

## Question 20

**Correct**
**Mark 1.00 out of 1.00**

**Question text**
Which statement about Security Groups is true?

**Select one:**
- [ ] a. They operate at the instance level
- [ ] b. They allow only outbound traffic
- [ ] c. They operate at the subnet level
- [ ] d. They are attached to route tables

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. They operate at the instance level
</details>
