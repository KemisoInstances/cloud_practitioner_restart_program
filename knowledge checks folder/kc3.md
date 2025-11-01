### AWS Storage Quiz

Here are the answers to the questions, with collapsible sections for a clean review.

***

### Question 1: EBS Volume for Throughput

You are planning to deploy a video streaming application with frequently accessed, throughput-intensive workloads to your EC2 instance which requires fast, consistent throughput. What EBS volume type should you use to maximize performance as well as cost?
* a. Cold HDD
* b. General Purpose SSD
* c. Throughput Optimized HDD
* d. Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. Throughput Optimized HDD
  
  **Explanation:** Throughput Optimized HDD (`st1`) is specifically designed for frequently accessed, throughput-intensive workloads like big data, data warehousing, and log processing. It provides a good balance of performance and cost for this type of workload.
</details>

---

### Question 2: On-Premises to AWS Data Transfer

Which of the following AWS service can help you automate and simplify the process of transferring data between on-premises storage systems and AWS storage services?
* A. AWS Transfer Family
* B. AWS Direct Connect
* C. AWS Storage Gateway
* D. AWS DataSync

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS DataSync
  
  **Explanation:** **AWS DataSync** is a data transfer service that simplifies, automates, and accelerates moving data between on-premises storage and AWS storage services like Amazon S3 and Amazon EFS. It uses an optimized protocol to provide high-speed, secure data transfer.
</details>

---

### Question 3: S3 Storage Class for Unpredictable Access

A media company stores large video files in Amazon S3. These files are accessed heavily for the first few weeks after upload, but access frequency drops unpredictably over time. The operations team wants to optimise storage costs without impacting retrieval times, and they do not want to manage lifecycle policies manually. Which S3 storage class is the MOST suitable?
* A. S3 One Zone-Infrequent Access
* B. S3 Glacier Flexible Retrieval
* C. S3 Intelligent-Tiering
* D. S3 Standard-Infrequent Access (S3 Standard-IA)

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. S3 Intelligent-Tiering
  
  **Explanation:** **S3 Intelligent-Tiering** is designed for data with unpredictable or changing access patterns. It automatically moves objects between a frequent access tier and an infrequent access tier based on usage, helping you optimize costs without manual intervention or lifecycle policies.
</details>

---

### Question 4: S3 Durability

An e-commerce company is evaluating Amazon S3 for storing product images and order history data. The CTO wants assurance that the stored objects will not be lost due to hardware failures, even if multiple facilities are affected. What is the durability of objects stored in Amazon S3?
* A. 99.99%
* B. 99.95%
* C. 99.999999999%
* D. 100%

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. 99.999999999%
  
  **Explanation:** Amazon S3 is designed for **11 nines of durability** (99.999999999%) of objects over a given year. This is achieved by redundantly storing data across a minimum of three Availability Zones, protecting against hardware failure and data loss.
</details>

---

### Question 5: AWS Hybrid Storage

Which of the following is an AWS hybrid storage service that allows you to connect your on-premises data storage to Amazon S3 and simplify storage management?
* A. Internet Gateway
* B. AWS Direct Connect
* C. Amazon S3 Gateway Endpoint
* D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** is a hybrid cloud storage service that connects an on-premises software appliance with cloud-based storage. It allows you to seamlessly integrate your on-premises IT environment with AWS storage services.
</details>

---

### Question 6: S3 Cost Optimization

Which of the following should be used to automatically transfer infrequently accessed data in an Amazon S3 bucket to a more cost-effective storage class?
* A. AWS Storage Gateway
* B. AWS Transfer Family
* C. S3 Lifecycle Policy
* D. S3 access control list

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. S3 Lifecycle Policy
  
  **Explanation:** An **S3 Lifecycle Policy** is a set of rules that defines actions for objects throughout their lifespan. It can be used to automatically transition objects to a more cost-effective storage class (like S3 Standard-IA or S3 Glacier) after a specified number of days, helping to optimize storage costs.
</details>

