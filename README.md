# Azure Databricks & Spark For Data Engineers (Pyspark/SQL)
## [Azure Portal](https://portal.azure.com/#home)


## 1. Databrick Clusters
Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Azure Databricks| This is an Apache Spark-based big data analytics service designed for data science and data engineering offered by Microsoft. It allows collaborative working as well as working in multiple languages like Python, Spark, R and SQL. Working on Databricks offers the advantages of cloud computing - scalable, lower cost, on demand data processing and data storage.  |  N/A  | 
| Databricks Clusters   | This is a set of computation resources and configurations on which you run data engineering, data science, and data analytics workloads, such as production ETL pipelines, streaming analytics, ad-hoc analytics, and machine learning. |  [Docs](https://docs.databricks.com/en/clusters/index.html) |  
| Cluster Configuration  | Databricks provides a number of options when you create and configure clusters to help you get the best performance at the lowest cost. |  [Docs](https://docs.databricks.com/en/clusters/cluster-config-best-practices.html) |  
| Cluster Pools  | This reduce cluster start and scale-up times by maintaining a set of available, ready-to-use instances. Databricks recommends taking advantage of pools to improve processing time while minimizing cost. |  [Docs](https://docs.databricks.com/en/clusters/pools.html) | 
| Cluster Policies  | This allow administrators to enforce controls over the creation and configuration of clusters |  [Docs 1](https://docs.databricks.com/en/administration-guide/clusters/policies.html) ,  [Docs 2](https://docs.databricks.com/en/administration-guide/clusters/policies-best-practices.html) | 

## 2. Databrick Notebooks

| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Introducing Databricks Notebooks   | Notebooks are a common tool in data science and machine learning for developing code and presenting results. In Databricks, notebooks are the primary tool for creating data science and machine learning workflows and collaborating with colleagues. Databricks notebooks provide real-time coauthoring in multiple languages, automatic versioning, and built-in data visualizations. |  [Docs](https://docs.databricks.com/en/notebooks/index.html) |  
| Magic Commands  | Magic commands in Databricks let you execute the code snippets other than the default language of the notebook. | [Docs](https://insightsndata.com/databricks-notebook-magic-commands-b5e3aa3f1585) |  
| Databricks Utilities (dbutils) | Databricks Utilities (dbutils) make it easy to perform powerful combinations of tasks. You can use the utilities to work with object storage efficiently, to chain and parameterize notebooks, and to work with secrets. |  [Docs](https://docs.databricks.com/en/dev-tools/databricks-utils.html) | 

## 3. Accessing Azure DataLake from Databricks - (Section 6 & 7) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Creating DataLake Storage Gen 2   | Azure Data Lake Storage Gen2 is a set of capabilities dedicated to big data analytics, built on Azure Blob Storage. |  [About Datalake Storage Gen 2](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction), [step-by-step guide](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=azure-portal) |  
| Azure Storage Explorer | This is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux. | [Docs](https://learn.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=windows) |  
| Accessing Azure Data Lake Storage Gen2 From Databricks |This tutorial guides you through all the steps necessary to connect from Azure Databricks to Azure Data Lake Storage Gen2 using OAuth 2.0 with an Azure service principal.|  [Docs](https://learn.microsoft.com/en-us/azure/databricks/getting-started/connect-to-azure-storage) | 
