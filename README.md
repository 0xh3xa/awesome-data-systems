# Awesome Data Systems
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated guide to the data ecosystem — SQL/NoSQL databases, warehouses, lakehouses, pipelines, ETL, message queues, and analytics tools.


## Table of Contents
- [Relational Databases (SQL)](#relational-databases-sql)
- [Key-Value Stores](#key-value-stores)
- [Document Databases (NoSQL)](#document-databases-nosql)
- [Graph Databases](#graph-databases)
- [Columnar Databases](#columnar-databases)
- [Time-Series Databases](#time-series-databases)
- [Vector Databases](#vector-databases)
- [Search Engines / Specialized](#search-engines--specialized)
- [Streaming Databases](#streaming-databases)
- [Data Warehouses & Lakehouses](#data-warehouses--lakehouses)
- [Cloud Databases (Managed Services)](#cloud-databases-managed-services)
  - [Amazon Web Services (AWS)](#amazon-web-services-aws)
  - [Google Cloud Platform (GCP)](#google-cloud-platform-gcp)
  - [Microsoft Azure](#microsoft-azure)
  - [Other Managed Providers](#other-managed-providers)
- [Tools & Utilities](#tools--utilities)
  - [GUI Clients](#gui-clients)
  - [Migration & Schema Tools](#migration--schema-tools)
  - [Backup & Replication](#backup--replication)
  - [Monitoring & Performance](#monitoring--performance)
  - [Data Visualization & BI](#data-visualization--bi)
  - [Caching & In-Memory Databases](#caching--in-memory-databases)
  - [Data Governance & Catalogs](#data-governance--catalogs)
  - [Data Quality & Observability](#data-quality--observability)
- [ORMs & Query Builders by Language](#orms--query-builders-by-language)
  - [Java](#java)
  - [Python](#python)
  - [Nodejs / TypeScript](#nodejs--typescript)
  - [Ruby](#ruby)
  - [PHP](#php)
  - [Go](#go)
  - [.NET](#net--c)
- [Message Queues & Streaming Platforms](#message-queues--streaming-platforms)
- [Data Pipelines & ETL Tools](#data-pipelines--etl-tools)
- [Workflow Orchestration](#workflow-orchestration)
- [Data Sharing & Federation](#data-sharing--federation)
- [ML Feature Stores](#ml-feature-stores)
- [Resources](#resources)
- [Contribute](#contribute)
- [License](#license)


## Relational Databases (SQL)
- [MariaDB](https://mariadb.org/) - Community-driven fork of MySQL.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - Relational DB for enterprise use.
- [MySQL](https://www.mysql.com/) - Popular open-source relational database.
- [Oracle Database](https://www.oracle.com/database/) - Enterprise-grade relational database.
- [PostgreSQL](https://www.postgresql.org/) - Advanced open-source relational database.
- [SQLite](https://www.sqlite.org/) - Embedded relational database, serverless.

## Key-Value Stores
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Fully managed key-value and document database by AWS.
- [etcd](https://etcd.io/) - Distributed key-value store for configuration and service discovery.
- [Redis](https://redis.io/) - In-memory data structure store, used as a database, cache, and message broker.
- [Riak KV](https://riak.com/products/riak-kv/) - Distributed key-value store.
- [Valkey](https://valkey.io/) - Open-source Redis fork, maintained by the Linux Foundation.

## Document Databases (NoSQL)
- [ArangoDB](https://arangodb.com/) - Multi-model database (document, graph, key-value).
- [CouchDB](https://couchdb.apache.org/) - Database that uses JSON for documents, HTTP for APIs, and JavaScript for queries.
- [MongoDB](https://www.mongodb.com/) - General-purpose document database.
- [RavenDB](https://ravendb.net/) - Document database with ACID guarantees.

## Graph Databases
- [JanusGraph](https://janusgraph.org/) - Scalable graph database optimized for large-scale storage.
- [Neo4j](https://neo4j.com/) - Leading graph database.
- [OrientDB](https://orientdb.org/) - Multi-model database supporting graph, document, object, and key/value models.
- [TigerGraph](https://www.tigergraph.com/) - Enterprise-level scalable graph database.

## Columnar Databases
- [Apache Cassandra](https://cassandra.apache.org/) - Distributed wide-column store, highly scalable.
- [Apache Kudu](https://kudu.apache.org/) - Fast analytics on fast data with Hadoop ecosystem.
- [ClickHouse](https://clickhouse.com/) - Column-oriented DBMS for online analytical processing.
- [HBase](https://hbase.apache.org/) - Hadoop database for large-scale columnar storage.

## Time-Series Databases
- [InfluxDB](https://www.influxdata.com/) - Time-series platform for metrics & events.
- [Prometheus](https://prometheus.io/) - Monitoring system with time-series database.
- [QuestDB](https://questdb.io/) - High-performance time-series database.
- [TimescaleDB](https://www.timescale.com/) - PostgreSQL extension for time-series data.

## Vector Databases
- [Milvus](https://milvus.io/) - Cloud-native, open-source vector database.
- [Weaviate](https://weaviate.io/) - Open-source vector database with hybrid search.
- [Qdrant](https://qdrant.tech/) - High-performance vector search engine.
- [Pinecone](https://www.pinecone.io/) - Managed vector database for similarity search.
- [Vespa](https://vespa.ai/) - Big data serving engine with vector and keyword search.

## Search Engines / Specialized
- [Elasticsearch](https://www.elastic.co/elasticsearch/) - Distributed search and analytics engine.
- [MeiliSearch](https://www.meilisearch.com/) - Fast, relevant, and typo-tolerant search engine.
- [Solr](https://solr.apache.org/) - Open-source enterprise search platform.
- [Typesense](https://typesense.org/) - Open-source, typo-tolerant search engine.

## Streaming Databases
- [ksqlDB](https://ksqldb.io/) - Event streaming database built on Kafka.
- [Materialize](https://materialize.com/) - Streaming SQL database for real-time applications.

## Data Warehouses & Lakehouses
- [Apache Iceberg](https://iceberg.apache.org/) - High-performance table format for huge analytic datasets.
- [Databricks Lakehouse](https://www.databricks.com/) - Unified platform for data warehousing and AI.
- [Delta Lake](https://delta.io/) - Storage layer for reliability and ACID transactions in lakehouses.
- [Snowflake](https://www.snowflake.com/) - Cloud data warehouse with separation of compute and storage.


## Cloud Databases (Managed Services)

### Amazon Web Services (AWS)
- [Amazon Aurora](https://aws.amazon.com/rds/aurora/) - MySQL- and PostgreSQL-compatible relational database built for the cloud.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Managed key-value & document NoSQL database.
- [Amazon Neptune](https://aws.amazon.com/neptune/) - Managed graph database service.
- [Amazon RDS](https://aws.amazon.com/rds/) - Managed relational databases (MySQL, PostgreSQL, MariaDB, Oracle, SQL Server).
- [Amazon Redshift](https://aws.amazon.com/redshift/) - Managed data warehouse.

### Google Cloud Platform (GCP)
- [BigQuery](https://cloud.google.com/bigquery) - Fully managed data warehouse.
- [Bigtable](https://cloud.google.com/bigtable) - Scalable wide-column store for time-series & IoT.
- [Cloud Spanner](https://cloud.google.com/spanner) - Globally distributed relational database.
- [Cloud SQL](https://cloud.google.com/sql) - Managed MySQL, PostgreSQL, and SQL Server.
- [Firestore](https://cloud.google.com/firestore) - NoSQL document database.

### Microsoft Azure
- [Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/) - Multi-model distributed NoSQL database.
- [Azure Database for MySQL](https://azure.microsoft.com/en-us/products/mysql/) - Managed MySQL.
- [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/products/postgresql/) - Managed PostgreSQL.
- [Azure SQL Database](https://azure.microsoft.com/en-us/products/azure-sql/database) - Managed relational database.

### Other Managed Providers
- [CockroachDB Cloud](https://www.cockroachlabs.com/product/cockroachdb-cloud/) - Distributed SQL database.
- [MongoDB Atlas](https://www.mongodb.com/atlas) - Managed MongoDB in the cloud.
- [PlanetScale](https://planetscale.com/) - Serverless MySQL database built on Vitess.
- [Supabase](https://supabase.com/) - Open-source Firebase alternative with PostgreSQL.


## Tools & Utilities

### GUI Clients
- [Beekeeper Studio](https://www.beekeeperstudio.io/) - Cross-platform SQL editor and database manager.
- [DBeaver](https://dbeaver.io/) - Universal database client supporting most databases.
- [HeidiSQL](https://www.heidisql.com/) - Lightweight SQL client for MySQL, MariaDB, PostgreSQL, and more.
- [pgAdmin](https://www.pgadmin.org/) - Popular PostgreSQL administration tool.
- [TablePlus](https://tableplus.com/) - Modern native client for multiple databases.

### Migration & Schema Tools
- [Alembic](https://alembic.sqlalchemy.org/) - Lightweight database migration tool for SQLAlchemy.
- [Flyway](https://flywaydb.org/) - Database migrations made easy.
- [Liquibase](https://www.liquibase.org/) - Version control for your database schema.
- [Prisma Migrate](https://www.prisma.io/docs/concepts/components/prisma-migrate) - Declarative data modeling & migrations for Prisma.

### Backup & Replication
- [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) - Open-source hot backup utility for MySQL.
- [pgBackRest](https://pgbackrest.org/) - Reliable backup & restore for PostgreSQL.
- [wal-g](https://github.com/wal-g/wal-g) - Backup and restore tool for Postgres, MySQL, and others.

### Monitoring & Performance
- [New Relic Database Monitoring](https://newrelic.com/) - Cloud monitoring with database insights.
- [Percona Monitoring and Management (PMM)](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Open-source database monitoring platform.
- [pgBadger](https://github.com/darold/pgbadger) - PostgreSQL log analyzer.
- [pgHero](https://github.com/ankane/pghero) - PostgreSQL performance dashboard.

### Data Visualization & BI
- [Grafana](https://grafana.com/) - Open-source analytics and monitoring platform.
- [Metabase](https://www.metabase.com/) - Open-source business intelligence & analytics.
- [Redash](https://redash.io/) - Query your data sources and build dashboards.
- [Superset](https://superset.apache.org/) - Apache Superset, data exploration & visualization.

### Caching & In-Memory Databases
- [DragonflyDB](https://www.dragonflydb.io/) - Modern in-memory data store, drop-in replacement for Redis/Memcached.
- [KeyDB](https://docs.keydb.dev/) - Multithreaded fork of Redis for better scalability.
- [Memcached](https://memcached.org/) - High-performance, distributed memory object caching system.
- [Valkey](https://valkey.io/) - High-performance, open-source Redis fork.

### Data Governance & Catalogs
- [Amundsen](https://www.amundsen.io/) - Open-source data discovery and metadata engine by Lyft.
- [DataHub](https://datahubproject.io/) - Modern data catalog and metadata platform.
- [OpenMetadata](https://open-metadata.org/) - Centralized metadata management platform.
- [Apache Atlas](https://atlas.apache.org/) - Governance and metadata framework for Hadoop ecosystems.

### Data Quality & Observability
- [Great Expectations](https://greatexpectations.io/) - Data validation and testing framework.
- [Monte Carlo](https://www.montecarlodata.com/) - Data observability platform.
- [Soda](https://soda.io/) - Data quality monitoring and validation.
  

## ORMs & Query Builders by Language

### Java
- [Ebean ORM](https://ebean.io/) - Lightweight ORM for Java/Kotlin.
- [Hibernate](https://hibernate.org/) - Most popular ORM for Java.
- [JPA (Jakarta Persistence API)](https://jakarta.ee/specifications/persistence/) - Standard for Java persistence.
- [MyBatis](https://mybatis.org/mybatis-3/) - Data mapper framework for SQL databases.

### Python
- [Django ORM](https://docs.djangoproject.com/en/stable/topics/db/) - Built-in ORM for Django framework.
- [Peewee](http://docs.peewee-orm.com/) - Small, expressive ORM for SQLite, MySQL, and PostgreSQL.
- [SQLAlchemy](https://www.sqlalchemy.org/) - SQL toolkit and ORM.
- [Tortoise ORM](https://tortoise.github.io/) - Easy async ORM inspired by Django.

### Node.js / TypeScript
- [Objection.js](https://vincit.github.io/objection.js/) - SQL-friendly ORM for Node.js built on Knex.
- [Prisma](https://www.prisma.io/) - Next-gen ORM with TypeScript support.
- [Sequelize](https://sequelize.org/) - Promise-based Node.js ORM for SQL.
- [TypeORM](https://typeorm.io/) - ORM for TypeScript and JavaScript.

### Ruby
- [Active Record](https://guides.rubyonrails.org/active_record_basics.html) - ORM for Ruby on Rails.
- [Sequel](https://sequel.jeremyevans.net/) - Database toolkit and ORM for Ruby.

### PHP
- [Doctrine ORM](https://www.doctrine-project.org/projects/orm.html) - Powerful PHP ORM.
- [Eloquent ORM](https://laravel.com/docs/eloquent) - ORM built into Laravel.

### Go
- [Ent](https://entgo.io/) - Entity framework for Go.
- [GORM](https://gorm.io/) - Popular ORM for Go.
- [SQLBoiler](https://github.com/volatiletech/sqlboiler) - Generate Go ORM models from your schema.

### .NET / C#
- [Dapper](https://github.com/DapperLib/Dapper) - Lightweight micro ORM for .NET.
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/) - Official Microsoft ORM for .NET.
- [NHibernate](https://nhibernate.info/) - Mature ORM for .NET.


## Message Queues & Streaming Platforms
- [ActiveMQ](https://activemq.apache.org/) - Open-source multi-protocol messaging server.
- [Amazon SQS](https://aws.amazon.com/sqs/) - Fully managed message queuing service by AWS.
- [Apache Kafka](https://kafka.apache.org/) - Distributed streaming platform for high-throughput event processing.
- [Azure Service Bus](https://azure.microsoft.com/en-us/products/service-bus/) - Fully managed enterprise message broker by Microsoft Azure.
- [Celery](https://docs.celeryq.dev/) - Distributed task queue for Python, often used with brokers like RabbitMQ/Redis.
- [Google Pub/Sub](https://cloud.google.com/pubsub) - Global real-time messaging service by Google Cloud.
- [NATS](https://nats.io/) - High-performance messaging system for cloud-native apps, IoT, and microservices.
- [Pulsar](https://pulsar.apache.org/) - Cloud-native, distributed messaging and streaming platform.
- [RabbitMQ](https://www.rabbitmq.com/) - Lightweight, widely used open-source message broker.
- [Redpanda](https://redpanda.com/) - Kafka-compatible streaming platform written in C++.
- [ZeroMQ](https://zeromq.org/) - High-performance asynchronous messaging library.


## Data Pipelines & ETL Tools
- [Apache Airflow](https://airflow.apache.org/) - Platform to programmatically author, schedule, and monitor workflows.
- [Apache NiFi](https://nifi.apache.org/) - Dataflow automation tool for data ingestion and ETL.
- [AWS Glue](https://aws.amazon.com/glue/) - Serverless ETL service by AWS.
- [Azure Data Factory](https://azure.microsoft.com/en-us/products/data-factory/) - Cloud-based data integration service.
- [dbt (Data Build Tool)](https://www.getdbt.com/) - Transform data inside your warehouse using SQL.
- [Google Dataflow](https://cloud.google.com/dataflow) - Fully managed streaming and batch data processing service.
- [Kafka Connect](https://kafka.apache.org/documentation/#connect) - Move data between Apache Kafka and other systems.
- [Luigi](https://github.com/spotify/luigi) - Python module to build complex pipelines of batch jobs.
- [Pentaho Data Integration (Kettle)](https://community.hitachivantara.com/s/article/data-integration-kettle) - ETL tool from the Pentaho suite.
- [Singer](https://www.singer.io/) - Standard for writing scripts that move data between databases, web APIs, files, etc.
- [Talend](https://www.talend.com/) - Commercial & open-source data integration platform.



## Workflow Orchestration
- [Prefect](https://www.prefect.io/) - Dataflow orchestration for modern pipelines.
- [Dagster](https://dagster.io/) - Orchestration platform for ML, analytics, and ETL.
- [Azkaban](https://azkaban.github.io/) - Batch workflow job scheduler by LinkedIn.
- [Oozie](https://oozie.apache.org/) - Workflow scheduler for Hadoop jobs.

## Data Sharing & Federation
- [Trino (PrestoSQL)](https://trino.io/) - SQL query engine for distributed data sources.
- [PrestoDB](https://prestodb.io/) - Distributed SQL engine for large-scale data analytics.
- [Dremio](https://www.dremio.com/) - Data lake query engine and lakehouse platform.

## ML Feature Stores
- [Feast](https://feast.dev/) - Open-source feature store.
- [Tecton](https://www.tecton.ai/) - Enterprise-grade feature platform.
- [Hopsworks](https://www.hopsworks.ai/) - Feature store with online/offline support.


## Resources
- [Awesome Database Learning](https://github.com/pingcap/awesome-database-learning) - Curated list for database learning resources.
- [Database Internals (Book)](https://www.databass.dev/) - A deep dive into how databases work.
- [Use The Index, Luke](https://use-the-index-luke.com/) - Guide to database performance for developers.
- [Database of Databases](https://dbdb.io/) - An extensive catalog of databases.
- [Awesome Big Data](https://github.com/0xnr/awesome-bigdata) - Curated list of big data frameworks.
- [CMU Database Group Lectures](https://www.youtube.com/c/cmudatabasegroup) - Deep dive into database systems.


## Contribute
Contributions are welcome! Please read the [contribution guidelines](contributing.md) first.


## License
[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  
This repository is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
