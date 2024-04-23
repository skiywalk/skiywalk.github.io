---
title: csapp_lab
date: 2024-04-17T21:12:22+08:00
lastmod: 2024-04-17T21:12:22+08:00
author:
  - zinonye
keywords: 
categories: 
tags: 
description: 
weight: 
slug: ""
draft: false
comments: true
mermaid: true
showToc: true
TocOpen: true
disableShare: true
showbreadcrumbs: true
---
**本书价值等重的黄金**
 csapp不愧是最好的入门书（有基础之后），以程序员的视角自底向上全面地剖析计算机系统，难得在于全面的同时还具有一定的深度（这也是为什么难学），然而，学好它也仅仅是打一个好底子、以支撑入门后的进一步学习
## 简短总结：
三部分
### 1.机器码到cpu 
	1. 数据的表示和运算
	2. 汇编与编译：最难，也是精华所在，将高级语言与汇编对应
	3. cpu architecture：本书最"浅"的一章，pipeline 分支预测 ，--->《计算机组成原理：软硬件接口》《计算机体系结构：量化方法》
	4. 优化程序性能：对前面的小结，顺带一点剖析性能的方法
	5. memory hierarchy：locality and cache，存储器山
### 2.在系统上运行
	1. linker：很好，但是太浅--->《程序员的自我修养：链接装载与库》《Linkers&Loders》
	2. 异常控制流ECF：很好--->《APUE》？
	3. virtual memory：很好，实现方式（page TLB...）和dynamic malloc--->系统方面
### 3.程序间的交互和通信
	1. 系统级I/O：过于浅，基本是上一章的延续（按照专门讲系统的书来说）--->《APUE》
	2. 网络编程：浅，一点socket知识--->《计算机网络》《UNP》
	3. 并发编程（concurrency）：仍然浅，但这个主题很重要--->既出现在系统层面（cpu）也出现在数据库（io多路复用）

---

## lab
总共存在11个lab（因为历史版本原因，有一些被替换），3ed主要写了9个
1. Data_Lab**
2. Bomb_Lab***
3. Attack_Lab***
4. Cpu_Lab*
5. 性能_Lab*
6. Cache_Lab*
7. Shell_Lab*
8. Malloc_Lab***
9. Proxy_Lab*









