# Microsoft 365 Defender Queries
Place to stash my Microsoft 365 Defender KQL (Kusto Query Language) Queries with information and ways to finetune results to get what you want.

## What is KQL?
KQL (or Kusto) is the query language that Microsoft Defender uses to pull data from Azure Sentinel, Azure logs, and Azure Data Explorer. It is particularly useful in investigations as Defender does not give a lot of information in its alerts page and it can be frustrating sorting through all information by clicking around under Device Timeline. Instead, pulling all relevant information with a few lines provides a faster and more complete (if done correctly) experience in understanding the how, when, and when threat hunting. 

Overall, the structure is very similar to SQL and other SIEM languages, so if you have experience in Splunk, Elastic Kibana, or SQL, it will feel like a natural transition. 

## Creating Detection Rules
Another advantage of learning KQL for Defender is the ability to create detection rules for your organization. 

## Labeling Each Query
I group each query under a technique from the MITRE ATT&CK framework depending on what the query is attampting to detect.

Link: https://attack.mitre.org/matrices/enterprise/

## Proof-of-Concepts
WORK IN PROGRESS ONCE VSPHERE STOPS HATING ME
