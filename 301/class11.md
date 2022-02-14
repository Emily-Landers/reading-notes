# Mongo and Mongoose

| SQL    | NoSQL |
| ----------- | ----------- |
| primarily called as Relational Databases (RDBMS)    | primarily called as non-relational or distributed database      |
|  table based databases  | document based, key-value pairs, graph databases or wide-column stores       | 
|  predefined schema | dynamic schema for unstructured data |
|  vertically scalable | horizontally scalable |
|  uses structured query language for defining and manipulating the data, | queries are focused on collection of documents |
|  examples: MySql, Oracle, Sqlite, Postgres and MS-SQL |  examples: MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb |
|  good fit for the complex query intensive environment | databases are not good fit for complex queries |
|  not best fit for hierarchical data storage |better for the hierarchical data storage |
|   single server | multiple servers |
|  best fit for heavy duty transactional type applications | not comparable and stable enough in high load and for complex transactional applications |
|   Excellent support available | community support |
|   emphasizes on ACID properties ( Atomicity, Consistency, Isolation and Durability) | the Brewers CAP theorem ( Consistency, Availability and Partition tolerance ) |
|  classified as either open-source or close-sourced from commercial vendors | classified on the basis of way of storing data as graph database |

- What kind of data is a - good fit for an SQL database?
    - highly structured and associations among the program entities are clearly defined.
- Give a real world example.
    - POS systems
- What kind of data is a good fit a NoSQL database?
    - unstructured data
- Give a real world example.
    - social media analysis websites
- Which type of database is best for hierarchical data storage?
    - NoSQL
- Which type of database is best for scalability?
    - SQL
- What does SQL stand for?
    - Structured Query Language
- What is a realational database?
    - a database structured to recognize relations among stored items of information.
- What type of structure does a relational database work with?
    - tables
- What is a ‘schema'?
    - abstract design that represents the storage of your data in a database
- What is a NoSQL database?
    - non-tabular databases
- How does it work?
    - does not rely on tabular data, rather key value pairs, documents, etc...
- What is inside of a Mongo database?
    - one or more collections of documents
- Which is more flexible - SQL or MongoDB? and why.
    - MongoDB
- What is the disadvantage of a NoSQL database?
    - they are not as reliable