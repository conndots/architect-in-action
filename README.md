# 架构师之路

# 目的

梳理清楚成为一个架构师的技能树可能有哪些，自己在什么位置。给自己未来3~5年制定一个目标。



# 优秀的高级工程师之路

## 基础知识

### 数据结构与算法

1. 数组
   1. 并发安全
      1. CopyOnWriteArrayList
2. 哈希表
   1. Golang map实现
      1. 可能存在的内存泄漏问题 
   2. 并发安全的哈希表
      1. Golang sync.Map的实现
      2. Java 8 ConcurrentHashMap的实现
3. 队列
   1. 并发安全的Queue实现
      1. LinkedBlockingQueue实现
      2. ConcurrentLinkedQueue实现non-blocking队列
      3. 【深入】Disruptor源码解析
4. 树
   1. 平衡二叉树
   2. 红黑树
   3. B树，B+树
   4. Log-Structured Merge Tree
      1. https://github.com/dgraph-io/badger 源码解析
      2. RocksDB架构与设计
5. 布隆过滤器
6. 字符串算法
   1. KMP
7. 图
   1. 最短路径
   2. 拓扑排序
   3. 便利算法
   4. 最小生成树 Kruskal和Prim
8. 贪心算法
9. 动态规划

### 并发

1. 乐观锁，悲观锁
2. CAS
3. [Java] AQS
4. [Java] ReentrantLock
5. CyclincBarrier & CountDownLatch
6. JVM
   1. 内存模型
   2. 重排序
   3. Happens-before
7. Go的goroutine调度器实现
8. 事务
   1. ACID
   2. 事务的隔离级别
   3. MVCC
   4. *Design Data-Intensive Applications* - Transactions chapter
9. 一致性
  1. 两阶段提交
  2. Paxos
  3. Raft
  4. Zookeeper架构与实现
  5. etcd架构与实现
10. 并发队列实现
  1. 锁实现
  2. CAS实现
  3. Disruptor实现


### 中间件

1. Web Server
   1. Nginx
   2. Traefik
2. MQ
   1. RocketMQ
   2. Kafka
   3. Nsq
3. RPC
   1. gRPC
   2. Thrift
4. 缓存
   1. Redis
   2. 缓存失效算法
   3. Tair

### Cloud Native

1. Docker
2. Kubernetes
3. Service Mesh
   1. lstio

### 网络

1. TCP协议
2. HTTP & HTTP 2.0
3. HTTPS
4. WebSocket
5. 网络模型
   1. Reactor [Paper](https://arxiv.org/pdf/1704.04651.pdf)
   2. Proactor [Paper](http://www.laputan.org/pub/sag/proactor.pdf)
   3. select/poll/epoll
   4. Java NIO
6. Netty剖析

### 数据库

1. Mysql
   1. innodb
   2. 优化
2. Redis
   1. Redis数据结构
      1. List
      2. Set
      3. ZSet
      4. Hash
   2. Codis
3. 存储索引算法
   1. Log Structured Merge Tree
      1. Paper: [The Log-Structured Merge Tree](https://www.cs.umb.edu/~poneil/lsmtree.pdf)
      2. [dgraph-io/badger](https://github.com/dgraph-io/badger)
   2. B Tree
      1. [etcd-io/bbolt](https://github.com/etcd-io/bbolt)

### 大数据

