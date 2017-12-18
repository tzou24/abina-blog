---
published: true
author: Robin Wen
layout: post
title: "DBA杂谈"
category: Other
summary: "DBA不应该把思维限制在什么数据库上，不论什么数据库，原理性的东西还是相通的，也不要因为别人运维Oracle，你运维SQLServer，就会感觉差很多档次。每个数据库的存在肯定有其合理性，没被市场淘汰说明它在某方面还是很有价值的。世界上没有完美的东西，数据库也是一样。应该根据具体需求选择你需要使用的数据库，至于你在运维什么数据库，很多时候真得没有那么重要。"
tags: 
- Other
- DBA
- 杂谈
- Tittle-tattle
---

`文/温国兵`

人们一提起DBA，第一反应是这个职位多么的高端，殊不知DBA并不是你想象的那样。

一个人会搭建DG，会RMAN，会搭建RAC集群，会GoldenGate，另一个人只会写SQL，只会优化SQL，你觉得这两个人谁的发展空间更大？这个问题想必是仁者见仁智者见智。DG、RMAN、RAC、GoldenGate等等是Oracle相对高级的技术，而SQL确是几乎所有的程序员、运维工程师都会的。无论技术多么高端，长时间的积累基本上停留在会用，甚至熟练的地步，如果你不去研究原理性的东西，最多可以成为高级DBA，离数据库架构师还差十万八千里。是的，一个DG搭建，一个RAC集群，最多只是步骤多些，搭建难度稍微大些，却没有多大技术含量，而一个看似简单的SQL优化仍然可以大有作为。你想想别人写个SQL跑两个小时，你优化下20多分钟就跑完，这个差距还是相当大的。SQL优化不仅体现你对SQL的掌握熟练程度，更体现你对SQL语句的深层次理解。我始终相信你要在某个方面达到出神入化，你必定知道为什么。可以这样说，所有操作性的东西技术价值都不太大，价值大的是你知道为什么这样做。所以，以后你认识的在写报表，在写PL/SQL，不要鄙视，或许某一天他达到的高度你望尘莫及。

![Zatan on dba](http://i.imgur.com/9n525Jw.jpg)

整个运维的特点就是杂。一个运维工程师或者DBA掌握的知识太多了，而一个运维人员的价值恰恰体现在博上。从操作系统、网络、存储、数据库，甚至上层的运用或者硬件，你都要有足够多的了解。平时运维的工作稍显清闲，可以好好利用这些时间拓宽你的知识面，养兵千日用兵一时，你不知道你闲暇的一次TroubleShooting就会在以后派上用场。遇到的很多问题都可以根据现有的思路解决，而那些对数据库性能进行调整的却不是这样，你需要深入理解Oracle体系结构和操作系统，才能在经验的积累上快速高效地做出决策。

这里再说下DBA和数据库。DBA不应该把思维限制在什么数据库上，不论什么数据库，原理性的东西还是相通的，也不要因为别人运维Oracle，你运维SQLServer，就会感觉差很多档次。每个数据库的存在肯定有其合理性，没被市场淘汰说明它在某方面还是很有价值的。世界上没有完美的东西，数据库也是一样。应该根据具体需求选择你需要使用的数据库，至于你在运维什么数据库，很多时候真得没有那么重要。

最后，说下DBA还是DA。**我们的视角应该更关注数据，而不是数据库。**数据库是为数据服务的，数据库只是一个载体，最根本的东西是数据，很多时候我们考虑问题都会被数据库局限思维，如果抛开数据库，想得更宽，或许很多问题会柳暗花明又一村。

–EOF–

原文地址：微信公众号文章

题图来自：Google Images

版权声明：自由转载-非商用-非衍生-保持署名<a href="http://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh" target="_blank">（创意共享4.0许可证）</a>