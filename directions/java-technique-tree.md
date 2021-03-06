# Java-based Technique Tree 

### CS Foundations

  - Data Structure and Algorithms
  - Computer Architecture
  - Operating System Concepts
  - Computer Networks
  - Database System Concepts

### Programming Languages 

  - Infrastructure
    - C
    - C++ (pronounced "cee plus plus")
    - Golang
    - Rust (/rʌst/)
    - Lua (pronounced "Loo-uh")
  - Application
    - Java (pronounced "/ˈdʒɑːvə/")
    - C# (pronounced "c sharp")
    - Visual Basic .NET
    - PHP
    - Ruby (/ˈruːbi/)
    - JavaScript
    - Kotlin (/ˈkɒtlɪn/)
    - Objective-C
    - Swift
  - Glue
    - Python (/ˈpaɪθɑːn/)
    - Perl (/pɜː(r)l/)
    - Groovy (/ˈɡruːvi/)
  - Specific Domain
    - SQL (pronounced "S-Q-L" /ˈɛs kjuː ˈɛl/ or "sequel" /ˈsiːkwəl/)
    - Shell (/ʃel/)
    - R

### Java Utility Libraries

- Common Utilities
  - Google Guava
  - Apache Commons
  - Hutool
- JSON
  - GSON
  - Jackson
  - org.json (JSON in Java)
- XML
  - JDK JAXB
- HTTP Client
  - Java Built-in `HttpURLConnection`
  - Java 9 `HttpClient` API
  - Apache HttpComponents `HttpClient`
  - Unirest HTTP API
  - OkHttp
- Email
  - Spring
- Logging
  - Slf4j + Log4j
  - Scribe + Kafka
- Datetime
  - JodaTime
- IO
  - apache commons
  - google guava
  - zip4j
- Schedule
  - Spring
  - quartz
- Work Flow
  - Activiti

### Java Data Access

  - Cache
    - Guava Cache
    - Ehcache
    - Redis
    - Memcached
  - JDBC Database Access
    - JDBC for PostgreSQL, MySQL, SQL Server, Oracle
      - Batch Operations, Transaction Management, Advanced Data Type, Store Procedure
- JDBC Connection Pools
  - Apache Commons DBCP
  - C3P0
  - HikariCP
  - Tomcat JDBC
  - Alibaba Druid
- Java NoSQL Access
  - Redis
    - Lettuce
    - Jedis
    - Redisson
  - MongoDB
    - MongoDB Java Driver
- Java Persistence Framework 
  - Spring JdbcTemplate
  - Spring Data for JPA
  - JOOQ
  - JPA
  - MyBatis
  - Mybatis-Plus
  - Hibernate
  - paoding-rose-jade

### Java Web Development

  - Web Protocols
    - HTTP
    - HTTPS
    - HTTP/2
  - Web Servers
    - Apache HTTP Server
    - Apache Tomcat
    - Nginx (pronounced "engine-x")
    - Caddy
    - WebLogic
    - Jetty
    - Resin web server
    - Microsoft IIS
    - JBoss
- Java Web
  - Java Servlet
  - Web pages / Template Engines
    - JavaServer Pages (JSP), Apache FreeMarker, Thymeleaf
    - Apache Velocity, Groovy Template, JSF, Jade4j
  - Web Frameworks
    - Spring Framework
    - Spring Boot
    - Spring Boot Admin
    - Spring Cloud
  - Security Frameworks
    - Spring Security
    - Apache Shiro
  - API
    - Swagger UI
    - RESTful
    - GraphQL
- Component Libraries
  - Logging
    - Log4j
    - SLF4j
  - Job Scheduling
    - Quartz
    - Spring Scheduling Tasks
  - Workflow Engine
    - Activiti
    - Bonita, jBPM, Workflow Server, Camunda, Copper
  - Web Crawler
    - Jsoup
    - Crawler4j
    - WebMagic
    - Apache Nutch
  - Single Sign-on
    - Spring Boot and OAuth2
    - OAuth
    - OpenSSO

### Third Party Platforms

- WeChat official account
- Payment
  - WeChat Pay
  - Alipay
- Share SDK
  - Open QQ, Weixin, Weibo
  - Facebook, Twitter
