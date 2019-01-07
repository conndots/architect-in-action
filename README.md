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
3. AQS
4. ReentrantLock
5. CyclincBarrier & CountDownLatch
6. JVM
   1. 内存模型
   2. 重排序
   3. Happens-before
7. Actor模型
8. Go的goroutine调度器实现

