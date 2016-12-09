# Databases, Big Data, and Cloud Services

- [Apache Foundation](https://www.apache.org/)
    + [Apache Projects List (by category)](https://projects.apache.org/projects.html?category)
    + [HBase](https://hbase.apache.org/book.html) - Apache HBase is the Hadoop database, a distributed, scalable, big data store
    + [Hadoop](http://hadoop.apache.org/docs/current/) - Open-source software for reliable, scalable, distributed computing
        * HDFS - Scalable and reliable data storage that is designed to span large clusters of commodity servers
    + [Spark](http://spark.apache.org/docs/latest/) - A fast and general engine for large-scale data processing
    + [Hive](https://cwiki.apache.org/confluence/display/Hive/LanguageManual) - Data warehouse software that facilitates reading, writing, and managing large datasets residing in distributed storage using SQL
    + [Pig](http://pig.apache.org/docs/r0.16.0/) - A platform for analyzing large data sets that consists of a high-level language for expressing data analysis programs, coupled with infrastructure for evaluating these programs
    + [Kylin](http://kylin.apache.org/docs15/) - An open source Distributed Analytics Engine designed to provide SQL interface and multi-dimensional analysis (OLAP) on Hadoop supporting extremely large datasets, original contributed from eBay Inc
    + [Lens](http://lens.apache.org/user/index.html) - A unified analytics interface
    + [Ignite](https://apacheignite.readme.io/docs) - A high-performance, integrated and distributed in-memory platform for computing and transacting on large-scale data sets in real-time, orders of magnitude faster than possible with traditional disk-based or flash technologies
    + [Brooklyn](https://brooklyn.apache.org/documentation/index.html) - A framework for modeling, monitoring, and managing applications through autonomic blueprints
    + [Apex](https://apex.apache.org/docs.html) - Enterprise-grade unified stream and batch processing engine
    + [Tajo](http://tajo.apache.org/docs/current/index.html) - A robust big data relational and distributed data warehouse system for Apache Hadoop
    + [Tez](https://tez.apache.org/user_guides.html) - An application framework which allows for a complex directed-acyclic-graph of tasks for processing data
    + [Bigtop](http://bigtop.apache.org/) - Project for Infrastructure Engineers and Data Scientists looking for comprehensive packaging, testing, and configuration of the leading open source big data components
    + [REEF](http://reef.apache.org/introduction.html) - Apache REEF (Retainable Evaluator Execution Framework) is a library for developing portable applications for cluster resource managers such as Apache Hadoop YARN or Apache Mesos
    + [Storm](http://storm.apache.org/index.html) - A free and open source distributed realtime computation system 
    + [Kafka](https://kafka.apache.org/) - A distributed streaming platform
    + [Sqoop](http://sqoop.apache.org/) - A tool designed for efficiently transferring bulk data between Apache Hadoop and structured datastores such as relational databases
    + [JMeter](http://jmeter.apache.org/) - Java application designed to load test functional behavior and measure performance
    + [Yarn](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html) - Pluggable architecture and resource management for data processing engines to interact with data stored in HDFS

- Data Warehouse and Data Lake
    + [Redshift](https://aws.amazon.com/documentation/redshift/) - Fast, simple, cost-effective data warehousing
    + [BigQuery](https://cloud.google.com/bigquery/docs/) - Fully managed, petabyte scale, low cost analytics data warehouse
- Real-time/streaming data and big data pipeline
    + [Kinesis](https://aws.amazon.com/documentation/kinesis/) - Real-time streaming data in the AWS cloud
        * Firehouse - Easily load real-time streaming data into AWS
        * Analytics - Get actionable insights from streaming data in real-time
        * Streams - Build custom applications that process or analyze streaming data for specialized needs
    + [Dataflow](https://cloud.google.com/dataflow/docs/) - A fully-managed cloud service and programming model for batch and streaming big data processing
    + [AWS Data Pipeline](https://aws.amazon.com/documentation/data-pipeline/) - Easily automate the movement and transformation of data
    + [Amazon EMR](https://aws.amazon.com/documentation/elastic-mapreduce/) - Easily Run and Scale Apache Hadoop, Spark, HBase, Presto, Hive, and other Big Data Frameworks
    + [Dataproc](https://cloud.google.com/dataproc/docs/) - A managed Apache Spark and Apache Hadoop service that lets you take advantage of open source data tools for batch processing, querying, streaming, and machine learning
- Business Intelligence
    + [QuickSight](https://aws.amazon.com/documentation/quicksight/) - Fast, easy to use business analytics
    + [Datalab](https://cloud.google.com/datalab/docs/) - An easy to use interactive tool for large-scale data exploration, analysis, and visualization
- IoT
    + [IoT](https://aws.amazon.com/documentation/iot/) - Easily and securely connect devices to the cloud
- NoSQL
    + Document
        + [MongoDB](https://docs.mongodb.com/) - NoSQL document store
        + [CouchBase](http://developer.couchbase.com/documentation-archive) - A document database with a SQL-based query language that is engineered to deliver performance at scale
        + [CouchDB](http://docs.couchdb.org/en/2.0.0/) - NoSQL document store
        + [DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [RethinkDB](https://rethinkdb.com/docs/) - RethinkDB is the open-source, scalable database that makes building realtime apps dramatically easier
        + [Azure's DocumentDB](https://docs.microsoft.com/en-us/azure/documentdb/) - A fully managed NoSQL database service built for fast and predictable performance, high availability, elastic scaling, global distribution, and ease of development
    + Column and wide-column (Big-table style)
        + [BigTable](https://cloud.google.com/bigtable/docs/) - Fast, fully managed, massively scalable NoSQL database service
        + [Cassandra](http://cassandra.apache.org/doc/latest/) - Free and open-source distributed database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure
        + [Druid](http://druid.io/docs/latest/design/index.html) - An open source data store designed for OLAP queries on event data
        + [HyperTable](http://www.hypertable.com/documentation/) - A high performance, open source, massively scalable database modeled after Bigtable
        + [HBase](https://hbase.apache.org/book.html) - Apache HBase is the Hadoop database, a distributed, scalable, big data store
        + [SimpleDB](https://aws.amazon.com/documentation/simpledb/) - A highly available, scalable, and flexible non-relational data store that enables you to store and query data items using web services requests
    + Key-value
        + [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
        + [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
        + [Riak](https://docs.basho.com/) - Distributed NoSQL Database
        + [DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability
        + [Azure Table Storage (ATS)](https://docs.microsoft.com/en-us/azure/storage/)
    + Graph
        + [Neo4j](https://neo4j.com/docs/) - World's fastest and most scalable graph database
        + [Titan](https://github.com/thinkaurelius/titan) - A highly scalable graph database optimized for storing and querying large graphs with billions of vertices and edges distributed across a multi-machine cluster
        * [OrientDB](http://orientdb.com/docs/last/) - A document-graph database, meaning it has full native graph capabilities coupled with features normally only found in document databases
- RDBMS
    - [RDS](https://aws.amazon.com/documentation/rds/) - Amazon Relational Database Service
        + [Amazon Aurora](https://aws.amazon.com/rds/aurora/getting-started/) - MySQL-compatible relational database with 5X performance
        + [Oracle](https://docs.oracle.com/en/database/)
        + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
        + [PostgreSQL](https://www.postgresql.org/docs/)
        + [MySQL](https://dev.mysql.com/doc/)
        + [MariaDB](https://mariadb.org/learn/)
    + [MySQL](https://dev.mysql.com/doc/) - Open source RDBMS
    + [PostgreSQL](https://www.postgresql.org/docs/) - Open-source Object-Relational DBMS supporting almost all SQL constructs
    + [SQLite](https://www.sqlite.org/docs.html) - A self-contained, high-reliability, embedded, full-featured, public-domain, SQL database engine
    + [Oracle Database](http://www.oracle.com/technetwork/database/index.html)
    + [Microsoft SQL Server](https://msdn.microsoft.com/en-us/library/mt590198(v=sql.1).aspx)
- Static storage
    - [S3](https://aws.amazon.com/documentation/s3/) - Simple, durable, massively scalable object storage
- Search and full-text
    - [ElasticSearch](https://www.elastic.co/guide/index.html) - Service that makes it easy to deploy, operate, and scale Elasticsearch in the AWS Cloud
    - [Apache Lucene](https://lucene.apache.org/core/documentation.html) - Java-based indexing and search technology, as well as spellchecking, hit highlighting and advanced analysis/tokenization capabilities
    - [Apache Solr](http://lucene.apache.org/solr/resources.html#documentation) - A high performance search server built using Lucene Core, with XML/HTTP and JSON/Python/Ruby APIs, hit highlighting, faceted search, caching, replication, and a web admin interface
    - [PyLucene](http://lucene.apache.org/pylucene/features.html) - A Python port of the Lucene Core project
- Cache
    - [Memcache](https://memcached.org/) - High-performance, distributed memory object caching system
    - [Redis](http://redis.io/documentation) - An open source (BSD licensed), in-memory data structure store, used as database, cache and message broker
- Time-series and event data
    + [InfluxDB](https://docs.influxdata.com/influxdb/v1.1/) - A time series database built from the ground up to handle high write and query loads
    + [Prometheus](https://prometheus.io/docs/introduction/overview/) - An open-source systems monitoring and alerting toolkit originally built at SoundCloud
    + [Druid](http://druid.io/docs/0.9.1.1/design/index.html) - An open source data store designed for OLAP queries on event data
- Machine learning and AI Cloud services and APIs
    + [DataRobot](https://www.datarobot.com/) - Automated Machine Learning
    + [IBM Watson](http://www.ibm.com/watson/developercloud/doc/getting_started/) - Cognitive computing features in your app using IBM Watson's Language, Vision, Speech and Data APIs
    + [Microsoft Machine Learning](Machine Learning) - Powerful cloud based analytics
    + [Machine Learning](https://aws.amazon.com/documentation/machine-learning/)
    + [Machine Learning](https://cloud.google.com/ml/docs/) - Machine Learning on any data, of any size
    + [Prediction API](https://cloud.google.com/prediction/docs/) - A RESTful API to build Machine Learning models
    + [Jobs API](https://cloud.google.com/jobs-api/) - Job search and discovery powered by machine learning
    + [Natural Language API](https://cloud.google.com/natural-language/docs/) - Provides natural language understanding technologies to developers, including sentiment analysis, entity recognition, and syntax analysis
    + [Speech API](https://cloud.google.com/speech/docs/) - Easy integration of Google speech recognition technologies into developer applications
    + [Translate API](https://cloud.google.com/translate/docs/) - Dynamically translate text between thousands of language pairs
    + [Vision API](https://cloud.google.com/vision/docs/) - Easily integrate vision detection features within applications, including image labeling, face and landmark detection, optical character recognition (OCR), and tagging of explicit content
- Massively parallel processing database (MPP)
- Messaging, communications, notifications, and more
    + [Pub/Sub](https://cloud.google.com/pubsub/docs/) - A fully-managed real-time messaging service that allows you to send and receive messages between independent applications