# bus-licences-2013-2024
Projects
Overview of cloud-based data analytics project using AWS services.
# [Project: Business License Analytics on AWS (2013–2024)](https://github.com/azeezat97/aws-business-license-analysis)
In this project, a full-stack Data Analytics Platform (DAP) was designed and deployed to analyze variations in business license fees across Canadian cities using the AWS cloud ecosystem.
- Pipeline 1: Data Ingestion – Uploaded raw CSV data to S3 bucket `business-licence-raw-azeezat`.
- Pipeline 2: Data Profiling – Used AWS Glue DataBrew to assess data quality (nulls, duplicates, schema).
- Pipeline 3: Data Cleaning – Cleaned and transformed data; exported as CSV and Parquet to curated S3 buckets.
- Pipeline 4: Data Cataloging – Created Glue Crawlers and Data Catalog to register and expose datasets.
- Pipeline 5: SQL Analysis – Queried cleaned data in Athena to visualize trends in average fees across cities.
- pipeline 6: DAP Estimated Cost- using aws pricing calculator to calculate the total jobrub using aws console 
- Pipeline 7: Data Security – Used AWS KMS for encryption, bucket versioning, and replication rules for backup.
- Pipeline 8: Data Governance – Implemented quality checks using Glue ETL and routed records to Passed/Failed buckets.
- Pipeline 9: Monitoring – Created CloudWatch dashboards and CloudTrail logs to track jobs and activities.
![Data ingestion](https://github.com/user-attachments/assets/1f5db2a1-1c8f-421e-a210-66ea3b8c1346)
![profile implementation](https://github.com/user-attachments/assets/3618cb9c-e6ed-4caf-aa70-186fb020740e)
![profile design](https://github.com/user-attachments/assets/254b48c1-9cbc-44cd-8754-b91ceab8e50a)
![cleaning implementation](https://github.com/user-attachments/assets/d265f296-ec28-4ce6-b902-08bbc390afe3)
![data catalog](https://github.com/user-attachments/assets/57efdc1f-4bf0-4a9f-936a-c8b049414271)
![crawler](https://github.com/user-attachments/assets/365f43e2-5fee-4d8d-b2f1-14b51344b06a)
![athena](https://github.com/user-attachments/assets/92c0d9f3-9076-4fe2-9ba5-50dd7d636f78)
![cost eva summary](https://github.com/user-attachments/assets/30bbad60-d3df-4a38-9eed-cd3ab393ef09)
![kms key](https://github.com/user-attachments/assets/46dd9351-d444-4cb6-b2ad-808e99b4075e)
![Bucket versioning   encryption](https://github.com/user-attachments/assets/37156b87-7ce6-4fcf-a56f-084c48c97341)
![rep rule](https://github.com/user-attachments/assets/24b324ff-a088-44a7-9bf8-aaa167b7449b)
![QC folder](https://github.com/user-attachments/assets/99b89b01-b870-46a9-9f07-c2c89313455c)
![visual ETL of QC](https://github.com/user-attachments/assets/3d3ea333-6c66-4f87-8e60-721b876da15d)






