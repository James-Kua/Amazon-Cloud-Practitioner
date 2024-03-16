---
title: "ACCP"
---


# AWS Certified Cloud Practitioner (ACCP) Exam Notes

This is my notes regarding ACCP exam which is completed gradually when I was studing the exam objectives.

The following table lists the main content domains and their weightings.<br>

<div align="center">

| Domain                            | % of Exam |
|:----------------------------------|:---------:|
| Domain 1: Cloud Concepts          | 26%       |
| Domain 2: Security and Compliance | 25%       |
| Domain 3: Technology              | 33%       |
| Domain 4: Billing and Pricing     | 16%       |
| **Total**                         | **100%**  |

</div>

***

### Amazon AppStream 2.0
- AWS End User Computing (EUC) service that can be configured for SaaS application **streaming or delivery of virtual desktops with selective persistence.** 
- When AppStream 2.0 is used for virtual desktops, saved files and application settings remain persistent between user sessions, and a fresh virtual desktop is assigned to the user every time they log on.


### Amazon Aurora
- Amazon Aurora provides built-in security, continuous backups, **serverless** compute, up to 15 read replicas, automated multi-Region replication, and integrations with other AWS services.
- Hands-off capacity management, and **pay only for capacity consumed** with instantaneous and fine-grained scaling to save up to 90% of cost.
- **MySQL and PostgreSQL** compatible **relational database engine** that combines the speed and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases


### AWS Artifact
- It is a self-service audit artifact retrieval **portal** that provides our customers with on-demand access to AWS’ **compliance documentation** and AWS **agreements**.
- You can use **AWS Artifact Reports** to download AWS security and compliance documents, such as <ins>AWS ISO certifications</ins>, <ins>Payment Card Industry (PCI)</ins>, and <ins>System and Organization Control (SOC) reports</ins>.
- It is **online**, self-service portal that AWS provides to enable customers to *view reports* and, such as *PCI reports*, and *accept agreements*.
- It is your **go-to**, central resource for compliance-related information that matters to you.



### Amazon Athena
- For interactive analysis
- Analyze data directly in **S3** and **Glacier** using <ins>standard SQL queries</ins>


### AWS Auto Scaling Group
- **Scaling Policy** determine when, if, and how the ASG scales and shrinks:
    - **on-demand**(dynamic scaling)
    - **cyclic**(scheduled scaling)
- **Scaling Plan** define the triggers and when instances should be provisioned/de-provisioned


### AWS Budgets
- With AWS Budgets, set custom budgets to track your costs and usage, and respond quickly to alerts received from email or SNS notifications if you exceed your threshold.


### AWS CloudFormation
- Allows you to model, provision, and manage AWS and third-party resources by treating **infrastructure as code.**
- It provides a **common language** for you to <ins>describe</ins> and <ins>provision</ins> all the infrastructure resources in your cloud environment.
- It's free of charge.
- **Change sets** allow you to preview how proposed changes to a stack might impact your running resources


### Amazon CloudFront
- It has a **global scope**.
- It is a content delivery network (**CDN**) that allows you to store (cache) your content at “**edge locations**” located around the world.
- This allows customers to access content **more quickly** and provides security against **DDoS attacks**.
- It can be used for **data**, **videos**, **applications**, and **APIs**.
- Routing policies:
    - simple
    - weighted
    - latency based
    - failover
    - geo-location
    - geo-proximity
    - multi-value
    - traffic flow
- It supports below **origins**:
    - S3 Bucket
    - EC2 instance
    - Elastic Load Balancer
    - Route 53



### AWS Cloud9
- It's a cloud-based integrated development environment (**IDE**) that lets you write, run, and debug your code with just a **browser**.



### AWS CloudHSM
- Is a **cloud-based hardware security module**(HSM) that allows you to easily <ins>add secure key storage</ins> and <ins>high performance crypto operations</ins> to your AWS applications.
- CloudHSM has **no upfront costs** and provides the ability to *start* and *stop* HSMs **on-demand**, allowing you to provision cpacity when and where it is needed quickly and cost-effectively.
- CloudHSM is a managed service that **automates** <ins>time-consuming administrative tasks</ins>, such as hardware provisioning, **software patching**, **high availability**, and **backups**.
- It uses a highly secure *hardware storage device* to **store encryption keys**


### AWS CloudTrail
- It is a web service that **records activity** made on your account and delivers <ins>log files</ins> to an **Amazon S3 bucket**.
- logging and saves a history of API calls for your AWS account.
- It is for **auditing**.
- It records account activity and service events from most AWS services and logs the following records:
    - The **identity of the API caller**.
    - The **time of the API call**.
    - The **source IP address of the API caller**.
    - The request parameters.
    - The response elements returned by the AWS service.

### AWS Cloudwatch
- Amazon CloudWatch collects and visualizes real-time logs, metrics, and event data in **automated dashboards** to streamline your infrastructure and application maintenance.


### AWS CodeBuild
- AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces ready-to-deploy software packages.


### AWS CodeStar
- It enables you to **quickly develop**, **build**, and **deploy** applications on AWS. AWS CodeStar provides a **unified user interface**, enabling you to easily manage your software development activities <ins>in one place</ins>.


### AWS CodeGuru
- CodeGuru Security uses ML and automated reasoning to precisely **identify code vulnerabilities**.


### AWS CodeCommit
- **Git-based Version Control**: CodeCommit is based on the popular Git version control system, providing all the standard Git functionalities such as branch management, pull requests, code reviews, and merging.

