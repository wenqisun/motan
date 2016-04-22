Quickstart
Simple call sample
Cluster call sample
Using Consul as a registry
Using ZooKeeper as a registry
The quick start gives very basic example of running client and server on the same machine.For the detailed information about using and developing Motan, please jump to Documents.

The minimum requirements to run the quick start are:

JDK 1.6 or above
A java-based project management software like Maven or Gradle


1.Add dependency to pom
<dependency>
    <groupId>com.weibo</groupId>
    <artifactId>motan-core</artifactId>
    <version>0.0.1</version>
</dependency>
<dependency>
    <groupId>com.weibo</groupId>
    <artifactId>motan-transport-netty</artifactId>
    <version>0.0.1</version>
</dependency>

<!-- dependencies blow were only needed for spring-based features -->
<dependency>
    <groupId>com.weibo</groupId>
    <artifactId>motan-springsupport</artifactId>
    <version>0.0.1</version>
</dependency>
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-context</artifactId>
    <version>4.2.4.RELEASE</version>
</dependency>

2.Create an interface for both service provider and consumer.
3.Implement service provider.
4.The service consumer
