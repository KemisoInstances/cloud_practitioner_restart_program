# AWS Cloud Practitioner Quiz

This quiz is designed to be self-graded. You can "select" your answers by ticking the boxes. When you are ready to review your responses, click the "Show Correct Answer" dropdown at the end of each question.

---

### Question 1: Well-Architected Framework
Which of the following are pillars of the AWS Well-Architected Framework? (Select TWO.)

- [ ] a. Agility
- [ ] b. High Availability
- [ ] c. Performance Efficiency
- [ ] d. Sustainability
- [ ] e. Scalability

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- c. Performance Efficiency
- d. Sustainability

**Explanation:** The AWS Well-Architected Framework is a set of best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. The six pillars are Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability. Agility, High Availability, and Scalability are key benefits of cloud computing, but they are not formal pillars of the framework itself.
</details>

---

### Question 2: AWS Support Plans
A leading mobile game company has a mission-critical server that is currently down in AWS. The Systems Administrator needs to bring it back up within 15 minutes for service continuity. Which of the following support plans will allow the Administrator to contact technical support to immediately resolve the issue?

- [ ] a. Developer
- [ ] b. Business
- [ ] c. Enterprise On-Ramp
- [ ] d. Enterprise

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Enterprise

**Explanation:** The Enterprise Support plan is the only plan that offers a guaranteed response time of 15 minutes or less for business-critical system down issues. The Business plan has a 1-hour response time for production system down issues, while the Developer plan has a 12-hour response time.
</details>

---

### Question 3: Global Infrastructure
What is the right arrangement of the AWS Global Infrastructure components according to their geographical coverage area size, in descending order?

- [ ] a. Availability Zones, Edge Locations, Regions
- [ ] b. Regions, Availability Zones, Edge Locations
- [ ] c. Edge Locations, Availability Zones, Regions
- [ ] d. Regions, Edge Locations, Availability Zones

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. Regions, Availability Zones, Edge Locations

**Explanation:** An AWS **Region** is a physical location in the world with multiple, isolated Availability Zones. An **Availability Zone** is one or more discrete data centers within a region, and **Edge Locations** are data centers used by Amazon CloudFront to cache content closer to end-users for lower latency.
</details>

---

### Question 4: Support Plans
A small team has been using the Developer Support Plan for minor queries. Now they’re moving mission-critical systems to AWS and want proper technical help, including someone they can contact directly. Which support plan should they switch to?

- [ ] a. Stick with Developer and get help from a partner instead
- [ ] b. Move to Enterprise On-Ramp
- [ ] c. Upgrade to Business Support
- [ ] d. Just rely on documentation and online forums

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. Upgrade to Business Support

**Explanation:** The Business Support plan is the minimum plan that provides 24/7 access to technical support via phone, email, and chat for production workloads, which is what the team needs for their mission-critical systems. The Enterprise On-Ramp plan provides access to a pool of Technical Account Managers, but the Business plan is the most cost-effective solution that fulfills the team's immediate needs for dedicated technical help.
</details>

---

### Question 5: Global Infrastructure Components
Which statement below is correct regarding the components of the AWS Global Infrastructure?

- [ ] a. An Availability Zone contains multiple AWS Regions.
- [ ] b. An Availability Zone contains edge locations.
- [ ] c. An AWS Region contains multiple Availability Zones.
- [ ] d. An edge location contains multiple AWS Regions.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. An AWS Region contains multiple Availability Zones.

**Explanation:** AWS regions are geographically isolated and consist of at least two or more Availability Zones. This design provides high availability and fault tolerance. 
</details>

---

### Question 6: High Availability
A tech startup is running their app in the Cape Town region. They want to make sure the app stays up and running during AWS maintenance or outages. What’s the best thing they can do?

- [ ] a. Use one strong instance in a single zone
- [ ] b. Install AWS Outposts in their office
- [ ] c. Copy the app to different regions
- [ ] d. Spread it across multiple Availability Zones

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:**
- d. Spread it across multiple Availability Zones

**Explanation:** By distributing their application across multiple Availability Zones (AZs) within the same region, the startup ensures that if one AZ experiences an outage or maintenance event, the application can continue to run seamlessly in the other AZs, thus providing high availability.
</details>

---

### Question 7: Cloud Best Practices
Which of the following cloud best practices reinforces the use of the Service-Oriented Architecture (SOA) design principle?

- [ ] a. Decouple your components.
- [ ] b. Design for failure.
- [ ] c. Implement elasticity.
- [ ] d. Think parallel.

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Decouple your components.

**Explanation:** Service-Oriented Architecture (SOA) is an architectural approach that breaks down a large application into smaller, independent, and loosely coupled services. **Decoupling** components is the practice of building services that can operate independently and communicate through well-defined interfaces, which is a core principle of SOA.
</details>

---

