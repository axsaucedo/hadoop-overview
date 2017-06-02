# Introduction

These are complete notes on Hands on practice, exercises and installation of hadoop related services including: HDFS, YARN, MapReduce, Pig, Hive, Ambari, Spark, Mesos, TEZ, HBase, Storm, Oozie, Flink, Scoop, Flume, Kafka, MySQL, Cassandra, MongoDB, Drill, Hue, Phoenix, Presto and Zeppelin.

The live notebook can be found at: [docs/index.html](docs/index.html) 

List of contents: 

* Section 1
    - [1-1 - Hortonworks Installation](section-1/1-1.md) 
    - [1-2 - The Hadoop Ecosystem](section-1/1-2.md) 
    - [1-3 - Hadoop Ecosystem and Technologies](section-1/1-3.md) 
* Section 2
    - [2-1 - HDFS: What is it and how it works](section-2/2-1.md) 
    - [2-2 - Install Movielens dataset](section-2/2-2.md) 
    - [2-3 - HDFS: Command line interface ](section-2/2-3.md) 
    - [2-4 - MapReduce Fundamental Concepts](section-2/2-4.md) 
    - [2-5 - MapReduce on a Cluster - How MR Scales](section-2/2-5.md) 
    - [2-6 - MapReduce: A Real Life Example](section-2/2-6.md) 
    - [2-7 - Running MapReduce with MRJOB](section-2/2-7.md) 
    - [2-8 - Running with MRJob](section-2/2-8.md) 
    - [2-9 - Hadoop Your Challenge](section-2/2-9.md) 
    - [2-10 - Check your results](section-2/2-10.md) 
* Section 3
    - [3-1 - Introducing Ambari](section-3/3-1.md)
    - [3-2 - Introducing Pig](section-3/3-2.md)
    - [3-3 - PIG Example](section-3/3-3.md)
    - [3-4 - Runing Pig Script](section-3/3-4.md)
    - [3-5 - PigLatin: Diving Deeper](section-3/3-5.md)
    - [3-6 - PIG Challenge](section-3/3-6.md)
* Section 4
    - [4-1 - SPARK](section-4/4-1.md)
    - [4-2 - Introducing RDDs](section-4/4-2.md)
    - [4-3 - Example RDD in Spark](section-4/4-3.md)
    - [4-4 - Spark2.0 way of DataFrames and DataSets](section-4/4-4.md)
    - [4-5 - Spark2 Finding movies!](section-4/4-5.md)
    - [4-6 - Using MLLib in Spark](section-4/4-6.md)
    - [4-7 - Spark2 Challenge](section-4/4-7.md)
* Section 5
    - [5-1 - What is HIVE?](section-5/5-1.md)
    - [5-2 - Hive Example](section-5/5-2.md)
    - [5-3 - How Hive Works](section-5/5-3.md)
    - [5-4 - Hive Challenge](section-5/5-4.md)
    - [5-5 - Integrating MySQL & Hadoop](section-5/5-5.md)
    - [5-6 - Install MySQL and Run Stuff](section-5/5-6.md)
    - [5-7 - Using Sqoop to extract data from MySQL](section-5/5-7.md)
    - [5-8 - Sqoop export data to MySQL](section-5/5-8.md)
* Section 6
    - [6-1 - Why NoSQL](section-6/6-1.md)
    - [6-2 - HBase](section-6/6-2.md)
    - [6-3 - Let's play with HBase](section-6/6-3.md)
    - [6-4 - HBase / Pig Integration](section-6/6-4.md)
    - [6-5 - Cassandra Overview](section-6/6-5.md)
    - [6-6 - Installing Cassandra](section-6/6-6.md)
    - [6-7 - Write Spark to Cassandra](section-6/6-7.md)
    - [6-8 - MongoDB](section-6/6-8.md)
    - [6-9 - Installing MongoDB](section-6/6-9.md)
    - [6-10 - MongoDB Shell](section-6/6-10.md)
    - [6-11 - Choosing your database](section-6/6-11.md)
    - [6-12 - Exercise](section-6/6-12.md)
* Section 7
    - [7-1 - External query engiens](section-7/7-1.md)
    - [7-2 - Setting up drill](section-7/7-2.md)
    - [7-3 - Querying with Drill](section-7/7-3.md)
    - [7-4 - Apache Phoenix](section-7/7-4.md)
    - [7-5 - Installing Phoenix](section-7/7-5.md)
    - [7-6 - Using Phoenix](section-7/7-6.md)
    - [7-7 - What is presto?](section-7/7-7.md)
    - [7-8 - Installing PRESTO!](section-7/7-8.md)
    - [7-9 - Presto Cassandra integration](section-7/7-9.md)
* Section 8
    - [8-1 - Hadoop under the hood](section-8/8-1.md)
    - [8-2 - TEZ Explained](section-8/8-2.md)
    - [8-3 - Configure and run hive](section-8/8-3.md)
    - [8-4 - Apache Mesos](section-8/8-4.md)
    - [8-5 - Zookeeper Overview](section-8/8-5.md)
    - [8-6 - Simulating Zookeeper Master Failure](section-8/8-6.md)
    - [8-7 - Oozie](section-8/8-7.md)
    - [8-8 - Workflow in Oozie](section-8/8-8.md)
    - [8-9 - Zeppelin Overview](section-8/8-9.md)
    - [8-10 - Playing with Zepplin](section-8/8-10.md)
    - [8-11 - Zeppelin Advanced ](section-8/8-11.md)
    - [8-12 - HUE](section-8/8-12.md)
    - [8-13 - Other Admin Technologies](section-8/8-13.md)
* Section 9
    - [9-1 - Streaming with Kafka](section-9/9-1.md)
    - [9-2 - Setting up Kafka](section-9/9-2.md)
    - [9-3 - Advanced Kafka](section-9/9-3.md)
    - [9-4 - Apache Flume](section-9/9-4.md)
    - [9-5 - Setup Flume](section-9/9-5.md)
    - [9-6 - Setup Flume Flow](section-9/9-6.md)
* Section 10
    - [10-1 - Spark STREAMING](section-10/10-1.md)
    - [10-2 - Spark Streaming Example](section-10/10-2.md)
    - [10-3 - Python Challenge](section-10/10-3.md)
    - [10-4 - Apache Storm](section-10/10-4.md)
    - [10-5 - Apache Storm Example](section-10/10-5.md)
    - [10-6 - What is Flink](section-10/10-6.md)
    - [10-7 - Counting words with Flink](section-10/10-7.md)
* Section 11
    - [11-1 - All the other services](section-11/11-1.md)
    - [11-2 - How pieces fit together](section-11/11-2.md)
    - [11-3 - Understanding your requirements](section-11/11-3.md)
    - [11-4 - Example Top Sellers](section-11/11-4.md)
    - [11-5 - Example: Movie Recommendations](section-11/11-5.md)
    - [11-6 - Challenge: System report](section-11/11-6.md)
* Section 12
    - [12-1 - Books and Online Courses](section-12/12-1.md)







