<!-- fetched 2026-10-13 from https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.AuroraPostgreSQL.html by sweep-shape-compat.py; text extracted from the provider's own page -->

Working with Amazon Aurora PostgreSQL - Amazon Aurora 
 View a markdown version of this page 
 Working with Amazon Aurora PostgreSQL - Amazon Aurora 
 Documentation Amazon RDS User Guide for Aurora 
 Working with Amazon Aurora PostgreSQL
 Amazon Aurora PostgreSQL is a fully managed, PostgreSQL–compatible, and ACID–compliant relational
 database engine that combines the speed, reliability, and manageability of Amazon Aurora
 with the simplicity and cost-effectiveness of open-source databases. Aurora PostgreSQL is a
 drop-in replacement for PostgreSQL and makes it simple and cost-effective to set up,
 operate, and scale your new and existing PostgreSQL deployments, thus freeing you to focus
 on your business and applications. To learn more about Aurora in general, see
 What is Amazon Aurora? . 
 In addition to the benefits of Aurora, Aurora PostgreSQL offers a convenient migration pathway from
 Amazon RDS into Aurora, with push-button migration tools that convert your existing RDS for PostgreSQL
 applications to Aurora PostgreSQL. Routine database tasks such as provisioning, patching, backup, recovery,
 failure detection, and repair are also easy to manage with Aurora PostgreSQL. 
 Aurora PostgreSQL can work with many industry standards. For example, you can use
 Aurora PostgreSQL databases to build HIPAA-compliant applications and to store healthcare
 related information, including protected health information (PHI), under a completed
 Business Associate Agreement (BAA) with AWS.
 Aurora PostgreSQL is FedRAMP HIGH eligible. For details about AWS and compliance efforts,
 see AWS services in scope by
 compliance program . 
 Important
 If you encounter an issue with your Aurora PostgreSQL DB cluster, your AWS support agent might need more information about the health of your databases. 
 The goal is to ensure that AWS Support gets as much of the required information as possible in the shortest possible time.
 You can use PG Collector to help gather valuable database information in a consolidated HTML file. For more information on PG Collector, how to run it, and how to download the HTML report, see 
 PG Collector .
 Upon successful completion, and unless otherwise noted, the script returns output in a readable HTML format. The script is designed to exclude any data or security details from the HTML that might compromise your business. 
 It also makes no modifications to your database or its environment. However, if you find any information in the HTML that you are uncomfortable sharing, feel free to remove the problematic information before uploading the HTML. 
 When the HTML is acceptable, upload it using the attachments section in the case details of your support case.
 For information about local write forwarding on Aurora PostgreSQL secondary DB clusters, see Local write forwarding in Aurora PostgreSQL .
 Topics
 Working with the database preview environment 
 Security with Amazon Aurora PostgreSQL 
 Updating applications to connect to Aurora PostgreSQL DB clusters using new SSL/TLS certificates 
 Using Kerberos authentication with Aurora PostgreSQL 
 Migrating data to Amazon Aurora with PostgreSQL compatibility 
 Optimizing query performance in Aurora PostgreSQL 
 Querying Apache Iceberg and Parquet data directly in Aurora PostgreSQL 
 Working with unlogged tables in Aurora PostgreSQL 
 Working with PostgreSQL autovacuum on Amazon Aurora PostgreSQL 
 Managing TOAST OID contention in Amazon Aurora PostgreSQL 
 Using Babelfish for Aurora PostgreSQL 
 Performance and scaling for Amazon Aurora PostgreSQL 
 Tuning with wait events for Aurora PostgreSQL 
 Tuning Aurora PostgreSQL with Amazon DevOps Guru proactive insights 
 Best practices with Amazon Aurora PostgreSQL 
 Replication with Amazon Aurora PostgreSQL 
 Local write forwarding in Aurora PostgreSQL 
 Using Aurora PostgreSQL as a Knowledge Base for Amazon Bedrock 
 Integrating Amazon Aurora PostgreSQL with other AWS services 
 Monitoring query execution plans and peak memory for Aurora PostgreSQL 
 Managing query execution plans for Aurora PostgreSQL 
 Working with extensions and foreign data wrappers 
 Working with Trusted Language Extensions for PostgreSQL 
 Amazon Aurora PostgreSQL reference 
 Database engine updates for Amazon Aurora PostgreSQL 
 Document Conventions 
 Database engine updates and fixes for Amazon Aurora MySQL
 The database preview environment
 Did this page help you? - Yes
 Thanks for letting us know we're doing a good job!
 If you've got a moment, please tell us what we did right so we can do more of it.
 Did this page help you? - No
 Thanks for letting us know this page needs work. We're sorry we let you down.
 If you've got a moment, please tell us how we can make the documentation better.
