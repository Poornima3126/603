## Comparison of NoSQL Database Management Systems and Models

### Introduction to NoSQL
  NoSQL Database mangement systems have become most common in recent years becuase of their own advantages, disadvantages, and use cases. NoSQL databases are equipped to handle normalized data and they are able to sort data within a predefined schema.
RDBMS stores data in the form of rows and columns and uses sql for managing and accessing the data. Relational databases has some limitations including horizontal scaling and storing unstructured data.

### Types of NoSql

#### Key-value store: 
  key-value databases defines a key and provide a matching value which can later be retrieved the same way by supplying the key. Because of the high performance, efficiency and scalability, it is commonly used for caching, message queuing and session management.
Redis, Memcached, Riak are some popular key-value data stores.

#### Columnar database: 
  Columnar databases stored data in the format of columns with all the columns having same data type. Each column is saved in a separate file. Run length encoding is done. Mostly used in situations when an application which performs aggregate operations. 
One disadvantage of this type of database is slow load performance.
Examples: Apache Cassandra, Apache HBase, ClickHouse.
  
#### Document store: 
  Document store stores data in the form of document and each document has a unique key.
Examples: MongoDB, Couchbase, Apache CouchDB.

#### Graph database: 
  It is a subcategory of document store, difference is graph databases add an extra layer to the document model by highlighting the relationships between individual documents. Grpah databases has node, property, edge.
  Most popular open source datbases are Neo4j, ArangoDB, OrientDB.

### Conclusion: 
  The NoSQL database category is very diverse and is still developing today. 
 
