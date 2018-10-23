# IMPRO-spark-docker Monitoring runtime engine statistics for Spark and Docker swarm
Over the last years, stream data processing has been gaining attention both in industry and in academia due to its wide range of applications. To fulfill the need for scalable and efficient stream analytics, numerous open source stream data processing systems have been developed, with high throughput and low latency being their key performance targets. Apache Spark is one of the stream processing systems used both in industry and in academia [1]. Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications, whether on laptops, data center VMs, or the cloud [2]. The goal of this project is to integrate docker with Spark Streaming and expose Docker- and Spark-specific statistics to a common history server and visualize them. For example, Docker provides network related statistics and Spark provides JVM related statistics.