- SMS
  - 创蓝, alisms
- Push
  - 个推, 极光, 腾讯推送
- Bot
  - Telegram
  - Slack
- Automation Workflow
  - Zapier

### Data Storage and Search

> Database Index & Cache Cluster & Search Engine

- Relational Databases
  - MySQL (pronounced "My S-Q-L" or "my sequel")
  - MariaDB
  - PostgreSQL
  - SQL Server
  - Oracle
- NoSQL Databases
  - Redis
  - MongoDB
- Graph Databases
  - Neo4j
- Cache
  - Ehcache
  - Guava's Cache
  - Redis
  - Memcached
- Search Engines
  - Apache Lucene
  - Apache Solr
  - Elasticsearch
- Object Storage
  - MinIO
  - SeaweedFS

### Network Programming

  - TCP/IP
  - Network IO (BIO, NIO, AIO) 
  - Socket & SSL
  - Web Socket
  - NIO Frameworks
    - Netty
    - Apache Mina
  - Reactive Frameworks 
    - Eclipse Vert.x
  - RPC Frameworks
    - Web Service
    - Apache Thrift
    - gRPC

### Information Security

Web Security

- HTTPS, SSL
- Authentication and Authorization
  - OAuth2.0
  - JSON Web Token(JWT)
- Encryption
  - Jasypt-spring-boot

### Performance Optimization

Optimization Goals

- High Concurrency
  - Factors
    - Throughput
    - Response Time
    - QPS (Query Per Second)
    - Concurrent Users Number
  - Solutions
    - Scale Up
    - Scale Out
- High Performance
  - Factors
    - Resource Utilization
- High Availability
- High Scalability
- Big Data

Optimization Aspects

- Application Architecture
- Concurrency Performance
- Network and Disk IO Performance
- Data Cache and Storage Performance
- JVM Memory Optimization
- Database and SQL Optimization

### DevOps & SRE

  - Source Control Management
    - GitHub, GitLab
  - Cloud Continuous Integration (CI) Services
    - CircleCI
    - Codeship
    - Travis
    - Wercker
    - GitLab CI
    - GitHub Actions
  - Code Quality Analysis
    - SonarQube
  - CD Tools – Automate the Build
    - Jenkins
    - GitHub Webhooks
    - Script 
      - Bash Shell
      - Python
- Container
  - Docker
  - Kubernates
  - Helm
- Monitor / Issue Tracking
  - Zabbix
  - Prometheus
  - Jira
  - Slack
- Repo Badges
  - Basic
    - Shields.io
  - Continuous Integration
    - Travis
  - Code Quality
    - Codacy Grade
  - Test Coverage
    - Codecov.io
  - Security Vulnerability Detection
    - Snyk.io
  - Team Work Analysis
    - Code Climate

### Test

  - UI Test
    - Selenium
    - Robot Framework
    - Protractor
  - Unit Test
    - JUnit
    - TestNG
    - Spock
- Mock Test
  - Mockito
  - PowerMock
- Service/Integration Test
  - JBehave, FitNesse, SoapUI, JMeter Performance Tests
- Performance Test
  - Jmeter

### Common Tools

  - Version Control
    - Git
    - SVN
  - Editor
    - Vim
    - Nano
    - Atom
    - Visual Studio Code
    - Sublime Text
    - Emacs
    - Notepad++
  - Web Browser DevTools
    - Chrome DevTools
    - Firefox Developer Tools

### Java Tools

- Project Build
  - Maven
  - Maven Wrapper
  - Gradle
- IDE
  - IntelliJ IDEA (pronounced "Intelli(gent) J(ava) idea")
  - Eclipse
- JVM Monitor / Application Performance Monitor
  - Java Mission Control (JMC, included in JDK/bin)
  - JConsole (included in JDK/bin). A tool for GC profiling.
  - VisualVM (included in JDK/bin, the VisualGC is a plugin for VisualVM)
  - Alibaba Arthas (open source by Alibaba)
  - Micrometer
  - Stagemonitor
  - Pinpoint
  - GCHisto. An offline GC analysis tool, but now it's unavailable.