- **Secure and Private**: CodeCommit ensures the security of your source code by encrypting data in transit and at rest. It integrates with AWS Identity and Access Management (IAM) to manage user permissions and control access to repositories.

- **Scalable and Highly Available**: Amazon CodeCommit is a fully managed service, which means AWS handles the underlying infrastructure. It automatically scales to accommodate growing repositories and provides high availability to ensure your code is always accessible.

- **Integration with AWS Services**: CodeCommit seamlessly integrates with other AWS developer tools and services, such as AWS CodePipeline, AWS CodeBuild, and AWS CodeDeploy. This allows you to create a complete end-to-end continuous integration and deployment (CI/CD) pipeline.

- **Collaboration and Code Reviews**: CodeCommit supports collaboration among developers by facilitating code reviews and pull requests. It provides features to comment on code changes, request changes, and merge code branches.

- **Regional Replication**: CodeCommit allows you to replicate your repositories across multiple AWS regions, providing increased availability and disaster recovery capabilities.



### AWS CodeDeploy
- It is a deployment service that **automates application deployments** to <ins>Amazon EC2 instances</ins>, <ins>on-premises instances</ins>, or <ins>serverless Lambda functions</ins>.



### AWS CodePipeline
- AWS CodePipeline is a **continuous delivery service** you can use to **model**, **visualize**, and **automate the steps** required to release your software. You can quickly model and configure the different stages of a software release process. CodePipeline automates the steps required to release your software changes continuously.
- To orchestrate and **automate** the **various phases** involved in the release of application updates in-line with a predefined release model.



### AWS Cognito
- Add user sign-up and sign-in features and control access to your web and mobile applications.
- Provides an identity store that scales to millions of users, supports social and enterprise identity federation, and offers advanced security features to protect your consumers and business.



### Amazon Comprehend
- Amazon Comprehend is a natural language processing (**NLP**) service that uses **machine learning** to find insights and relationships in **text**.



### AWS Config
-  It allows you to **automate the evaluation of recorded** configurations against desired configuration.
-  It enables you to **assess**, **audit**, and **evaluate** the <ins>**configurations of your AWS resources**</ins>.
-  It continuously **monitors** and **records** your <ins>AWS resource configurations</ins> and allows you to automate the evaluation of recorded configurations against desired configurations.
-  It can be used to **keep track** of configuration changes on AWS resources, *keeping multiple date-stamped* versions in a reviewable history.
-  It can be used to **retrive configuration** changes made to AWS resources causing *operational issues*.



### AWS Cost Explorer
- It is a free tool that allows you to **view charts** of your costs. 
- You can view cost data for the **past 13 months** and **forecast** how much you are likely to spend over the **next three months**. 
- Cost Explorer can be used to **discover patterns** in how much you spend on AWS resources over time and to **identify cost problem** area.



### AWS Data Sync
- It is a simple and fast way to **move huge amounts** of data (hundreds of terabytes) between **on-premise** storage to **S3**, **EFS**, **FSx**.


### Amazon Detective
- It uses **machine learning** and **graph theory** capability collected log data to help you conduct faster and efficient security investigations.
- Supports the analysis, investigation, and **identification of the root cause of security and suspicious activities** in an AWS account


### Amazon DevPay
- That makes it easy for budinesses to **sell applications** that are built in, or run on top of, *Amazon Web Services*.


### AWS Device Farm
- It is an **app testing service** that lets you **test** and **interact** with your **Android**, **iOS**, and **web apps** on <ins>many devices</ins> at once, or reproduce issues on a device in real time



### AWS Direct Connect
- Benefits:
    - Reduce cost when using large volumes of traffic
    - Increase reliability (predictable performance)
    - Increase bandwidth (predictable bandwidth)
    - Decrease latency
