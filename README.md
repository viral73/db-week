## Database Week at the AWS Loft

Database Week at the AWS Loft is an opportunity to learn about Amazon’s broad and deep family of managed database services. These services provide easy, scalable, reliable, and cost-effective ways to manage your data in the cloud.

## Current Labs
[Getting Started with Linux on Amazon EC2](https://github.com/wrbaldwin/db-week/blob/master/Labs/getting-started-with-ec2-linux.pdf) - This lab will walk you through launching, configuring, and customizing an EC2 virtual machine to run a web server. It will walk you though successfully provisioning and starting an EC2 instance using the AWS Management Console.

[Running SQL Server on Amazon RDS and Migrating to MySQL](https://github.com/wrbaldwin/db-week/blob/master/Labs/running-SQL-Server-on-Amazon-RDS-and-Migrating-to-MySQL.md) - If you'd like to move your SQL Server databases to the cloud, this workshop is for you. We review the basics of Amazon Relational Database Service (Amazon RDS) and how SQL Server databases run in Amazon RDS. We then leverage the combination of AWS Schema Conversion Tool (AWS SCT) and AWS Database Migration Service (AWS DMS), and we show you how to migrate your databases to Amazon Aurora MySQL. We provide an AWS CloudFormation template to set up the entire environment for the lab. You need a laptop with a Firefox or Chrome browser and a working AWS account.

[Getting Started with Amazon RDS](https://github.com/wrbaldwin/db-week/blob/master/Labs/RDS HOL.pdf) - Amazon RDS is a web service that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while managing time-consuming database administration tasks, freeing you up to focus on your applications and business.

[Replicate, Analyze, and Visualize Datasets Using AWS Database Migration Service and Serverless Big Data Technologies](https://github.com/wrbaldwin/db-week/blob/master/Labs/Reinvent2018-DAT308.zip) - In this workshop, you will use AWS serverless technologies to replicate, analyze, and visualize data from relational and semi-structured datasets to gain insight and drive business outcomes. You will leverage AWS Schema Conversion Tool (SCT) and AWS Database Migration Service (DMS) to convert MS SQL server database to Amazon Aurora Serverless MySQL, use AWS Glue to build data catalog & transform data, use Amazon Athena to run ad-hoc SQL queries and interactively analyze data stored on Amazon S3 data store, and use Amazon QuickSight to visualize data and drive additional insights.

[Accelerating Application Development with Amazon Aurora](https://github.com/wrbaldwin/db-week/blob/master/Labs/accelerating-application-development-with-Amazon-Aurora.md) - Learn how to leverage the unique features of the Amazon Aurora platform to build faster, more scalable database applications optimized for the cloud. We discuss architectural best practices and features, such as Aurora Serverless, Read Replica Auto-Scaling, Cross-Region Replicas, Backtrack, Fast Database Cloning, and Performance Insights. They are designed to help increase agility so you can develop applications faster to reach the widest possible audience. Through a hands-on lab, we help you understand how to best take advantage of the capabilities of the Aurora platform to effectively accelerate application development.

[Search Dynamo DB Data with Amazon Elasticsearch Service](https://github.com/wrbaldwin/db-week/blob/master/Labs/Search_DDB_Data_with_AES.pdf) - In this lab, you’ll explore using Amazon Elasticsearch Service (Amazon ES) to augment the more fundamental query capabilities of Amazon Dynamo DB (Dynamo DB). You’ll deploy a CloudFormation template that generates a Dynamo DB table and loads movie data into that table. You’ll employ Dynamo Streams to replicate the initial data load to an Amazon Elasticsearch Service domain. You’ll enable Cognito authentication to provide simple access to Kibana so that you can use Kibana’s UI to send searches to Amazon ES. Finally, you’ll run a Lambda function to generate updates to the Dynamo DB table, see those updates replicated to Amazon ES, and build Kibana visualizations for the changes.


[Building Your First Graph Application with Amazon Neptune](https://github.com/wrbaldwin/db-week/blob/master/Labs/Building_Your_First_Graph_Application_with_Amazon_Neptune.md) - In this session, get hands on with Amazon Neptune and build a cloud-based graph application. Learn how to quickly load data and begin writing Gremlin traversals.

## Old Labs

[Managed Database Basics](https://github.com/wrbaldwin/db-week/blob/master/Labs/managed-database-basics.md) - In this lab you will learn, how to create an EC2 instance for use as a SQL client that connects to an RDS/MySQL instance. Next, you will create a database, load a public Landsat dataset into it, and query your database using SQL. Finally, you will learn how to use the RDS console including stopping, starting, monitoring, snapshots and other RDS features.

[Aurora MySQL](https://github.com/wrbaldwin/db-week/blob/master/Labs/Aurora%20MySQL%20Hands%20On%20Lab%20Manual%202.1.pdf) - In this lab you will create Aurora MySQL DB Cluster, modify security group to allow access to the Aurora MySQL DB instance from your computer, load data from S3 into Aurora MySQL database, create read replica instance & access table, create a database copy using Aurora “Clone” feature, and perform DML query on primary DB and validate data on primary and cloned DB copy.

[Upgrading and Consolidating MySQL](https://github.com/wrbaldwin/db-week/blob/master/Labs/upgrading-and-consolidating-mySQL.md) - In this lab you will load data into a MySQL instance running on EC2. Next you will create an Aurora MySQL instance. Finally, you will use DMS to migrate data from one MySQL database to another.

[A Simple Database Migration](https://github.com/wrbaldwin/db-week/blob/master/Labs/a-simple-database-migration.md) - This workshop is a hands-on journey for existing Oracle DBAs moving to Aurora PostgreSQL. Attendees will deploy an instance of Aurora PostgreSQL, migrate and generate a test workload on PostgreSQL, and manually monitor the database to understand the workload. They will review a few ways to track queries and their execution plans, and what can be done to optimize the queries. Attendees will also learn how to do the same on Aurora PostgreSQL using Performance Insights for query analysis and tuning.

[Comparing Redis with Relational](https://github.com/wrbaldwin/db-week/blob/master/Labs/comparing-redis-with-relational.md) - In this lab you create an EC2 instance for use as a SQL and Redis client. Next, you will create an RDS instance using MySQL, connect your SQL client instance to your RDS instance. Then you will create a database and load a public landsat dataset into it and query your database using SQL. Finally, you will create an ElastiCache for Redis cluster, connect your Redis client instance to your ElastiCache cluster, and query your ElastiCache cluster using Redis commands.

[Using a Property Graph](https://github.com/paulfryer/neptune-developer-workshop/blob/master/Labs/Airports/README.md) - In the lab you will create a Neptune instance and configure security groups. You will then use Gremlin to run transversals after you load data into Neptune

[DynamoDB Basics](https://github.com/wrbaldwin/db-week/blob/master/Labs/dynamoDB-basics.md) - In this lab you will set up and use DynamoDB and DAX. You’ll need a laptop with a Firefox or Chrome browser.

[Break a Monolith Application into Microservices](https://aws.amazon.com/getting-started/projects/break-monolith-app-microservices-ecs-docker-ec2/) - In this tutorial, you will deploy a monolithic node.js application to a Docker container, then decouple the application into microservices without any downtime. The node.js application hosts a simple message board with threads and messages between users.
