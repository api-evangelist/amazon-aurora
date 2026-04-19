# Amazon Aurora

Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

## Overview

The Amazon Aurora API enables programmatic control over DB clusters, DB instances, cluster snapshots, parameter groups, custom endpoints, and global database configurations. It is accessed through the Amazon RDS API endpoint.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html
- **Base URL:** https://rds.us-east-1.amazonaws.com

## Features

- MySQL and PostgreSQL compatible relational database engine
- Up to 5x throughput of standard MySQL and 3x of standard PostgreSQL
- Auto-scaling storage from 10GB to 128TB
- Up to 15 low-latency read replicas
- Aurora Serverless for intermittent and unpredictable workloads
- Aurora Global Database for multi-region deployments
- Continuous backup to Amazon S3 with point-in-time recovery
- Fast database cloning for testing and development
- Parallel query for faster analytical queries
- Machine learning integration through Aurora ML

## Use Cases

- Enterprise applications requiring high availability and durability
- SaaS applications needing scalable multi-tenant databases
- E-commerce platforms with variable traffic patterns
- Financial applications requiring ACID compliance
- Global applications needing low-latency multi-region access
- Development and testing with fast database cloning

## Artifacts

### OpenAPI Specification
`openapi/amazon-aurora-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all Aurora API paths.

### Spectral Rules
`rules/amazon-aurora-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/aurora-api.yaml` — Shared per-API capability definition
- `capabilities/relational-database-management.yaml` — Workflow capability for relational database management

### Vocabulary
`vocabulary/amazon-aurora-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 54 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 54 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-aurora-context.jsonld`

### Examples
`examples/` — 54 example JSON files.

## Integrations

- Amazon RDS
- Amazon S3
- AWS Lambda
- Amazon CloudWatch
- AWS IAM
- Amazon VPC
- AWS KMS
- AWS Secrets Manager
- Amazon SageMaker
- AWS DMS

## Tags

Amazon Aurora, MySQL, PostgreSQL, Relational Database, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
