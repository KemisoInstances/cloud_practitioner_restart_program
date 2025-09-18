### AWS Databases and Analytics Quiz

This quiz covers key AWS services for databases, data warehousing, and analytics.

---

### Question 1: Amazon DocumentDB High Availability

How does Amazon DocumentDB ensure high availability of data?
* A. By using local instance storage
* B. By automatically distributing data using sharding
* C. By replicating data to three Availability Zones
* D. Through manual backups and snapshots

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. By replicating data to three Availability Zones
  
  **Explanation:** Amazon DocumentDB automatically replicates six copies of your data across three Availability Zones. This provides high durability and availability, ensuring your data is protected from the failure of a single instance or an entire Availability Zone.
</details>

---

### Question 2: Amazon Relational Database Service (Amazon RDS)

Which of the following are true regarding Amazon Relational Database Service (Amazon RDS)? (Select TWO.)
* a. Provides 99.99999999999% reliability and durability
* b. Automatically scales up the relational database instance size based on the incoming workload
* c. It is a fully managed nonrelational database service
* d. Makes it easy to set up, operate, and scale a relational database
* e. Simplifies the management of time-consuming database administration tasks

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** d. Makes it easy to set up, operate, and scale a relational database and e. Simplifies the management of time-consuming database administration tasks
  
  **Explanation:** Amazon RDS is a managed service that simplifies the setup and operation of relational databases. It automates common administrative tasks like backups, patching, and scaling, but does not automatically scale the instance size in the same way that a service like Aurora Serverless does. The high durability percentage is a characteristic of services like Amazon S3 and DynamoDB, not RDS.
</details>

---

### Question 3: AWS’ Data Warehousing Service

Which of the following is AWS’ Data Warehousing service?
* A. Elastic Map Reduce
* B. Snowball
* C. Redshift
* D. S3 Big Data

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Redshift
  
  **Explanation:** Amazon **Redshift** is a fully managed, petabyte-scale data warehouse service in the cloud. It is designed for large-scale data analytics and business intelligence, making it the primary data warehousing solution offered by AWS.
</details>

---

### Question 4: Benefit of using RDS

Which of the following is an example of a benefit of using RDS?
* A. Database software installation and patching
* B. Scaling
* C. The optimization of your application using RDS
* D. All of these

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** A. Database software installation and patching and B. Scaling
  
  **Explanation:** Both database software installation/patching and scaling are core benefits of using Amazon RDS. As a managed service, AWS handles these administrative tasks, which are often time-consuming. "All of these" is a possible answer in some quizzes, but A and B are the most direct benefits.
</details>

---

### Question 5: Sales Data for Analysis

Your sales operations group would like to perform monthly analyses on large amounts of sales activity. They want to be able to rank the performance of different territories, product categories, and sales channels. They will use visualization tools to generate graphical representations of the data. Which AWS service will provide the best solution for storing the sales data?
* A. Amazon ElastiCache
* B. Amazon Redshift
* C. Amazon Aurora
* D. Amazon DynamoDB

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** B. Amazon Redshift
  
  **Explanation:** The use case described involves performing complex analytical queries on a large amount of data for business intelligence. **Amazon Redshift** is a data warehouse service specifically designed for this type of workload.
</details>

---

### Question 6: Traditional vs. Blockchain Database

What is one primary difference between a traditional database and a blockchain ledger?
* A. Blockchain data can be modified, while traditional database data is immutable.
* B. Traditional databases are decentralized, while blockchains are centralized.
* C. Blockchain records are immutable, while traditional database records can be updated or deleted.
* D. Blockchain supports SQL queries, while traditional databases do not.

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Blockchain records are immutable, while traditional database records can be updated or deleted.
  
  **Explanation:** A fundamental property of a blockchain is that its records are immutable and append-only. Once a record is added to the ledger, it cannot be changed or deleted. Traditional databases, in contrast, are designed to allow data to be updated or deleted.
</details>

---

### Question 7: Data Warehouse in AWS

Which of the following will allow you to create a data warehouse in AWS for your business intelligence needs?
* A. Amazon DynamoDB
* B. Amazon S3
* C. Amazon Redshift
* D. Amazon RDS

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Amazon Redshift
  
  **Explanation:** **Amazon Redshift** is the AWS service for building a data warehouse. It is optimized for running complex analytical queries on petabytes of data using standard SQL.
</details>

---

### Question 8: BI Tools and ETL

Which service in AWS supports various business intelligence tools such as Apache Spark so that you may perform data transformation workloads (ETL) and analytics at a low cost?
* A. Amazon RDS
* B. Amazon Redshift
* C. Amazon EMR
* D. Amazon OpenSearch

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Amazon EMR
  
  **Explanation:** **Amazon EMR (Elastic MapReduce)** is a managed cluster platform that simplifies running big data frameworks like Apache Spark and Hadoop. It is commonly used for ETL (Extract, Transform, Load) workloads and large-scale data analytics.
</details>

---

### Question 9: ETL Automation Service

A company has a large amount of data stored in multiple sources such as S3, Redshift, and RDS, and they need to extract, transform and load this data into a data warehouse. Which AWS service can help automate this process?
* A. AWS Lambda
* B. Amazon Athena
* C. AWS Glue
* D. Amazon EC2

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. AWS Glue
  
  **Explanation:** **AWS Glue** is a fully managed extract, transform, and load (ETL) service. It automatically crawls data sources, discovers schema, and generates Python or Spark code to transform and load the data.
</details>

---

### Question 10: Read-Heavy Database Workloads