- JVM Command-Line Utility
  - jps (included in JDK/bin, obtain jvm Process ID)
  - jstack (included in JDK/bin, obtain Java and native stack information)
  - jmap (included in JDK/bin, obtain memory map information, including a heap histogram)
  - jcmd (included in JDK/bin, to send diagnostic command requests to the JVM)
  - jstat (included in JDK/bin, obtain information about performance and resource consumption)
- JVM Profiling
  - JProfiler (commercial. features: live profiling, offline profiling, view HPROF snapshot)
  - Eclipse Memory Analyzer (MAT, free, to analyze heap dumps)
- Java Development tools
  - Hot Reload / Restart
    - JRebel
    - Spring Boot DevTools
  - Automate code
    - Lombok
    - MyBatis Generator

### Distributed System

Microservices

- Distributed Collaboration (Centralized Service, Service Registration and Discovery, Service Governance)
  - Spring Cloud
  - Apache Zookeeper (/ˈzuːˌkiːpə(r)/)
  - Apache Dubbo (/ˈdʌbəʊ/)
  - Nagios
  - Zabbix
  - Consul
  - Paxos
  - Raft
  - Apache Curator
- Distributed Messaging (Asynchronous Message Queuing)
  - RabbitMQ 
  - Apache Kafka (/ˈkæfkə/)
  - Apache ActiveMQ
  - Amazon SQS
- RPC
  - gRPC
  - Apache Thrift

Distributed Data Storage and Search

- Database Cluster (Sharding, High Availability, Compatible with MySQL Protocol)
  - Mycat
  - TiDB
  - alibaba/cobar
- Distributed Database
  - Cassandra
  - Consensus
  - Bigtable
  - HBase
- Distributed Cache
  - Memcached
  - Redis
- Distributed Search Engine
  - Elasticsearch
- Distributed File Systems
  - HDFS
  - IPFS
  - FastDFS
- Big Data
  - Apache Hadoop (/həˈduːp/)

Distributed Computing

- MapReduce
- Kafka Streams
- Apache Spark
- Apache Storm
- Apache Samza
- TensorFlow
- Mesos
- Hadoop

Distributed DevOps

- Container
  - Docker (/ˈdɑːkər/)
  - Kubernates (/k(j)uːbəˈnɛtɪs/)
  - Helm
- Load Balancing
  - HAProxy
  - nginx
  - squid 
  - Keepalived

### Architecture & Design Patterns

  - Design Patterns

### Cloud Computing

  - Types of cloud computing
    - Public cloud
    - Private cloud
    - Hybrid cloud
  - Types of cloud services
    - FaaS (Functions as a Service) / Serverless Computing
      - AWS Lambda (Event-driven Serverless Applications)
    - SaaS (Software as a Service)
    - PaaS (Platform as a Service)
    - IaaS (Infrastructure as a Service)
      - OpenStack
      - CloudStack
  - Virtualization
    - KVM/XEN
  - Container

### AI

  - Machine Learning
  - Deep Learning
  - Reinforcement Learning
  - Robotics
  - Computer Vision
  - Natural Language Processing (NLP)
  - Recommender Systems

### Big Data

  - Big Data Engineering
    - Hadoop
    - HDFS
    - Kafka
    - MapReduce
    - Apache Zookeeper
    - Hive
  - Big Data Analytics
    - Apache Storm
    - Apache Spark
    - Apache Kinesis
    - Apache Spark Streaming

### Game Development

### IoT




### References

[1] [A Thorough Introduction to Distributed Systems](https://www.freecodecamp.org/news/a-thorough-introduction-to-distributed-systems-3b91562c9b3c/)

[2] [What is cloud computing? A beginner’s guide](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/)

[3] [Big Data Learning Path for all Engineers and Data Scientists out there](https://www.analyticsvidhya.com/blog/2017/03/big-data-learning-path-for-all-engineers-and-data-scientists-out-there/)

[4] [repo-badges - GitHub](https://github.com/dwyl/repo-badges)

[5] [Hot topics in AI research - Medium](https://towardsdatascience.com/hot-topics-in-ai-research-4367bdd93564)

[6] [Artificial Intelligence - Research Areas - Tutorialspoint](https://www.tutorialspoint.com/artificial_intelligence/artificial_intelligence_research_areas.htm)

--END--


