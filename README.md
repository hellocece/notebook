# 系统设计入门

## 序言

翻译此书的目的：

1.了解如何设计大型系统。

学习如何设计可扩展系统将有助于您成为更好的工程师。

系统设计是一个广泛的主题。**整个网络**上有**大量资源分散在**系统设计原则上。

此repo是一个**有组织**的资源**集合**，可帮助您了解如何大规模构建系统。

2.准备系统设计面试。

除了编码的访谈，系统设计是**必需的组件**中的**技术面试过程中**，在许多高科技公司。

**练习常见的系统设计面试问题**，**并将**您的结果与**示例解决方案进行比较**：讨论，代码和图表。

面试准备的其他主题：

* [学习指导](https://github.com/hellocece/system-design-primer#study-guide)
* [如何处理系统设计面试问题](https://github.com/hellocece/system-design-primer#how-to-approach-a-system-design-interview-question)
* [系统设计面试问题，**有解决方案**](https://github.com/hellocece/system-design-primer#system-design-interview-questions-with-solutions)
* [面向对象的设计面试问题，**有解决方案**](https://github.com/hellocece/system-design-primer#object-oriented-design-interview-questions-with-solutions)
* [附加系统设计面试问题](https://github.com/hellocece/system-design-primer#additional-system-design-interview-questions)

## 目录

> #### `各种系统设计主题的摘要，包括优点和缺点。每一个主题都面临着取舍和权衡。`
>
> #### `每个章节都包含着更多的资源的链接。`

![](/assets/687474703a2f2f692e696d6775722e636f6d2f6a6a3341354e382e706e67.png)

* 系统设计主题：从这里开始

  * 第一步：回顾可扩展性的视频讲座

  * 第二步：回顾可扩展性的文章

  * 接下来的步骤

* [性能与拓展性](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#性能与可扩展性)

* [延迟与吞吐量](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#延迟与吞吐量)

* [可用性与一致性](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#可用性与一致性)

 *  [CAP 理论](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#cap-%E7%90%86%E8%AE%BA)
   * [CP - 一致性和分区容错性](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#cp--%E4%B8%80%E8%87%B4%E6%80%A7%E5%92%8C%E5%88%86%E5%8C%BA%E5%AE%B9%E9%94%99%E6%80%A7)
   * [AP - 可用性和分区容错性](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#ap--%E5%8F%AF%E7%94%A8%E6%80%A7%E4%B8%8E%E5%88%86%E5%8C%BA%E5%AE%B9%E9%94%99%E6%80%A7)
* 一致模式
 * 弱一致
 * 最终一致
 * 强一致
* 可用模式
 * 故障切换
 * 复制
* 域名系统
* CDN
 * CDN 推送
 * CDN 拉取
* 负载均衡器
 * 工作到备用切换(active-passive)
 * 双工作模式(ACTIVE-ACTIVE)
 * 四层负载均衡
 * 七层负载均衡
 * 水平扩展
* 反向代理(web 服务器)
 * 负载均衡与反向代理
* 应用层
 * 微服务
 * 服务发现
* 数据库
 * 关系型数据库管理系统
  * master-slave 复制集
  * master-master 复制集
  * 联合
  * 分片
  * 非规范化
  * sql 调优
 * NOSQL
  * KEY-VALUE存储
  * 文档存储
  * 宽列存储
  * 图数据库
 * sql 还是nosql
* 缓存
 * 客户端缓存
 * CDN 缓存
 * web服务器缓存
 * 数据库缓存
 * 应用缓存
 * 数据库查询级别缓存
 * 对象级别缓存
 * 何时更新缓存
  * 缓存模式
  * 直写模式
  * 回写模式
  * 刷新
 * 异步
  * 消息队列
  * 任务队列
  * 背压机制
 * 通讯
  * 传输控制协议（TCP）
  * 用户数据报协议（UDP）
  * 远程控制调用协议（RCP）
  * 表述性状态转移（REST）
 * 安全
 * 附录
  * 2 的次方表
  * 每个coder 应知道的延迟数
  * 其他的系统设计面试题
  * 真实的架构
  * 公司系统架构
  * 公司工程博客
  
 



