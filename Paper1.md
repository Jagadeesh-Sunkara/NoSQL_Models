
# Comparison of NoSQL Database Management Systems and Models:

Traditional relational databases have been the most popular option for many years which can handle the majority of data but alternative databases have become more common in recent years to overcome the limitationslike being better suited only for structural data, horizontal scaling.The article highlights various non-relational data models also known as NoSQL databases, each with its use cases, advantages, and disadvantages. 

- **Key- Value Databases:** These databases use associative arrays (dictionary) containing key-value pairs to efficiently store the data and retrieve, where each key uniquely identifies an associated value. Examples: Redis and DynamoDB
- **Document-Oriented Databases:** These databases store data as documents where each document having a unique key-value pair. These are fit for semi-structured/ unstructured data. Example: MongoDB.
- **Columnar Databases:** These databases store the data in columns and are very efficient in handling large volumes of data.  Examples: Apache Cassandra.
- **Graph Databases:** Graph databases like Neo4j are designed for managing highly interconnected data and are suitable for applications like social networks and recommendation systems.

# Data Lakehouse: 

The article introduces the concept of "Data Lakehouse," which combines the benefits of data lakes and warehouses. It uses platforms like Databricks which helps in storing large raw and structured data, offering data warehousing features like ACID, schemas, and SQL queries. Delta Lake, a major component, adds reliability to data lakes by providing transactions and schema enforcement. It also leverages features like data indexing, caching, and auto-optimization to improve query performance.