---

### Question 7: Preventing Unauthorized S3 Deletion

There is an incident with your team where an S3 object was deleted using an account without the owner’s knowledge. What can be done to prevent unauthorized deletion of your S3 objects?
* A. Set up stricter IAM policies that will prevent users from deleting S3 objects
* B. Configure MFA delete on the S3 bucket.
* C. Set your S3 buckets to private so that objects are not publicly readable/writable
* D. Create access control policies so that only you can perform S3-related actions

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Configure MFA delete on the S3 bucket.
  
  **Explanation:** **MFA (Multi-Factor Authentication) Delete** is a feature that, when enabled on a versioned S3 bucket, requires an MFA code from a hardware or virtual MFA device to either permanently delete an object version or suspend versioning. This provides an additional layer of security against accidental or unauthorized deletion.
</details>

---

### Question 8: S3 Data Recovery

A company is using Amazon S3 to store various types of documents in a single bucket, and different teams frequently access the stored objects. If the document is accidentally overwritten or deleted, the data must be recoverable. Which of the following S3 features should they use?
* A. S3 Lifecycle
* B. S3 Versioning
* C. S3 Glacier Vault Lock
* D. S3 Event Notifications

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. S3 Versioning
  
  **Explanation:** **S3 Versioning** keeps multiple versions of an object in the same bucket. When an object is overwritten or deleted, a new version is created (or a delete marker is placed), allowing you to easily recover previous versions of the object.
</details>

---

### Question 9: Cost-Effective Long-Term Archiving

You have a large number of log files that will be archived in AWS for a long time and should have a retrieval time of 12 hours or less. Which service is the most cost-effective storage class for this purpose?
* A. Amazon S3 Glacier Deep Archive
* B. Amazon EBS Cold HDD
* C. Amazon S3 Glacier Instant Retrieval
* D. Amazon S3 Standard-IA

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** A. Amazon S3 Glacier Deep Archive
  
  **Explanation:** **Amazon S3 Glacier Deep Archive** is the lowest-cost storage class for long-term data archiving (data accessed once or twice a year). It provides a standard retrieval time of 12 hours, which aligns with the requirement and offers the lowest cost per GB.
</details>

---

### Question 10: Low Latency Content Delivery

Users from different parts of the globe are complaining about the slow performance of the newly launched photo-sharing website in loading their high-resolution images. Which combination of AWS services should you use to serve the files with lowest possible latency? (Select TWO.)
* A. Amazon Glacier
* B. Amazon S3
* C. Amazon Elastic File System
* D. Amazon CloudFront
* E. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** B. Amazon S3 and D. Amazon CloudFront
  
  **Explanation:** The solution involves storing the images in **Amazon S3** as a highly available and scalable object store. To reduce latency for global users, you would use **Amazon CloudFront**, a content delivery network (CDN) that caches the images at edge locations around the world, serving them to users from the nearest location.
</details>

---

### Question 11: S3 Cost Impact

Which of the following actions does not affect costs when using Amazon S3?
* A. Choosing S3 Standard IA rather than One Zone IA
* B. Data transfer costs for uploading objects into your S3 bucket.
* C. Making GET requests to your S3 objects
* D. Moving objects out of your S3 bucket to another bucket

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Data transfer costs for uploading objects into your S3 bucket.
  
  **Explanation:** There are **no data transfer costs for data ingress (uploading data) into Amazon S3** from the internet. All other options—choosing a different storage class, making requests, and transferring data out of S3—incur charges.
</details>

---

### Question 12: High-Performance Temporary Block Storage

Which AWS storage service offers faster disk read and write performance and provides temporary block-level storage for your instance?
* A. EBS Throughput Optimized HDD
* B. Instance Store
* C. EFS
* D. EBS Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Instance Store
  
  **Explanation:** An **Instance Store** provides temporary block storage that is physically attached to the host computer of an EC2 instance. It offers very high I/O performance but data stored on it is lost when the instance is stopped, terminated, or fails.
</details>

