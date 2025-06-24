# bus-licences-2013-2024
Projects
Overview of cloud-based data analytics project using AWS services.
# [Project: Business License Analytics on AWS (2013–2024)](https://github.com/azeezat97/aws-business-license-analysis)
In this project, a full-stack Data Analytics Platform (DAP) was designed and deployed to analyze variations in business license fees across Canadian cities using the AWS cloud ecosystem.
- Pipeline 1: Data Ingestion** – Uploaded raw CSV data to S3 bucket `business-licence-raw-azeezat`.
- Pipeline 2: Data Profiling** – Used AWS Glue DataBrew to assess data quality (nulls, duplicates, schema).
- Pipeline 3: Data Cleaning** – Cleaned and transformed data; exported as CSV and Parquet to curated S3 buckets.
- Pipeline 4: Data Cataloging** – Created Glue Crawlers and Data Catalog to register and expose datasets.
- Pipeline 5: SQL Analysis** – Queried cleaned data in Athena to visualize trends in average fees across cities.
- Pipeline 6: Data Security** – Used AWS KMS for encryption, bucket versioning, and replication rules for backup.
- Pipeline 7: Data Governance** – Implemented quality checks using Glue ETL and routed records to Passed/Failed buckets.
- Pipeline 8: Monitoring** – Created CloudWatch dashboards and CloudTrail logs to track jobs and activities.
![AWS Architecture Diagram](https://github.com/azeezat97/aws-business-license-analysis/blob/main/architecture/architecture-diagram.png)
