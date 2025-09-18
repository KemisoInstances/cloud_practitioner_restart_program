# AWS Quiz on Storage, Hybrid Cloud, and Data Transfer

This quiz is for self-study. You can click on the checkboxes to select your answers. To see the correct answer and an explanation, expand the "Show Correct Answer" dropdown.

---

### Question 1: EBS Volumes
You are planning to deploy a video streaming application with frequently accessed, throughput-intensive workloads to your EC2 instance which requires fast, consistent throughput. What EBS volume type should you use to maximize performance as well as cost?

- [ ] a. Cold HDD
- [ ] b. General Purpose SSD
- [ ] c. Throughput Optimized HDD
- [ ] d. Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** c. Throughput Optimized HDD
  
  **Explanation:** **Throughput Optimized HDD (st1)** is a low-cost HDD volume type designed for frequently accessed, throughput-intensive workloads with large datasets, such as big data, data warehousing, and log processing. It provides fast, consistent throughput but is not suitable for small, random I/O operations.
</details>

---

### Question 2: Hybrid Cloud
Which of the following AWS service can help you automate and simplify the process of transferring data between on-premises storage systems and AWS storage services?

- [ ] A. AWS Transfer Family
- [ ] B. AWS Direct Connect
- [ ] C. AWS Storage Gateway
- [ ] D. AWS DataSync

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS DataSync
  
  **Explanation:** **AWS DataSync** is a data transfer service that simplifies, automates, and accelerates moving data between on-premises storage systems and AWS storage services (like S3, EFS, or FSx). It's designed for high-performance data migration.
</details>

---

### Question 3: S3 Storage Classes
A media company stores large video files in Amazon S3. These files are accessed heavily for the first few weeks after upload, but access frequency drops unpredictably over time. The operations team wants to optimise storage costs without impacting retrieval times, and they do not want to manage lifecycle policies manually. Which S3 storage class is the MOST suitable?

- [ ] A. S3 One Zone-Infrequent Access
- [ ] B. S3 Glacier Flexible Retrieval
- [ ] C. S3 Intelligent-Tiering
- [ ] D. S3 Standard-Infrequent Access (S3 Standard-IA)

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. S3 Intelligent-Tiering
  
  **Explanation:** **S3 Intelligent-Tiering** is designed for data with unknown or unpredictable access patterns. It automatically moves objects between a frequent access tier and an infrequent access tier, optimizing storage costs without any operational overhead or manual lifecycle policies. It also has no impact on retrieval times for frequently or infrequently accessed data.
</details>

---

### Question 4: S3 Durability
An e-commerce company is evaluating Amazon S3 for storing product images and order history data. The CTO wants assurance that the stored objects will not be lost due to hardware failures, even if multiple facilities are affected. What is the durability of objects stored in Amazon S3?

- [ ] A. 99.99%
- [ ] B. 99.95%
- [ ] C. 99.999999999%
- [ ] D. 100%

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. 99.999999999%
  
  **Explanation:** Amazon S3 is designed for **11 nines (99.999999999%)** of durability. This is achieved by redundantly storing objects across multiple devices in a minimum of three Availability Zones, protecting against hardware failures, data corruption, and other issues.
</details>

---

### Question 5: Hybrid Cloud
Which of the following is an AWS hybrid storage service that allows you to connect your on-premises data storage to Amazon S3 and simplify storage management?

- [ ] A. Internet Gateway
- [ ] B. AWS Direct Connect
- [ ] C. Amazon S3 Gateway Endpoint
- [ ] D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** is a hybrid cloud storage service that connects an on-premises software appliance with cloud-based storage. It allows you to store data in the cloud while retaining local access for low-latency operations.
</details>

---

### Question 6: S3 Cost Optimization
Which of the following should be used to automatically transfer infrequently accessed data in an Amazon S3 bucket to a more cost-effective storage class?

- [ ] A. AWS Storage Gateway
- [ ] B. AWS Transfer Family
- [ ] C. S3 Lifecycle Policy
- [ ] D. S3 access control list

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. S3 Lifecycle Policy
  
  **Explanation:** An **S3 Lifecycle Policy** defines rules to automatically transition objects to a different storage class (for cost savings) or expire them after a set period. This is the correct method for automating the movement of data between storage tiers.
