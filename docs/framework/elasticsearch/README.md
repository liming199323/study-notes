# Elasticsearch查询引擎学习
## · 基础介绍
### ES简介
Elasticsearch 是一个分布式的开源搜索和分析引擎，适用于所有类型的数据，包括文本、数字、地理空间、结构化和非结构化数据。  
Elasticsearch 在 Apache Lucene 的基础上开发而成，Elasticsearch 以其简单的 REST 风格 API、分布式特性、速度和可扩展性而闻名，是 Elastic Stack 的核心组件。  
Elastic Stack 是适用于数据采集、充实、存储、分析和可视化的一组开源工具。人们通常将 Elastic Stack 称为 ELK Stack（代指 Elasticsearch、Logstash 和 Kibana）。  
目前 Elastic Stack 包括一系列丰富的轻量型数据采集代理，这些代理统称为 Beats，可用来向 Elasticsearch 发送数据。
### ES优点
>(1) Elasticsearch是一个近实时的搜索平台，查询速度非常快，由于 Elasticsearch 是在 Lucene 基础上构建而成的，所以在全文本搜索方面表现十分出色。  
>(2) Elasticsearch具有很好的横向扩展性，可以轻松的添加节点到集群，处理PB量级的数据；也可以部署集群在单机上，处理一些轻量级的数据。  
>(3) Elasticsearch具有分布式的本质特征，文档数据分布在集群中的不同容器中(即分片shard)，还具有replica机制，为一个shard设置多个副本，某台节点宕机之后，任然可以正常查询  
>(4) Elasticsearch的功能非常的广泛，全文检索、同义词处理、相关度排名、数据汇总和索引生命周期管理等，可以方便用户更加高效地存储和搜索数据。  
>(5) Elasticsearch使用非常方便，无论是集群的搭建部署或者是在查询交互方面上手都非常的容易，同时支持多种编程语言的开发，支持34中文本语言。
## · 集群成员分析
## · 常见用词介绍
## · 底层机制分析
