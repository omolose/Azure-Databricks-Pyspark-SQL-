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

## 3. Accessing Azure DataLake from Databricks - (Section 6, 7 & 8) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Creating DataLake Storage Gen 2   | Azure Data Lake Storage Gen2 is a set of capabilities dedicated to big data analytics, built on Azure Blob Storage. |  [About Datalake Storage Gen 2](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction), [step-by-step guide](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=azure-portal) |  
| Azure Storage Explorer | This is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux. | [Docs](https://learn.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=windows) |  
| Accessing Azure Data Lake Storage Gen2 From Databricks |This tutorial guides you through all the steps necessary to connect from Azure Databricks to Azure Data Lake Storage Gen2 using OAuth 2.0 with an Azure service principal.|  [Docs](https://learn.microsoft.com/en-us/azure/databricks/getting-started/connect-to-azure-storage) | 
|Databricks File System(DBFS) | The Databricks File System (DBFS) is a distributed file system mounted into a Databricks workspace and available on Databricks clusters. DBFS is an abstraction on top of scalable object storage that maps Unix-like filesystem calls to native cloud storage API calls|  [Docs](https://docs.databricks.com/en/dbfs/index.html) | 
|Mount ADLS Gen2 or Blob Storage in Azure Databricks | Find the step-by-step guide in the documentation|  [Docs](https://techcommunity.microsoft.com/t5/azure-paas-blog/mount-adls-gen2-or-blob-storage-in-azure-databricks/ba-p/3802926) | 


## 4. Spark Architecture - (Section 10) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Spark Architecture | Apache Spark is an actively developed and unified computing engine and a set of libraries. It is used for parallel data processing on computer clusters and has become a standard tool for any developer or data scientist interested in big data.Spark supports multiple widely used programming languages, such as Java, Python, R, and Scala. It includes libraries for a diverse range of tasks, such as SQL, streaming, machine learning, etc. It runs anywhere from a laptop to a cluster of thousands of servers, making it a beginner-friendly system with a steep learning curve, and users can scale up to big data processing or an incredibly large scale. |  [Docs](https://intellipaat.com/blog/tutorial/spark-tutorial/spark-architecture/)|  

## 5. Data Ingestion - (Section 11 - 13) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Data Ingestion | The add data UI allows you to easily load data into Databricks from a variety of sources.  |  [Docs](https://docs.databricks.com/en/ingestion/add-data/index.html)|  

## 6. Databrick Workflow - (Section 14) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Databrick Workflow | Databricks Workflows orchestrates data processing, machine learning, and analytics pipelines in the Databricks Lakehouse Platform. Workflows has fully managed orchestration services integrated with the Databricks platform, including Databricks Jobs to run non-interactive code in your Databricks workspace and Delta Live Tables to build reliable and maintainable ETL pipelines. |  [Docs](https://docs.databricks.com/en/workflows/index.html)|  

## 7. Filter and Join Transformation  - (Section 15) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Filter and Join Transformation | This article shows you how to load and transform data using the Apache Spark Python (PySpark) DataFrame API in Databricks. |  [Docs](https://docs.databricks.com/en/getting-started/dataframes-python.html)|  


## 8. Aggregations  - (Section 16) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Aggregations | N/A |  [Docs](https://learn.microsoft.com/en-us/azure/databricks/sql/language-manual/functions/aggregate)|  



## 9. Spark SQL  - (Section 17 - 20) 
| Key Terms | Definition of terms | Documentation Sources |
| ----------- | ----------- |  ----------- |
| Local Temp View | N/A |  [Docs](https://sparkbyexamples.com/spark/spark-createorreplacetempview-explained/#:~:text=So%20if%20you%20are%20comfortable,is%20not%20materialized%20into%20files.)| 
| Global Temp View | N/A |  [Docs](https://spark.apache.org/docs/latest/sql-getting-started.html#:~:text=Temporary%20views%20in%20Spark%20SQL,create%20a%20global%20temporary%20view.)|  
| Filter, Joins & Aggregations  | N/A |  [Docs](https://kaizen.itversity.com/courses/hdpcsd-hdp-certified-spark-developer-hdpcsd-python/lessons/hdpcsd-apache-spark-2-data-frames-and-spark-sql-python/topic/hdpcsd-spark-sql-basic-transformations-such-as-filtering-aggregations-joins-etc-python/)|  