A customer has a popular website that has millions of viewers from all over the world and has read-heavy database workloads. Which of the following is the best option to use to increase the read throughput on their database?
* A. Enable Amazon RDS Standby Replicas
* B. Enable Multi-AZ deployments
* C. Enable Amazon RDS Read Replicas
* D. Use Amazon SQS to queue up the requests

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Enable Amazon RDS Read Replicas
  
  **Explanation:** **Amazon RDS Read Replicas** are specifically designed to offload read traffic from the primary database instance. By creating one or more read replicas, you can distribute read queries across multiple instances, significantly increasing read throughput.
</details>

---

### Question 11: Permissioned Blockchain

In a permissioned blockchain, what is required for a participant to join the network?
* A. Proof of Work
* B. Public Key Infrastructure only
* C. None of the above
* D. Approval from a central authority or consortium

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Approval from a central authority or consortium
  
  **Explanation:** Unlike a public blockchain, a permissioned blockchain is a closed network where new members must be invited or approved by a central authority or a group of pre-approved participants (consortium).
</details>

---

### Question 12: Managed, Low-Cost Relational Database

You need a managed, low-cost relational database for your e-commerce store. Which of the following should you use?
* A. MySQL on EC2
* B. AWS ElastiCache
* C. RDS
* D. DynamoDB

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. RDS
  
  **Explanation:** **Amazon RDS** is the managed relational database service offered by AWS. It is designed to be easy to use and cost-effective for a wide range of workloads. MySQL on EC2 is not a managed service, and DynamoDB and ElastiCache are not relational databases.
</details>

---

### Question 13: Fast, Fully Managed Data Warehouse

Which of the following AWS services is a fast, fully managed data warehouse that makes it simple and cost-effective to analyse all your data using standard SQL and your existing Business Intelligence tools?
* A. Kinesis
* B. DynamoDB
* C. Redshift
* D. Elastic Map Reduce

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. Redshift
  
  **Explanation:** **Amazon Redshift** is the AWS service that perfectly fits this description. It is a managed data warehouse optimized for analytical queries using SQL.
</details>

---

### Question 14: Managed NoSQL Database

The Solutions Architect leading your project tells you the application your team is working on requires a managed NoSQL database. Which of the following AWS services best fits that description?
* A. Redshift
* B. ElastiCache
* C. RDS
* D. DynamoDB

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. DynamoDB
  
  **Explanation:** **Amazon DynamoDB** is AWS's fully managed, serverless NoSQL database service. It is designed for applications requiring high performance at any scale.
</details>

---

### Question 15: Database Migration Service

A company plans to migrate their on-premises MySQL database to Amazon RDS. Which AWS service should they use for this task?
* A. AWS Schema Conversion Tool (AWS SCT)
* B. AWS Glue
* C. AWS Application Migration Service
* D. AWS Database Migration Service (AWS DMS)

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. AWS Database Migration Service (AWS DMS)
  
  **Explanation:** **AWS Database Migration Service (DMS)** is specifically built to help you migrate databases to AWS quickly and securely with minimal downtime. It can be used for both homogeneous and heterogeneous migrations.
</details>

---

### Question 16: Quick SQL Server Setup

A group of Software Engineers is working on a project that requires a new Microsoft SQL Server database to be hosted in AWS. The team needs to ensure that the database can be set up quickly and efficiently to meet an urgent deadline. Which of the following AWS services should they use to meet their requirement? (Select TWO.)
* a. Amazon Aurora
* b. Amazon EC2
* c. Amazon Relational Database Service (Amazon RDS)
* d. Amazon Redshift
* e. Amazon Aurora Backtrack

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answers:** b. Amazon EC2 and c. Amazon Relational Database Service (Amazon RDS)
  
  **Explanation:** For a Microsoft SQL Server database, the two primary options are running it on an **Amazon EC2** instance or using the managed **Amazon RDS** service. RDS is the fastest way to get a SQL Server instance running as it automates setup and administration. Running it on EC2 gives you full control over the OS and database, but requires more manual setup.
</details>

---

### Question 17: RDS Multi-AZ Failover

What happens when an RDS Master database in a Multi-AZ deployment goes down?
* A. You must use the AWS console to promote the standby to Master.
* B. You must copy the attached EBS volume to the standby.
* C. The asynchronous replication of RDS Multi-AZ deployments means you will suffer some data loss.
* D. RDS automatically fails over to the standby, which is promoted to Master.

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. RDS automatically fails over to the standby, which is promoted to Master.
  
  **Explanation:** The primary benefit of an RDS Multi-AZ deployment is automatic failover. If the primary database instance becomes unavailable, RDS detects the failure and automatically promotes the standby replica to the new primary instance.
</details>

---

### Question 18: Blockchain Network Management

Which AWS service allows you to create and manage scalable blockchain networks using Hyperledger Fabric?
* A. AWS Ledger Manager
* B. Amazon DocumentDB
* C. Amazon QLDB
* D. Amazon Managed Blockchain

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** D. Amazon Managed Blockchain
  
  **Explanation:** **Amazon Managed Blockchain** is a fully managed service that helps you set up and manage a scalable blockchain network. It supports the popular open-source frameworks Hyperledger Fabric and Ethereum.
</details>

---

### Question 19: Cross-Region Object Storage

You need to store a collection of objects that can also be accessed from a different AWS Region. Which service should you use to do this?
* A. DynamoDB
* B. Elastic Container Service
* C. S3
* D. EBS

<details>
  <summary>Show Correct Answer</summary>
  
  **Correct Answer:** C. S3
  
  **Explanation:** **Amazon S3** is an object storage service that allows you to store and retrieve data from anywhere in the world. You can use S3's cross-region replication feature to automatically replicate objects to a bucket in a different AWS Region, ensuring the data is also accessible there.
</details>
