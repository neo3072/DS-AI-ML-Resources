## Databases and Database Management Systems

- Data Warehouse and Data Lake
    + [AWS Redshift](https://aws.amazon.com/documentation/redshift/) - Fast, simple, cost-effective data warehousing
    + [Google Cloud BigQuery](https://cloud.google.com/bigquery/docs/) - Fully managed, petabyte scale, low cost analytics data warehouse
    + [Apache Tajo](http://tajo.apache.org/docs/current/index.html) - A robust big data relational and distributed data warehouse system for Apache Hadoop
    + [Greenplum](http://gpdb.docs.pivotal.io/43100/common/welcome.html) - The World's First Open Source Massively Parallel Data Warehouse
    + [IBM Netazza](https://www-01.ibm.com/software/data/netezza/) - The Simple Data Warehouse Appliance for Serious Analytics
- NoSQL
    + Document
        + [MongoDB](https://docs.mongodb.com/) - NoSQL document store
        + [CouchBase](http://developer.couchbase.com/documentation-archive) - A document database with a SQL-based query language that is engineered to deliver performance at scale
        + [CouchDB](http://docs.couchdb.org/en/2.0.0/) - NoSQL document store
        + [AWS DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [RethinkDB](https://rethinkdb.com/docs/) - RethinkDB is the open-source, scalable database that makes building realtime apps dramatically easier
        + [Azure's DocumentDB](https://docs.microsoft.com/en-us/azure/documentdb/) - A fully managed NoSQL database service built for fast and predictable performance, high availability, elastic scaling, global distribution, and ease of development
    + Column and wide-column (Big-table style)
        + [Google Cloud BigTable](https://cloud.google.com/bigtable/docs/) - Fast, fully managed, massively scalable NoSQL database service
        + [Apache Cassandra](http://cassandra.apache.org/doc/latest/) - Free and open-source distributed database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure
        + [Druid](http://druid.io/docs/latest/design/index.html) - An open source data store designed for OLAP queries on event data
        + [HyperTable](http://www.hypertable.com/documentation/) - A high performance, open source, massively scalable database modeled after Bigtable
        + [Apache HBase](https://hbase.apache.org/book.html) - Apache HBase is the Hadoop database, a distributed, scalable, big data store
        + [AWS SimpleDB](https://aws.amazon.com/documentation/simpledb/) - A highly available, scalable, and flexible non-relational data store that enables you to store and query data items using web services requests
    + Key-value
        + [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
        + [Apache Accumulo](https://accumulo.apache.org/) - A sorted, distributed key/value store that provides robust, scalable data storage and retrieval
        + [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
        + [Riak](https://docs.basho.com/) - Distributed NoSQL Database
        + [AWS DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [Azure Table Storage (ATS)](https://docs.microsoft.com/en-us/azure/storage/)
    + Graph
        + [Neo4j](https://neo4j.com/docs/) - World's fastest and most scalable graph database
        + [Titan](https://github.com/thinkaurelius/titan) - A highly scalable graph database optimized for storing and querying large graphs with billions of vertices and edges distributed across a multi-machine cluster
        * [OrientDB](http://orientdb.com/docs/last/) - A document-graph database, meaning it has full native graph capabilities coupled with features normally only found in document databases
- RDBMS
    - [AWS RDS](https://aws.amazon.com/documentation/rds/) - Amazon Relational Database Service
        + [AWS Aurora](https://aws.amazon.com/rds/aurora/getting-started/) - MySQL-compatible relational database with 5X performance
        + [Oracle](https://docs.oracle.com/en/database/)
        + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
        + [PostgreSQL](https://www.postgresql.org/docs/)
        + [MySQL](https://dev.mysql.com/doc/)
        + [MariaDB](https://mariadb.org/learn/)
    + [MySQL](https://dev.mysql.com/doc/) - Open source RDBMS
    + [PostgreSQL](https://www.postgresql.org/docs/) - Open-source Object-Relational DBMS supporting almost all SQL constructs
    + [SQLite](https://www.sqlite.org/docs.html) - A self-contained, high-reliability, embedded, full-featured, public-domain, SQL database engine
    + [Apache Kudu](https://kudu.apache.org/docs/) - A columnar storage manager developed for the Hadoop platform
    + [Oracle Database](http://www.oracle.com/technetwork/database/index.html)
    + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
- In-memory
    + [VoltDB](https://docs.voltdb.com/) - The only in-memory, operational database purpose-built to help businesses build high velocity applications
    + [MemSQL](http://docs.memsql.com/docs) - A high-performance, in-memory database that combines
    + [SAP HANA](https://hcp.sap.com/index.html#) - An open platform-as-a-service that provides unique in-memory database and application services
the horizontal scalability of distributed systems with the familiarity of SQL
- Static storage
    - [AWS S3](https://aws.amazon.com/documentation/s3/) - Simple, durable, massively scalable object storage
- Containerized
    + [Pachyderm](https://www.pachyderm.io/) - A Containerized Data Lake
- Search and full-text
    - [ElasticSearch](https://www.elastic.co/guide/index.html) - Service that makes it easy to deploy, operate, and scale Elasticsearch in the AWS Cloud
    - [Apache Lucene](https://lucene.apache.org/core/documentation.html) - Java-based indexing and search technology, as well as spellchecking, hit highlighting and advanced analysis/tokenization capabilities
    - [Apache Solr](http://lucene.apache.org/solr/resources.html#documentation) - A high performance search server built using Lucene Core, with XML/HTTP and JSON/Python/Ruby APIs, hit highlighting, faceted search, caching, replication, and a web admin interface
    - [Apache PyLucene](http://lucene.apache.org/pylucene/features.html) - A Python port of the Lucene Core project
- Cache
    - [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
    - [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
- Time-series and event data
    + [InfluxDB](https://docs.influxdata.com/influxdb/v1.1/) - A time series database built from the ground up to handle high write and query loads
    + [Prometheus](https://prometheus.io/docs/introduction/overview/) - An open-source systems monitoring and alerting toolkit originally built at SoundCloud
    + [Druid](http://druid.io/docs/0.9.1.1/design/index.html) - An open source data store designed for OLAP queries on event data
    + [Geras](http://1248.io/geras.php) - 
    + [KairosDB](https://github.com/kairosdb/kairosdb) - 
    + [kdb+](http://kx.com/resources.php) - 
    + [OpenTSDB](http://opentsdb.net/) - 
    + [TempoIQ](https://www.tempoiq.com/) - 

## Database Considerations and Tradeoffs
- ACID
    + Atomicity - An atomic transaction is an indivisible and irreducible series of database operations such that either all occur, or nothing occurs
    + Consistency - The requirement that any given database transaction must change affected data only in allowed ways, and that any data written to the database must be valid according to all defined rules, including constraints, cascades, triggers, and any combination thereof
    + Isolation - How transaction integrity is visible to other users and systems, i.e., how/when the changes made by one operation become visible to other
    + Durability - Guarantees that transactions that have committed will survive permanently
- BASE
    + Basically Available - Any data request should receive a response, but that response may indicate a failure or changing state as opposed to the requested data
    + Soft state - Given eventual consistency, the system may be in a changing state until consistency is reached
    + Eventual consistency - Informally guarantees that (to achieve high availability), if no new updates are made to a given data item, eventually all accesses to that item will return the last updated value
- CAP (Brewers theorem) and PACELC
    + Consistency - All clients always have the same view of the data
    + Availability - Each client can always read and write
    + Partition tolerance - The system works well despite physical network partitions
- Consistency vs eventually consistency
- Speed and performance
- Locks
    + Lock contention
    + Long term blocking
    + Database deadlocks
    + System deadlocks
- Schema on write vs schema on read
- Isolation levels
- Concurrency control
- Different read types (e.g., dirty, non-repeatable, phantom, ...)

## Databases by CAP (non-exhaustive)
- CA - Typically deal with P with replication
    + RDBMS
- AP - Achieve "eventual consistency" through replication and verification
    + Dynamo
    + Voldemort
    + Cassandra
    + SimpleDB
    + CouchDB
    + Riak
- CP - Have trouble with availability while keeping data consistent across partitioned nodes
    + BigTable
    + MongoDB
    + HBase
    + MemcacheDB
    + Redis

## Database Comparisons
- [MongoDB and HBase Compared](https://www.mongodb.com/compare/mongodb-hbase)

## Database, data warehouse, and Analytical Terminology
+ Dimension (e.g., customer, product, ...)
    * Data must vary to be considered a dimension
        - E.g., Analysis of sales of a single product, product not considered a dimension in this case. Analysis of sales across many products, product is considered a dimension.
    * Types
        - Conformed
        - Junk
        - Degenerate
        - Role-playing
+ Fact
+ Measures (e.g., sales)
    * Types
        - Additive
        - Non-additive
        - Semi-additive
+ Data elements
+ OLAP
    * Associated with OLAP data, tools, data storage, and querying 
+ OLAP Cube
    * A multi-dimensional array of data or multi-dimensional dataset
        - Pivoting (spreadsheet analysis) done via holding dimensions constant and leaving two dimensions to analyze
        - Associated with analytical operations (shown below)
+ OLTP
+ CRUD
+ Multidimensional analysis - Data dimensions and measurements
+ Analytical operations
    * Consolidation (roll-up)
    * Drill-down/up - new cube with one dimension the subset of the original cube's parent dimension
    * Slicing - filtering data across a dimension(s), i.e., reduce the cubes dimension by one by selecting a single value for one dimension
    * Dicing - grouping data and reducing cube size, i.e., creating a subcube
    * Pivot - rotate the cube for different perspective of the data

## Database Design
- Wide vs narrow data, or stacked vs un-stacked
    + Wide (unstacked): Every feature in a separate column
    + Narrow (stacked): Single feature column with all values (e.g., categorical), with another column containing corresponding values
- Entity vs event data
    + Entity: One table per entity and normalized, but requires lots of tables and joins for analytics
    + Event: JSON a good format, denormalized, nested, and schemaless
- Transactional vs operational vs analytics database/data store
- Table types
    + Dimension table
    + [Fact table](https://en.wikipedia.org/wiki/Fact_table#Types_of_fact_tables)
        * Contain foreign keys of related dimension tables
        * Primary key usually a composite key of its foreign keys 
        * Types
            - Transactional
            - Periodic snapshots
            - Accumulating snapshots
            - Temporal snapshots
- Database schemas
    + Star
        * Best for data marts
        * One or more fact tables referencing any number of denormalized single-dimension tables
        * Simple and fast to query
        * More difficult to maintain
    + Reverse star
    + Snowflake
        * Best for data warehouses
        * One or more fact tables referencing any number of normalized dimension tables (i.e., one or multiple tables per dimension)
        * Reduces redundancy, size, and storage, also helps referential integrity
        * Slower and more complex to query, particularly due to complex queries and often required joins
        * Easier to maintain
    + Fact constellation
    + Galaxy
- Normal forms
    + First Normal Form (1NF)
        * Wikipedia: A relation is in first normal form if and only if the domain of each attribute contains only atomic (indivisible) values, and the value of each attribute contains only a single value from that domain.
    + Second Normal Form (2NF)
        * Wikipedia: A table is in 2NF if it is in 1NF and every non-prime attribute of the table is dependent on the whole of every candidate key.
    + Third Normal Form (3NF) - If met, a DB is considered 'Normalized'
        * Wikipedia: A table is in 3NF if it is in 2NF and all the attributes in a table are determined only by the candidate keys of that table and not by any non-prime attributes
    + Boyce-Codd Normal Form (BCNF)

## Data Lake vs Data Warehouse vs Data Mart
- Data Warehouse (EDW)
    + [Definition](https://en.wikipedia.org/wiki/Data_warehouse) - A system used for reporting and data analysis, and is considered a core component of business intelligence
    + Characteristics
        * Data
            - Structured
            - Processed
        * Schema-on-write processing
        * Relatively expensive for large volumes
        * Fixed configuration and less flexible
        * Better suited for business intelligence and business professionals
    + Technologies
        * AWS Redshift
- Data Lake
    + [Definition](http://www.kdnuggets.com/2015/09/data-lake-vs-data-warehouse-key-differences.html) - A data lake is a storage repository that holds a vast amount of raw data in its native format, including structured, semi-structured, and unstructured data. The data structure and requirements are not defined until the data is needed.
    + Characteristics
        * Data
            - Structured, semi-structured, unstructured
            - Raw
        * A data lake delivers maximum scale and insight with the lowest possible friction and cost
        * Increased efficiency
        * Reduced storage costs
        * Data processing workload optimization, including data integration and transformation
        * Schema-on-read processing and associated flexibility and new opportunities
        * Multi-use and multi-workload data processing on same data from batch to real-time across business units
        * Eliminate need for ETL and associated costs
        * Keep 100% of source data and historical data for ongoing exploration (both raw and processed)   
        * Easy and dynamic configuration and reconfiguration
        * Better suited for data scientists
    + Technologies
        * Hadoop
        * Apache YARN
- Data Mart
    + [Definition](https://en.wikipedia.org/wiki/Data_mart) - The access layer of the data warehouse environment that is used to get data out to the users. The data mart is a subset of the data warehouse and is usually oriented to a specific business line or team.

## Data Modeling and Mapping
- Active record (AR)
- Data access object (DAO)
- Data mapper
- Table gateway
- Object relational mapping (ORM)
- Data transfer object (DTO)
- CRUD - Create, read, update, delete

## Querying
- SQL - Structured Query Language
- DMQL - Data Mining Query Language

## Articles
- [DAO vs ORM vs ActiveRecord vs TableGateway vs AHHHH!](https://www.sitepoint.com/community/t/dao-vs-orm-vs-activerecord-vs-tablegateway-vs-ahhhh/2473/2)
