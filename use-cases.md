# 📘 Database Use Cases

This guide maps different database categories to **real-world use cases**, so you can choose the right tool for the job.  

## Relational Databases (SQL)
Traditional row-based databases with strong ACID guarantees and structured schemas.  

**Use when:**  
- You need strong **ACID guarantees** (banking, payments).  
- Your data is **structured and relational** with joins.  
- You want **mature ecosystems** (tooling, ORMs, drivers).  

**Examples:**  
- Banking systems → PostgreSQL, Oracle  
- E-commerce platforms → MySQL, SQL Server  
- SaaS multi-tenant apps → PostgreSQL, MariaDB  

## Key-Value Stores (NoSQL)
Databases optimized for simple key-based access, often in-memory and highly scalable.  

**Use when:**  
- Ultra-fast **key-based lookups** are needed.  
- You need **caching** or session storage.  
- High-throughput reads/writes with low latency.  

**Examples:**  
- Web session caching → Redis  
- Feature flags & configs → etcd  
- Real-time leaderboards → DynamoDB  

## Document Databases (NoSQL)
Databases that store semi-structured data as JSON-like documents with flexible schemas.  

**Use when:**  
- Data is **semi-structured / JSON-like**.  
- Schema evolves frequently.  
- You need flexible queries across documents.  

**Examples:**  
- Product catalogs → MongoDB  
- Content management → CouchDB  
- Event logging → ArangoDB  

## Graph Databases (NoSQL)
Databases designed for highly connected data, optimized for traversals and relationships.  

**Use when:**  
- Relationships are **first-class citizens**.  
- You need **deep traversals** or graph algorithms.  

**Examples:**  
- Social networks → Neo4j  
- Fraud detection → TigerGraph  
- Knowledge graphs → JanusGraph  

## Wide-Column Stores (NoSQL)
Column-family databases optimized for high write throughput and large-scale distributed storage.  

**Use when:**  
- You need to handle **massive-scale writes**.  
- Queries are predictable and denormalized.  

**Examples:**  
- IoT telemetry → Cassandra  
- Time-series metrics → HBase  

## Analytical Columnar Databases (SQL)
Databases that store data by columns, optimized for analytical queries and OLAP workloads.  

**Use when:**  
- You need **OLAP-style analytics** over large datasets.  
- Workloads are **read-heavy** with aggregations.  

**Examples:**  
- Clickstream analytics → ClickHouse  
- Real-time dashboards → Apache Kudu  

## Time-Series Databases (Mixed)
Databases optimized for time-stamped data, metrics, and events.  

**Use when:**  
- Data is primarily **time-stamped**.  
- You need efficient retention, downsampling, rollups.  

**Examples:**  
- DevOps monitoring → Prometheus  
- IoT metrics → InfluxDB  
- Financial tick data → TimescaleDB  

## Vector Databases (NoSQL)
Databases specialized for storing and querying high-dimensional vectors for AI/ML use cases.  

**Use when:**  
- You need **semantic search** or **AI embeddings**.  
- High-dimensional nearest-neighbor queries.  

**Examples:**  
- Image similarity search → Milvus  
- LLM retrieval (RAG) → Weaviate, Pinecone  

## Search Engines / Specialized (NoSQL)
Engines optimized for full-text search, relevance scoring, and specialized query types.  

**Use when:**  
- You need **full-text search**.  
- Queries need **relevance ranking, fuzzy match**.  

**Examples:**  
- E-commerce product search → Elasticsearch  
- App search → Typesense  
- Log analytics → Solr  

## Streaming Databases (SQL)
Databases that support continuous queries and real-time processing on data streams.  

**Use when:**  
- You need **real-time continuous queries**.  
- Streaming transformations matter as much as storage.  

**Examples:**  
- Fraud detection → Materialize  
- Real-time personalization → ksqlDB  

## Data Warehouses & Lakehouses (SQL)
Centralized systems for large-scale analytics, combining storage and compute for BI/ML.  

**Use when:**  
- You need **centralized analytics at scale**.  
- You want **separation of compute & storage**.  

**Examples:**  
- Enterprise BI → Snowflake  
- Data lake analytics → Databricks Lakehouse  

## Storage Engines
Low-level engines handling how data is stored, indexed, and retrieved inside databases.  

**Use when:**  
- You need to optimize the **persistence layer** inside a DB.  
- Choice of engine affects **ACID, performance, durability**.  

**Examples:**  
- OLTP → InnoDB (MySQL)  
- Analytics → ColumnStore (MariaDB)  
- Embedded KV store → RocksDB  

## Data Sharing & Federation (SQL Engines)
Engines that provide SQL queries across distributed, external, or federated data sources.  

**Use when:**  
- You query **across multiple systems**.  
- You don’t want to centralize data first.  

**Examples:**  
- BI across data lakes → Trino  
- Data virtualization → Dremio  
- Ad-hoc analytics → DuckDB  

## ML Feature Stores
Specialized databases for storing and serving ML features for training and inference.  

**Use when:**  
- ML pipelines need **consistent feature values** online & offline.  
- You want **training-serving consistency**.  

**Examples:**  
- Recommender systems → Feast  
- Real-time ML → Tecton  