### Question 8: Cloud Benefits
A company used to experience delays in developing new services due to the time it took to procure and set up on-premises servers. They recently migrated their infrastructure to the AWS Cloud. This change has allowed them to spin up testing environments in just days, accelerating the time to market for their services. Which of the following AWS Cloud benefits is showcased in this scenario?

- [ ] a. Agility
- [ ] b. Deploy globally in minutes
- [ ] c. Cost savings
- [ ] d. Elasticity

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- a. Agility

**Explanation:** **Agility** is the ability to provision resources quickly and easily. By moving to the cloud and being able to spin up test environments in days instead of weeks or months, the company has significantly increased its agility and sped up its time to market.
</details>

---

### Question 9: Optimization
A company is using multiple AWS services to host its application. It wants to ensure the environment is optimized by adhering to AWS best practices. Which of the following services can inspect an AWS environment and making recommendations to lower expenditures, improve system performance and reliability, and close security gaps?

- [ ] a. AWS Cost Explorer
- [ ] b. AWS Trusted Advisor
- [ ] c. Amazon Inspector
- [ ] d. AWS Budgets

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- b. AWS Trusted Advisor

**Explanation:** **AWS Trusted Advisor** is a service that acts as an automated consultant. It inspects your AWS environment and provides recommendations across five categories: Cost Optimization, Performance, Security, Fault Tolerance, and Service Limits.
</details>

---

### Question 10: Cost Management
Which of the following Cost Management Tools allows tracking of Amazon EC2 Reserved Instance (RI) usage and provides visibility into the discounted RI rate charged to resources?

- [ ] a. AWS Price List Bulk API
- [ ] b. AWS Cost and Usage report
- [ ] c. AWS Budgets
- [ ] d. AWS Cost Explorer

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. AWS Cost Explorer

**Explanation:** **AWS Cost Explorer** is a tool that lets you visualize, understand, and manage your AWS costs and usage over time. It provides pre-configured views, including a report that tracks your Amazon EC2 Reserved Instance (RI) usage and provides insight into the cost savings.
</details>

---

### Question 11: Enterprise Support
The Enterprise Support Plan is designed for serious business use. Which of the following perks are only available with this plan? (Choose 2)

- [ ] a. Full Free Tier access for 12 months
- [ ] b. Free Well-Architected reviews
- [ ] c. Help planning large launches or upgrades
- [ ] d. You get a Technical Account Manager (TAM)
- [ ] e. Unlimited storage with no charge

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- c. Help planning large launches or upgrades
- d. You get a Technical Account Manager (TAM)

**Explanation:** The **Technical Account Manager (TAM)** is a dedicated point of contact that is exclusive to the Enterprise Support plan. Additionally, **Infrastructure Event Management**, which helps you plan for large launches or upgrades, is a benefit included with this plan. The other options are either available with other plans or are not related to support plans.
</details>

---

### Question 12: Shared Responsibility
Which of the following is the responsibility of the customer in the AWS cloud? (Select TWO.)

- [ ] a. Upgrading chipsets to the latest commercially available product
- [ ] b. Ensuring that AWS services comply with the standards required of them
- [ ] c. Managing users in their AWS account
- [ ] d. Disposal of disk drives
- [ ] e. Managing data stored in the AWS resources

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answers:**
- c. Managing users in their AWS account
- e. Managing data stored in the AWS resources

**Explanation:** In the Shared Responsibility Model, AWS is responsible for the "security *of* the cloud," which includes the hardware and physical infrastructure (like chipsets and disk drive disposal). The customer is responsible for "security *in* the cloud," including their own data and user access management (IAM).
</details>

---

### Question 13: Support Plans
Which of the following is the most cost-effective AWS Support Plan to use if you need access to AWS Support API for programmatic case management?

- [ ] a. Basic
- [ ] b. Developer
- [ ] c. Enterprise
- [ ] d. Business

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Business

**Explanation:** Access to the AWS Support API is available with the Business, Enterprise On-Ramp, and Enterprise plans. The **Business** plan is the most cost-effective of these three, as it has a lower monthly minimum fee than the Enterprise plans.
</details>

---

### Question 14: Shared Responsibility
A user has turned on encryption for their S3 bucket and is using their own key. Who’s meant to manage that key—like setting the access rules and handling key rotation?

- [ ] a. AWS Trusted Advisor
- [ ] b. AWS KMS engineers
- [ ] c. The customer
- [ ] d. AWS

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- c. The customer

**Explanation:** When the customer brings their own encryption key for a service like S3, they are solely responsible for managing that key, including its access rules, rotation, and lifecycle, as per the Shared Responsibility Model.
</details>

---

### Question 15: Low Latency
A financial company is serving clients in both South Africa and the UK. They want to make sure their services respond quickly no matter where users are based. Which parts of AWS should they use to make this work? (Choose 2)

