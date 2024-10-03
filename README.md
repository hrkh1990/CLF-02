1. Identity and Access Management (IAM)

	•	Users: Represents individuals or services accessing AWS resources.
	•	Groups: Logical grouping of users for managing permissions collectively.
	•	Policies: Documents that define permissions. Policies are assigned to users, groups, or roles.
	•	Roles: A set of permissions that AWS resources can assume, useful for services like EC2, Lambda, etc.
	•	Security Features:
	•	MFA (Multi-Factor Authentication): Adds a second layer of protection.
	•	Access Keys: Used for programmatic access.
	•	Audit Tools:
	•	IAM Credential Reports: Provides a report of all users and their credentials status.
	•	Access Advisor: Shows permissions granted to a user and last accessed time.

2. Compute Services

	•	Amazon EC2: Virtual servers in the cloud, with flexible instance types and pricing models.
	•	AWS Lambda: Run code without provisioning or managing servers. Scales automatically based on demand.
	•	AWS Elastic Beanstalk: Platform as a Service (PaaS) for deploying web applications and services.
	•	AWS Fargate: Serverless compute for containers, integrated with Amazon ECS and EKS.
	•	AWS Outposts: Extends AWS services to on-premises environments for hybrid cloud solutions.
	•	Amazon Lightsail: Easy-to-use virtual private servers, ideal for simple workloads.
	•	AWS Batch: Run batch computing jobs at any scale.
	•	AWS Local Zones: Extend AWS regions closer to end-users for low-latency applications.
	•	AWS Wavelength: Brings AWS services to the edge of 5G networks for ultra-low-latency applications.

3. Storage Services

	•	Amazon S3: Object storage with scalability, availability, and performance.
	•	Amazon S3 Glacier: Low-cost archival storage for long-term backups.
	•	Amazon Elastic Block Store (EBS): Persistent block storage for EC2 instances.
	•	Amazon Elastic File System (EFS): Managed file storage for EC2 instances, scalable.
	•	Amazon FSx: Managed file systems for Windows, Lustre, and NetApp.
	•	AWS Backup: Centrally managed backup solution for AWS resources.
	•	AWS Elastic Disaster Recovery: Ensures minimal downtime for mission-critical applications by quickly recovering from failures.
	•	AWS Storage Gateway: Provides hybrid cloud storage, enabling on-premises resources to use cloud storage.

4. Networking and Content Delivery

	•	Amazon VPC: Virtual Private Cloud that allows isolation of resources.
	•	Amazon Route 53: Scalable domain name system (DNS) web service for routing users to applications.
	•	AWS Direct Connect: Establishes a dedicated network connection from your premises to AWS.
	•	AWS VPN: Connects on-premise resources to AWS over a secure, encrypted connection.
	•	AWS Global Accelerator: Improves application performance for global users by routing traffic through the AWS global network.
	•	Amazon CloudFront: Content Delivery Network (CDN) that caches content globally for low-latency access.
	•	Amazon API Gateway: Fully managed service for creating and managing APIs.

5. Databases

	•	Amazon RDS (Relational Database Service): Supports MySQL, PostgreSQL, MariaDB, Oracle, and SQL Server.
	•	Amazon Aurora: MySQL and PostgreSQL-compatible relational database, offering high performance.
	•	Amazon DynamoDB: Fully managed NoSQL database for fast, predictable performance.
	•	Amazon Neptune: Fully managed graph database.
	•	Amazon MemoryDB for Redis: Fully managed, Redis-compatible in-memory database for high availability.
	•	Amazon Redshift: Fully managed data warehouse optimized for complex queries.
	•	Amazon ElastiCache: Managed Redis and Memcached for in-memory caching.

6. Analytics

	•	Amazon Athena: Query data in S3 using SQL without needing to provision infrastructure.
	•	Amazon QuickSight: Scalable business intelligence service for creating dashboards.
	•	AWS Glue: Serverless ETL (Extract, Transform, Load) service.
	•	Amazon Kinesis: Real-time data streaming and analytics.
	•	Amazon Redshift: Data warehousing for big data analytics.
	•	Amazon Managed Streaming for Apache Kafka (MSK): Managed service for Apache Kafka.
	•	Amazon OpenSearch Service: Managed service to search, analyze, and visualize large volumes of data.
	•	AWS Data Exchange: Facilitates the exchange and access of third-party data sets.
	•	Amazon EMR (Elastic MapReduce): Managed big data platform using Apache Hadoop and Spark.

7. Application Integration

	•	Amazon Simple Queue Service (SQS): Message queuing service to decouple application components.
	•	Amazon Simple Notification Service (SNS): Push notifications for sending messages to multiple endpoints.
	•	AWS Step Functions: Orchestrates multiple AWS services into serverless workflows.
	•	Amazon EventBridge: Serverless event bus service to connect different AWS services and external applications.