---

### Question 13: EBS Backups

You are planning to create point-in-time backups of your Amazon EBS volumes. Which of the following are correct statements? (Select TWO.)
* A. You can create point-in-time backups through EBS snapshots
* B. EBS backups are stored durably in Amazon S3
* C. Backing up the same EBS volume will create a new back up of the whole volume
* D. You can take EBS backups by creating Amazon Machine Images (AMIs)
* E. Instances will have to be stopped first to start the EBS backup

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** A. You can create point-in-time backups through EBS snapshots and B. EBS backups are stored durably in Amazon S3
  
  **Explanation:**
* **EBS snapshots** are point-in-time backups of EBS volumes. They are incremental, meaning only the blocks that have changed since the last snapshot are stored.
* All EBS snapshots are **stored durably in Amazon S3**, but you manage them from the EBS console.
* Snapshots are **incremental**, not full backups each time.
* You can create snapshots of a running volume, so you **do not need to stop the instance**.
* AMIs are used to create new instances with pre-configured software and settings, not to back up data volumes directly.
</details>

---

### Question 14: Recommended EBS Volume Type

What type of EBS volume is recommended for most workloads and is also usable as a boot volume?
* A. Throughput Optimized HDD
* B. Cold HDD
* C. General Purpose SSD
* D. Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. General Purpose SSD
  
  **Explanation:** **General Purpose SSD (gp2/gp3)** is a balanced EBS volume type that's suitable for a wide variety of transactional workloads, including boot volumes for EC2 instances. It is the default choice for most use cases due to its good performance-to-cost ratio.
</details>

---

### Question 15: Windows File System

An architectural design firm uses Windows-based applications that require native support for the SMB protocol and Windows NTFS permissions. They need a fully managed file system that integrates with Microsoft Active Directory and can be accessed by multiple Windows servers in AWS and on-premises. Which AWS service should they choose?
* A. Amazon FSx for Lustre
* B. AWS Storage Gateway
* C. Amazon EFS
* D. Amazon FSx for Windows File Server

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Amazon FSx for Windows File Server
  
  **Explanation:** **Amazon FSx for Windows File Server** is a fully managed, native Windows file system. It supports the SMB protocol and Windows NTFS permissions, and it can be seamlessly integrated with Microsoft Active Directory and accessed from both AWS and on-premises environments.
</details>

---

### Question 16: Exabyte-Scale Data Transfer

Which service must be used to quickly and securely transfer hundreds of petabytes of data to AWS?
* A. AWS Snowmobile
* B. AWS DataSync
* C. AWS Snowball Edge
* D. AWS Data Exchange

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** A. AWS Snowmobile
  
  **Explanation:** **AWS Snowmobile** is a petabyte-scale data transfer service that uses a secure, ruggedized shipping container to move exabytes of data. It is the most appropriate service for transferring extremely large datasets (hundreds of petabytes).
</details>

---

### Question 17: Long-Term Archiving

Where is the best place to archive logs and other infrequently accessed files for a long period of time?
* A. Amazon Storage Gateway
* B. Amazon EBS
* C. Amazon S3 Glacier Flexible Retrieval
* D. Amazon S3 Standard-IA

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Amazon S3 Glacier Flexible Retrieval
  
  **Explanation:** **Amazon S3 Glacier Flexible Retrieval** is specifically designed for long-term archiving where data is infrequently accessed. It provides various retrieval options, ranging from minutes to hours, at a very low cost.
</details>

---

### Question 18: On-Premises Storage Expansion

Which of the following services should you provision if your local data center requires additional storage space without having to migrate data?
* A. AWS Direct Connect
* B. AWS Storage Gateway
* C. AWS Backup
* D. AWS Snowball Edge

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** allows you to connect your on-premises applications to cloud storage, providing seamless, scalable storage for your local data center without a full-scale data migration. It acts as an extension of your on-premises storage.
</details>

---

### Question 19: Data Transport Appliances