</details>

---

### Question 7: S3 Security
There is an incident with your team where an S3 object was deleted using an account without the owner’s knowledge. What can be done to prevent unauthorized deletion of your S3 objects?

- [ ] A. Set up stricter IAM policies that will prevent users from deleting S3 objects
- [ ] B. Configure MFA delete on the S3 bucket.
- [ ] C. Set your S3 buckets to private so that objects are not publicly readable/writable
- [ ] D. Create access control policies so that only you can perform S3-related actions

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Configure MFA delete on the S3 bucket.
  
  **Explanation:** **MFA (Multi-Factor Authentication) Delete** is an S3 bucket-level feature that requires a user to authenticate with a physical or virtual MFA device to permanently delete an object version or change the S3 Versioning state of the bucket. This adds an extra layer of security against accidental or malicious deletions.
</details>

---

### Question 8: S3 Versioning
A company is using Amazon S3 to store various types of documents in a single bucket, and different teams frequently access the stored objects. If the document is accidentally overwritten or deleted, the data must be recoverable. Which of the following S3 features should they use?

- [ ] A. S3 Lifecycle
- [ ] B. S3 Versioning
- [ ] C. S3 Glacier Vault Lock
- [ ] D. S3 Event Notifications

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. S3 Versioning
  
  **Explanation:** **S3 Versioning** keeps multiple versions of an object in the same bucket. If an object is accidentally deleted or overwritten, you can restore a previous version of the object. This is a crucial feature for data recovery and protection.
</details>

---

### Question 9: S3 Archival
You have a large number of log files that will be archived in AWS for a long time and should have a retrieval time of 12 hours or less. Which service is the most cost-effective storage class for this purpose?

- [ ] A. Amazon S3 Glacier Deep Archive
- [ ] B. Amazon EBS Cold HDD
- [ ] C. Amazon S3 Glacier Instant Retrieval
- [ ] D. Amazon S3 Standard-IA

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** A. Amazon S3 Glacier Deep Archive
  
  **Explanation:** **S3 Glacier Deep Archive** is the lowest-cost storage class for long-term data archiving (7-10 years or more). It offers retrieval times of up to 12 hours, which meets the requirement and makes it the most cost-effective choice for cold data with long-term retention needs.
</details>

---

### Question 10: Low-Latency File Delivery
Users from different parts of the globe are complaining about the slow performance of the newly launched photo-sharing website in loading their high-resolution images. Which combination of AWS services should you use to serve the files with lowest possible latency? (Select TWO.)

- [ ] A. Amazon Glacier
- [ ] B. Amazon S3
- [ ] C. Amazon Elastic File System
- [ ] D. Amazon CloudFront
- [ ] E. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** B. Amazon S3 and D. Amazon CloudFront
  
  **Explanation:** You should store the images in **Amazon S3** as a highly available object store. To deliver these images with low latency to a global user base, you should use **Amazon CloudFront**, which is a Content Delivery Network (CDN) that caches the content at Edge Locations around the world, closer to your users.
</details>

---

### Question 11: S3 Costs
Which of the following actions does not affect costs when using Amazon S3?

- [ ] A. Choosing S3 Standard IA rather than One Zone IA
- [ ] B. Data transfer costs for uploading objects into your S3 bucket.
- [ ] C. Making GET requests to your S3 objects
- [ ] D. Moving objects out of your S3 bucket to another bucket

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Data transfer costs for uploading objects into your S3 bucket.
  
  **Explanation:** Data transfer into an Amazon S3 bucket from the internet is generally **free**. All other options involve costs: different storage classes have different prices, GET requests are a billable operation, and data transfer out of an S3 bucket is charged.
</details>

---

### Question 12: Storage
Which AWS storage service offers faster disk read and write performance and provides temporary block-level storage for your instance?

- [ ] A. EBS Throughput Optimized HDD
- [ ] B. Instance Store
- [ ] C. EFS
- [ ] D. EBS Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Instance Store
  
  **Explanation:** An **Instance Store** provides temporary, block-level storage for an EC2 instance. The data on an instance store volume persists only during the life of the instance, but it offers very low latency and high I/O performance.
</details>

---

