# Awesome Databases
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of databases, database engines, tools, and resources for learning, exploring, and building with data.  

## Table of Contents
- [Relational Databases (SQL)](#relational-databases-sql)
- [Key-Value Stores](#key-value-stores)
- [Document Databases (NoSQL)](#document-databases-nosql)
- [Graph Databases](#graph-databases)
- [Columnar Databases](#columnar-databases)
- [Time-Series Databases](#time-series-databases)
- [Search Engines / Specialized](#search-engines--specialized)
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
- [ORMs & Query Builders by Language](#orms--query-builders-by-language)
  - [Java](#java)
  - [Python](#python)
  - [Nodejs--typescript](#nodejs--typescript)
  - [Ruby](#ruby)
  - [PHP](#php)
  - [Go](#go)
  - [.NET](#net--c)
- [Data Pipelines & ETL Tools](#data-pipelines--etl-tools)
- [Resources](#resources)
- [Contribute](#contribute)


## Relational Databases (SQL)
- [PostgreSQL](https://www.postgresql.org/) - Advanced open-source relational database.
- [MySQL](https://www.mysql.com/) - Popular open-source relational database.
- [MariaDB](https://mariadb.org/) - Community-driven fork of MySQL.
- [SQLite](https://www.sqlite.org/) - Embedded relational database, serverless.
- [Oracle Database](https://www.oracle.com/database/) - Enterprise-grade relational database.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - Relational DB for enterprise use.

## Key-Value Stores
- [Redis](https://redis.io/) - In-memory data structure store, used as a database, cache, and message broker.
- [Valkey](https://valkey.io/) - Open-source Redis fork, maintained by the Linux Foundation.
- [Riak KV](https://riak.com/products/riak-kv/) - Distributed key-value store.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Fully managed key-value and document database by AWS.
- [etcd](https://etcd.io/) - Distributed key-value store for configuration and service discovery.

## Document Databases (NoSQL)
- [MongoDB](https://www.mongodb.com/) - General-purpose document database.
- [CouchDB](https://couchdb.apache.org/) - Database that uses JSON for documents, HTTP for APIs, and JavaScript for queries.
- [ArangoDB](https://arangodb.com/) - Multi-model database (document, graph, key-value).
- [RavenDB](https://ravendb.net/) - Document database with ACID guarantees.

## Graph Databases
- [Neo4j](https://neo4j.com/) - Leading graph database.
- [OrientDB](https://orientdb.org/) - Multi-model database supporting graph, document, object, and key/value models.
- [JanusGraph](https://janusgraph.org/) - Scalable graph database optimized for large-scale storage.
- [TigerGraph](https://www.tigergraph.com/) - Enterprise-level scalable graph database.

## Columnar Databases
- [Apache Cassandra](https://cassandra.apache.org/) - Distributed wide-column store, highly scalable.
- [HBase](https://hbase.apache.org/) - Hadoop database for large-scale columnar storage.
- [ClickHouse](https://clickhouse.com/) - Column-oriented DBMS for online analytical processing.
- [Apache Kudu](https://kudu.apache.org/) - Fast analytics on fast data with Hadoop ecosystem.

## Time-Series Databases
- [InfluxDB](https://www.influxdata.com/) - Time-series platform for metrics & events.
- [TimescaleDB](https://www.timescale.com/) - PostgreSQL extension for time-series data.
- [Prometheus](https://prometheus.io/) - Monitoring system with time-series database.
- [QuestDB](https://questdb.io/) - High-performance time-series database.

## Search Engines / Specialized
- [Elasticsearch](https://www.elastic.co/elasticsearch/) - Distributed search and analytics engine.
- [Solr](https://solr.apache.org/) - Open-source enterprise search platform.
- [MeiliSearch](https://www.meilisearch.com/) - Fast, relevant, and typo-tolerant search engine.
- [Typesense](https://typesense.org/) - Open-source, typo-tolerant search engine.


## Cloud Databases (Managed Services)

### Amazon Web Services (AWS)
- [Amazon RDS](https://aws.amazon.com/rds/) - Managed relational databases (MySQL, PostgreSQL, MariaDB, Oracle, SQL Server).
- [Amazon Aurora](https://aws.amazon.com/rds/aurora/) - MySQL- and PostgreSQL-compatible relational database built for the cloud.
- [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Managed key-value & document NoSQL database.
- [Amazon Neptune](https://aws.amazon.com/neptune/) - Managed graph database service.
- [Amazon Redshift](https://aws.amazon.com/redshift/) - Managed data warehouse.

### Google Cloud Platform (GCP)
- [Cloud SQL](https://cloud.google.com/sql) - Managed MySQL, PostgreSQL, and SQL Server.
- [Cloud Spanner](https://cloud.google.com/spanner) - Globally distributed relational database.
- [Firestore](https://cloud.google.com/firestore) - NoSQL document database.
- [Bigtable](https://cloud.google.com/bigtable) - Scalable wide-column store for time-series & IoT.
- [BigQuery](https://cloud.google.com/bigquery) - Fully managed data warehouse.

### Microsoft Azure
- [Azure SQL Database](https://azure.microsoft.com/en-us/products/azure-sql/database) - Managed relational database.
- [Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/) - Multi-model distributed NoSQL database.
- [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/products/postgresql/) - Managed PostgreSQL.
- [Azure Database for MySQL](https://azure.microsoft.com/en-us/products/mysql/) - Managed MySQL.

### Other Managed Providers
- [MongoDB Atlas](https://www.mongodb.com/atlas) - Managed MongoDB in the cloud.
- [CockroachDB Cloud](https://www.cockroachlabs.com/product/cockroachdb-cloud/) - Distributed SQL database.
- [PlanetScale](https://planetscale.com/) - Serverless MySQL database built on Vitess.
- [Supabase](https://supabase.com/) - Open-source Firebase alternative with PostgreSQL.


## Tools & Utilities

### GUI Clients
- [DBeaver](https://dbeaver.io/) - Universal database client supporting most databases.
- [HeidiSQL](https://www.heidisql.com/) - Lightweight SQL client for MySQL, MariaDB, PostgreSQL, and more.
- [pgAdmin](https://www.pgadmin.org/) - The most popular PostgreSQL administration tool.
- [TablePlus](https://tableplus.com/) - Modern native client for multiple databases.
- [Beekeeper Studio](https://www.beekeeperstudio.io/) - Cross-platform SQL editor and database manager.

### Migration & Schema Tools
- [Flyway](https://flywaydb.org/) - Database migrations made easy.
- [Liquibase](https://www.liquibase.org/) - Version control for your database schema.
- [Alembic](https://alembic.sqlalchemy.org/) - Lightweight database migration tool for SQLAlchemy.
- [Prisma Migrate](https://www.prisma.io/docs/concepts/components/prisma-migrate) - Declarative data modeling & migrations for Prisma.

### Backup & Replication
- [pgBackRest](https://pgbackrest.org/) - Reliable backup & restore for PostgreSQL.
- [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) - Open-source hot backup utility for MySQL.
- [wal-g](https://github.com/wal-g/wal-g) - Backup and restore tool for Postgres, MySQL, and others.

### Monitoring & Performance
- [pgBadger](https://github.com/darold/pgbadger) - PostgreSQL log analyzer.
- [pgHero](https://github.com/ankane/pghero) - PostgreSQL performance dashboard.
- [Percona Monitoring and Management (PMM)](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Open-source database monitoring platform.
- [New Relic Database Monitoring](https://newrelic.com/) - Cloud monitoring with database insights.

### Data Visualization & BI
- [Metabase](https://www.metabase.com/) - Open-source business intelligence & analytics.
- [Superset](https://superset.apache.org/) - Apache Superset, data exploration & visualization.
- [Redash](https://redash.io/) - Query your data sources and build dashboards.
- [Grafana](https://grafana.com/) - Open-source analytics and monitoring platform.


## ORMs & Query Builders by Language

### Java
- [Hibernate](https://hibernate.org/) - Most popular ORM for Java.
- [MyBatis](https://mybatis.org/mybatis-3/) - Data mapper framework for SQL databases.
- [Ebean ORM](https://ebean.io/) - Lightweight ORM for Java/Kotlin.
- [JPA (Jakarta Persistence API)](https://jakarta.ee/specifications/persistence/) - Standard for Java persistence.

### Python
- [SQLAlchemy](https://www.sqlalchemy.org/) - SQL toolkit and ORM.
- [Django ORM](https://docs.djangoproject.com/en/stable/topics/db/) - Built-in ORM for Django framework.
- [Peewee](http://docs.peewee-orm.com/) - Small, expressive ORM for SQLite, MySQL, and PostgreSQL.
- [Tortoise ORM](https://tortoise.github.io/) - Easy async ORM inspired by Django.

### Node.js / TypeScript
- [Sequelize](https://sequelize.org/) - Promise-based Node.js ORM for SQL.
- [Prisma](https://www.prisma.io/) - Next-gen ORM with TypeScript support.
- [TypeORM](https://typeorm.io/) - ORM for TypeScript and JavaScript.
- [Objection.js](https://vincit.github.io/objection.js/) - SQL-friendly ORM for Node.js built on Knex.

### Ruby
- [Active Record](https://guides.rubyonrails.org/active_record_basics.html) - ORM for Ruby on Rails.
- [Sequel](https://sequel.jeremyevans.net/) - Database toolkit and ORM for Ruby.

### PHP
- [Eloquent ORM](https://laravel.com/docs/eloquent) - ORM built into Laravel.
- [Doctrine ORM](https://www.doctrine-project.org/projects/orm.html) - Powerful PHP ORM.

### Go
- [GORM](https://gorm.io/) - Popular ORM for Go.
- [Ent](https://entgo.io/) - Entity framework for Go.
- [SQLBoiler](https://github.com/volatiletech/sqlboiler) - Generate Go ORM models from your schema.

### .NET / C#
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/) - Official Microsoft ORM for .NET.
- [Dapper](https://github.com/DapperLib/Dapper) - Lightweight micro ORM for .NET.
- [NHibernate](https://nhibernate.info/) - Mature ORM for .NET.


## Tools & Utilities

### Caching & In-Memory Databases
- [Valkey](https://valkey.io/) - High-performance, open-source Redis fork.
- [KeyDB](https://docs.keydb.dev/) - Multithreaded fork of Redis for better scalability.
- [DragonflyDB](https://www.dragonflydb.io/) - Modern in-memory data store, drop-in replacement for Redis/Memcached.
- [Memcached](https://memcached.org/) - High-performance, distributed memory object caching system.

## Data Pipelines & ETL Tools

- [Apache Airflow](https://airflow.apache.org/) - Platform to programmatically author, schedule, and monitor workflows.
- [dbt (Data Build Tool)](https://www.getdbt.com/) - Transform data inside your warehouse using SQL.
- [Apache NiFi](https://nifi.apache.org/) - Dataflow automation tool for data ingestion and ETL.
- [Luigi](https://github.com/spotify/luigi) - Python module to build complex pipelines of batch jobs.
- [Talend](https://www.talend.com/) - Commercial & open-source data integration platform.
- [Pentaho Data Integration (Kettle)](https://community.hitachivantara.com/s/article/data-integration-kettle) - ETL tool from the Pentaho suite.
- [AWS Glue](https://aws.amazon.com/glue/) - Serverless ETL service by AWS.
- [Google Dataflow](https://cloud.google.com/dataflow) - Fully managed streaming and batch data processing service.
- [Azure Data Factory](https://azure.microsoft.com/en-us/products/data-factory/) - Cloud-based data integration service.
- [Kafka Connect](https://kafka.apache.org/documentation/#connect) - Scalable and reliable way to move data between Apache Kafka and other systems.
- [Singer](https://www.singer.io/) - Standard for writing scripts that move data between databases, web APIs, files, etc.


## Resources
- [Database Internals (Book)](https://www.databass.dev/) - A deep dive into how databases work.
- [Use The Index, Luke](https://use-the-index-luke.com/) - Guide to database performance for developers.
- [Awesome Database Learning](https://github.com/pingcap/awesome-database-learning) - Curated list for database learning resources.


## Contribute

Feel free to contribute by submitting a pull request or opening an issue to suggest improvements or additional tools.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This repository is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).


[Topic: Malware Dataset](https://github.com/topics/database)
