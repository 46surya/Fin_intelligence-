# Fin_intelligence-

Modernizing Government Intelligence Pipelines with CloudTransforming Financial Crime Surveillance with Scalable Data Infrastructure: A Case Study
<img width="2626" height="355" alt="image" src="https://github.com/user-attachments/assets/82774990-e655-4444-8126-785f86afecf5" />

Context: Financial Intelligence in the Public Sector
<img width="1596" height="158" alt="image" src="https://github.com/user-attachments/assets/9323e24a-f744-49b5-938a-d240dd794bd4" />
Client Description:A central intelligence agency under the Ministry of Finance focused on tracking illegal financial flows, trade misinvoicing, and smuggling.
Legacy Problems:
Ingesting data from 10+ departments (airports, customs, SEZs, trade portals)
Reliance on on-prem SQL and Excel workflows
Delays in actionable intelligence → slow interdictions
<img width="2511" height="396" alt="image" src="https://github.com/user-attachments/assets/6c6f7eac-0e6c-4861-bfd1-4386a14910bc" />

Where was the Leakage
<img width="894" height="175" alt="image" src="https://github.com/user-attachments/assets/816e0213-187c-4227-b591-75792a430e93" />
⛔ Data silos between agencies and systems (manual CSV sharing)
🕒 Ingestion lag: 24–48 hours → loss of real-time relevance
🔍 Poor deduplication + join logic across passenger, cargo & trade logs
🔐 High operational risk (no audit trail, no RBAC)
🧠 No downstream insights or anomaly tagging
<img width="1237" height="261" alt="image" src="https://github.com/user-attachments/assets/441c9cdd-a5a3-4a61-bcee-4f39cb412c07" />

My role
Led the architecture and migration design
Migrated critical SQL logic into scalable Lambda ETL scripts
Designed the schema, partitions, and Glue Catalog structure
Set up permissioned access controls and logging for audit
Trained government users on Quicksight + S3 lifecycle management
<img width="1195" height="261" alt="image" src="https://github.com/user-attachments/assets/548b0a5f-15d5-4664-b53c-98ecde95d957" />

Results Achieved
