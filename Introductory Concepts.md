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


### Pricing of the Cloud – Quick Overview

AWS follows three fundamental pricing principles based on the pay-as-you-go pricing model:

| **Fundamental**       | **Description**                                                                                                                                                      |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Compute**           | Pay for the compute time you consume. Examples include EC2 instance hours or Lambda invocation duration.                                                             |
| **Storage**           | Pay for the amount of data stored in the cloud. Examples include S3 storage space and EBS volume usage.                                                              |
| **Data Transfer OUT** | Pay for data transfer out of the cloud. Data transfer IN is free. This pricing structure solves the issue of expensive data transfer fees in traditional IT systems. |

### How Cloud Pricing Solves Traditional IT Cost Issues

- Traditional IT requires expensive upfront investments for hardware, maintenance, and upgrades.
- With AWS's pay-as-you-go model, you only pay for what you use, reducing overall costs.
- You can scale up or down based on demand, minimizing under-utilized resources.

### AWS Cloud Use Cases

1. **Web Hosting**: Host websites with elastic scaling and high availability.
2. **Big Data Analytics**: Run analytics on large datasets.
3. **Application Hosting**: Host applications with global accessibility and automated scaling.
4. **Disaster Recovery**: Implement disaster recovery strategies with minimized infrastructure.
5. **Backup and Storage**: Store backups in a highly durable and secure manner.

## AWS Global Infrastructure

### AWS Regions

- Geographically isolated areas where AWS clusters data centers.
- Each region has multiple Availability Zones.
- Used to deploy applications close to customers for lower latency.

### How to Choose an AWS Region?

- **Latency**: Choose a region closest to your customers for lower latency.
- **Compliance**: Ensure the region meets data residency and compliance requirements.
- **Services Available**: Check which AWS services are offered in the region.
- **Pricing**: Prices vary by region, so choose a region that fits your cost requirements.

### AWS Availability Zones (AZs)

- Multiple, isolated data centers within a region.
- Each AZ has independent power, cooling, and networking.
- Provides redundancy and fault tolerance in case of a failure.
- They’re connected with high bandwidth, ultra-low latency networking

### AWS Points of Presence (Edge Locations)

- Network locations that deliver content closer to end users.
- Used by services like Amazon CloudFront and AWS Global Accelerator.
- Provides low latency and improved performance for content delivery.

## AWS Shared Responsibility Model

### What is the Shared Responsibility Model?

- AWS and the customer share responsibility for security and compliance.
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
  - **Data protection**: Encrypt data in transit and at rest.
  - **IAM**: Control access through Identity and Access Management (IAM) roles, users, and policies.
  - **OS and application configurations**: Maintain security of guest operating systems, applications, and firewall configurations.
  - **Network settings**: Manage security group rules and network access control lists (NACLs).
  - **Compliance**: Ensure compliance with regulations and standards based on data storage and usage.

### Example Responsibilities for Different AWS Services

| **Service Type**     | **AWS Responsibility**                                     | **Customer Responsibility**                                            |
| -------------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------- |
| **IaaS (e.g., EC2)** | Securing physical infrastructure, hypervisor, and network. | Configure and secure OS, patch management, data, and network settings. |
| **PaaS (e.g., RDS)** | Managing the database engine, backups, and patching.       | Secure data at rest and in transit, manage DB access, and IAM roles.   |
| **SaaS (e.g., S3)**  | Protecting the service's underlying infrastructure.        | Manage permissions, bucket policies, and data lifecycle rules.         |

### Summary

- AWS handles security *of* the cloud, while customers manage security *in* the cloud.
- Understanding your responsibilities helps you implement appropriate security measures for your AWS environment.