Which of the following is a data transport solution that accelerates moving terabytes to petabytes of data into and out of AWS using appliances with on-board storage and compute capabilities?
* A. Lambda@Edge
* B. AWS DataSync
* C. AWS Snowcone
* D. AWS Snowball Edge

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS Snowball Edge
  
  **Explanation:** **AWS Snowball Edge** is a data migration and edge computing device. It is a rugged, portable appliance that you can use to transfer terabytes or petabytes of data into and out of AWS, and it also includes on-board computing capabilities.
</details>

---

### Question 20: Shared File System

Which AWS storage service is best suited for mounting a shared file system across multiple EC2 instances?
* A. Amazon Glacier
* B. Amazon EFS
* C. AWS Snowball
* D. Amazon S3

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Amazon EFS
  
  **Explanation:** **Amazon Elastic File System (EFS)** provides a scalable, managed file system that can be shared across multiple EC2 instances. It supports the NFS protocol, allowing many instances to access the same file system at the same time.
</details>

---

### Question 21: Hybrid Cloud Storage

A video production company wants to continue using its existing on-premises applications while expanding storage capacity in the cloud. The solution should provide seamless access to cloud-based files as if they were stored locally, and should also support data backup to virtual tapes. Which AWS service would best meet these requirements?
* a. AWS Storage Gateway
* b. AWS Transfer Family
* c. Amazon FSx for Windows File Server
* d. AWS Backup

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** a. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** is a hybrid storage service that provides on-premises applications with seamless access to cloud storage. The service can be configured as a file gateway (accessing S3 as a file share), a volume gateway, or a tape gateway for virtual tape backups. This makes it a perfect fit for both expanding storage and backing up data without changing existing workflows.
</details>

---

### Question 22: Secure File Transfer Protocols

A financial institution needs to securely migrate sensitive CSV files from an on-premises SFTP server to AWS, ensuring compatibility with existing workflows. The solution must support SFTP, FTPS, and FTP protocols while storing files directly in Amazon S3. Which AWS service BEST meets this requirement?
* A. AWS Snowball Edge
* B. AWS Transfer Family
* C. AWS DataSync
* D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. AWS Transfer Family
  
  **Explanation:** **AWS Transfer Family** is a fully managed service that enables the transfer of files into and out of Amazon S3 using SFTP, FTPS, and FTP. It is designed to work with existing file transfer workflows, making it the ideal solution for this use case.
</details>

---

### Question 23: Data Transfer in Constrained Environments

A customer in North Virginia, USA, is doing some drone work and collecting environmental data. Which of the following options allows easy access to terabytes of data storage for use in a space-constrained environment and allows data transfer to AWS?
* A. AWS Direct Connect
* B. AWS Transit Gateway
* C. AWS Snowcone
* D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. AWS Snowcone
  
  **Explanation:** **AWS Snowcone** is the smallest and most portable member of the AWS Snow Family. It is designed for data collection in space-constrained environments with limited or no network connectivity. It is a lightweight, rugged device that can be used to collect, process, and transfer data back to AWS either online or offline.
</details>

---

### Question 24: Centralized Backup Automation

Which AWS service centralizes and automates the backup of data across AWS services and on-premises environments, including compute, storage, and database resources?
* A. AWS Elastic Disaster Recovery
* B. AWS Backup
* C. AWS DataSync
* D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. AWS Backup
  
  **Explanation:** **AWS Backup** is a fully managed service that centralizes and automates backup across multiple AWS services (including EBS, RDS, EFS, and EC2) and on-premises environments, simplifying backup management and ensuring compliance with data protection policies.
</details>

---

### Question 25: Amazon S3 Characteristics

Which of the following characteristics correctly describes the Amazon Simple Storage Service? (Select TWO.)
* a. A durable, high throughput file system
* b. A highly durable object storage infrastructure
* c. A storage service with virtually unlimited space
* d. A hybrid cloud storage service
* e. A high-performance block storage service

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** b. A highly durable object storage infrastructure and c. A storage service with virtually unlimited space
  
  **Explanation:** **Amazon S3** is an object storage service, not a file or block storage service. It is known for its extreme durability (11 nines) and its ability to store a virtually unlimited amount of data.
