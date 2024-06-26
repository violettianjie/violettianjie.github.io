---
layout: post
title: "如何逃离大数据的黑洞？"
description: "从大数据到云计算"
category: blog
---

## 如何逃离大数据的黑洞？

生也有涯，知也无涯。宇宙中的黑洞（Black Hole）是一个1969年才被美国科学家约翰·惠勒(John Archibald Wheele)提出的概念，它是时空的一个区域，因为那里的引力是如此之强，以至于任何东西，甚至光都不能从该处逃逸出来。
今天的“大数据” （Big Data) 是否也是这样一个黑洞呢？


### 一 大数据：由来、定义与特点
1980年，未来学家、社会思想家托夫勒Alvin Toffler (1928 – 2016) 在其所著的《第三次浪潮》（The third wave）中将“大数据”称颂为 “第三次浪潮的华彩乐章”。
2008年9月，《自然》杂志在推出了名为“大数据”的封面专栏。
2009年开始，“大数据”才成为互联网技术行业中的热门词汇。

全球最早应用“大数据”的是管理咨询公司麦肯锡公司(McKinsey)。麦肯锡公司看到了各种网络平台记录的个人海量信息具备潜在的商业价值，提出对“大数据”进行收集和分析的设想，投入大量人力物力进行调研，在2011年6月发布了关于“大数据”的报告《Big data: The next frontier for innovation, competition, and productivity》，该报告对“大数据”的影响、关键技术和应用领域等进行了详尽分析。
从百度搜索引擎数据看，国内“大数据”这个词从2012年才引起国人关注，之后搜索量迅猛增长。
维基百科对“大数据”的解读是：
「大数据”(Big data)，或称巨量数据、海量数据、大资料，指的是所涉及的数据量规模巨大到无法通过人工，在合理时间内达到截取、管理、处理、并整理成为人类所能解读的信息。」
近年来，全球数据量猛增，2015年已达到7500EB（1EB=1028PB）。IDC预计，未来全球数据总量年增长率将维持在50%左右。
当前会涉及到大数据的数据量为 几十TB(万亿字节) 和 几个PB(千万亿字节)。
维克托·迈尔-舍恩伯格和肯尼斯·克耶编写的《大数据时代》中提出
“大数据”的4V特点：Volume(数据量大)、Velocity(输入和处理速度快)、Variety(数据多样性)、Value(价值密度低)。
现有的 Hadoop （由Apache基金会所开发的开源的分布式系统基础架构）大数据技术的基础 为谷歌的三篇技术论文：

2003年发表的《The Google File System》

2004年发表的《MapReduce: Simplified Data Processing on Large Clusters 》

2006年发表的《Bigtable: A Distributed Storage System for Structured Data》

### 二 云计算起源、定义

2006年，27岁的Google高级工程师比西莉亚Christophe Bisciglia第一次向Google CEO 埃里克·斯密特（Eric E. Schmidt）提出“云计算”的思想。Google公司出资在华盛顿大学搭建一个类似于Google搜索的分布式计算系统，由比西莉亚向华盛顿大学的师生们讲授Google的核心技术：GFS分布式文件系统和MapReduce分布式编程框架。
斯密特先生采纳了比西莉亚的建议，向华盛顿大学捐赠了40台服务器，比西莉亚定期到华盛顿大学进行授课。
2006年8月，埃里克·斯密特在搜索引擎大会上首次提出“云计算”的概念。
2007年，Amazon推出名为“弹性计算云”的收费服务，供中小软件企业按照需求购买，成为业界第一个提供商业云服务的公司。
维基百科中对于云计算的定义：云计算是一种通过Internet以服务的方式提供动态可伸缩的虚拟化的资源的计算模式。

### 三 云计算与“大数据”

将各种“大数据”的应用比作一辆辆“汽车”，支撑起这些“汽车”运行的“高速公路”就是云计算。最著名的实例就是Google搜索引擎。面对海量Web数据，Google于2006年首先提出“云计算”的概念。支撑Google内部各种“大数据”应用的，正是Google公司自行研发的云计算服务器。有了云计算服务器才有了“大数据”应用的价值。

