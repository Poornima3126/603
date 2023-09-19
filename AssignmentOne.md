## Comparison of NoSQL Database Management Systems and Models

### Introduction to NoSQL
   NoSQL databases are equipped to handle normalized data and they are able to sort data within a predefined schema.
RDBMS stores data in the form of rows and columns and uses sql for managing and accessing the data. Relational databases has some limitations including horizontal scaling and storing unstructured data.

### Types of NoSql

![Nosql](https://github.com/Poornima3126/603/assets/43727585/cfcc2891-3018-43ea-8b7a-b66c5eda726c)

#### Key-value store: 
  key-value databases defines a key and provide a matching value which can later be retrieved the same way by supplying the key.
Examples: Redis, Memcached, Riak.

#### Columnar database: 
  Columnar databases stored data in the format of columns with all the columns having same data type. Each column is saved in a separate file.
Examples: Apache Cassandra, Apache HBase, ClickHouse.
  
#### Document store: 
  Document store stores data in the form of document and each document has a unique key.
Examples: MongoDB, Couchbase, Apache CouchDB.

#### Graph database: 
  It is a subcategory of document store, difference is graph databases add an extra layer to the document model by highlighting the relationships between individual documents.
 Examples: Neo4j, ArangoDB, OrientDB.
 
## Data Lakehouse
A data lakehouse is a new, open data management architecture that combines the flexibility, cost-efficiency. 
 
### Advantages of DataLakehouse:
1. Open data formats
2. High performance
   
### Key Technology Enabling the Data Lakehouse
1. metadata layers for data lakes
2. new query engine designs providing high-performance SQL execution on data lakes
3. better machine learning and data science tool availability.

### History of Data Architectures
![image](https://github.com/Poornima3126/603/assets/43727585/b7ff6c79-6da3-4b30-9dcf-acd98fa88a85)

#### Data Warehouses
Mostly used in decision support and business intelligence applications, but it is not suited for handling unstructured data, semi-structured data, and data with high variety, velocity, and volume
#### Data Lakes
Data lakes handle raw data but has limitations like data qulaity, consistency

### Sources:
   1. https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models
   2. https://www.databricks.com/glossary/data-lakehouse

