## Lecture 1
**RAID**  
Redundant Array of Independent Disks

**RAID Purpose**  
Fault tolerance & performance boost

**RAID 0**  
No redundancy, high performance

**RAID 1**  
Mirroring for data protection

**RAID 5**  
Striping with parity, balanced

**Software RAID**  
RAID via software, flexible

**MTBF**  
Mean Time Before Failure

**MTTD**  
Mean Time to Detect issues

**MTTR**  
Mean Time to Repair systems

**MTTA**  
Mean Time to Acknowledge events

**Error Budget**  
Time system can afford errors

**SLA**  
Service Level Agreement goals

**Three V's**  
Volume, Variety, Velocity

**Big Data Volume**  
Massive data amounts

**Big Data Variety**  
Different formats & sources

**Big Data Velocity**  
Real-time data changes

**DAS**  
Direct-Attached Storage

**DAS Limitation**  
Controller bottlenecks

**SAN**  
Storage Area Network

**SAN Purpose**  
Virtualized storage, scalable

**SAN Advantage**  
Separates processing & storage

## Lecture 2

**DFS**  
Distributed File System

**Fault Tolerance**  
Replication in DFS

**LFS**  
Local File System

**HDFS**  
Hadoop Distributed File System

**Namenode**  
Master in HDFS

**ETL**  
Extract, Transform, Load

**ELT**  
Extract, Load, Transform

**EtLT**  
Extended ETL process

**Data Lakehouse**  
Warehouse + Data Lake

**Avro**  
Row-based data format

**Parquet**  
Columnar data format

**Avro Schema**  
Schema for data evolution

**Parquet Schema**  
Optimized column schema

**Avro Data Types**  
Primitives and complex types

**Parquet Types**  
Logical and physical types

**Schema Evolution**  
Adapting schemas in Avro

**Columnar Format**  
Parquet storage style

**Random Writes**  
Avoided in DFS

**Data Zones**  
Data lake organization

**SPOF**  
Single Point of Failure

## Lecture 3
**Sqoop**  
Structured data import/export

**Flume**  
Stream unstructured data

**Sqoop vs Flume**  
Structured vs unstructured

**Flume Agent**  
Independent data daemon

**Source**  
Flume input data point

**Channel**  
Flume data buffer

**Sink**  
Flume data destination

**Kafka**  
Distributed data transport

**Topics**  
Kafka data streams

**Partitions**  
Kafka topic subdivisions

**Producer**  
Writes data to topics

**Consumer**  
Reads data from topics

**ZooKeeper**  
Kafka’s coordination tool

**Replication Factor**  
Kafka data redundancy

**Consumer Group**  
Shared Kafka topic readers

**Kafka Connect**  
Kafka data integration

**Connector**  
Manages Kafka tasks

**Dead Letter Queue**  
Handles Kafka errors

**ksqlDB**  
Stream-processing SQL

**Event Stream**  
Continuous data flow

## Lecture 4
**Spark**  
Distributed data engine

**RDD**  
Resilient Distributed Dataset

**Partition**  
Batch for parallel processing

**Narrow Dependency**  
Single-partition data usage

**Wide Dependency**  
Cross-partition data shuffle

**DAG**  
Directed Acyclic Graph

**Task Scheduling**  
Optimized job execution

**Spark SQL**  
Declarative query model

**DataFrame**  
Schema-enforced RDD

**RDD vs DataFrame**  
Untyped vs typed schema

**JSON DataFrame**  
Schema from JSON source

**Spark Streaming**  
Real-time batch processing

**D-Stream**  
RDDs from streaming data

**Sliding Window**  
Grouped past data batches

**Structured Streaming**  
Improved real-time processing

**Data Locality**  
Task close to partition

**Schema Enforcement**  
Ensures consistent structure

**Exactly-Once**  
Guaranteed data processing

## Lecture 5
**MapReduce**  
Distributed processing model

**Map Function**  
Processes key-value pairs

**Reduce Function**  
Combines key-grouped values

**Shuffle Phase**  
Groups data by keys

**Hive**  
SQL on Hadoop framework

**Schema in Hive**  
Defines data structure

**Partitioning**  
Data split across servers

**Vertical Partitioning**  
Divide by columns

**Horizontal Partitioning**  
Divide by rows

**HBase**  
Column-based NoSQL DB

**Cassandra**  
High-performance NoSQL DB

**MongoDB**  
Document-based NoSQL DB

**Replica Sets**  
MongoDB HA strategy

**Sharding**  
Scalable data distribution

**Gossip Protocol**  
Cassandra node communication

**Redis**  
Fast in-memory DB

**Master-Replica**  
Write-read database scaling

**Consistency Trade-off**  
Relational DB scaling issue

## Tools

**HDFS Pros**  
Distributed, fault-tolerant, scalable

**HDFS Cons**  
Not for transactional data

**HDFS Use Case**  
Big data pipelines & analytics

**Kafka Storage Pros**  
Persistent, fault-tolerant, scalable

**Kafka Storage Cons**  
Not for batch analytics

**Kafka Storage Use Case**  
Real-time event streaming

**HBase Pros**  
Column-oriented, random R/W

**HBase Cons**  
Complex schema design

**HBase Use Case**  
Large NoSQL random access

**Redis Pros**  
In-memory, ultra-fast, TTL keys

**Redis Cons**  
Limited to key-value storage

**Redis Use Case**  
Caching, leaderboards, sessions

**GFS Pros**  
Pioneered distributed storage

**GFS Cons**  
Proprietary to Google

**GFS Use Case**  
Internal Google applications

**Avro Pros**  
Row-based, schema evolution

**Avro Cons**  
Inefficient for analytics

**Avro Use Case**  
Streaming, write-heavy workloads

**Parquet Pros**  
Columnar, high compression

**Parquet Cons**  
Slower writes

**Parquet Use Case**  
Analytics on large datasets

**JSON Pros**  
Human-readable, debug-friendly

**JSON Cons**  
Inefficient storage, large size

**JSON Use Case**  
Data interchange, debugging

**Kafka Transport Pros**  
High throughput, scalable

**Kafka Transport Cons**  
Overkill for small tasks

**Kafka Transport Use Case**  
Real-time messaging

**Flume Pros**  
Simple log ingestion

**Flume Cons**  
Log data only, not versatile

**Flume Use Case**  
Ingesting logs into HDFS

**Sqoop Pros**  
Easy structured data transfer

**Sqoop Cons**  
Batch only, no real-time use

**Sqoop Use Case**  
RDBMS ↔ HDFS data transfer

**MapReduce Pros**  
Reliable, handles massive data

**MapReduce Cons**  
Disk-based, high latency

**MapReduce Use Case**  
Batch jobs, slow-critical tasks

**Spark Pros**  
Fast, in-memory, unified API

**Spark Cons**  
High memory requirements

**Spark Use Case**  
Streaming & machine learning

**Hive Pros**  
SQL-like, legacy integration

**Hive Cons**  
High latency, batch only

**Hive Use Case**  
SQL on HDFS for structured data

**Storage Tools**  
HDFS, Kafka, HBase, Redis, GFS

**File Formats**  
Avro, Parquet, JSON

**Transport Tools**  
Kafka, Flume, Sqoop

**Processing Tools**  
MapReduce, Spark, Hive