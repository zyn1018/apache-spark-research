# Apache Spark研究报告
 ## 1. Spark简介 #

 ## 2. Apache Spark目前发展应用情况 #

  ## 3. Spark体系结构
  ## 4. Spark相关概念 #
  
  ## 5. Spark核⼼ — 弹性分布式数据集(RDD) #

  ### 5.1. RDD是什么 #
  ### 5.2. 窄依赖与宽依赖 #
  ### 5.3. RDD支持的操作 #
  ### 5.4. RDD对容错的支持 #
  
  ## 6. Spark运⾏原理 #

  ### 6.1. Spark分布式部署 #
  ### 6.2. Spark内部执⾏流程 #
  ### 6.3. Job、Stage、Task的关系 #
  ### 6.4. DAG Scheduler的⼯作流程 #
  ### 6.5. TASK Scheduler的⼯作流程 #
  
  ## 7. Spark SQL #

  ### 7.1. Spark SQL核⼼数据结构—Dataframe #
  ### 7.2. Spark SQL 语句执⾏的查询优化框架—Catalyst #
  
  ## 8. Spark Streaming #

  ### 8.1. DStream #
  ### 8.2. Spark Streaming工作原理 #
  
  ## 9. Spark MLlib
  ## 10. Spark GraphX
  ### 10.1. GraphFrames
  
  ## 11. 总结

  # Apache Spark细节与优化
  ## 1. SparkContext加载 #

  ## 2. RDD分区 #

  ## 3. 累加器与广播变量 #
  ### 3.1. 累加器 #
  ### 3.2. 广播变量 #
  ## 4. Spark运行时架构 #
  ### 4.1. 驱动器节点 #
  ### 4.2. 执行器节点 #
  ### 4.3. 集群上运行Spark应用的过程 #

  ## 5. Spark性能优化 #

  ### 5.1. 避免创建重复的RDD #
  ### 5.2. 尽可能重用同一个RDD #
  ### 5.3. 对多次使用的RDD进行持久化 #
  ### 5.4. 尽量避免使用shuffle类算子 #
  ### 5.5. 使用map-side预聚合的shuffle操作 #
  ### 5.6. 使用广播变量 #
  ### 5.7. 使用Kryo优化序列化性能 #
  ### 5.8. 资源调优 #
  #### 5.8.1. Spark作业基本运⾏原理
  #### 5.8.2. 资源参数调优

