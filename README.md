# MIT 6.824 Study Notes

MIT 6.824: Distributed Systems in Spring 2023 的课程笔记、论文总结、实验代码及实现思路。

目录：

- [MIT 6.824 Study Notes](#mit-6824-study-notes)
  - [学习资料](#学习资料)
  - [课程笔记](#课程笔记)
  - [论文总结](#论文总结)
  - [实验思路](#实验思路)

## 学习资料

课程主页：[6.824 Home Page](https://pdos.csail.mit.edu/6.824/)

视频资料：

* [YouTube - 英文原版](https://www.youtube.com/channel/UC_7WrbZTCODu1o_kfUMq88g/videos)
* [B站 - 中文字幕]((https://www.bilibili.com/video/BV1R7411t71W))

课程讲义：

* [MIT 6.824 - 中文翻译](https://mit-public-courses-cn-translatio.gitbook.io/mit6-824/)

杂项:
* [设计数据密集型应用 - 中文翻译](https://github.com/Vonng/ddia)
* [etcd](https://github.com/etcd-io/etcd)

## 实验准备
* Lab1：[Lecture 6: Lab 1 Q&A](https://link.zhihu.com/?target=https%3A//www.youtube.com/watch%3Fv%3DQkPiiRQmom8)，[Lecture 10: Guest Lecture on Go: Russ Cox](https://link.zhihu.com/?target=https%3A//www.youtube.com/watch%3Fv%3DIdCbMO0Ey9I)
* Lab2：[Raft Locking Advice](https://link.zhihu.com/?target=https%3A//pdos.csail.mit.edu/6.824/labs/raft-locking.txt)，[Raft Structure Advice](https://link.zhihu.com/?target=https%3A//pdos.csail.mit.edu/6.824/labs/raft-structure.txt)，[Students' Guide to Raft](https://link.zhihu.com/?target=https%3A//thesquareplanet.com/blog/students-guide-to-raft/)，[Lecture 8:Lab 2A/2B Q&A](https://link.zhihu.com/?target=https%3A//www.youtube.com/watch%3Fv%3DVIZCheV4dWY)，[SOFAJRaft 日志复制 - pipeline 实现剖析 | SOFAJRaft 实现原理](https://link.zhihu.com/?target=https%3A//mp.weixin.qq.com/s/jzqhLptmgcNix6xYWYL01Q)，[TiKV 功能介绍 - Raft 的优化](https://link.zhihu.com/?target=https%3A//pingcap.com/blog-cn/optimizing-raft-in-tikv/)，[Raft 算法介绍](https://link.zhihu.com/?target=https%3A//tanxinyu.work/raft/)，[Raft 博士论文的翻译](https://link.zhihu.com/?target=https%3A//github.com/LebronAl/raft-thesis-zh_cn)
* Lab3：[Raft 博士论文的翻译](https://link.zhihu.com/?target=https%3A//github.com/LebronAl/raft-thesis-zh_cn)，[Raft 如何实现线性化语义](https://www.zhihu.com/question/278551592)，[一致性模型与共识算法](https://link.zhihu.com/?target=https%3A//tanxinyu.work/consistency-and-consensus/%23etcd-%25E7%259A%2584-Raft)，[SOFAJRaft 线性一致读实现剖析 | SOFAJRaft 实现原理](https://link.zhihu.com/?target=https%3A//www.sofastack.tech/blog/sofa-jraft-linear-consistent-read-implementation/)
* Lab4：[6.824 Lab 4: Sharded Key/Value Service Hint](https://link.zhihu.com/?target=https%3A//pdos.csail.mit.edu/6.824/labs/lab-shard.html)，[MIT 6.824 LAB 4B(分布式shard database)](https://link.zhihu.com/?target=https%3A//www.jianshu.com/p/f5c8ab9cd577)


  

## 课程笔记

* Lecture 1: Introduction
* Lecture 2: RPC and Threads
* Lecture 3: GFS
* Lecture 4: Primary-Backup Replication
* Lecture 5 - Go, Threads, and Raft（TODO）
* Lecture 6 & 7 -  Fault Tolerance Raft（TODO）

## 论文总结

* MapReduce 论文阅读
* gfs 论文阅读
* vm-ft 论文阅读
* Raft 论文阅读

TODO

## 实验思路

* Lab 1: MapReduce
* Lab 2: Raft
* Lab 3: KV Raft
* Lab 4: Sharded KV
