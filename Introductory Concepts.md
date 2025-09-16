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

## Types of Cloud Computing
-  **Infrastructure as a Service (IaaS)** - Full control of your infrastructure without the maintenance and operating costs of the servers. IaaS provides access to servers, storage, networking, and operating systems.
</br></br>
- **Platform as a Service (PaaS)** - In this model, you can focus on the deployment and management of your applications. PaaS eliminates the need to manage the underlying infrastructure.
</br></br>
- **Software as a Service (SaaS)** - The software is ready to be used and operated by the service provider. SaaS is also known as an end-user application.

## Cloud Computing Deployment Models


- [Benefits of Cloud Computing ](#benefits-of-cloud-computing)
- [Types of Cloud Computing](#types-of-cloud-computing) 
- [Cloud Computing Deployment Models](#cloud-computing-deployment-models)
- [Cloud Infrastructure vs On-Premises Infrastructure](#cloud-infrastructure-vs-on-premises-infrastructure)




### The Deployment Models of the Cloud

| **Private Cloud**                                                        | **Public Cloud**                                                                                         | **Hybrid Cloud**                                                             |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| The deployment of resources on-premises, using virtualization and resource management tools, is sometimes **called the private cloud** |  the cloud provider makes resources available to the public through the internet. While the resources vary depending on the provider, it usually includes storage capabilities, applications, or virtual machines. | A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud |
|  On-premises deployment doesn’t provide many of the benefits of cloud computing but is sometimes sought for its ability to provide dedicated resources. |Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing.|Keep some servers on-premises and extend some capabilities to the Cloud.|


### Cloud Infrastructure vs On-Premises Infrastructure

1. **Public** - No upfront Investment, Low ongoing costs, Focus on innovation, Flexible capacity, Speed and agility, Global reach on demand
2. **Private** - Large initial purchase, Labour, patches, and upgrade cycles, System Administration, Fixed capacity, Long procurement and setup, Limited geographic regions
</br>
**What can you do in the cloud?** : Application hosting, Backup and Storage, Content delivery, Websites, Enterprise IT, Database
 


### Six Advantages of Cloud Computing

1. **Cost Savings**: Pay only for the computing power, storage, and other resources you use.
2. **Speed and Agility**: Quickly deploy services and resources.
3. **Scalability**: Easily scale resources up or down as needed.
4. **High Availability**: Highly available architecture for business continuity.
5. **Global Reach**: Access services from any geographical region.
6. **Security**: AWS provides robust security capabilities to protect your data.

### Problems Solved by the Cloud

- **High upfront costs**: Replaced by a pay-as-you-go model.
- **Scalability limitations**: Dynamic scaling to meet business demands.
- **Limited infrastructure availability**: Global infrastructure to support workloads.

### Types of Cloud Computing

| **Infrastructure as a Service (IaaS)**                                      | **Platform as a Service (PaaS)**                                                                               | **Software as a Service (SaaS)**                                                            |
| --------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Provides virtualized computing resources over the internet (e.g., AWS EC2). | Provides a platform allowing customers to develop, run, and manage applications (e.g., AWS Elastic Beanstalk). | Provides software applications over the internet on a subscription basis (e.g., AWS Chime). |
| Offers maximum control over the infrastructure.                             | Focus on deploying applications without managing underlying infrastructure.                                    | Accessible over the internet, usually via a web browser.                                    |
| Suitable for developers needing control over OS, middleware, and runtime.   | Ideal for developers who want to focus on application development.                                             | Suitable for users needing access to software without infrastructure management.            |

### Example of Cloud Computing Types

- **IaaS**: AWS EC2 (Elastic Compute Cloud)
  - GCP, Azure, Rackspace, Digital Ocean, Linode
- **PaaS**: AWS Elastic Beanstalk
  - Heroku, Google App Engine (GCP), Windows Azure (Microsoft)
- **SaaS**: AWS Chime
  - Google Apps (Gmail), Dropbox, Zoom

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