G=f（x） G 目标，f云计算，x大数据。

云计算带来的转变：
1、用户消费模式的转变：云计算通过互联网提供软硬件与服务，并由网络浏览器或轻量级终端软件来获取和使用服务。
2、商业模式的转变：消费者和企业将从“购买软硬件产品”向“购买信息服务”转变，如同100年前“电”的演变，农场和公司逐渐关闭了自己的发电机，从发电厂购买电力。

### 四 云计算的发展路径和落地思路

第一条路：基于大规模搜索数据处理。

源自于谷歌对大规模数据的处理，谷歌为全球的互联网用户提供同一个服务——搜索，它需要将全世界所有的网站的数据都爬回去，然后做排序和索引，再为用户提供搜索服务。这样的工作需要对海量数据进行处理，谷歌需要把上百万台的服务器整合起来去做排序、索引和查询。

第二条路：基于超大规模在线交易。

淘宝则发展出来云计算的第二条路径，与谷歌有类似之处，同样需要把很多数据整合起来做一件事情。淘宝做的事情是交易。承载6亿用户在线访问和下单支付。因为有极其严格的业务要求，虽然在规模上淘宝用不了像谷歌那样多达百万台的机器，但也是把众多廉价服务器整合起来去做一件事情，聚沙成塔。

第三条路：赋闲服务器资源化、虚拟化。

源于过去十几年间企业内部在硬件方面进行的大量投资，造成大量赋闲服务器资源。对于企业内部的使场景而言，往往仅有几千或者几万个用户，即便是大型的国有企业拥有有上百万用户，也仅此而已。和动辄上千万、上亿的互联网用户相比，企业投入大量的IT资源特别是硬件资源的情况下，服务的客户数过少，造成服务器资源的赋闲。面对由此造成的资源利用率低的情况，带来的挑战就是如何更多更好地去利用这些赋闲资源。
虚拟化技术，最早IBM在小型机上或者大型机上实现，通过虚拟化或者分区技术，解决资源利用率低的问题。虚拟化的技术后来被VMWare发扬光大，在X86的平台上进行了广泛传播应用。
云计算经过发展最终沉淀下来的这些技术，既需要有效利用资源，将规模从小变大；也需要面向客户和业务做在线并且有业务质量保证的交易，同时也需要对数据进行大规模处理，进而产生对数据的洞察来支持业务的智能化。
能够把云计算的三个方向整合到一起的一个方向是大数据的处理。

2007年，阿里明确了未来10年的发展战略：以数据为中心，建设一个生态系统，需要把旗下所有业务的数据打通，是为“奔月计划”。

2009年，阿里云还是亚洲最大的Oracle集群，但已经无法承载飞速发展的业务于是选择了3条分支路径去探索。

第一条路径：用商业的Greenplum（一个大数据分析公司，2010年被EMC 收购）来替代分析型数据运算；

第二条路径：使用Hadoop做类似事情；

第三条路径：启动了飞天操作系统的研发，目标是打造一个属于自己的大数据平台。

2010年，Greenplum 这条路因规模和可用性的问题以及计算准确性问题被放弃；
2013年，Hadoop 平台因数据中心规模扩展不上去和安全管理以及权限管理和资源管理等一系列问题，被放弃。最后打造了飞天操作系统。
2015年，飞天上线。
2018年Q3 阿里的云计算业务亏损2.3亿，过去12个季度云计算业务总亏损24.9亿。

从云计算回到大数据，Hadoop 大数据技术基础源于十几年前三篇谷歌人的论文。十余年来给无数人就业机会、无数公司创业的由头，估计还会延续很多年。而据称 Google 几年前已经又发表了新论文，新技术替换了之前 MapReduce、HFS、BigTable 三篇论文里的技术。

白云在天，数路漫漫。如果说大数据是宇宙中的一个黑洞，云计算会是黑洞蒸发的方法吗？





参考文章：  [阿里云的发展](http://www.techweb.com.cn/news/2016-06-08/2344624.shtml)