### Question 13: EBS Snapshots
You are planning to create point-in-time backups of your Amazon EBS volumes. Which of the following are correct statements? (Select TWO.)

- [ ] A. You can create point-in-time backups through EBS snapshots
- [ ] B. EBS backups are stored durably in Amazon S3
- [ ] C. Backing up the same EBS volume will create a new back up of the whole volume
- [ ] D. You can take EBS backups by creating Amazon Machine Images (AMIs)
- [ ] E. Instances will have to be stopped first to start the EBS backup

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** A. You can create point-in-time backups through EBS snapshots and B. EBS backups are stored durably in Amazon S3
  
  **Explanation:** **EBS snapshots** are point-in-time backups of your EBS volumes. They are stored durably in **Amazon S3**. The snapshots are incremental, which means that only the blocks that have changed since the last snapshot are stored, making the process more efficient. Snapshots can be taken while the volume is in use; a stop is not required.
</details>

---

### Question 14: EBS Volumes
What type of EBS volume is recommended for most workloads and is also usable as a boot volume?

- [ ] A. Throughput Optimized HDD
- [ ] B. Cold HDD
- [ ] C. General Purpose SSD
- [ ] D. Provisioned IOPS SSD

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. General Purpose SSD
  
  **Explanation:** **General Purpose SSD (gp2/gp3)** is the default and recommended EBS volume type for a wide variety of transactional workloads. It balances cost and performance, making it suitable for boot volumes and many general-purpose applications.
</details>

---

### Question 15: File Systems
An architectural design firm uses Windows-based applications that require native support for the SMB protocol and Windows NTFS permissions. They need a fully managed file system that integrates with Microsoft Active Directory and can be accessed by multiple Windows servers in AWS and on-premises. Which AWS service should they choose?

- [ ] A. Amazon FSx for Lustre
- [ ] B. AWS Storage Gateway
- [ ] C. Amazon EFS
- [ ] D. Amazon FSx for Windows File Server

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Amazon FSx for Windows File Server
  
  **Explanation:** **Amazon FSx for Windows File Server** provides a fully managed, highly reliable file system that is optimized for Windows-based workloads. It supports the native SMB protocol, NTFS permissions, and integrates with Microsoft Active Directory, making it a perfect fit for this use case.
</details>

---

### Question 16: Data Transfer
Which service must be used to quickly and securely transfer hundreds of petabytes of data to AWS?

- [ ] A. AWS Snowmobile
- [ ] B. AWS DataSync
- [ ] C. AWS Snowball Edge
- [ ] D. AWS Data Exchange

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** A. AWS Snowmobile
  
  **Explanation:** **AWS Snowmobile** is an exabyte-scale data transfer service used to move massive amounts of data to AWS. It is a 45-foot ruggedized shipping container, pulled by a semi-trailer truck, that is capable of transferring up to 100 PB of data. This is ideal for transferring hundreds of petabytes.
</details>

---

### Question 17: Archival Storage
Where is the best place to archive logs and other infrequently accessed files for a long period of time?

- [ ] A. Amazon Storage Gateway
- [ ] B. Amazon EBS
- [ ] C. Amazon S3 Glacier Flexible Retrieval
- [ ] D. Amazon S3 Standard-IA

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Amazon S3 Glacier Flexible Retrieval
  
  **Explanation:** **S3 Glacier Flexible Retrieval** is a cost-effective storage class designed for long-term archiving where data is accessed infrequently. It offers multiple retrieval options, from minutes to hours, making it suitable for logs and other non-time-sensitive archived data.
</details>

---

### Question 18: Hybrid Cloud
Which of the following services should you provision if your local data center requires additional storage space without having to migrate data?

- [ ] A. AWS Direct Connect
- [ ] B. AWS Storage Gateway
- [ ] C. AWS Backup
- [ ] D. AWS Snowball Edge

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** allows you to seamlessly extend your on-premises storage to the cloud. It provides local storage in the form of a virtual or hardware appliance and backs up that data to Amazon S3, allowing you to scale your storage without a full migration.
</details>

---

### Question 19: Data Transfer
Which of the following is a data transport solution that accelerates moving terabytes to petabytes of data into and out of AWS using appliances with on-board storage and compute capabilities?

