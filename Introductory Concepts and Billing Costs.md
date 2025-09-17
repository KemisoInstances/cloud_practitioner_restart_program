# IT INFRASTRUCTURE

- [What is IT Infrastructure?](#what-is-it-infrastructure)
- [Components that make IT Infrastructure](#components-that-make-it-infrastructure)
  
# ClOUD COMPUTING
- [What is Cloud Computing](#what-is-cloud-computing)
- [Benefits of Cloud Computing ](#benefits-of-cloud-computing)
- [Types of Cloud Computing](#types-of-cloud-computing) 
- [Cloud Computing Deployment Models](#cloud-computing-deployment-models)
- [Cloud Infrastructure vs On-Premises Infrastructure](#cloud-infrastructure-vs-on-premises-infrastructure)

# AWS INTRO
- [What is AWS](#what-is-aws)
- [AWS Use Cases ](#aws-use-cases)
- [AWS Global Infrastructure](#aws-global-infrastructure) 
- [Cloud Computing Deployment Models](#cloud-computing-deployment-models)
    - [AWS Regions](#aws-regions)
    - [How to Choose an AWS Region?](#how-to-choose-an-aws-region)
    - [AWS Availability Zones (AZs)](#aws-availability-zones-azs)
    - [AWS Points of Presence (Edge Locations)](#aws-points-of-presence-edge-locations)

# AWS Well Architected Framework
 - [Cloud Design Princiles](#cloud-design-principles)
 - [Architected Framework Pillars](#architected-framework-pillars)
    - [Operational Excellence](#operational-excellence)
    - [Performance Efficiency](#performance-efficiency)
    - [Reliability](#reliability)
    - [Sustainability](#sustainability)
    - [Security](#security)
    - [Cost Optimisation](#cost-optimisation)


# AWS Shared Responsibility Model
- [What is the Shared Responsibility Model?](#what-is-the-shared-responsibility-model)
- [AWS Responsibilities: **Security *of* the Cloud**](#aws-responsibilities-security-of-the-cloud)
- [Customer Responsibilities: **Security *in* the Cloud**](#customer-responsibilities-security-in-the-cloud)
- [Example Responsibilities for Different AWS Services](#example-responsibilities-for-different-aws-services)
    

# Cloud Financial Management
 - [AWS Total Cost of Ownership](#aws-total-cost-of-ownership)
 - [AWS Pricing Calculator](#aws-pricing-calculator)
 - [AWS Cost Allocation Tags](#aws-cost-allocation-tags)
 - [AWS Cost and Usage Reports](#aws-cost-and-usage-reports)
 - [AWS Cost Explorer](#aws-cost-explorer)
 - [AWS Budgets](#aws-budgets)
 - [AWS Savings Plan](#aws-savings-plan)

# AWS Support Plans

 - [Basic](#basic)
 - [Developer](#developer)
 - [Business](#business)
 - [Enterprise On-Ramp](#enterprise-on-ramp)
 - [Enterprise](#enterprise)
 - [AWS Savings Plan](#aws-savings-plan)

</br></br>

> [!NOTES]</br>

😄😄😄😄😄😄😄😄😄😄😄😄😄😄😄😄 😄😄 😄😄 😄😄 😄😄 😄😄 😄😄 😄😄 😄😄 😄😄 

# IT Infrastructure😄😄 

## What is IT Infrastructure
* The combination of hardware, software, network connectivity and human resources that allow an organisation to deliver information technology services to people within organisations.

## Components that make up IT Infrastructure
* Hardware
* Software
* Network connectivity
* Human Resources

**Hardware**
* Physical components that make up a computer system.
  * CPU, memory, motherboard, network card
    
<img width="600" height="375" alt="image" src="https://github.com/user-attachments/assets/feb54807-40f1-4198-a78b-fcdee4661b14" />

</br></br>
**Software**
* Programs that direct the operation of a computer, as well as documentation giving instructions on how to use them
* A set of instructions or commands that tell a computer what to do.
  * Operating Systems:
    * Microsoft Windows
    * Linux
    * MacOS
   
  * Application Software (programs for specific user tasks):
    * Microsoft Office (Word, Excel, Powerpoint
    * Web browsers (Google Chrome, Firefox, Safari)
    * Multimedia (VLC Media Player, Spotify, Adobe Photoshop)
    * Communication (Gmail, WhatsApp, Zoom)
  
  * Systems Softwares e.g Antivirus

**Network Connectivity**
* The ability of devices to connect and communicate with each other
  * Networking hubs, switches, routers, bridges

<img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/aaad42bb-b14b-4ca7-85b3-d4facd18cb52" />

</br></br>
**Human Resources**
 * Refers to people in charge of parts of IT infrastructure.
 * They look at an organisation’s needs and determine what hardware, and software will do the job.
 * They can either buy an existing solution or develop a solution from scratch.
  * Developers, system administrators, network administrators
    

🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫🤫
# Cloud Computing🤫🤫

## What is Cloud Computing
* Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources
* A cloud services platform such as Amazon Web Services owns and maintains the network-connected hardware required for these application services, while you provision and use what you need via a web application.

## Benefits of Cloud Computing
* Cost-Effectiveness: pay as you go/Pay for what you use
* Elasticity: the ability to scale out and scale in when needed
* Agility: rapidly develop, test, and launch software applications
* Deploy Globally in Minutes: With just a few clicks, you can quickly deploy your application to different locations and enhance the experience of your users with reduced latency.
* Stop spending money running and maintaining data centers – Focus on projects that differentiate your business, not the infrastructure.
* Stop guessing capacity – Eliminate guessing about your infrastructure capacity needs. When you make a capacity decision prior to deploying an application, you often end up either sitting on expensive idle resources or dealing with limited capacity.
* Benefit from massive economies of scale – By using cloud computing, you can achieve a lower variable cost than you can get on your own
* Trade fixed expense for variable expense - Instead of having to invest heavily in data centers and servers before you know how you’re going to use them, you can pay only when you consume computing resources, and pay only for how much you consume

## Types of Cloud Computing
-  **Infrastructure as a Service (IaaS)** - Full control of your infrastructure without the maintenance and operating costs of the servers. IaaS provides access to servers, storage, networking, and operating systems.
</br></br>
- **Platform as a Service (PaaS)** - In this model, you can focus on the deployment and management of your applications. PaaS eliminates the need to manage the underlying infrastructure.
</br></br>
- **Software as a Service (SaaS)** - The software is ready to be used and operated by the service provider. SaaS is also known as an end-user application.



### The Deployment Models of the Cloud

| **Private Cloud**                                                        | **Public Cloud**                                                                                         | **Hybrid Cloud**                                                             |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| The deployment of resources on-premises, using virtualization and resource management tools, is sometimes **called the private cloud** |  the cloud provider makes resources available to the public through the internet. While the resources vary depending on the provider, it usually includes storage capabilities, applications, or virtual machines. | A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud |
|  On-premises deployment doesn’t provide many of the benefits of cloud computing but is sometimes sought for its ability to provide dedicated resources. |Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing.|Keep some servers on-premises and extend some capabilities to the Cloud.|


### Cloud Infrastructure vs On-Premises Infrastructure

1. **Public** - No upfront Investment, Low ongoing costs, Focus on innovation, Flexible capacity, Speed and agility, Global reach on demand
2. **Private** - Large initial purchase, Labour, patches, and upgrade cycles, System Administration, Fixed capacity, Long procurement and setup, Limited geographic regions
</br>
***What can you do in the cloud?***
* Application hosting, Backup and Storage, Content delivery, Websites, Enterprise IT, Database
 

### Example of Cloud Computing Types

- **IaaS**: AWS EC2 (Elastic Compute Cloud)
  - GCP, Azure, Rackspace, Digital Ocean, Linode
- **PaaS**: AWS Elastic Beanstalk
  - Heroku, Google App Engine (GCP), Windows Azure (Microsoft)
- **SaaS**: AWS Chime
  - Google Apps (Gmail), Dropbox, Zoom
</br></br>
🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗🤗

# AWS🤗🤗
## What is AWS?
* AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of  (IaaS),  (PaaS) and  (SaaS) offerings.
* AWS Use Cases
  * AWS Use Cases
    * Enterprise IT, Backup & Storage, Big Data Analytics
    * Website hosting, Mobile & Social Apps
    * Gaming

## AWS Global Infrastructure
</br>
<img width="1137" height="391" alt="image" src="https://github.com/user-attachments/assets/36c28ad7-c76e-4d9b-8d3f-7f8a636b7ce0" />

### AWS Regions
* It is a physical geographical location in the world where AWS has multiple Availability Zones.
*  Regions include North America, South America, Europe, Asia, and other parts of the globe. 
  * Since a single AZ consists of multiple data centers, your system can achieve a higher level of fault tolerance by running it in two
    #### Data Centers:
    * A data center is a location where the actual physical data resides, and data processing occurs.
    * AWS data centers are built in clusters in various global regions

    ##### How to choose an AWS Region
    1.  **Compliance with data governance and legal requirements**: data never leaves a region without your explicit permission
    2.   **Latency**: reduced latency can make substantial impact on enhancing the user experience.
    3.   **Services and features**: new services and new features aren’t available in every Region
    4.   **Pricing/ cost**: pricing varies from region to region and is transparent on the service pricing page

### AWS Availability Zones
* Availability Zones consist of one or more discrete data centers that are designed for fault isolation.
* They’re separate from each other so that they’re isolated from disasters.
* They’re connected with high bandwidth, ultra-low latency networking.
</br>
                                            <img width="557" height="413" alt="image" src="https://github.com/user-attachments/assets/381e6ee8-78f1-4884-a6e9-fdca3aa12342" />
  </br>
  ### AWS Edge Locations
  * Edge locations are AWS data centers designed to deliver services with the lowest latency possible
  * They’re closer to users than Regions or Availability Zones, often in major cities, so responses can be fast
  </br>
                                         <img width="402" height="490" alt="image" src="https://github.com/user-attachments/assets/98ea0bd2-90f1-45e5-b228-e7bd52e7f772" />

 </br></br>
 🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️  🏖️🏖️

 # AWS ARCHITECTURED FRAMEWORK 🏖️🏖️
 - Architected Framework helps you understand the pros and cons of decisions you make while building systems on AWS.
   ## AWS Cloud Best Practices – Design Principles
   +  **Scalability**: vertical & horizontal
   +  **Design for Failure**: This concept encourages you to be a pessimist when designing architectures in the cloud and assumes that the components of your architecture will fail.
   +  **Disposable Resources**: servers should be disposable and easily configured.
   +  **Decouple your components**: the key concept is to build components that do not have tight dependencies on each other so that if one component were to fail for some reason, the other components in the system will continue to work. This is also known as loose coupling.
   +  **Services, not servers**: Don’t use just EC2, use managed services, databases, serverless services
  
   ## Architected Framework Pillars
   </br>
                           <img width="1300" height="660" alt="image" src="https://github.com/user-attachments/assets/2b9fe5b9-3192-4398-b746-96745dd38221" />


 </br>
 
 1. **Operational Excellence**
    
      ***Design Principles***
    
         a.  **Perform operations as code** - Infrastructure as code
         b.  **Annotate documentation** - Automate the creation of annotated documentation after every build
         c.  **Make frequent, small, reversible changes** - So that in case of any failure, you can reverse it
         d.   **Refine operations procedures frequently** - And ensure that team members are familiar with it
         e.  **Anticipate failure** - Learn from all operational failures

 3. **Performance Efficiency**
 - Includes the ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve
   
     ***Design Principles***:
   
- **Democratize advanced technologies** - Advance technologies become services and hence you can focus more on product development
- **Go global in minutes** - Easy deployment in multiple regions
- **Use serverless architectures** - Avoid the burden of managing servers
- **Experiment more often**- Easy to carry out comparative testing
- **Mechanical sympathy** - Be aware of all AWS services

 3. **Reliability**
 - Ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand and mitigate disruptions such as misconfigurations or transient network issues
   
 ***Design Principles**:
 
 - **Test recovery procedures** - Use automation to simulate different failures or to recreate scenarios that led to failures before
 - **Automatically recover from failure** - Anticipate and remediate failures before they occur
 - **Scale horizontally to increase aggregate system availability** - Distribute requests across multiple, smaller resources to ensure that they don't share a common point of failure
 - **Stop guessing capacity** - Maintain the optimal level to satisfy demand without over or 
- **under-provisioning** - Use Auto Scaling
- **Manage change in automation** - Use automation to make changes to infrastructure

4. **Sustainability**
     
 - The sustainability pillar focuses on minimizing the environmental impacts of running cloud workloads.
   
    ***Design Principles***:
   
 - **Understand your impact** – establish performance indicators, evaluate improvements
 - **Establish sustainability goals** – Set long-term goals for each workload, model return on investment (ROI)
 - **Maximize utilization** – Right size each workload to maximize the energy efficiency of the underlying hardware and minimize idle resources.
 - **Anticipate and adopt new, more efficient hardware and software offerings** – and design for flexibility to adopt new technologies over time.
 - **Use managed services** – Shared services reduce the amount of infrastructure; Managed services help automate sustainability best practices as moving infrequent accessed data to cold storage and adjusting compute capacity.
 - **Reduce the downstream impact of your cloud workloads** – Reduce the amount of energy or resources required to use your services and reduce the need for your customers to upgrade their devices

5. **Security**
   
- Includes the ability to protect the information, systems, and assets while delivering business value through risk assessments and mitigation strategies

 ***Design Principles***:
 
- **Implement a strong identity foundation** - Centralize privilege management and reduce (or even eliminate) reliance on long-term credentials - Principle of least privilege - IAM
- **Enable traceability** - Integrate logs and metrics with systems to automatically respond and take action
- **Apply security at all layers** - Like edge network, VPC, subnet, load balancer, every instance, operating system, and application
- **Keep people away from data** - Reduce or eliminate the need for direct access or manual processing of data
  
6. **Cost Optimisation**
   
- Includes the ability to run systems to deliver business value at the lowestprice point

***Design Principles***:

- **Adopt a consumption mode** - Pay only for what you use
- **Measure overall efficiency** - Use CloudWatch
- **Stop spending money on data center operations** - AWS does the infrastructure part and enables customers to focus on organization 
projects
 - **Analyze and attribute expenditure** - Accurate identification of system usage and costs helps measure return on investment (ROI) - Make sure to use tags
 </br></br>
⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽ ⛽⛽

</br>

# AWS FINANCIAL MANAGEMENT⛽⛽

  ## Types of Financial Management
     *  AWS Total Cost of Ownership
     * AWS Pricing Calculator
     * AWS Cost Allocation Tags
     * AWS Cost and Usage Reports
     * AWS Cost Explorer
     * AWS Budgets
     * AWS Savings Plan

</br>

1. **AWS Total Cost of Ownership**: reducing the need to invest in large capital expenditures and providing a pay-as-you-go model. TCO calculators allow you to estimate the cost savings  and provide a detailed set of reports that can be used in executive presentations.
</br>

2. **AWS Pricing Calculator**: estimate the monthly cost of AWS services for use case based on your expected usage
</br>

3. **AWS Cost Allocation Tags**: used to organize AWS resources, and cost allocation tags to track the AWS costs on a detailed 
level making it easier to categorize and track your AWS costs
</br>

4. **AWS Cost and Usage Reports**: track your AWS usage and provide estimated charges associated with your account. Track your savings 
plan use
 • Understand trends in your bill
</br>

5. **AWS Cost Explorer**: Cost explorer is a free service. You can see a forecast of future costs and historical cost data (comparing and 
forecasting).  Forecast usage for up to 12 months based on the previous usage
</br>

6. **AWS Budgets**: Track your AWS usage and cost. AWS Budgets notify you when you go over your budgeted amounts or when your estimated costs exceed your budgets.
   
   **Types of Budgets**:
    
• Cost budgets 
• Usage budgets 
• RI utilization budgets 
• RI coverage budgets
</br>

7. **AWS Savings Plan**: offer significant savings over On-Demand Instances, just like EC2 Reserved Instances, in exchange for a 
commitment to use a specific amount of compute power **(measured in $/hour) for a one or three-year period**



</br></br>
🙂🙂 🙂🙂 🙂🙂 🙂🙂🙂🙂 🙂🙂 🙂🙂 🙂🙂 🙂🙂🙂🙂 🙂🙂 🙂🙂
</br>

# AWS Shared Responsibility Model🙂🙂

  ## What is the Shared Responsibility Model?
   - AWS and the customer share responsibility for security and compliance
   - Divides security tasks based on **AWS as the provider** and **customer as the user** of cloud services.

     ### AWS Responsibilities: **Security *of* the Cloud**

     - AWS is responsible for protecting the infrastructure that runs all services offered in the AWS Cloud.
     - Includes hardware, software, networking, and facilities:
       - **Physical security** of data centers (e.g., access control, environmental controls).
       - **Infrastructure** security, such as maintaining hypervisors, host operating systems, and network infrastructure.
       - **Global network** operations, such as DDoS protection and monitoring.


     ### Customer Responsibilities: **Security *in* the Cloud**

     - Customers are responsible for managing and securing what they put in the cloud.
     - Includes:
       -  **Data protection**: Encrypt data in transit and at rest.
       -  **IAM**: Control access through Identity and Access Management (IAM) roles, users, and policies.
       -  **OS and application configurations**: Maintain security of guest operating systems, applications, and firewall configurations.
       -  **Network settings**: Manage security group rules and network access control lists (NACLs).
       -  **Compliance**: Ensure compliance with regulations and standards based on data storage and usage.


     ### Example Responsibilities for Different AWS Services

| **Service Type**     | **AWS Responsibility**                                     | **Customer Responsibility**                                            |
| -------------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------- |
| **IaaS (e.g., EC2)** | Securing physical infrastructure, hypervisor, and network. | Configure and secure OS, patch management, data, and network settings. |
| **PaaS (e.g., RDS)** | Managing the database engine, backups, and patching.       | Secure data at rest and in transit, manage DB access, and IAM roles.   |
| **SaaS (e.g., S3)**  | Protecting the service's underlying infrastructure.        | Manage permissions, bucket policies, and data lifecycle rules.         |

</br></br>

😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀 😀😀
</br>

# AWS Support Plans😀😀
</br>

  ## Types of Support Plans
</br>

- **BASIC**: Offers cutomer service, such as 24/7 customer sevice, documentation, whitepaper, 7 core Trusted Advisor
- **Developer**: Offers building block architectural support, All Basic Support Plan + Business hours email access to Cloud Support Associates, Unlimited cases / 1 primary contact. Case severity / response times:
  - General guidance: < 24 business hours
  - System impaired: < 12 business hours
- **Businees**: offers features from developer support tier such as technical support, Third party support and all trusted Advisor cherks
- **Enterprise On-Ramp**: Recommended if you have a business and/or mission critical workloads in AWS, there is Access to a pool of Technical Account Managers (TAM), support team (billing) and Infrastructure Event Manager and Architecture.
- **Enterprise**: 15 minutes response time,  A dedicated technical accounts manager (TAM), short term engagement with AWS support to partner

     

</br>
</br>

# Additional Content

## AWS Organization - Consolidated Billing

- When enabled, provides you with:
  - Combined Usage – combine the usage across all AWS accounts in the AWS Organization to share the volume pricing, Reserved Instances and Savings Plans discounts
  - One Bill – get one bill for all AWS Accounts in the AWS Organization
- The management account can turn off Reserved Instances discount sharing for any account in the AWS Organization, including itself.

## Pricing Models in AWS

- AWS has 4 pricing models:
- **Pay as you go**: pay for what you use, remain agile, responsive, meet scale demands
- **Save when you reserve**: minimize risks, predictably manage budgets, comply with long-terms requirements
  - Reservations are available for EC2 Reserved Instances, DynamoDB Reserved Capacity, ElastiCache Reserved Nodes, RDS Reserved Instance, Redshift Reserved Nodes
- **Pay less by using more**: volume-based discounts
- **Pay less as AWS grows**

## Compute Pricing

### EC2

- Only charged for what you use
- Number of instances
- Instance configuration:
  - Physical capacity
  - Region
  - OS and software
  - Instance type
  - Instance size
- ELB running time and amount of data processed
- Detailed monitoring

- On-demand instances:
  - Minimum of 60s
  - Pay per second (Linux/Windows) or per hour (other)
- Reserved instances:
  - Up to 75% discount compared to On-demand on hourly rate
  - 1- or 3-years commitment
  - All upfront, partial upfront, no upfront
- Spot instances:
  - Up to 90% discount compared to On-demand on hourly rate
  - Bid for unused capacity
- Dedicated Host:
  - On-demand
  - Reservation for 1 year or 3 years commitment
  - Savings plans as an alternative to save on sustained usage

### Lambda & ECS

- Lambda:
  - Pay per call
  - Pay per duration
- ECS:
  - EC2 Launch Type Model: No additional fees, you pay for AWS resources stored and created in your application
- Fargate:
  - Fargate Launch Type Model: Pay for vCPU and memory resources allocated to your applications in your containers

## Storage Pricing

### S3

- Storage class: S3 Standard, S3 Infrequent Access, S3 One-Zone IA, S3 Intelligent Tiering, S3 Glacier and S3 Glacier Deep Archive
- Number and size of objects: Price can be tiered (based on volume)
- Number and type of requests
- Data transfer OUT of the S3 region
- S3 Transfer Acceleration
- Lifecycle transitions
- Similar service: EFS (pay per use, has infrequent access & lifecycle rules)

### EBS

- Volume type (based on performance)
- Storage volume in GB per month provisioned
- IOPS:
  - General Purpose SSD: Included
  - Provisioned IOPS SSD: provisioned amount in IOPS
  - Magnetic: Number of requests
- Snapshots:
  - Added data cost per GB per month
- Data transfer:
  - Outbound data transfer are tiered for volume discounts
  - Inbound is free

## Database Pricing - RDS

- Per hour billing
- Database characteristics:
  - Engine
  - Size
  - Memory class
- Purchase type:
  - On-demand
  - Reserved instances (1 or 3 years) with required up-front
- Backup Storage: There is no additional charge for backup storage up to 100% of your total database storage for a region.
- Additional storage (per GB per month)
- Number of input and output requests per month
- Deployment type (storage and I/O are variable):
  - Single AZ
  - Multiple AZs
- Data transfer:
  - Outbound data transfer are tiered for volume discounts
  - Inbound is free

## Content Delivery - CloudFront

- Pricing is different across different geographic regions
- Aggregated for each edge location, then applied to your bill
- Data Transfer Out (volume discount)
- Number of HTTP/HTTPS requests

## Networking Costs in AWS per GB - Simplified

- Use Private IP instead of Public IP for good savings and better network performance
- Use same AZ for maximum savings (at the cost of high availability)

## Savings Plan

- Commit a certain $ amount per hour for 1 or 3 years
- Easiest way to setup long-term commitments on AWS
- EC2 Savings Plan
  - Up to 72% discount compared to On-Demand
  - Commit to usage of individual instance families in a region (e.g. C5 or M5)
  - Regardless of AZ, size (m5.xl to m5.4xl), OS (Linux/Windows) or tenancy
  - All upfront, partial upfront, no upfront
- Compute Savings Plan
  - Up to 66% discount compared to On-Demand
  - Regardless of Family, Region, size, OS, tenancy, compute options
  - Compute Options: EC2, Fargate, Lambda
- Setup from the AWS Cost Explorer console
- Estimate pricing at <https://aws.amazon.com/savingsplans/pricing/>

## AWS Compute Optimizer

- Reduce costs and improve performance by recommending optimal AWS resources for your workloads
- Helps you choose optimal configurations and right - size your workloads (over/under provisioned)
- Uses Machine Learning to analyze your resources’ configurations and their utilization CloudWatch metrics
- Supported resources
  - EC2 instances
  - EC2 Auto Scaling Groups
  - EBS volumes
  - Lambda functions
- Lower your costs by up to 25%
- Recommendations can be exported to S3

## Billing and Costing Tools

- Estimating costs in the cloud:
  - Pricing Calculator
- Tracking costs in the cloud:
  - Billing Dashboard
  - Cost Allocation Tags
  - Cost and Usage Reports
  - Cost Explorer
- Monitoring against costs plans:
  - Billing Alarms
  - Budgets

## AWS Pricing Calculator

- Available at <https://calculator.aws/>
- Estimate the cost for your solution architecture

## Cost Allocation Tags

- Use cost allocation tags to track your AWS costs on a detailed level
- AWS generated tags
  - Automatically applied to the resource you create
  - Starts with Prefix aws: (e.g. aws: createdBy)
- User-defined tags
  - Defined by the user
  - Starts with Prefix user:

## Tagging and Resource Groups

- Tags are used for organizing resources:
  - EC2: instances, images, load balancers, security groups…
  - RDS, VPC resources, Route 53, IAM users, etc…
  - Resources created by CloudFormation are all tagged the same way
- Free naming, common tags are: Name, Environment, Team …
- Tags can be used to create **Resource Groups**
  - Create, maintain, and view a collection of resources that share common tags
  - Manage these tags using the Tag Editor

## Cost and Usage Reports

- Dive deeper into your AWS costs and usage
- The AWS Cost & Usage Report contains the most comprehensive set of AWS cost and usage data available, including additional metadata about AWS services, pricing, and reservations (e.g., Amazon EC2 Reserved Instances (RIs)).
- The AWS Cost & Usage Report lists AWS usage for each service category used by an account and its IAM users in hourly or daily line items, as well as any tags that you have activated for cost allocation purposes.
- Can be integrated with Athena, Redshift or QuickSight

## Cost Explorer

- Visualize, understand, and manage your AWS costs and usage over time
- Create custom reports that analyze cost and usage data.
- Analyze your data at a high level: total costs and usage across all accounts
- Or Monthly, hourly, resource level granularity
- Choose an optimal **Savings Plan**(to lower prices on your bill)
- **Forecast usage up to 12 months based on previous usage**

- Cost Explorer – Monthly Cost by AWS Service
- Cost Explorer– Hourly & Resource Level
- Cost Explorer – Savings Plan Alternative to Reserved Instances
- Cost Explorer – Forecast Usage

## Billing Alarms in CloudWatch

- Billing data metric is stored in CloudWatch us-east1
- Billing data are for overall worldwide AWS costs
- It’s for actual cost, not for projected costs
- Intended a simple alarm (not as powerful as AWS Budgets)

## AWS Budgets

- Create budget and send alarms when costs exceeds the budget
- 3 types of budgets: Usage, Cost, Reservation
- For Reserved Instances (RI)
  - Track utilization
  - Supports EC2, ElastiCache, RDS, Redshift
- Up to 5 SNS notifications per budget
- Can filter by: Service, Linked Account, Tag, Purchase Option, Instance Type, Region, Availability Zone, API Operation, etc…
- Same options as AWS Cost Explorer!
- 2 budgets are free, then $0.02/day/budget

## AWS Cost Anomaly Detection

- Continuously monitor your cost and usage using ML to detect unusual spends
- It learns your unique, historic spend patterns to detect one-time cost spike
and/or continuous cost increases (you don't need to define thresholds)
- Monitor AWS services, member accounts, cost allocation tags, or cost categories
- Sends you the anomaly detection report with root-cause analysis
- Get notified with individual alerts or daily/weekly summary (using SNS)

## AWS Service Quotas

- Notify you when you're close to a service quota value threshold
- Create CloudWatch Alarms on the Service Quotas console
- Example: Lambda concurrent executions
- Request a quota increase from AWS Service Quotas or shutdown resources before limit is reached


## Trusted Advisor

- No need to install anything – high level AWS account assessment
- Analyze your AWS accounts and provides recommendation on 5 categories
- Cost optimization
- Performance
- Security
- Fault tolerance
- Service limits

## Trusted Advisor - Support Plans

| 7 CORE CHECKS Basic & Developer Support plan                         | FULL CHECKS Business & Enterprise Support plan        |
| -------------------------------------------------------------------- | ----------------------------------------------------- |
| S3 Bucket Permissions, Security Groups – Specific Ports Unrestricted | Full Checks available on the 5 categories             |
| IAM Use (one IAM user minimum), MFA on Root Account                  | Ability to set CloudWatch alarms when reaching limits |
| EBS Public Snapshots, RDS Public Snapshots, Service Limits           | Programmatic Access using AWS Support API             |

## AWS Basic Support Plan

- Customer Service & Communities - 24x7 access to customer service, documentation, whitepapers, and support forums.
- AWS Trusted Advisor - Access to the 7 core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security.
- AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted.

## AWS Developer Support Plan

- All Basic Support Plan +
- Business hours email access to Cloud Support Associates
- Unlimited cases / 1 primary contact
- Case severity / response times:
  - General guidance: < 24 business hours
  - System impaired: < 12 business hours

## AWS Business Support Plan (24/7)

- Intended to be used if you have production workloads
- Trusted Advisor – Full set of checks + API access
- 24x7 phone, email, and chat access to Cloud Support Engineers
- Unlimited cases / unlimited contacts
- Access to Infrastructure Event Management for additional fee.
- Case severity / response times:
  - General guidance: < 24 business hours
  - System impaired: < 12 business hours
  - Production system impaired: < 4 hours
  - Production system down: < 1 hour

## AWS Enterprise On-Ramp Support Plan (24/7)

- Intended to be used if you have production or business critical workloads
- All of Business Support Plan +
- Access to a pool of Technical Account Managers (TAM)
- Concierge Support Team (for billing and account best practices)
- Infrastructure Event Management, Well-Architected & Operations Reviews
- Case severity / response times:
  - Production system impaired: < 4 hours
  - Production system down: < 1 hour
  - Business-critical system down: < 30 minutes

## AWS Enterprise Support Plan (24/7)

- Intended to be used if you have mission critical workloads
- All of Business Support Plan +
- Access to a designated Technical Account Manager (TAM)
- Concierge Support Team (for billing and account best practices)
- Infrastructure Event Management, Well-Architected & Operations Reviews
- Case severity / response times:
  - Production system impaired: < 4 hours
  - Production system down: < 1 hour
  - Business-critical system down: < 15 minutes

## Account Best Practices - Summary

- Operate multiple accounts using Organizations
- Use SCP (service control policies) to restrict account power
- Easily setup multiple accounts with best-practices with AWS Control Tower
- Use Tags & Cost Allocation Tags for easy management & billing
- IAM guidelines: MFA, least-privilege, password policy, password rotation
- Config to record all resources configurations & compliance over time
- CloudFormation to deploy stacks across accounts and regions
- Trusted Advisor to get insights, Support Plan adapted to your needs
- Send Service Logs and Access Logs to S3 or CloudWatch Logs
- CloudTrail to record API calls made within your account
- If your Account is compromised: change the root password, delete and rotate all passwords / keys, contact the AWS support

## Billing and Costing Tools - Summary

- **Compute Optimizer**: recommends resources’ configurations to reduce cost
- **Pricing Calculator**: cost of services on AWS
- **Billing Dashboard**: high level overview + free tier dashboard
- **Cost Allocation Tags**: tag resources to create detailed reports
- **Cost and Usage Reports**: most comprehensive billing dataset
- **Cost Explorer**: View current usage (detailed) and forecast usage
- **Billing Alarms**: in us-east-1 – track overall and per-service billing
- **Budgets**: more advanced – track usage, costs, RI, and get alerts
- **Savings Plans**: easy way to save based on long-term usage of AWS
- **Cost Anomaly Detection**: detect unusual spends using Machine Learning
- **Service Quotas**: notify you when you're close to service quota threshold




