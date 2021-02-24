# MIT-6.8.24-Distributed-Systems-Spring-2021

## 课前阅读

[Mikito Takada](https://github.com/mixu/) 大佬提供了这篇写于2013年的文章：[Distributed systems, for fun and profit ](http://book.mixu.net/distsys/) [[本地连接](./readings/Distributed System -- for fun and profit.md)]。算是科普一下分布式系统领域的一些基础知识和基本理念。

通过这篇文章对分布式系统有了大致的轮廓之后，就可以开始刷Paper和Lab了。Schedule为我们规划了一个合适的路线来打怪升级，当周Lab的内容与布置的Paper或多或少都有联系，比如MapReduce，Fault-Tolerant，Paxos等，还有一些Paper是与当前流行的技术有关的话题，如Spark，Bitcoin。时间充裕的话静下心来花一整块时间读完一篇还是很有收获的，不懂的地方多用Google。最好是先对Paper所讨论的话题有一个大概的了解，可以通过维基百科等网站，比如Paxos，如果你不理解什么是一致性，容错，是没法读下去的。

整个课程一共有5个Lab，MapReduce，Primary/Backup，Paxos，Shards，Persistence。每个Lab都有若干个Part，每个Part都会有一个大致的代码框架和完整的测试代码，可以从网站上给的git地址下载下来。一定要仔细阅读每个Part具体要做什么，然后到相应的代码位置补充相关的实现。在代码中需要我们添加代码的位置都有注释提示，不能添加代码的位置也有相应的注释，最好按照人家的要求做。在添加代码的同时也不要忘了阅读题目下面的一系列Hint，那些都是容易踩到的坑以及给你的一些提示。在理解了题目意思之后建议先看一下测试代码(test_test.go)，了解每个方法的输入输出是什么，根据测试驱动开发。

以后想详细地一个一个地总结一下这些Lab，当作温故而知新。我现在的进度是Lab基本上已经完成，Paper就读了跟Lab内容相关的几篇，没办法整块的时间太少了，而读Paper又想一口气读完一篇不想思路断掉。接下来还是想在业余时间把课程推荐的Paper尽量读完。

## 课程安排 Schedule

[课程安排](https://pdos.csail.mit.edu/6.824/schedule.html)

<iframe  
 height=850 
 width=90% 
 src="https://pdos.csail.mit.edu/6.824/schedule.html"  
 frameborder=0  
 allowfullscreen>
 </iframe>

## 视频 Videos

[2020年lectures视频地址](https://www.bilibili.com/video/av87684880)

<iframe src="//player.bilibili.com/player.html?aid=87684880&bvid=BV1R7411t71W&cid=155854088&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

## 讲座 Lectures

- [Lec1: 入门介绍(以MapReduce为例)](https://github.com/chaozh/MIT-6.824/issues/2)
- [Lec2: RPC与线程机制(Go语言实战)](https://github.com/chaozh/MIT-6.824/issues/3)
- [Lec3: GFS](https://github.com/chaozh/MIT-6.824/issues/6)
- [Lec4：主从备份](https://github.com/chaozh/MIT-6.824/issues/7)
- [Lec 5：Raft基本](https://github.com/chaozh/MIT-6.824/issues/9)
- [Lec6：Raft实现](https://github.com/chaozh/MIT-6.824/issues/10)

## 学完这门课后必须了解的概念

1. MapReduce
2. RPC
3. Goroutine
4. Primary/Backup
5. Paxos
6. Raft
7. Spark
8. Shard
9. Scalability
10. Performance
11. Availability
12. Partition and Replicate
13. CAP and FLP
14. Consistency
15. Fault tolerance
16. 2PC and 3PC
17. Byzantine fault tolerance
18. GFS
19. Big Table
20. Time and order and clocks

## 参考链接

- [MIT 6.824 课程的学习资料](https://github.com/chaozh/MIT-6.824)
- [MIT-6.824学习之路](http://ts25504.github.io/2016/08/16/MIT-6-824%E5%AD%A6%E4%B9%A0%E4%B9%8B%E8%B7%AF/)