# Amazon Aurora

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