8. Security, Identity, and Compliance

	•	AWS IAM (Identity and Access Management): Manages user permissions and access to resources.
	•	AWS Artifact: Provides access to AWS compliance reports and agreements.
	•	AWS Shield: DDoS protection for AWS resources.
	•	AWS WAF (Web Application Firewall): Protects web applications by filtering and monitoring HTTP/HTTPS requests.
	•	Amazon GuardDuty: Threat detection service that monitors malicious activity and unauthorized behavior.
	•	Amazon Macie: Detects and protects sensitive data in S3.
	•	AWS Key Management Service (KMS): Manages cryptographic keys and integrates with AWS services for encryption.
	•	AWS Secrets Manager: Automates the rotation, management, and retrieval of secrets such as database credentials and API keys.
	•	AWS CloudHSM: Hardware security module for managing encryption keys.
	•	Amazon Cognito: Provides user authentication and authorization for web and mobile applications.

9. Management and Governance

	•	AWS CloudFormation: Infrastructure as code tool for automating AWS resource provisioning.
	•	AWS Systems Manager: Provides operational insights into AWS resources and automates management tasks.
	•	AWS Trusted Advisor: Offers real-time guidance to help optimize your AWS environment.
	•	AWS Control Tower: Automates the setup of a multi-account AWS environment following best practices.
	•	Amazon CloudWatch: Monitors AWS resources, collects metrics, and generates alarms.
	•	AWS Config: Tracks configuration changes and evaluates compliance.
	•	AWS Auto Scaling: Automatically adjusts the capacity of AWS services to maintain performance and cost efficiency.
	•	AWS Service Catalog: Manages approved AWS services across the organization.
	•	AWS Resource Access Manager (RAM): Enables resource sharing between AWS accounts.
	•	AWS License Manager: Simplifies management of software licenses from vendors like Microsoft.

10. Developer Tools

	•	AWS CodePipeline: Automates CI/CD workflows.
	•	AWS CodeBuild: Fully managed build service to compile code and run tests.
	•	AWS CodeDeploy: Automates the deployment of applications to EC2, Lambda, or on-prem servers.
	•	AWS CodeCommit: Managed source control service that hosts Git repositories.
	•	AWS CodeStar: Enables rapid application development in AWS using integrated AWS services.
	•	AWS Cloud9: Cloud-based integrated development environment (IDE) for writing, running, and debugging code.
	•	AWS CLI: Command-line tool for managing AWS services.
	•	AWS X-Ray: Debugs and traces requests as they travel through distributed applications.

11. Migration and Transfer

	•	AWS DMS (Database Migration Service): Helps migrate databases to AWS.
	•	AWS Application Migration Service: Simplifies migrating on-premises applications to AWS.
	•	AWS Migration Hub: Tracks progress of application migrations across AWS.
	•	AWS Snow Family: Transfers large datasets into AWS using physical devices.
	•	AWS Transfer Family: Transfers files directly into S3 and EFS via SFTP, FTPS, or FTP.
	•	AWS SCT (Schema Conversion Tool): Converts database schemas and application code during database migration.

12. Customer Engagement

	•	Amazon Connect: Cloud-based contact center service.
	•	Amazon SES (Simple Email Service): Provides scalable email sending capabilities.
	•	AWS IQ: Connects customers with certified AWS experts.
	•	AWS Activate: Provides startups with AWS credits, training, and resources.

13. Cost Management

	•	AWS Cost Explorer: Allows detailed cost tracking and analysis of AWS spending.
	•	AWS Budgets: Set custom budgets and receive alerts when nearing limits.
	•	AWS Billing Conductor: Provides insights into AWS billing and invoicing.
	•	AWS Cost and Usage Reports (CUR): Provides the most detailed cost and usage data for AWS resources.
	•	AWS Marketplace: Digital catalog for third-party software and services available on AWS.

14. Business Productivity

	•	Amazon WorkSpaces: Virtual desktops in the cloud for remote workers.
	•	Amazon WorkSpaces Web: Web-based applications for secure, managed browsing.
	•	Amazon AppStream 2.0: Application streaming for delivering desktop applications securely.
	•	Amazon SES (Simple Email Service): Scalable cloud-based email sending.

15. End-User Computing

	•	Amazon WorkSpaces: Cloud-based desktop service.
	•	Amazon AppStream 2.0: Stream desktop applications to users in real-time.

16. Frontend Web and Mobile

	•	AWS Amplify: Develop and deploy scalable mobile and web applications.
	•	AWS AppSync: Serverless GraphQL API for building real-time applications.
	•	AWS Device Farm: Testing applications across real devices.

17. Internet of Things (IoT)

	•	AWS IoT Core: Securely connects IoT devices to the cloud.
	•	AWS IoT Greengrass: Enables local execution of AWS services on IoT devices.

18. Machine Learning

	•	Amazon SageMaker: Build, train, and deploy machine learning models.
	•	Amazon Comprehend: NLP service to analyze text and extract insights.
	•	Amazon Rekognition: Image and video analysis for object detection and facial recognition.
	•	Amazon Textract: Extracts text and data from scanned documents.
	•	Amazon Polly: Converts text to lifelike speech.
	•	Amazon Lex: Build conversational interfaces and chatbots.
	•	Amazon Kendra: Enterprise search service powered by machine learning.
	•	Amazon Transcribe: Converts speech to text.
	•	Amazon Translate: Automatic language translation.
