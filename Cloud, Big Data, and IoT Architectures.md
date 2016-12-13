# Cloud, Big Data, and IoT Architectures

## Reference Architectures
+ Extended Relational
+ Non-Relational
+ Hybrid

## Goals and Deliverables
+ Real time intelligence and analytics
+ Data and insights discovery and exploration
+ Decision management
+ Business reporting and analysis
+ Self-service (ad-hoc)
+ Stream computing
    * Event and data streams
+ Data and text analytics
    * Descriptive analytics - What happened and why?
    * Predictive analytics - What is the probability of something happening?
    * Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
    * Query and reporting
    * OLAP Cubes
    * Advanced analytics
    * MapReduce
    * Search engines

## Considerations
- Consistency
- Batch vs. real-time streaming data processing
- Embedded models or interfaces
- API or RPC or REST
- Deployed trained models (offline learning) vs. [online learning](https://en.wikipedia.org/wiki/Online_machine_learning)
+ Latency (near real time)
+ Reliability and fault tolerance
+ Volume handling and scale
+ Performance
+ Throughput
+ Extensibility
+ Security
+ Cost
+ Data quality
+ Skills availability

## Enterprise Big Data Components
- Governance
- Operations, Infrastructure, and DevOps
- Security and privacy
    + Authentication
    + Authorization
    + Accounting
    + Data protection
    + Compliance
- Data Integration
    + Messaging and message queues
    + ETL
    * API/ODBC
    * Replication
    * Bulk movement
    * Virtualization
- Data Processing
    + Event ingestion
    + Batch and stream processing
    + Parallel computing platform
        * Clusters or grids
        * Massively parallel processing (MPP)
        * High performance computing (HPC)
- Data Access
    + Querying
    + Real-time analytics
    + BI analytics
    + MapReduce analytics
- Data Modeling and Structure
    + Star schema
    + Snowflake schema
- Data Storage and Management
    + Data lake
    * Data warehouse
        - Centralized, integrated data store
        - Powers BI analytics, reporting, and drives actionable insights
        - Responsible for integrating data
        - Structured, prepared, and stored data optimized for
            + Analytical applications and decision support
            + Querying and reporting
            + Data mining
    * Operational data store (ODS)
    * Database Systems and DBMS
        - Relational (RDBMS)
        - NoSQL
            + Real-time analytics and insights
        - NewSQL
        - Hybrid
    * Data marts
        - Data warehouse extracted data subsets oriented to speciﬁc business lines, departments or analytical applications
    * Distributed file systems (e.g., HDFS)
        - Real-time and MapReduce analytics and insights
    * In-memory
- Data lifecycle management
    + Rule-based Data and Policy Tracking
    + Data compression
    + Data archiving
- Deployment Choice
    + On-premise
    + In-cloud
    + Appliance
- Presentation, Analytics, and Applications
    + Browser/web
    + Mobile
    + Desktop
    + Dashboards
    + Reports
    + Notifications and messaging

## Enterprise Big Data Components
- http://hortonworks.com/wp-content/uploads/2014/03/11.png

## Data Storage Functions
- Staging
    + Temporary storage
    + Used for cleaning, integration and transformation routines
- Data management
    + Long-time managed storage
    + Clean and integrated data
- Sandboxing
    + Temporary data stores
    + Used by people, groups, and departments
    + Experimentation with data, processing, and analysis techniques
- Application optimized storage
    + Example usage = data mart
- Archive and raw data archive
    + Raw, processed, and transformed data

## [The 7 V's of Big Data](https://www.impactradius.com/blog/7-vs-big-data/)
+ Volume - Scale of data
+ Variety - Different forms of data
+ Velocity - Analysis of streaming data
+ Veracity - Overall quality and correctness of the data
    * Garbage in, garbage out
    * Assess the truthfulness and accuracy of the data as well as identify missing or incomplete information
- Visualization
- Value
- Variability

## Data types and sources
+ Structured
+ Unstructured
+ Semi-structured
+ Data storage (databases)
+ Sensors
+ RFID
+ Instore WiFi logs
+ Machine Logs
    * Application
    * Events
    * Server
    * CDRs
    * Clickstream
+ Text, including documents, emails, scanned documents, records, ...
+ Social networks
+ Public web
+ Geo-location
+ Machine generated
+ Clickstream
+ Software
+ Media
    * Images
    * Video
    * Audio
+ Business applications
    * OLTP, ERP, CRM systems - Online transaction processing, Enterprise resource planning, and customer relationship management
    * HR
    * Product/Project management
+ Online chat
+ Merchant listings
+ DMP - Data management platform (advertising/marketing)
+ CDR - Call detail records
+ Surveys, questionnaires, binary questions, and sentiment
+ Billing data
+ Product catalog
+ Network data
+ Subscriber data
+ Staffing
+ Inventory
+ POS and transactional
+ eCommerce transactions
+ Biometrics

## Database Considerations and Tradeoffs
- ACID
    + Atomicity
    + Consistency
    + Isolation
    + Durability
- BASE
    + Basically Available
    + Soft state
    + Eventual consistency
- CAP (Brewers theorem) and PACELC
    + Consistency
    + Availability
    + Partition tolerance
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

## Hadoop Benefits
- Ability to store any and all data types relatively cheap
- Ability to process any and all data quickly and relatively cheap
- Vast community, ecosystem, and pluggable architecture
- Scalable, flexible, computational model

## Data Lake vs Data Warehouse
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
    + Considerations
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
    + Considerations
    + Technologies
        * Hadoop
        * Apache YARN

## Data Processing and access methods/patterns compared
- Batch
    + Process batches of data on regular time intervals, e.g., hourly, daily, overnight, etc.
- Real-time
    + Monitor and react in real time
- Streaming
- Interactive
    + Data analysts reviewing data
- Online
- Search
- In-memory

## Offline vs Online Learning

Coming soon...

## Architecture Guides and Examples

**AWS**
- [Solution Development Guides](https://aws.amazon.com/solutions)
    + Reference Architectures
        * [Web Application Hosting](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_web_01.pdf)
        * [Batch Processing](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_batch_03.pdf)
        * [Large Scale Computing and Large Data Sets](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_largescale_05.pdf)
        * [Time Series Processing](http://media.amazonwebservices.com/architecturecenter/AWS_ac_ra_timeseriesprocessing_16.pdf)
    + By Application
        * [Websites](https://aws.amazon.com/websites/)
        * [Backup and Recovery](https://aws.amazon.com/backup-recovery/)
        * [Archiving](https://aws.amazon.com/archive/)
        * [DevOps](https://aws.amazon.com/devops/)
        * [Big Data](https://aws.amazon.com/big-data/)
        * [High Performance Computing](https://aws.amazon.com/hpc/)
        * [Internet of Things](https://aws.amazon.com/iot/)
        * [Business Applications](https://aws.amazon.com/business-applications/)
        * [Content Delivery](https://aws.amazon.com/content-delivery/)
        * [Mobile Services](https://aws.amazon.com/mobile/)
        * [Scientific Computing](https://aws.amazon.com/government-education/scientific-computing1/)
        * [E-commerce](https://aws.amazon.com/ecommerce-applications/)
    + By Industry Sector
        * [Financial Services](https://aws.amazon.com/financial-services/)
        * [Digital Marketing](https://aws.amazon.com/digital-marketing/)
        * [Media and Entertainment](https://aws.amazon.com/digital-media/)
        * [Gaming](https://aws.amazon.com/game-hosting/)
        * [Enterprise IT](https://aws.amazon.com/enterprise/)
        * [Healthcare & Life Sciences](https://aws.amazon.com/health/)
        * [Government](https://aws.amazon.com/government-education/government/)
        * [Nonprofit](https://aws.amazon.com/government-education/nonprofits/)
        * [Education](https://aws.amazon.com/education/)
- [Partner Solutions](https://aws.amazon.com/solutions/partners/)
    + [Big Data](https://aws.amazon.com/big-data/partner-solutions/)
    + [Storage](https://aws.amazon.com/backup-recovery/partner-solutions/)
    + [DevOps](https://aws.amazon.com/devops/partner-solutions/)
- [Case Studies](https://aws.amazon.com/solutions/case-studies/)
    + [Analytics](https://aws.amazon.com/solutions/case-studies/analytics/)
    + [Big Data](https://aws.amazon.com/solutions/case-studies/big-data/)
    + [Enterprise](https://aws.amazon.com/solutions/case-studies/enterprise-it/)
    + [Startups](https://aws.amazon.com/solutions/case-studies/start-ups/)
    + [Web Apps](https://aws.amazon.com/solutions/case-studies/web-mobile-social/)

**Google Cloud Platform**
- [Big data reference architecture diagram](https://cloud.google.com/images/products/big-data/big-data-diagram.png)
- [Solution Development Guides](https://cloud.google.com/solutions/)
    + [Media](https://cloud.google.com/solutions/media/)
    + [Mobile Applications](https://cloud.google.com/solutions/mobile/#development_guides)
    + [Big Data](https://cloud.google.com/solutions/big-data/#development_guides)
    + [Financial Services](https://cloud.google.com/solutions/financial-services/#development_guides)
    + [Gaming](https://cloud.google.com/solutions/gaming/#development_guides)
    + [Retail & Commerce](https://cloud.google.com/solutions/commerce/#development_guides)
    + [Internet of Things](https://cloud.google.com/solutions/iot/#development_guides)
    + [Websites and Web Apps](https://cloud.google.com/solutions/websites/#development_guides)
    + [Development & Test](https://cloud.google.com/solutions/dev-test/#development_guides)

**IoT**

Coming soon...

**General**
- [Lambda Architecture](http://lambda-architecture.net/)
- [AWS Architecture Center](https://aws.amazon.com/architecture/?nc1=f_cc)
- [AWS Big Data Partner Solutions](https://aws.amazon.com/big-data/partner-solutions/)
- [GCP Architecture](https://cloud.google.com/docs/tutorials#architecture)
- [Introduction to big data classification and architecture](http://www.ibm.com/developerworks/library/bd-archpatterns1/)
- [An Enterprise Architect’s Guide to Big Data](http://www.oracle.com/technetwork/topics/entarch/articles/oea-big-data-guide-1522052.pdf)
- [BIG DATA REFERENCE ARCHITECTURE](https://thinkbiganalytics.com/leading_big_data_technologies/big-data-reference-architecture/)
- [Getting Started with Big Data Architecture](http://blog.cloudera.com/blog/2014/09/getting-started-with-big-data-architecture/)
- [BIG DATA: Architectures and Technologies](https://www.sei.cmu.edu/go/big-data/)
- [Big Data Architecture](http://bigdata.teradata.com/US/Big-Ideas/Big-Data-Architecture/)
- [Big Data Analytics Architecture](http://www.thebigdatainsightgroup.com/site/sites/default/files/Teradata's%20-%20Big%20Data%20Architecture%20-%20Putting%20all%20your%20eggs%20in%20one%20basket.pdf)
- [What is Streaming Data?](https://aws.amazon.com/streaming-data/)
