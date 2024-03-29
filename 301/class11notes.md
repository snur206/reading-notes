# [Class 11 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class11notes.md)

This topic matters because it is introducing the topics of nosql and sql.

## nosql vs sql

Five differences between nosql and sql:

- SQL databases are primarily called as Relational Databases and NoSQL database are primarily called as non-relational or distributed database.
 	  
- SQL databases are table based databases and NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. This means that SQL databases represent data in form of tables which consists of n number of rows of data whereas NoSQL databases are the collection of key-value pair, documents, graph databases or wide-column stores which do not have standard schema definitions which it needs to adhered to.

- SQL databases have predefined schema and NoSQL databases have dynamic schema for unstructured data.

- SQL databases are vertically scalable and the NoSQL databases are horizontally scalable.

- SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.

Complex query intensive environment data is a good fit for an SQL database.

A real world example is how web developers and data scientists uses SQL to access data.

A dynamic schema for unstructured data is a good fit a NoSQL database and are highly preferred for large data set.

A real world example is how companies like Microsoft, Google, Amazon, Facebook, and Netflix use NoSQL to storing and modeling structured, semi-structured, and unstructured data in one database. 

NoSQL database is best for hierarchical data storage.

SQL database is best for scalability.

## sql vs nosql (Video)

SQL stands for Structured Query Language.

A relational database means that a database works with certain assumptions or supports SQL language. This database is used with multiple tables that can be combined in queries.

The type of structure does a relational database work with are tables with rows and columns.

A ‘schema’ is how data is organized in a relational database.

NoSQL database has no schema and does not tables but collections.

NoSQL works by having multiple documents in one collection that  have different fields. No schema applied.

Collection and document is inside of a MongoDB database.

MongoDB is more flexible than SQL because you can split data across multiple servers and then merge it together automatically so horizontal scaling is possible in NoSQL.

The disadvantage of a NoSQL database is that you cannot rely on your record to have a certain field, it might just have it because there is no schema to force it to have, no relations or very few relations where if you have a lot of write request that affect multiple collections because you then have to update some data in multiple collections because you are duplicating it instead of keeping a relation.

## Things I want to know more about

NoSQL and SQL.