</details>

---

### Question 26: Optimizing S3 Costs

A customer is using Amazon S3 to store sprites of game characters. When players retrieve these sprites, they are temporarily stored on the player’s computer. The sprites are currently stored in the S3 Standard storage class. Which of the following options would you recommend to optimize storage costs?
* A. Add a lifecycle policy to move sprites to S3 Glacier Flexible Retrieval after the customer uploads them.
* B. Have the customer directly upload the sprites to S3 Standard – Infrequent Access.
* C. Have the customer compress the sprites to reduce storage consumption.
* D. Add a lifecycle policy to move sprites to S3 Standard – Infrequent Access after the customer uploads them.

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Add a lifecycle policy to move sprites to S3 Standard – Infrequent Access after the customer uploads them.
  
  **Explanation:** The key information is that the sprites are "temporarily stored on the player's computer," implying they will be accessed frequently at first and then less so. Moving them directly to S3 Standard-IA or S3 Glacier is not cost-effective due to minimum storage durations and retrieval costs. The most suitable option is a **lifecycle policy** that automatically transitions the objects to a cheaper, infrequent access tier after a set period, such as 30 days, optimizing long-term storage costs.
</details>

---

### Question 27: S3 Bucket Access Control

A company is using Amazon S3 to store their static media contents such as photos and videos. Which of the following should you use to provide specific users access to the bucket?
* A. SSH key
* B. Security Group
* C. Bucket Policy
* D. Network Access Control List

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Bucket Policy
  
  **Explanation:** A **Bucket Policy** is an IAM resource-based policy that you attach to an S3 bucket to grant permissions to users or other AWS accounts. It is the primary way to manage fine-grained access to objects within a bucket.
</details>

---

### Question 28: Centralized Backup for Multiple Resources

A healthcare provider must comply with strict data retention policies for patient records. The organisation needs a centralised service to automate and manage backups for multiple AWS resources. Which AWS service should they use?
* A. AWS Storage Gateway
* B. Amazon S3 Glacier Deep Archive
* C. AWS Backup
* D. AWS DataSync

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. AWS Backup
  
  **Explanation:** **AWS Backup** is designed for exactly this use case. It provides a centralized service to automate and manage backups across multiple AWS services (including databases, block storage, and file systems) and can enforce compliance through backup plans and retention policies.
</details>

---

### Question 29: High-Performance Computing File System

A visual effects studio is rendering high-resolution animations on a Linux-based high-performance computing cluster. The workload requires millisecond latency, extremely high throughput, and seamless integration with Amazon S3 so results can be written back automatically after processing. Which AWS service is the BEST fit for this use case?
* A. Amazon EFS
* B. Amazon S3 Intelligent-Tiering
* C. Amazon FSx for Windows File Server
* D. Amazon FSx for Lustre

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Amazon FSx for Lustre
  
  **Explanation:** **Amazon FSx for Lustre** is a high-performance file system optimized for compute-intensive workloads like high-performance computing (HPC), machine learning, and media processing. It provides sub-millisecond latency and high throughput, and it can be seamlessly integrated with S3 to access and write back data.
</details>

---

### Question 30: Centralized, Scalable File Storage

A company has a fleet of on-premises servers that require a centralized scalable and durable file storage. It should be able to support massive parallel access. Which of the following is the most appropriate service to use?
* A. Amazon Storage Gateway – File Gateway
* B. Amazon Redshift
* C. Amazon Elastic File System (EFS)
* D. Amazon S3

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Amazon Elastic File System (EFS)
  
  **Explanation:** **Amazon EFS** is a scalable, fully managed file storage service for use with AWS Cloud services and on-premises resources. It is built to support massive parallel access from hundreds or thousands of clients, making it ideal for a fleet of on-premises servers that require shared file storage.
</details>
