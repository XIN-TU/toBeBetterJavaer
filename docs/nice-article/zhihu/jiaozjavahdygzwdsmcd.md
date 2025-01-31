---
title: 校招Java后端应该掌握到什么程度？
shortTitle: 校招Java后端应该掌握到什么程度
description: 参加了21届的春招和秋招，拿到过阿里、腾讯、字节等大厂的offer，目前刚刚入职阿里淘系技术（Java后端开…
tags:
  - 程序员
  - 后端技术
  - Java
  - 校园招聘
  - 后端工程师
author: 阿里巴巴大淘宝技术 
category:
  - 知乎
head:
  - - meta
    - name: description
      content: 参加了21届的春招和秋招，拿到过阿里、腾讯、字节等大厂的offer，目前刚刚入职阿里淘系技术（Java后端开…
  - - meta
    - name: keywords
      content: 程序员,后端技术,Java,校园招聘,后端工程师
---

下面简单分享我认为的**Java 校招生应该具备的专业能力和知识水平**，并附上个人总结的**Java 岗知识点不完全整理以及推荐学习书籍**，供大家参考。

## 说点虚的

**印象最深刻的三场面试：**

**一场是某大厂的非 Java 的后端开发岗**

（我当时的简历几乎全是 Java 相关。）

面试官上来就问：你认为你对哪方面技术或知识最熟悉，我们就聊聊你最熟悉的。

（当时就觉得面试官太有水平了:D）

**另一场是某个自动驾驶创业公司**

（面试之前就了解到该公司对于算法水平要求极高，而我的算法水平也仅限于力扣。）

面试过程中问了一道闻所未闻的 acm 算法题，拿到题目以后毫无思路，于是全程在面试官的引导下一步步解题。

后来收到 offer 之后才意识到，面试官出题时就没指望面试者能当场解答出来，而是想考察其学习和理解、思考和解决问题的能力。

**最深刻的还属淘系的面试**

比起面试感觉更像是和大牛进行了一场交流；

比起单方向的提问，面试官更注重双向交流，短短一个多小时却收获颇丰；

（论大佬的向下兼容性:D）

**我认为这几场面试反映出了面试官或公司对校招同学的一些期望和要求：**

1.  **技术和知识深度：**重点不是写过多少语言，用过多少框架，而是对于接触过的项目，学习过的技术和知识，我们能够达到什么深度。
2.  **主动思考和学习：**在面试中，面试官经常对求职者简历中提到的项目或者相关技术进行提问，也是希望考察求职者在实际学习和工作过程中**发现、思考和解决问题的能力**。都说在日常工作中，程序员们最擅长的事情便是“面向搜索引擎编程”，但在我看来，搜索到答案只是第一步，bug 出现的原因、代码为什么不 work、又为什么最终能 work 更是我们应该深究的问题。

来点实在的
---

根据自己的面试经历梳理了一些 Java 岗的知识点，供大家参考。


### Java 基础

基础语法、面向对象、常用类、继承和多态等基础知识不必多说，可以看《Java 程序员进阶之路》。

**书籍推荐：**《On Java 8》

**强烈推荐大家学习 Java 的过程中多学习和参考 JDK 源码，领会其中精妙的编程思想，JDK 源码和 Java doc 才是最权威的 Java 学习资料。**

### 多线程

很多同学在学校接触到的并发场景可能比较少，所以要更加重视。

**重点知识：**线程池、volatile 和 synchronized 关键字、各种锁机制、中断、CAS、JUC 并发包（如：ReentrantLock 和 AQS）等

**推荐书籍：**《Java 并发编程的艺术》、《Java 程序员进阶之路》并发编程部分。

### JVM

**重点知识：**垃圾回收机制、Java 内存结构、类加载机制、Java 内存模型、JVM 性能调优等

**书籍推荐：**强推《深入理解 Java 虚拟机》

（能把这么枯燥的底层知识写的这么清晰有趣，膜拜大佬）

### Spring

**强烈推荐阅读 Spring 源码**，如果觉得枯燥可以跟着视频学习。如果时间不足，至少阅读一下 Spring 容器启动和 bean 的实例化、循环依赖等模块的源码，做到真正理解 Spring 框架的思想，也培养自己阅读源码的能力。

**重点知识：**Spring Bean 的实例化和循环依赖、IOC 思想、AOP 和动态代理、常用注解等