- [ ] a. Run EC2 in different zones within one region
- [ ] b. Deliver content using CloudFront edge locations
- [ ] c. Deploy services in Local Zones near their users
- [ ] d. Link Availability Zones using VPC peering
- [ ] e. Use AWS Regions in Cape Town and London

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answers:**
- b. Deliver content using CloudFront edge locations
- e. Use AWS Regions in Cape Town and London

**Explanation:** To serve users in different continents with low latency, you should deploy your application in multiple **AWS Regions** (e.g., Cape Town and London). For static content like images or videos, using **CloudFront** and its network of Edge Locations will cache the content close to the end-users, further reducing latency.
</details>

---

### Question 16: Shared Responsibility
In AWS, What is the responsibility of the customer?.

- [ ] a. Making sure the core networking works
- [ ] b. Swapping out broken hardware
- [ ] c. Securing data centres against physical access
- [ ] d. Encrypting files before they go into S3

<details>
  <summary>Show Correct Answer</summary>
  
**Correct Answer:**
- d. Encrypting files before they go into S3

**Explanation:** The customer is responsible for the security *in* the cloud, which includes data protection. Encrypting your data before uploading it to a service like S3 is a customer responsibility. AWS handles the "security *of* the cloud," including the physical data centers, core networking, and hardware.
</details>

---

### Question 17: Support Plans
A customer is choosing the best AWS support plan which includes a designated Technical Account Manager. Which of the following should they choose?

- [ ] a. Enterprise On-Ramp
- [ ] b. Developer
- [ ] c. Business
- [ ] d. Enterprise

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:**
- d. Enterprise

**Explanation:** The Enterprise Support plan is the only AWS support tier that provides a **designated Technical Account Manager (TAM)**, who acts as your primary point of contact and helps you plan and optimize your AWS environment.
</details>

---

### Question 18: Support Plans
What is the lowest support plan that allows an unlimited number of technical support cases to be opened?

- [ ] a. Enterprise
- [ ] b. Basic
- [ ] c. Developer
- [ ] d. Business

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:**
- d. Business

**Explanation:** Both the Business and Enterprise support plans allow for an unlimited number of technical support cases. Since the **Business** plan has a lower cost, it is the lowest tier that provides this benefit.
</details>

---

### Question 19: Shared Responsibility
Which of the following does AWS automatically handle for you? (Select TWO.)

- [ ] a. Introduce updates and patches to EC2 hypervisors
- [ ] b. Introduce updates and patches to EC2 guest operating systems
- [ ] c. Secure AWS data centres from environmental hazards
- [ ] d. Provide web application firewall protection to your public endpoints.
- [ ] e. Makes sure your data is safely kept and replicated between AZs

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answers:**
- a. Introduce updates and patches to EC2 hypervisors
- c. Secure AWS data centres from environmental hazards

**Explanation:** AWS is responsible for the security *of* the cloud, which includes the physical infrastructure, network, and hypervisor. The customer is responsible for the security *in* the cloud, which includes the guest operating system, data, and application-level security.
</details>

---

### Question 20: Cost Management
You’ve been asked to keep track of AWS costs, set budgets, and get alerts before things go over. Which AWS tools would help with this? (Choose 2)

- [ ] a. AWS Cost Explorer
- [ ] b. AWS Shield
- [ ] c. AWS Pricing Calculator
- [ ] d. AWS Config
- [ ] e. AWS Budgets

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answers:**
- a. AWS Cost Explorer
- e. AWS Budgets

**Explanation:** **AWS Cost Explorer** is a tool for visualizing and analyzing your costs. **AWS Budgets** allows you to set custom budgets and receive alerts when your costs or usage exceed (or are forecasted to exceed) your defined threshold.
</details>

---

### Question 21: Cost Management
A company uses several AWS accounts and wants to see their total monthly spend in one place. What should they use to do this?

- [ ] a. AWS Cost Explorer
- [ ] b. IAM roles with billing permissions
- [ ] c. Consolidated Billing in AWS Organisations
- [ ] d. AWS Trusted Advisor

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:**
- c. Consolidated Billing in AWS Organisations

**Explanation:** **Consolidated Billing**, a feature of AWS Organizations, allows you to receive a single bill for all of your AWS accounts, which simplifies cost tracking and management.
</details>

---

### Question 22: Cost Management
Your manager wants to avoid surprise charges and would like a heads-up when a project starts getting close to its spending limit. What AWS services can help set this up? (Choose 2)

- [ ] a. Billing Dashboard
- [ ] b. Cost Anomaly Detection
- [ ] c. AWS Config
- [ ] d. AWS Organisations Service Control Policies (SCPs)
- [ ] e. AWS Budgets

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answers:**
- b. Cost Anomaly Detection
- e. AWS Budgets

**Explanation:** **AWS Budgets** allows you to set spending limits and receive alerts when costs are approaching or exceed that limit. **Cost Anomaly Detection** uses machine learning to identify unusual spending patterns and alert you to unexpected cost spikes.
