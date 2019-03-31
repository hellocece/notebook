系统设计面试是一个**开放式的对话**。他们期望你去主导这个对话。

你可以使用下面的步骤来指引讨论。为了巩固这个过程，请使用下面的步骤完成[系统设计的面试题和解答](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98%E5%92%8C%E8%A7%A3%E7%AD%94)这个章节。

### 第一步：描述使用场景，约束和假设

把所有需要的东西聚集在一起，审视问题。不停的提问，以至于我们可以明确使用场景和约束。讨论假设。

* 谁会使用它？
* 他们会怎样使用它？
* 有多少用户？
* 系统的作用是什么？
* 系统的输入输出分别是什么？
* 我们希望处理多少数据？
* 我们希望每秒钟处理多少请求？
* 我们希望的读写比率？

### 第二步：创造一个高层级的设计

使用所有重要的组件来描绘出一个高层级的设计。

* 画出主要的组件和连接
* 证明你的想法

### 第三步：设计核心组件

对每一个核心组件进行详细深入的分析。举例来说，如果你被问到[设计一个 url 缩写服务](https://github.com/hellocece/system-design-primer/blob/master/solutions/system_design/pastebin/README.md)，开始讨论：

* 生成并储存一个完整 url 的 hash
  * [MD5](https://github.com/hellocece/system-design-primer/blob/master/solutions/system_design/pastebin/README.md)
    和
    [Base62](https://github.com/hellocece/system-design-primer/blob/master/solutions/system_design/pastebin/README.md)
  * Hash 碰撞
  * SQL 还是 NoSQL
  * 数据库模型
* 将一个 hashed url 翻译成完整的 url
  * 数据库查找
* API 和面向对象设计

### 第四步：扩展设计

确认和处理瓶颈以及一些限制。举例来说就是你需要下面的这些来完成扩展性的议题吗？

* 负载均衡
* 水平扩展
* 缓存
* 数据库分片

论述可能的解决办法和代价。每件事情需要取舍。可以使用[可扩展系统的设计原则](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1%E4%B8%BB%E9%A2%98%E7%9A%84%E7%B4%A2%E5%BC%95)来处理瓶颈。

### 预估计算量

你或许会被要求通过手算进行一些估算。[附录](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#%E9%99%84%E5%BD%95)涉及到的是下面的这些资源：

* [使用预估计算量](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)
* [2 的次方表](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#2-%E7%9A%84%E6%AC%A1%E6%96%B9%E8%A1%A8)
* [每个程序员都应该知道的延迟数](https://github.com/hellocece/system-design-primer/blob/master/README-zh-Hans.md#%E6%AF%8F%E4%B8%AA%E7%A8%8B%E5%BA%8F%E5%91%98%E9%83%BD%E5%BA%94%E8%AF%A5%E7%9F%A5%E9%81%93%E7%9A%84%E5%BB%B6%E8%BF%9F%E6%95%B0)

### 相关资源和延伸阅读

查看下面的链接以获得我们期望的更好的想法：

* [怎样通过一个系统设计的面试](https://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
* [系统设计的面试](http://www.hiredintech.com/system-design)
* [系统架构与设计的面试简介](https://www.youtube.com/watch?v=ZgdS0EUmn70)



