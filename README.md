# Azure Databricks & Spark For Data Engineers (Pyspark/SQL)
## [Azure Portal](https://portal.azure.com/#home)
### DOCUMENTATIONS:
- [SAS](https://learn.microsoft.com/en-us/azure/databricks/storage/azure-storage#access-azure-data-lake-storage-gen2-or-blob-storage-using-a-sas-token)

Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Azure Databricks| This is an Apache Spark-based big data analytics service designed for data science and data engineering offered by Microsoft. It allows collaborative working as well as working in multiple languages like Python, Spark, R and SQL. Working on Databricks offers the advantages of cloud computing - scalable, lower cost, on demand data processing and data storage.  |  N/A  | 
| Databricks Clusters   | This is a set of computation resources and configurations on which you run data engineering, data science, and data analytics workloads, such as production ETL pipelines, streaming analytics, ad-hoc analytics, and machine learning. |  [Docs](https://docs.databricks.com/en/clusters/index.html) |  
| Cluster Configuration  | Databricks provides a number of options when you create and configure clusters to help you get the best performance at the lowest cost. |  [Docs](https://docs.databricks.com/en/clusters/cluster-config-best-practices.html) |  
| Cluster Pools  | This reduce cluster start and scale-up times by maintaining a set of available, ready-to-use instances. Databricks recommends taking advantage of pools to improve processing time while minimizing cost. |  [Docs](https://docs.databricks.com/en/clusters/pools.html) | 
| Cluster Policies  | This allow administrators to enforce controls over the creation and configuration of clusters |  [Docs 1](https://docs.databricks.com/en/administration-guide/clusters/policies.html) ,  [Docs 2](https://docs.databricks.com/en/administration-guide/clusters/policies-best-practices.html) | 

## 1. Databrick Clusters
- What is Databricks clusters
- Databricks clusters types
- Creating a Databricks Cluster
- Databricks Cluster Configurations
- Databricks Cluster Pools
- Databricks Cluster Policy
- Databricks Pricing


## 2. Databrick Notebooks
- Magic commands
- Databrick utilities

## 3. Accessing Azure DataLake from Databricks - (Section 6)     
- Creating DataLake Storage Gen 2.
- Accessing Azure DataLake using Access Key.
- [Access Azure Data Lake using SAS Token](https://learn.microsoft.com/en-us/azure/databricks/storage/azure-storage#access-azure-data-lake-storage-gen2-or-blob-storage-using-a-sas-token)
- Access Azure Data Lake using Service Principal.
- Cluster Scoped Authentication.
- Azure Azure Data Lake using Credential Passthrough
  
     
## 4. Securing Access to Azure Data Lake - Section (7)
- Creating Azure Key Vault
- Creating Secret Scope
- Databricks Secrets Utility
- Using Secrets to Access DataLake Using NoteBooks
- Using Secrets Utility in Clusters
