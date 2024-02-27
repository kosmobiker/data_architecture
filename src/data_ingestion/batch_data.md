# Batch data

A batch data source refers to a type of data source that provides a set of examples in a single batch. This
means that the entire dataset is loaded into memory at once, and the model processes the entire batch in a single step.

Batch data sources are often used in situations where the dataset is too large to fit entirely into memory or where the processing time for each example in the dataset is significant. For example, if you have a large dataset of images that need to be processed by a machine learning model, it may not be practical to process each image individually because it would take too long. In this case, you could use a batch data source to load a few hundred or thousand images at a time and process them in parallel using multiple GPUs or CPU cores.


## Sources of batch data

There are several sources that can be used for batch data ingestion, depending on the specific use case and the type of data being ingested. Some common sources include:

1. Relational databases: Databases such as MySQL, PostgreSQL, and Oracle can be used as sources for batch data ingestion. Another data warehouses can also be used as sources for batch data ingestion such as Amazon Redshift, Google BigQuery, etc.
2. Cloud storage: Cloud storage services such as Amazon S3, Google Cloud Storage, and Azure Blob Storage.
3. File systems: Local file systems or network file systems can also be used as sources for batch data ingestion.
4. APIs: RESTful APIs or other web APIs can be used to extract data from external sources in batch mode.
5. Social media platforms: Social media platforms such as Twitter, Facebook, and LinkedIn 
6. E-commerce platforms: Online marketplaces such as Amazon or eBay can be used as sources.
7. Marketing paltforms
8. CRMs and ERP systems
9. Logs
10. Many more

