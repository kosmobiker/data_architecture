# Data Architecture

Last time, I realized that my knowledge in data engineering is quite extensive. It sparked a thought: what if I were tasked with creating the data architecture for an entire company? What solutions could I suggest? In this repository, I aim to summarize my ideas and provide a comprehensive guide to building a robust, scalable, and open-source-based data architecture that can meet the needs of modern enterprises.

The whole data platform consists of several parts, and I am going to describe each of them separately.

Here, I'll outline the key components of each part of the data platform and delve into the technologies that can be used, best practices for their implementation, and how they fit into the larger ecosystem of data management. This guide will serve as a blueprint for establishing a data-driven culture within an organization, ensuring that every decision is backed by empirical evidence and advanced analytics.



## Data Architecture Components

**A. Data Ingestion**

1. [Batch data](./src/data_ingestion/batch_data.md)
2. Streaming data
3. [Batch ingestion](./src/data_ingestion/batch_ingestion.md)
4. Streaming ingestion and pre-processing

**B. Data Platform**

5. Data storage
6. ETL Cluster
7. Ad-hoc cluster
8. Real-time analytics cluster

**C. ML Platform**

9. Experiment Tracking and model registry
10. Feature Store
11. ML Serving cluster

**D. BI**

12. BI Cluster

**E. Orchestration**

13. Airflow Cluster

**F. Infrastructure**

**G. Security**

**H. Data quality and data lineage**


## Diagram

Raw version

![Diagram](./diagram/infra.drawio.svg)


## Inspiration

- [AWS Financial Services Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/financial-services-industry-lens/welcome.html?did=wp_card&trk=wp_card)
- [AWS Analytics Lens](https://docs.aws.amazon.com/wellarchitected/latest/analytics-lens/analytics-lens.html)
- [AWS Machine Learning Lens](https://docs.aws.amazon.com/wellarchitected/latest/machine-learning-lens/machine-learning-lens.html)
