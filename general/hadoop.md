>![](http://www.easyicon.net/api/resize_png_new.php?id=1174989&size=16)[youngwookim/awesome-hadoop](https://github.com/youngwookim/awesome-hadoop)

# Awesome Hadoop

A curated list of amazingly awesome Hadoop and Hadoop ecosystem resources. Inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php), [Awesome Python](https://github.com/vinta/awesome-python) and [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin)

- [Awesome Hadoop](#awesome-hadoop)
	- [Hadoop](#hadoop)
	- [YARN](#yarn)
	- [NoSQL](#nosql)
	- [SQL on Hadoop](#sql-on-hadoop)
	- [Workflow, Lifecycle and Governance](#workflow_lifecycle_and_Governance)
	- [Data Ingestion and Integration](#data-ingestion-and-integration)
	- [DSL](#dsl)
	- [Libraries and Tools](#libraries-and-tools)
	- [Realtime Data Processing](#realtime-data-processing)
	- [Distributed Computing and Programming](#distributed_computing_and_programming)
	- [Packaging, Provisioning and Monitoring](#packaging-provisioning-and-monitoring)
	- [Monitoring](#monitoring)
	- [Search](#search)
	- [Benchmark](#benchmark)
	- [Machine learning and Big Data analytics](#machine_learning_and_big_data_analytics)
	- [Misc.](#misc)
- [Resources](#resources)
	- [Websites](#websites)
	- [Presentations](#presentations)
	- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)

## Hadoop

* [Apache Hadoop](http://hadoop.apache.org/) - Apache Hadoop
* [Apache Tez](http://tez.incubator.apache.org/)
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) - SpatialHadoop is a MapReduce extension to Apache Hadoop designed specially to work with spatial data.
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) - Big Data Spatial Analytics for the Hadoop Framework
* [Elasticsearch Hadoop](https://github.com/elasticsearch/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop. Supports Map/Reduce, Cascading, Apache Hive and Apache Pig.
* [dumbo](https://github.com/klbostee/dumbo) - Python module that allows you to easily write and run Hadoop programs.
* [hadoopy](https://github.com/bwhite/hadoopy) - Python MapReduce library written in Cython.
* [mrjob](https://github.com/Yelp/mrjob/) - mrjob is a Python 2.5+ package that helps you write and run Hadoop Streaming jobs.
* [pydoop](http://pydoop.sourceforge.net/) - Pydoop is a package that provides a Python API for Hadoop.
* [hdfs-du](https://github.com/twitter/hdfs-du) - HDFS-DU is an interactive visualization of the Hadoop distributed file system.
* [White Elephant](https://github.com/linkedin/white-elephant) - Hadoop log aggregator and dashboard
* [Kiji Project](http://www.kiji.org/)
* [Genie](https://github.com/Netflix/genie) - Genie provides REST-ful APIs to run Hadoop, Hive and Pig jobs, and to manage multiple Hadoop resources and perform job submissions across them.

## YARN

* [Apache Twill](http://twill.incubator.apache.org/)
* [mpich2-yarn](https://github.com/clarkyzl/mpich2-yarn) - Running MPICH2 on Yarn

## NoSQL
*Next Generation Databases mostly addressing some of the points: being non-relational, distributed, open-source and horizontally scalable.*

* [Apache HBase](http://hbase.apache.org) - Apache HBase
* [Apache Phoenix](http://phoenix.apache.org/) - A SQL skin over HBase
* [happybase](https://github.com/wbolster/happybase) - A developer-friendly Python library to interact with Apache HBase.
* [Hannibal](https://github.com/sentric/hannibal) - Hannibal is tool to help monitor and maintain HBase-Clusters that are configured for manual splitting.
* [Haeinsa](https://github.com/VCNC/haeinsa) - Haeinsa is linearly scalable multi-row, multi-table transaction library for HBase
* [hindex](https://github.com/Huawei-Hadoop/hindex) - Secondary Index for HBase
* [Apache Accumulo](https://accumulo.apache.org/) - The Apache Accumulo™ sorted, distributed key/value store is a robust, scalable, high performance data storage and retrieval system.
* [OpenTSDB](http://opentsdb.net/) - The Scalable Time Series Database
* [Apache Cassandra](http://cassandra.apache.org/)

## SQL on Hadoop
*SQL on Hadoop*

* [Apache Hive](http://hive.apache.org)
* [Cloudera Impala](http://impala.io/)
* [Presto](http://prestodb.io/)
* [Apache Tajo](http://tajo.apache.org/)
* Hive Plugins
 * UDF
     * http://nexr.github.io/hive-udf/
     * https://github.com/edwardcapriolo/hive_cassandra_udfs
     * https://github.com/livingsocial/HiveSwarm
     * https://github.com/ThinkBigAnalytics/Hive-Extensions-from-Think-Big-Analytics
     * https://github.com/karthkk/udfs
     * https://github.com/kevinweil/elephant-bird - Twitter
     * https://github.com/lovelysystems/ls-hive
     * https://github.com/stewi2/hive-udfs
     * https://github.com/klout/brickhouse
     * https://github.com/markgrover/hive-translate (PostgreSQL translate())
     * https://github.com/deanwampler/HiveUDFs
     * https://github.com/myui/hivemall (Machine Learning UDF/UDAF/UDTF)
     * https://github.com/edwardcapriolo/hive-geoip (GeoIP UDF)
 * Storage Handler
     * https://github.com/dvasilen/Hive-Cassandra
     * https://github.com/yc-huang/Hive-mongo
     * https://github.com/balshor/gdata-storagehandler
     * https://github.com/karthkk/hive-hbase-json
     * https://github.com/sunsuk7tp/hive-hbase-integration
     * https://bitbucket.org/rodrigopr/redisstoragehandler
     * https://github.com/zhuguangbin/HiveJDBCStorageHanlder
     * https://github.com/chimpler/hive-solr
     * https://github.com/bfemiano/accumulo-hive-storage-manager
 * SerDe
     * https://github.com/rcongiu/Hive-JSON-Serde
     * https://github.com/mochi/hive-json-serde
     * https://github.com/ogrodnek/csv-serde
     * https://github.com/parag/HiveJsonSerde
     * https://github.com/johanoskarsson/hive-json-serde
     * https://github.com/electrum/hive-serde - JSON
     * https://github.com/karthkk/hive-hbase-json
 * Libraries and tools
     * https://github.com/forward/rbhive
     * https://github.com/synctree/activerecord-hive-adapter
     * https://github.com/hrp/sequel-hive-adapter
     * https://github.com/forward/node-hive
     * https://github.com/recruitcojp/WebHive
     * [shib](https://github.com/tagomoris/shib) - WebUI for query engines: Hive and Presto
     * [clive](https://github.com/bmuller/clive) - Clojure library for interacting with Hive via Thrift
     * http://www.phphiveadmin.net/
     * https://github.com/anjuke/hwi
     * https://code.google.com/a/apache-extras.org/p/hipy/
     * https://github.com/dmorel/Thrift-API-HiveClient2 (Perl - HiveServer2)
     * [PyHive](https://github.com/dropbox/PyHive) - Python interface to Hive and Presto
     * https://github.com/recruitcojp/OdbcHive
     * [Hive-Sharp](https://bitbucket.org/vadim/hive-sharp)
     * [HiveRunner](https://github.com/klarna/HiveRunner) - An Open Source unit test framework for hadoop hive queries based on JUnit4
     * [Beetest](https://github.com/kawaa/Beetest) - A super simple utility for testing Apache Hive scripts locally for non-Java developers.
     * [Hive_test](https://github.com/edwardcapriolo/hive_test)- Unit test framework for hive and hive-service

* [Apache Drill](http://incubator.apache.org/)

## Workflow, Lifecycle and Governance

* [Apache Oozie](http://oozie.apche.org) - Apache Oozie
* [Azkaban](http://azkaban.github.io/)
* [Apache Falcon](http://falcon.incubator.apache.org/) - Data management and processing platform

## Data Ingestion and Integration

* [Apache Flume](http://flume.apache.org) - Apache Flume
* [Apache Sqoop](http://sqoop.apache.org) - Apache Sqoop
* [Apache Kafka](http://kafka.apache.org/) - Apache Kafka
* Flume Plugins
 * [Flume MongoDB Sink](https://github.com/leonlee/flume-ng-mongodb-sink)
 * [Flume HornetQ Channel](https://github.com/btoddb/flume-ng-hornetq-channel)
 * [Flume MessagePack Source](https://github.com/leonlee/flume-ng-msgpack-source)
 * [Flume RabbitMQ source and sink](https://github.com/jcustenborder/flume-ng-rabbitmq)
 * [Flume UDP Source](https://github.com/whitepages/flume-udp-source)
 * [Stratio Ingestion](https://github.com/Stratio/stratio-ingestion) - Custom sinks: Cassandra, MongoDB, Stratio Streaming and JDBC
 * [Flume Custom Serializers](https://github.com/relistan/flume-serializers)
 * [Real-time analytics in Apache Flume](https://github.com/jrkinley/flume-interceptor-analytics)
 * [.Net FlumeNG Clients](https://github.com/marksl/DotNetFlumeNG.Clients)
* [Suro](https://github.com/Netflix/suro) - Netflix's distributed Data Pipeline

## DSL
**

* [Apache Pig](http://pig.apache.org) - Apache Pig
* [Apache DataFu](http://datafu.incubator.apache.org/) - A collection of libraries for working with large-scale data in Hadoop
* [vahara](https://github.com/Ganglion/varaha) - Machine learning and natural language processing with Apache Pig
* [packetpig](https://github.com/packetloop/packetpig) - Open Source Big Data Security Analytics
* [akela](https://github.com/mozilla-metrics/akela) - Mozilla's utility library for Hadoop, HBase, Pig, etc.
* [seqpig](http://seqpig.sourceforge.net/) - Simple and scalable scripting for large sequencing data set(ex: bioinfomation) in Hadoop
* [Lipstick](https://github.com/Netflix/Lipstick) - Pig workflow visualization tool. [Introducing Lipstick on A(pache) Pig](http://techblog.netflix.com/2013/06/introducing-lipstick-on-apache-pig.html)
* [PigPen](https://github.com/Netflix/PigPen) - PigPen is map-reduce for Clojure, or distributed Clojure. It compiles to Apache Pig, but you don't need to know much about Pig to use it.

## Libraries and Tools
**

* [Kite Software Development Kit](http://kitesdk.org/) - A set of libraries, tools, examples, and documentation
* [gohadoop](https://github.com/hortonworks/gohadoop) - Native go clients for Apache Hadoop YARN.
* [Hue](http://gethue.com/) - A Web interface for analyzing data with Apache Hadoop.
* [Zeppelin](http://zeppelin-project.org/)
* [Jumbune](https://github.com/impetus-opensource/jumbune) - Jumbune is an open-source product built for analyzing Hadoop cluster and MapReduce jobs.
* [Apache Thrift](http://thrift.apache.org/)
* [Apache Avro](http://avro.apache.org/) - Apache Avro is a data serialization system.
* [Elephant Bird](https://github.com/kevinweil/elephant-bird) - Twitter's collection of LZO and Protocol Buffer-related Hadoop, Pig, Hive, and HBase code.
* [Spring for Apache Hadoop](http://projects.spring.io/spring-hadoop/)

## Realtime Data Processing

* [Apache Storm](https://storm.incubator.apache.org/)
* [Apache Samza](http://samza.incubator.apache.org/)

## Distributed Computing and Programming

* [Apache Spark](http://spark.apache.org/)
* [Apache Crunch](http://crunch.apache.org)
* [Cascading](http://www.cascading.org/) - Cascading is the proven application development platform for building data applications on Hadoop.
* [Apache Flink](http://flink.incubator.apache.org/) - Apache Flink is a platform for efficient, distributed, general-purpose data processing.

## Packaging, Provisioning and Monitoring

* [Apache Bigtop](http://bigtop.apache.org/) - Apache Bigtop: Packaging and tests of the Apache Hadoop ecosystem
* [Apache Ambari](http://ambari.apache.org/) - Apache Ambari
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/)
* [ankush](https://github.com/impetus-opensource/ankush) - A big data cluster management tool that creates and manages clusters of different technologies.
* [Apache Zookeeper](http://zookeeper.apache.org/) - Apache Zookeeper
* [Apache Curator](http://curator.apache.org/) - ZooKeeper client wrapper and rich ZooKeeper framework
* [Buildoop](https://github.com/buildoop/buildoop) - Hadoop Ecosystem Builder
* [Deploop](http://deploop.github.io/) - The Hadoop Deploy System

## Search

* [ElasticSearch](http://www.elasticsearch.org/)
* [Apache Solr](http://lucene.apache.org/solr/)
* [SenseiDB](http://www.senseidb.com/) - Open-source, distributed, realtime, semi-structured database

## Benchmark
**

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)
* [HiBench](https://github.com/intel-hadoop/HiBench)
* [Big-Bench](https://github.com/intel-hadoop/Big-Bench)
* [hive-benchmarks](https://github.com/yhuai/hive-benchmarks)
* [hive-testbench](https://github.com/cartershanklin/hive-testbench) - Testbench for experimenting with Apache Hive at any data scale.

## Machine learning and Big Data analytics

* [Apache Maout](http://mahout.apache.org)
* [Cloudera Oryx](https://github.com/cloudera/oryx) - The Oryx open source project provides simple, real-time large-scale machine learning / predictive analytics infrastructure.
* [MLlib](https://spark.apache.org/mllib/) - MLlib is Apache Spark's scalable machine learning library.
* [R](http://www.r-project.org/) - R is a free software environment for statistical computing and graphics.
* [RHive](http://nexr.github.io/RHive/) - RHive is an R extension facilitating distributed computing via Apache Hive.
* [RHadoop](https://github.com/RevolutionAnalytics/RHadoop/wiki)

## Misc.

# Resources
Various resources, such as books, websites and articles.

## Websites
*Useful websites and articles*

* [Hadoop Weekly](http://www.hadoopweekly.com/)
* [The Hadoop Ecosystem Table](http://hadoopecosystemtable.github.io/)
* [Hadoop 1.x vs 2](http://www.slideshare.net/RommelGarcia2/hadoop-1x-vs-2)
* [Apache Hadoop YARN: Yet Another Resource Negotiator](http://www.socc2013.org/home/program/a5-vavilapalli.pdf)
* [Introducing Apache Hadoop YARN](http://hortonworks.com/blog/introducing-apache-hadoop-yarn/)
* [Apache Hadoop YARN - Background and an Overview](http://hortonworks.com/blog/apache-hadoop-yarn-background-and-an-overview/)
* [Apache Hadoop YARN - Concepts and Applications](http://hortonworks.com/blog/apache-hadoop-yarn-concepts-and-applications/)
* [Apache Hadoop YARN - ResourceManager](http://hortonworks.com/blog/apache-hadoop-yarn-resourcemanager/)
* [Apache Hadoop YARN - NodeManager](http://hortonworks.com/blog/apache-hadoop-yarn-nodemanager/)
* [Migrating to MapReduce 2 on YARN (For Users)](http://blog.cloudera.com/blog/2013/11/migrating-to-mapreduce-2-on-yarn-for-users/)
* [Migrating to MapReduce 2 on YARN (For Operators)](http://blog.cloudera.com/blog/2013/11/migrating-to-mapreduce-2-on-yarn-for-operators/)
* [Hadoop and Big Data: Use Cases at Salesforce.com](http://blogs.developerforce.com/engineering/2013/03/hadoop-use-cases-at-salesforce-com.html)
* [All you wanted to know about Hadoop, but were too afraid to ask: genealogy of elephants.](https://blogs.apache.org/bigtop/entry/all_you_wanted_to_know)
* [What is Bigtop, and Why Should You Care?](https://blogs.apache.org/bigtop/entry/bigtop_and_why_should_you)
* [Hadoop - Distributions and Commercial Support](http://wiki.apache.org/hadoop/Distributions%20and%20Commercial%20Support)
* [Ganglia configuration for a small Hadoop cluster and some troubleshooting](http://hakunamapdata.com/ganglia-configuration-for-a-small-hadoop-cluster-and-some-troubleshooting/)
* [Hadoop illuminated](http://hadoopilluminated.com/) - Open Source Hadoop Book
* [NoSQL Database](http://nosql-database.org/)
* [10 Best Practices for Apache Hive](http://www.qubole.com/hive-best-practices/)
* [Hadoop Operations at Scale](http://hortonworks.com/blog/apache-hadoop-operations-scale/)

## Presentations

* [Hadoop 24/7](http://www.slideshare.net/allenwittenauer/aw-apachecon2009-15342917)
* [An example Apache Hadoop Yarn upgrade](http://www.slideshare.net/mikejf12/an-example-apache-hadoop-yarn-upgrade)
* [Apache Hadoop In Theory And Practice](http://www.slideshare.net/AdamKawa/hadoop-intheoryandpractice)
* [Hadoop Operations at LinkedIn](http://www.slideshare.net/allenwittenauer/2013-hadoopsummitemea)
* [Hadoop Performance at LinkedIn](http://www.slideshare.net/allenwittenauer/2012-lihadoopperf)

## Books

* [Hadoop: The Definitive Guide](http://www.amazon.com/gp/product/1449311520/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449311520&linkCode=as2&tag=matratsblo-20)
* [Hadoop Operations](http://www.amazon.com/gp/product/1449327052/ref=as_li_ss_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449327052&linkCode=as2&tag=matratsblo-20)
* [Apache Hadoop Yarn](http://www.amazon.com/dp/0321934504?tag=matratsblo-20)
* [HBase: The Definitive Guide](http://shop.oreilly.com/product/0636920014348.do)
* [Programming Pig](http://shop.oreilly.com/product/0636920018087.do)
* [Programming Hive](http://shop.oreilly.com/product/0636920023555.do)

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.