- [ ] A. Lambda@Edge
- [ ] B. AWS DataSync
- [ ] C. AWS Snowcone
- [ ] D. AWS Snowball Edge

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS Snowball Edge
  
  **Explanation:** **AWS Snowball Edge** is a data migration and edge computing device that provides 80 TB or 210 TB of storage. It is used to transfer terabytes to petabytes of data into or out of AWS, as well as to run EC2 instances for edge computing.
</details>

---

### Question 20: Shared File System
Which AWS storage service is best suited for mounting a shared file system across multiple EC2 instances?

- [ ] A. Amazon Glacier
- [ ] B. Amazon EFS
- [ ] C. AWS Snowball
- [ ] D. Amazon S3

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** B. Amazon EFS
  
  **Explanation:** **Amazon EFS (Elastic File System)** is a scalable, fully managed file storage service that is purpose-built for multiple EC2 instances to access a shared file system simultaneously. It provides a file system interface and is perfect for use cases like web serving or containerized applications.
</details>

---

### Question 21: Hybrid Storage
A video production company wants to continue using its existing on-premises applications while expanding storage capacity in the cloud. The solution should provide seamless access to cloud-based files as if they were stored locally, and should also support data backup to virtual tapes. Which AWS service would best meet these requirements?

- [ ] a. AWS Storage Gateway
- [ ] b. AWS Transfer Family
- [ ] c. Amazon FSx for Windows File Server
- [ ] d. AWS Backup

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** a. AWS Storage Gateway
  
  **Explanation:** **AWS Storage Gateway** is the correct hybrid service for this use case. It allows on-premises applications to use cloud storage seamlessly. The virtual tape library (VTL) functionality within Storage Gateway is specifically designed for backing up data using virtual tapes that are stored in AWS.
</details>

---

### Question 22: File Transfer Protocol
A financial institution needs to securely migrate sensitive CSV files from an on-premises SFTP server to AWS, ensuring compatibility with existing workflows. The solution must support SFTP, FTPS, and FTP protocols while storing files directly in Amazon S3. Which AWS service BEST meets this requirement?

- [ ] A. AWS Snowball Edge
- [ ] B. AWS Transfer Family
- [ ] C. AWS DataSync
- [ ] D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** B. AWS Transfer Family
  
  **Explanation:** **AWS Transfer Family** is a fully managed service that provides secure file transfers using SFTP, FTPS, and FTP. It allows you to use your existing file transfer workflows and clients while storing the files directly into an Amazon S3 bucket.
</details>

---

### Question 23: Data Transfer
A customer in North Virginia, USA, is doing some drone work and collecting environmental data. Which of the following options allows easy access to terabytes of data storage for use in a space-constrained environment and allows data transfer to AWS?

- [ ] A. AWS Direct Connect
- [ ] B. AWS Transit Gateway
- [ ] C. AWS Snowcone
- [ ] D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** C. AWS Snowcone
  
  **Explanation:** **AWS Snowcone** is the smallest member of the Snow Family. It is designed for use in space-constrained or remote environments, providing a highly portable way to collect, process, and transfer data back to AWS either online or offline.
</details>

---

### Question 24: Backup
Which AWS service centralizes and automates the backup of data across AWS services and on-premises environments, including compute, storage, and database resources?

- [ ] A. AWS Elastic Disaster Recovery
- [ ] B. AWS Backup
- [ ] C. AWS DataSync
- [ ] D. AWS Storage Gateway

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** B. AWS Backup
  
  **Explanation:** **AWS Backup** is a fully managed, centralized backup service that makes it easy to automate and manage backups across multiple AWS services (like EBS, EFS, RDS, and DynamoDB) and on-premises workloads.
</details>

---

### Question 25: S3 Characteristics
Which of the following characteristics correctly describes the Amazon Simple Storage Service? (Select TWO.)

- [ ] a. A durable, high throughput file system
- [ ] b. A highly durable object storage infrastructure
- [ ] c. A storage service with virtually unlimited space
- [ ] d. A hybrid cloud storage service
- [ ] e. A high-performance block storage service

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answers:** b. A highly durable object storage infrastructure and c. A storage service with virtually unlimited space
  
  **Explanation:** Amazon S3 is a highly durable object storage service with a durability of 99.999999999%. It is also a key feature of S3 that it offers virtually unlimited storage capacity.