- It uses <ins>private network connections</ins> (It's **NOT** based on internet connection)
- It is available in **1Gbps** and **10Gbps** speeds.
- When connecting to AWS over Direct Connect:
    - You can connect to all AZs **within the VPC** of the **local region**.
    - You can connect to public services in **remote regions**.
- You can use **AWS Direct Connect Gateway** for connecting a company from their on-premises network to VPCs in **multiple regions** using **private connections**



### Amazon DynamoDB
- It's a fully managed **NoSQL** database service. (schema-less)
- Offers consistent **single-digit millisecond performance** at any scale
- You can scale the DB at any time **without incurring downtime**.
- DaynamoDB pricing models:
    - **On-demand capacity mode**: charges you for the data reads and writes your application
    - **Provisioned capacity mode**: you specify the number of reads and writes per second that you expect
- Availability model:
    - **Data is synchronously** replicated across **3** facilities in a region
- Best practices for storing **large items** and attributes in DynamoDB:
    - <ins>Compress</ins> large attribute values
    - Store large attributes as objects in <ins>Amazon S3</ins>.


### AWS Database SQL type
- Amazon RDS
- Amazon Aurora
- Amazon RedShift


### Amazon ElastiCache
- Amazon ElastiCache is a fully managed, Redis- and Memcached-compatible service delivering real-time, cost-optimized performance for modern applications. 
- ElastiCache scales to hundreds of millions of operations per second with microsecond response time, and offers enterprise-grade security and reliability.
- Can be used to improve database performance


### Amazon Elastic Container Service for Kubernetes (EKS)
- It's a managed Kubernetes service that makes it easy for you to run Kubernetes on AWS without needing to install, operate, and maintain your own Kubernetes **control plane**.


### Amazon Elastic Container Service (ECS)
- It is used for running Docker containers on <ins>EC2 instances</ins>.


### Amazon Elastic Filesystem
- Amazon Elastic File System (EFS) automatically grows and shrinks as you add and remove files with no need for management or provisioning.
- Automatically provides high available across multiple Availability Zones
- Allows file sharing between multiple Amazon EC2 instances


### Amazon Elastic Transcoder
- It **converts video and audio files** from their source format into versions that will **playback** on devices like smartphones, tablets and PC


### Amazon Elasticsearch Service
- For **operational analytics** such as:
    - application monitoring
    - log analytics
    - clickstream analytics
- It allows you to search, explore, filter, aggrigate and visualize your data in near real-time.



### AWS EBS
- EBS Volume type
    - **Provisioned IOPS SSD**: supports **up to 50 IOPS** *per GiB* with **up to 32,000 IOPS** *per volume*.
    - **General Purpose SSD**: supports 3 IOPS per GiB and can burst up to 3000 IOPS (volumes > 334GB), and a maximum of **10,000** *per volume*.
    - Throughput Optimized HDD:
    - Cold HDD:
- The **easiest** way to store a backup of an EBS volume on Amazon S3: Create a **snapshot** of the volume.
- Amazon EBS snapshots are stored on *S3*.
- EBS volumes must be **in the same AZ** as the instances they are attached to
- You can use *Amazon Data Lifecycle Manager* (**Amazon DLM**) to automate the creation, retention, and deletion of snapshots taken to back up your Amazon EBS volumes.
- The Fundamental *charges* for EBS volumes are:
    - the amount of data **provisioned** (**not** *consumed*) *per* <ins>month</ins>.
    - amount you provision in **IOPS**
- The **root** EBS volumes are **deleted** on termination by <ins>default</ins>.
- Extra **non-root** volumes are **not deleted** on termination by <ins>default</ins>.
- Both non-root and root if launched from an **encrypted** AMI.


### Amazon EBS volumes types
- **General purpose (gp2)**(SSD): provides a good balance of price to performance, is suitable for most workloads and can be used as a system boot volume.
- **Provisioned IOPS (io1)**(SSD): is a high-performance volume type that is more expensive and should be used for apps that require the higher performance.
- **Cold HDD (sc1)**:  cannot be used as a boot volume and is good for throughput oriented storage for infrequently accessed data.
- **Throughput Optimized (st1)**: It is ideal for streaming workloads with fast throughput such as big data and data warehouses.


 
### Amazon EC2
- EC2 pricing model:
    - **On-Demand**: It is the **most economical** option that will ensure **no interruptions**.
    - **Spot**: They are good for **short term requirements** as they can be very economical. However, you may find that the instance is terminated if the spot market price moves.
    - **Dedicated Instance**: They are EC2 instances that run on hardware dedicated to a single customer.
    - **Reserved**: They are good for **long-term**, static requirements as you must lock-in for **1 or 3 years** in return for a decent discount.
- It offers SLAs of **95%** for *each region*.
- EC2 **benefits** over using non-cloud servers:
    - Elastic Web-Scale computing
    - Inexpensive
- Types of Reserved Instance (RI):
    - **Standard RIs**: These provide the **most significant discount** (up to 75% off On-Demand) and are best suited for **steady-state** usage.
    - **Convertible RIs**: These provide a discount (up to 54% off On-Demand) and the <ins>capability to change</ins> the attributes of the RI as long as the exchange results in the creation of Reserved Instances of equal or greater value. Like Standard RIs, Convertible RIs are best suited for steady-state usage.
    - **Scheduled RIs**: These are available to launch within the time windows you 	reserve. This option allows you to match your capacity reservation to a predictable 		recurring schedule that only requires a **fraction of a day, a week, or a month**.
    - Payment options for reserverd instances include All Upfront, Partial Upfront, and NoUpfront.
- With EC2 you are billed either by the **second**, for some Linux instances or by **hour**
- with "**Inter-Region VPC Peering**" a company can connect their EC2 instances in <ins>*one region*</ins> with EC2 instances in <ins>*another region*</ins> using **private IP** addresses



### Amazon ELB
- A **listener** is a process that checks for connection requests, using the protocol and port that you configure.
- Each listener has a default **rule**.
- Each rule **action** has a type.
- There are two types of **rule condition**:
    - host
    - path
- The primary **benefits** of using AWS ELB:
    - High availability
    - Elasticity



### AWS Elastic Beanstalk
-  The **fastest** and **simplest** way to get web applications up and running on AWS.
-  It is more of a **PaaS** service and is focused on <ins>web applications</ins> not infrastructure.


### Amazon EventBridge
- Amazon EventBridge is an event-driven service that makes it easy to integrate your applications with data from a variety of sources. 
- It can be used to **monitor AWS resources and third-party applications**, and respond to events in real-time.


### AWS Fargate
- Fargate <ins>removes the need to provision and manage servers</ins>.
- Amazon ECS is a container orchestration service used to provision and manage container clusters.
- It's a **Serverless** offering (**no** EC2 instances)



### AWS Glacier
- Data access option **retrieves** data:
    - **Standard**: takes 3-5 hours
    - **Expedited**: within 1-5 minutes
- That is accessed though  S3
- You *pay* for <ins>storage on a per GB/month</ins> basis, <ins>retrival requests</ins> and <ins>quantity</ins> (based on expedited, standard or bulk)
- For **interacting** with AWS **Glacier** require that you use the **AWS CLI** or write code (Using **REST API**)
- Only Amazon Glacier has **a minimum storage** duration charge of **90** days



### AWS Glue
- Is a fully managed **extract**, **transform**, and **load** (**ETL**) service that makes it easy for customers to prepare and load their <ins>data for analytics</ins>.


### Amazon Global Accelerator
- Global Accelerator provides two global static public IPs that **act as a fixed entry point to your application endpoints**, such as Application Load Balancers, Network Load Balancers, Amazon Elastic Compute Cloud (EC2) instances, and elastic IPs.
-  Users can access your application endpoints through static IP addresses to **enjoy deterministic routing independent of DNS**.
- You are asked to **improve the performance** of the application for <ins>local and global users</ins>. As part of this initiative, you must **monitor** the **application endpoint health** and **route traffic** to the most appropriate endpoint. For aiming this we should use amazon global accelerator.


### AWS Ground Station
- AWS Ground Station is a fully managed service that lets you control satellite communications, process data, and scale your operations without having to worry about building or managing your own ground station infrastructure.
  

### Amazon GuardDuty
- Amazon GuardDuty is a **threat detection** service that **continuously monitors** your AWS accounts and workloads for **malicious activity** and delivers detailed security findings for visibility and remediation.
- For implementing a threat detection service that continuously monitors malicious activities and **unauthorized behaviors** protect AWS account, workloads and data stored in Amazon S3, we use this service.



### Amazon IAM
- Lists all the users in an account and reports on the status of the account details, including passwords, access keys, and multi-factor authentication (MFA) devices
- You **cannot** use IAM to create **local user accounts** on any system.
- You are also not charged for what you use, <ins>IAM is free to use</ins>.
- You can share access to your AWS account
- AWS recommended **best practices**:
    - Create individual IAM users
    - Grant lease privilage
- IAM **supported authentication** methods include:
    - console passwords
    - access keys
    - server certificates
- Best practice to ensure the security of AWS account
    - **Don’t generate** an access key for the **root account** user
    - Use **Temporary Security Credentials** (IAM Roles) Instead of Long-Term Access Keys
    - Manage IAM User Access Keys Properly
- You can enable single sign-on (**SSO**) to your AWS accounts by using **federation** and AWS Identity and Access Management (IAM).
-  All you can do with an **access key** once it has been generated is to:
    - make active
    - make inactive
    - delete



### AWS Inspector
- Inspector is an *automated security assessment* service that helps improve the security and compliance of applications deployed on AWS.
- It uses an **agent** installed in EC2 instances and assesses applications for *vulnerabilities* and *deviations* from best practices.
- Organization can assess applications for vulnerabilities and **deviations** *from best practice*.


### AWS Internet Gateway
- Do not have **allow/deny** rules
- It attached at the **VPC level**



### Amazon Kendra
- Amazon Kendra is an intelligent enterprise search service that helps you **search across different content repositories** with built-in connectors.



### Amazon Kinesis
- It enables you to build custom applications that process or analyze **streaming data** for specialized needs.
- **Producers** continually push data to Kinesis data Streams and **Consumers** process the data in *real time*.
- Consumers can <ins>store their results</ins> using an AWS service such as:
    - Amazon DynamoDB
    - Amazon Redshift
    - Amazon S3
- There are four **types** of Kinesis services:
    - Kinesis Video Streams
    - Kinesis Data Streams
    - Kinesis Data Firehose
    - Kinesis Data Analytics


### AWS Lambda
- Lambda functions can be invoked in response to **events**.
    - Invoke a function in response to resource lifecycle events, such as with Amazon **S3**. (*Lambda & S3*)
    - Respond to incoming **HTTP requests**. (*Lambda & API Gateway*)
    - Consume events *from* a **queue**. (*Lambda & SQS*)
    - Run a function on a **schedule**. (*Lambda & CloudWatch*)


### AWS Lex
- Amazon Lex is a fully managed **artificial intelligence** (AI) service with advanced natural language models to design, build, test, and **deploy conversational interfaces in applications**.


### Amazon Lightsail
- It provides developers compute, storage, and networking capacity and capabilities ** deploy and manage websites, web applications, and databases in the cloud. Also it provides **preconfigured VPS** that inclouds **everything required to deploy** or create a **DB**.
- The **product set** includes:
    - **VPS** (Virtual Private Servers)
    - Managed **MySQL** databases
    - **HA** storage
    - **Load balancing**


### Amazon Load Balancers
- NLBs process traffic at the TCP level (layer 4)
- ALBs process traffic at the HTTP, HTTPS level (layer 7)
- CLBs process traffic at the TCP, SSL, HTTP and HTTPS levels (layer 4 & 7).
- Allows ddeploying of third-party firewall appliances on AWS, by connecting your on-premises firewall to your VPCs, and automatically routes traffic between them.



### Amazon Lightsail
- It provides developers compute, storage, and networking capacity and capabilities to deploy and manage websites, web applications, and databases in the cloud. Also it provides **preconfigured VPS** that inclouds **everything required to deploy** or create a **DB**.
- The **product set** includes:
    - **VPS** (Virtual Private Servers)
    - Managed **MySQL** databases
    - **HA** storage
    - **Load balancing**



### Amazon Macie
- It can be used to **detect users' personal credit card numbers** from data stored in Amazon **S3**.
- Identify and protect various data types, including PII, PHI, regulatory documents, API keys, and secret keys
- Verify compliance with automated logs that allow for instant auditing
- Identify changes to policies and access control lists
- Receive notifications when data and account credentials leave protected zones
- Detect when large quantities of business-critical documents are shared internally and externally



### Amazon Machine Image (AMI)
- It contains three catagories:
    - Community AMIs
    - AWS Marketplace AMIs
    - My AMIs
- It stores the **information** that defines an **EC2 instance** such as the template for the *root volume*, *launch permissions* and *block device mappings*.


### AWS Managed Services
- It manages the **daily operations** of your AWS infrastructure in alignment with **ITIL** processes and provides a **baseline integration** with IT Service Management (**ITSM**) tools such as the ServiceNow platform.


### Amazon Neptune
- Amazon Neptune is a fast, reliable, fully-managed **graph database** service that makes it easy to build and run applications that work with highly connected datasets.

### AWS Network Firewall
= Stateful, managed, network firewall and intrusion detection and prevention service for your VPC, allowing you to filter traffic at the perimeter of your VPC.



### AWS Organization
- **One bill provided** per AWS organization
- Best practices:
    -  Always enable **multi-factor** authentication (MFA) on the root account
    -  Always use a **strong and complex password** on the root account
    -  The **Paying account** should be used for **billing purposes only**. Do not deploy resources into the Paying account
-  With below options organizations can **reduce their cost**:
    -  "Create an AWS Organization configuration linking the accounts"
    -  "Setup consolidated billing between the accounts": company can reach volume discount thresholders sooner
- Share pre-purchased Amazon EC2 resources across accounts


### AWS Outposts
- Run applications and workloads **on premises** using familiar AWS services, tools, and APIs. 
- Outposts supports workloads and devices requiring **low latency access to on-premises systems**, local data processing, data residency, and application migration with local system interdependencies. 


### Amazon Polly
- Amazon Polly uses **deep learning technologies** to synthesize natural-sounding human speech, so you can **convert articles to speech**. With dozens of lifelike voices across a broad set of languages, use Amazon Polly to **build speech-activated applications**.


### AWS Pricing Policies
- pay-as-you-go
- save when you reserve
- pay less by using more


### Amazon Personalize
- Amazon Personalize allows developers to quickly **build and deploy curated recommendations and intelligent user segmentation** at scale using **machine learning (ML)**. 
- Because Amazon Personalize can be tailored to your individual needs, you can deliver the right customer experience at the right time and in the right place.


### AWS Personal Health Dashboard
- It provides **alerts** and **remediation** *guidance* when AWS is experiencing events that may *impact* you.



### Amazon QuickSight
- For dashboards and visualizations of insights from business data



### Amazon RDS
- Read replicas are used for **offloading read traffic** from the primary RDS database.
    - You can configure **read replicas** to be:
        - within as AZ
        - across AZs
        - across regions
- It provides "**Multi-AZ**" and "**Read Replicas**" to deliver *scalability*, *availibility* and *durability*.
- You can **restore** a DB instance to a specific **point in time** with a granularity of **5 minutes**
- **Multi-AZ**: <ins>synchronously</ins>
- **Read Replicas**: <ins>asynchronously</ins>
- RDS supports the following **engines**:
    - SQL Server
    - Oracle
    - MySQL Server
    - PostgreSQL
    - Aurora
    - MariaDB
- **Read replicas** are available for:
    - MySQL
    - PostgreSQL
    - MariaDB
    - Aurora
- RDS **automated** *backups* allow point in time recovery to any point within the retention period down to a second.
- RDS supports **automated backups** as a **default** configuration
- With RDS you are **charged for**:
    - the type and size of DB
    - document type (e.g multi AZ)
    - data transfer outbound
    - requests
    - the uptime
    - any additional storage of backup



### AWS Rekognition
- Amazon Rekognition offers pre-trained and customizable computer vision (CV) capabilities to **extract information and insights from your images and videos**.
- Facial recognition, image labelling, text detection, video segment detection


### Amazon Redshift
- Amazon Redshift uses SQL to **analyze structured and semi-structured data across data warehouses, operational databases, and data lakes**, using AWS-designed hardware and machine learning to deliver the best price performance at any scale.



### Amazon Route 53
- It has a **global scope**.
- Both **CNAME** records and **Alias** records can be used to <ins>map a domain name to a target domain name</ins>. However, only a **CNAME** record can be used to map to a target domain **external** to AWS.
- You can transfer domains to Route 53 only if the Top Level Domain (**TLD**) is supported
- Amazon **Route 53 health checks** monitor the health and performance of your web applications, web servers, and other resources
- It offers the following *functions*:
    - Domain Name registry
    - DNS resolution
    - Health checking of resources: detect outages
- **Routing policies** include:
    - Simple
    - Weighted
    - Latency-based
    - Failover
    - Geo-Location


### Amazon S3
-  Highly durable object storage service that provides high-level performance, security, scalability, and data availability
- **CRR** (Cross-region replication): enables automatic, asynchronous copying of objects across buckets in different AWS Regions.
- You cannot reserve capacity.
- IAM policies can be written to grant access to Amazon S3 buckets.
- Amazon S3 storage tier:
    - **S3 Standard** -> 99.99% SLA -> for data that is accessed less frequently, but
    requires rapid access when needed
    - **S3 Standard-IA** -> 99.9% SLA -> offers the high durability, high throughput, and low latency of S3 Standard
    - **S3 One Zone-IA** -> 99% SLA ->  *the most cost-effective* Amazon S3 storage tier for data that is not often accessed but requires high durability. It stores data in a **single** AZ
    - **Glacier** -> No SLA
- **Multipart upload** can be used to speed up uploads to S3
- **S3 Copy** -> up to 5GB in size in a single atomic operation
- **S3 Intelligent-Tiering** is an appropriate Amazon S3 storage class for "data with unknown/changing access pattern", which helps to optimise storage costs and results in cost savings
- **Data consistency** models available are:
    - Read after write consistency for PUTS of new objects
    - Eventual consistency for overwrite PUTS and DELETES (takes time to propagate)
- "**MFA delete**" adds a layer of additional security to prevent accidental deletion.
- Amazon S3 **objects** consist of:
    - Key
    - Value
    - Version ID
    - Metadata
- **Object lifecycle management** can be used with objects so that they are stored cost effectively throughout their lifecycle. Objects can be transitioned to another storage class or expired. It enables you to **set rules** to **automatically transfer** objects between different storage classes at defined time intervals.
- **Standard-IA** and **One Zone-IA** both have a minimum storage duration charge of **30** days



### AWS Security Groups
- Only `allow` rules, You cannot create `deny` rules.
- A security group is **stateful** but this is not a rule type
- You can create **inbound** and **outbound** traffic rules in a security group


### AWS Security Hub
- Cloud security posture management (CSPM) service that aggregates alerts from various AWS services and partner products in a standardised format


### AWS Scalability
AWS Scaling **vertically**: increasing the instance size/CPU/RAM/DISK,...
AWS Scaling **horizontally**: adding more EC2 instances, AWS Lambda adding concurrently executing functions, Adding read replicas to an Amazon RDS database


### Amazon SNS
- **Topics**: how you label and group different endpoints that you
send messages to
- **Subscriptions**: the endpoints that a topic sends messages to
- **Publisher**: the person/alarm/event that gives SNS the message
that needs to be sent


### Amazon Simple Queue Service (SQS)
- is a fully managed message queuing service that enables you to *decouple* and *scale microservices*, *distributed systems*, and *serverless applications*.
- **Use case**: *Decoupling application* components to ensure that there is no dependency on the availability of a single component.
- It can be used to ensure the **persistence** of **in-flight** *transactions independently* of any single application component.
- It is a message queue used for **decoupling** application components



### Amazon SageMaker
- That enables developers and data scientists to quickly and easily **build**, **train**, and **deploy** <ins>machine learning models</ins> at any scale. 



### Amazon Simple Notification Service (SNS)
- It is a web service that makes it easy to **set up**, **operate**, and **send notifications** <ins>from the cloud</ins>.
- SNS supports notifications over multiple transports including *HTTP/HTTPS*, *Email/Email-JSON*, *SQS* and *SMS*.
- It is used for building and *integrating* **loosely-coupled**, *distributed applications*
- Uses combination of publishers and subscribers



### AWS Support Plans
- **Basic**: Does not provide any <ins>*technical support*</ins>.
- **Developer**: Provides **business hours** access via **email**.
- **Business**: Provides < 1-hour response times for a <ins>production system failure</ins>.
- **Enterprise**: Provides < 1-hour response times for a <ins>production system failure</ins> but is a **more expensive**.
- All support plans provide "**24/7**":
    - access to customer service
    - documentation
    - whitepapers
    - support forums
- Only the **Enterprise** plan provides a **response time of < 15 minutes** for the failure of a *business-critical system*.
- Both **Business** and **Enterprise** offer < 1-hour response time for the failure of a production system.
- Only **business** and **enterprise** plans provide *support via* **email**, **chat** and **phone**.
- **Enterprise** plan comes with a *Technical Account manager* (**TAM**)
- **Developer** plan provides **email support** by **cloud support associates** team whereas **business** and **enterprise** provide **email support** by the **cloud support engineers** team.
- With the **Developer** plan you can open **unlimited** cases.



### AWS Shared Responsibility Model
- Customers are responsible for *networking traffic protection*.
- AWS are responsible for networking **infrastructure**.
- AWS are responsible for **compute infrastructure**.
- Customers are responsible for *network and firewall configuration*.
- **AWS** are responsible for **edge locations**.
- **Shared Controls**: Apply to both the *infrastructure layer* and *customer layers*
    - Patch Management: AWS -> Infra patches | Customer -> OS/Applications patches
    - Configuration Management: AWS -> Configuration of its infra devices | Customer -> Configuration their OS, Apps, DBs.


### AWS Shield
- AWS Shield is a managed DDoS protection service that safeguards applications running on AWS.
- Provides near **real-time visibility into attacks** on the company's resources


### AWS Storage Gateway Volume Gateway
- The volume gateway represents the family of gateways that *support* **block-based volumes**, previously referred to as gateway-cached and gateway-stored modes. it allows you to <ins>use block-based volumes on-premise</ins> that are then **asynchronously** backed up to Amazon **S3**.
    - **Stored Volumes mode**:  the *entire dataset is stored on-site* and is **asynchronously** backed up to S3 (EBS point-in-time snapshots). Snapshots are incremental and compressed
    - **Cached Volume mode**: the *entire dataset is stored on S3* and a cache of the *most frequently accessed* data is cached on-site.


### AWS Step Functions
- It lets you **coordinate** *multiple AWS services* into **serverless workflows** so you can build and update apps quickly.
- It keeps your Lambda functions free of additional logic by triggering and tracking each step of your application
- It lets you build **visual** *workflows*.


### Amazon Simple Workflow Service (SWF)
- helps developers build, run, and scale background jobs that have parallel or sequential steps.
- SWF is **not** a <ins>*visual*</ins> workflow tool.
- It can assist with **coordinating tasks** across *distributed application* components.


### Amazon Security Token Service (STS)
- It's used for requesting **temporary** credentials.


### AWS Server Migration Service (SMS)
- It's an **agentless** service which makes it easier and faster for you migrate on-premises workloads to AWS.
- You can migrarte Virtual Machines from **VMware vSphere** and **Windows Hyper-V** to AWS with this sevice.



### AWS Service Catalog
- It can be used to <ins>create and manage a selection of AWS services</ins> that are approved for use on AWS.
- These IT services **can include everything** from virtual machine images, servers, software, and databases to complete multi-tier application architectures.



### Amazon S3 Transfer Acceleration
- It enables fast, easy, and secure **transfers** of files **over long distances** between your client and your Amazon S3 bucket.
- Uses the AWS backbone network and edge locations to **reduce latencies** from the end user to Amazon S3



### AWS Snowball
- It is a **petabyte-scale** <ins>data transport</ins> solution that uses devices designed to be secure to transfer large amounts of data **into and out of** the AWS Cloud.


### AWS Snowball Edge
- Snowball Edge can do **local processing and edge-computing workloads** in addition to transferring data between your local environment and the AWS Cloud.


### AWS Snowcone
- AWS Snowcone is a small, rugged, and secure device offering **edge computing, data storage, and data transfer on-the-go**, in austere environment with **little or no connectivity**.


### Amazon Textract
- Amazon Textract is a machine learning (ML) service that automatically **extracts text, handwriting, and data from scanned documents**.



### AWS Trusted Advisor
- An **online resource** that helps to *reduce cost*, *increase performance* and *improve security* by **optimizing** your AWS environment.
- Five *categories* of Trusted Advisor:
    - Cost optimization
    - Security
    - Performance
    - Service limits
    - Fault tolerance
- It can be used to **display current usage and limits**. It offers a Service Limits check (in the *Performance* category) that displays your usage and limits for some aspects of some services
- It can be used to provide **real time guidance** on provisioning resources following *AWS best practices*.
- It can be used to **check service limits** for resources launched within AWS Infrastructure.
- Can be used to check for IAM access keys that have not been rotated recently
- Can identiify any security group that is allowing unrestricted incoming SSH traffic



### AWS TCO Calculator
- It can be used to **compare** the *cost of running* your applications in an *on-premises* or colocation environment to *AWS*.
- "**Compute Hardware**" and "**Data Center Security**" should be included in a TCO analysis comparing on-premise to AWS Cloud.



### AWS WAF
- Is a **web application firewall** that protects against **common exploits** that could compromise application availability, compromise security or consume excessive resources.
- **Create custom rules** that block <ins>common attack patterns</ins>, such as:
    - SQL injection.
    - Cross-site scripting.
    - Rules that are designed for your specific application
- Used by Cloudfront and API Gateway
- Protects web apps by filtering, monitoring and **blocking any malicious HTTP/S traffic** travelling to the web application, and prevents any unauthorized data from leaving the app


### Amazon Workspaces
- Amazon WorkSpaces is a managed, secure cloud-based virtual desktop infrastructure (VDI) that allows users to access their desktop applications and documents from anywhere, on any supported device.


### AWS X-Ray
- It is a service that helps developers **analyze** and **debug** distributed applications.
- Can see detailed information not only about the request and response, but also about calls that your application makes to downstream AWS resources, microservices, databases, and web APIs.


### Cloud Computing
- Cloud computing is the **on-demand** delivery of compute power.
- With cloud computing you get to <ins>benefit from massive economies of scale</ins>.
- With cloud computing you can <ins>increase your speed and agility</ins>.


### Virtual Private Gateway
- It's the VPN concentrator on the **Amazon side** of the <ins>VPN connection</ins>.
-  You create a virtual private gateway and *attach* it to the **VPC** from which you want to create the VPN connection.
-  <ins>NAT devices and firewalls</ins> are **not** required for an *AWS managed VPN*.
-  A **customer gateway** is a physical device or software application on **your side** of the VPN connection.


### VPC peering connection
- if you have **more than one AWS account**, you can **peer** the VPCs across those accounts to create a <ins>file sharing network</ins>.
- You **cannot** peer *subnets*.
- It is a way of <ins>allowing routing between VPCs</ins> in *different AWS accounts*.
- It enables you to route traffic via **private IP addresses** between *two* peered VPCs.
- It enables the company to define its own IP address range, configure route tables and network gateways


### Five design principles for performance efficiency in the cloud
1. Democratize advanced technologies
2. Go global in minutes
3. Use serverless architectures
4. Experiment more often
5. Mechanical sympathy


### Five design principles for cost optimization in the cloud
1. Adopt a consumption model
2. Measure overall efficiency
3. Stop spending money on data center operations
4. Analyze and attribute expenditure
5. Use managed services to reduce cost of ownership


### Five design principles for reliability in the cloud
1. Test recovery procedures
2. Automatically recover from failure
3. Scale horizontally to increase aggregate system availability
4. Stop guessing capacity
5. Manage change in automation


### Six design principles for security in the cloud
1. Implement a strong identity foundation
2. Enable traceability
3. Apply security at all layers
4. Automate security best practices
5. Protect data in transit and at rest
6. Prepare for security events


### Five pillars of the AWS Well-Architected Framework
1. Operational excellence
2. Security
3. Reliability
4. Performance efficiency
5. Cost optimization


### Six advantages of Amzon Cloud (Benefits)
- Trade capital expense for variable expense.
- Benefit from massive economies of scale.
- Stop guessing about capacity.
- Increase speed and agility.
- Stop spending money running and maintaining data centres.
- Go global in minutes.


### Cloud Adoption Framework
- **Business**
The Business perspective helps ensure that your cloud investments accelerate your digital transformation ambitions and business outcomes. Common stakeholders include chief executive officer (CEO), chief financial officer (CFO), chief operations officer (COO), chief information officer (CIO), and chief technology officer (CTO).

- **People**
The People perspective serves as a bridge between technology and business, accelerating the cloud journey to help organizations more rapidly evolve to a culture of continuous growth, learning, and where change becomes business-as-normal, with focus on culture, organizational structure, leadership, and workforce. Common stakeholders include CIO, COO, CTO, cloud director, and cross-functional and enterprise-wide leaders.

- **Governance**
The Governance perspective helps you orchestrate your cloud initiatives while maximizing organizational benefits and minimizing transformation-related risks. Common stakeholders include chief transformation officer, CIO, CTO, CFO, chief data officer (CDO), and chief risk officer (CRO).

- **Platform**
The Platform perspective helps you build an enterprise-grade, scalable, hybrid cloud platform, modernize existing workloads, and implement new cloud-native solutions. Common stakeholders include CTO, technology leaders, architects, and engineers.
 
- **Security**
The Security perspective helps you achieve the confidentiality, integrity, and availability of your data and cloud workloads. Common stakeholders include chief information security officer (CISO), chief compliance officer (CCO), internal audit leaders, and security architects and engineers.
 
 

***
### Notes
- Network ACLs **allows or denies specific inbound or outbound traffic** at the subnet level.
- A **security group is associated with an EC2 instance,** whereas a **network ACL is associated with a subnet**.
- You can modify the rules for a security group at any time; you can’t modify the rules for a network ACL until you disassociate it from the subnet.
- **Security groups are stateful**; **network ACLs are stateless**. This means that if you allow traffic in one direction, traffic is allowed in the other direction also. With a network ACL, you must explicitly allow traffic in both directions.
- **Bootstrapping** and **Infrastructure as code** are two echniques for using automated, repeatable processes that are fast and avoid human error.
- **Golden Image Instances**: A golden image is a snapshot of a particular state for that resource. (e.g. EC2 instances, RDS instances, EBS volumes)
- "**Direct Connect**" and "**VPN CloudHub**" are two ways of connecting to an *Amazon VPC* from an *on-premise* data center.
- If you have **multiple VPN connections**, you can provide secure communication **between sites** using the **AWS VPN CloudHub**.
- "**File Gateway**" and "**Gateway Virtual Tape Library**" are types of <ins>AWS storage gateway</ins>.
- "**virtual gateway**" on the <ins>VPC side</ins> and a **customer gateway** on <ins>the on-premise network side</ins> are need to connect VPC with a VPN connection (Those are <ins>parts of Amazon Managed VPN connection</ins>).
- *AWS Managed VPN* uses **internet connection**
- **Resource groups** make it easy to group resources using the tags that are assigned to them. You can group resources that share one or more tags
- **NAT instances** are managed by **you** and they must be **scaled manually** and <ins>do not provide HA</ins>. They can be used as **bastion** hosts and can be *assigned to security groups*.
- **NAT Gateway** are managed for you by **AWS**. They can **scale automatically** and they are **not** *associated with any security groups*. They are highly available in **each AZ**.
- You can use **DynamoDB** and **SWF** for create a "stateless" application
- These are valid use cases for using AWS services to implement **real-time auditing**:
    - Use Amazon Inspector to monitor for compliance
    - Use AWS Lambda to scan log files
- Only the **Memcached** and **Redis** database engines can be used with **ElastiCache**
- **AWS Migration Hub** provides a **single location** to <ins>track the progress of application migrations</ins> across multiple AWS and partner solutions.
- The *EC2 container registry* (**ECR**) is a managed AWS Docker registry service for storing, managing and deploying Docker images.
- **Amazon Aurora Multi-Master** can scale out **write** performance for their Amazon Aurora database across *multiple* availability zones.
- **Placement groups** are a logical grouping of instances in one of the following configurations:
- **Cluster**: It's a logical grouping on intances **within a single AZ**. Cluster placement groups are recommended for **applications** that benefit from **low network latency**, **high network throughput**, or both, and if the majority of the network traffic is between the instances in the group
- A **spread**:  that are each placed on **distinct** underlying hardware. Spread placement groups are recommended for **applications** that have **a small number of critical instances** that should be kept separate from each other
- With "**EC2**, **Auto Scaling** and **E**lastic **L**oad **B**alancing" combination of AWS services could be used to deploy a **stateless** web application that can automatically and elastically scale.
- With the AWS cloud you get **fine-grained** billing and can **turn off resources** you are not using easily and not have to pay for them.
- In IAM user access and secrert keys:
    -  The customer is responsible for **rotating** keys.
- _Which compute hosting model should be accounted for in the Total Cost of Ownership (TCO) when undertaking a cost analysis that allows physical isolation of a customer workload?_ **Dedicated Hosts**.
- **Cost allocation tags** help track your AWS costs on a detailed level. After you activate cost allocation tags, AWS uses the cost allocation tags to organize your resource costs on your cost allocation report, to make it easier for you to categorize and track your AWS costs.
- **AWS Region** is a physical location around the world where data centers are clustered
- **Availability Zones** is one or more discrete data centers with redundant power, networking and connectivity
- **Edge locations**: part of the AWS global infrastructure that provides low-latency access to content by storing copies of data close to end users. Edge locations are strategically placed in multiple geographic areas around the world and are optimized to deliver content quickly and efficiently to end users.