**书籍推荐：**《Spring 技术内幕》

### 数据库

首先系统学习数据库，了解常见的关系型和非关系性数据库，掌握 SQL 语句，重点学习 MySQL。

**重点知识：**数据结构和索引、锁、事物、日志系统、InnoDB 特性等

**书籍推荐：**《数据库系统概念》、《MySQL 必知必会》

### 计算机网络

**重点知识：**HTTP、TCP、IP 等相关知识点

**书籍推荐：**《计算机网络-自顶向下方法》、《图解 HTTP》、《图解 TCP/IP》

### 网络编程

**重点知识：**同步/异步/阻塞/非阻塞/BIO/NIO/AIO、零拷贝、Netty 等

**书籍推荐：**《Netty 权威指南》、《NIO 与 Socket 编程技术指南》

### 操作系统

**重点知识：**进程和线程、进程通信、进程调度、内存管理等；熟练掌握 Linux 命令

**书籍推荐：**《深入理解计算机系统》、《现代操作系统》

### 分布式和微服务

系统学习分布式系统的原理和基本理论，了解 RPC、消息中间件、分布式缓存、注册中心、分布式事物、分布式一致性算法、分布式锁等

**重点知识：**Redis 及分布式缓存设计、RPC 及 Dubbo 框架、消息队列及 RocketMQ、Paxos、Raft 等分布式一致性算法等

### 数据结构与算法

建议看算法书和刷 leetcode 题并行，注重分类总结。

**重点知识：**常见数据结构（二叉树、栈和队列、链表等）、排序算法、动态规划、广度及深度优先遍历、回溯等

**书籍推荐：**《剑指 offer》（比较基础）➕《程序员代码面试指南：IT 名企算法与数据结构题目最优解》（牛客上有相应题库）

### 其他

1.  Git、Maven/Gradle 等原理和命令的使用、Docker
2.  场景题：（所谓面试造火箭）比如如何设计一个秒杀系统，设计一个消息中间件有哪些重点等，主要考察对系统的宏观理解、对基础知识和项目经验的综合运用。

### 欢迎加入

一个人可以走得很快，但一群人才能走得更远。欢迎加入[二哥的编程星球](https://mp.weixin.qq.com/s/3RVsFZ17F0JzoHCLKbQgGw)，里面的每个球友都非常的友善，除了鼓励你，还会给你提出合理的建议。星球提供的三份专属专栏《Java 面试指南》、《编程喵🐱（Spring Boot+Vue 前后端分离）实战项目笔记》、《Java 版 LeetCode 刷题笔记》，干货满满，价值连城。


![星球专属专栏《Java 面试指南》，干货满满⛽️](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/zhihu-jiaozjavahdygzwdsmcd-11e9c11a-60eb-4e91-8a09-6f0361956a8d.png)



[二哥的编程星球](https://mp.weixin.qq.com/s/3RVsFZ17F0JzoHCLKbQgGw)（戳链接加入）已经有 **370 多名** 小伙伴加入了，如果你也需要一个良好的学习氛围，戳链接加入我们的大家庭吧！这是一个 Java 学习指南 + 编程实战的私密圈子，你可以向二哥提问、帮你制定学习计划、跟着二哥一起做实战项目，冲冲冲。




![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/zhihu-jiaozjavahdygzwdsmcd-8b3bbad1-e18b-453e-a807-9ba07f960b91.png)


---

*没有什么使我停留——除了目的，纵然岸旁有玫瑰、有绿荫、有宁静的港湾，我是不系之舟*。




**推荐阅读**：

- [计划国庆前跳槽](https://mp.weixin.qq.com/s/1_9FVEhEErMhjCRNP9dqZw)
- [去外包，我也挺知足](https://mp.weixin.qq.com/s/1WdD2eLVMT-efMukLrtAwg)
- [我的第一次，4万！](https://mp.weixin.qq.com/s/2wW4ZZWMYXuyY2-tLGvIwQ)
- [入职新公司半个月了](https://mp.weixin.qq.com/s/16AvpvTZ4NOyfFvU57ok9Q)


![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/weixin-rumrabbitmqzypjdg-53717e59-63c9-44bd-99d3-dd2c26fe68bb.png)

> 转载链接：[https://www.zhihu.com/question/403508943/answer/2036074069](https://www.zhihu.com/question/403508943/answer/2036074069)，整理：沉默王二