</details>

---

### Question 26: S3 Cost Optimization
A customer is using Amazon S3 to store sprites of game characters. When players retrieve these sprites, they are temporarily stored on the player’s computer. The sprites are currently stored in the S3 Standard storage class. Which of the following options would you recommend to optimize storage costs?

- [ ] A. Add a lifecycle policy to move sprites to S3 Glacier Flexible Retrieval after the customer uploads them.
- [ ] B. Have the customer directly upload the sprites to S3 Standard – Infrequent Access.
- [ ] C. Have the customer compress the sprites to reduce storage consumption.
- [ ] D. Add a lifecycle policy to move sprites to S3 Standard – Infrequent Access after the customer uploads them.

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** D. Add a lifecycle policy to move sprites to S3 Standard – Infrequent Access after the customer uploads them.
  
  **Explanation:** The sprites are accessed frequently at first, then stored on the user's computer, meaning they become infrequently accessed. An S3 Lifecycle policy is the correct tool to automatically transition objects to a less expensive storage class, like **S3 Standard-IA**, once they are no longer frequently accessed.
</details>

---

### Question 27: S3 Access Control
A company is using Amazon S3 to store their static media contents such as photos and videos. Which of the following should you use to provide specific users access to the bucket?

- [ ] A. SSH key
- [ ] B. Security Group
- [ ] C. Bucket Policy
- [ ] D. Network Access Control List

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** C. Bucket Policy
  
  **Explanation:** A **Bucket Policy** is a resource-based policy used to grant or deny access to a specific S3 bucket and its objects. It can be used to control access for specific IAM users, accounts, or services.
</details>

---

### Question 28: Backup
A healthcare provider must comply with strict data retention policies for patient records. The organisation needs a centralised service to automate and manage backups for multiple AWS resources. Which AWS service should they use?

- [ ] A. AWS Storage Gateway
- [ ] B. Amazon S3 Glacier Deep Archive
- [ ] C. AWS Backup
- [ ] D. AWS DataSync

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** C. AWS Backup
  
  **Explanation:** **AWS Backup** is a fully managed service that centralizes and automates the process of creating and managing backups across multiple AWS services, helping organizations meet their compliance and data retention requirements.
</details>

---

### Question 29: File Systems
A visual effects studio is rendering high-resolution animations on a Linux-based high-performance computing cluster. The workload requires millisecond latency, extremely high throughput, and seamless integration with Amazon S3 so results can be written back automatically after processing. Which AWS service is the BEST fit for this use case?

- [ ] A. Amazon EFS
- [ ] B. Amazon S3 Intelligent-Tiering
- [ ] C. Amazon FSx for Windows File Server
- [ ] D. Amazon FSx for Lustre

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** D. Amazon FSx for Lustre
  
  **Explanation:** **Amazon FSx for Lustre** is a high-performance file system designed for compute-intensive workloads like high-performance computing (HPC) and machine learning. It provides sub-millisecond latency and high throughput and has native integration with Amazon S3 to easily process data.
</details>

---

### Question 30: File Systems
A company has a fleet of on-premises servers that require a centralized scalable and durable file storage. It should be able to support massive parallel access. Which of the following is the most appropriate service to use?

- [ ] A. Amazon Storage Gateway – File Gateway
- [ ] B. Amazon Redshift
- [ ] C. Amazon Elastic File System (EFS)
- [ ] D. Amazon S3

<details>
  <summary>Show Correct Answer</s-ummary>
  
**Correct Answer:** C. Amazon Elastic File System (EFS)
  
  **Explanation:** **Amazon EFS** is a highly scalable and durable file system that can be mounted by thousands of EC2 instances and also accessed from on-premises using AWS Direct Connect or a VPN. This makes it an ideal choice for a shared, centralized file storage that supports massive parallel access.
</details>

<br>

<br>

To learn more about how S3 Intelligent-Tiering automatically optimizes storage costs, you can watch this video: [Amazon S3 Intelligent-Tiering Overview](https://www.youtube.com/watch?v=QB2TUII3wtc).
http://googleusercontent.com/youtube_content/1
