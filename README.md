# 学习笔记

## 项目介绍

Java学习笔记，面试突击宝典，主要来源于B站上视频的学习，同时会记录平时一些学习和项目中遇到的问题，同步更新在 [蘑菇博客](http://www.moguit.cn)，如果对我的博客网站感兴趣的话，欢迎关注我的 [蘑菇博客源码](https://gitee.com/moxi159753/mogu_blog_v2)，如果笔记对您有帮助的话，欢迎star支持，谢谢~

笔记主要涵盖：Java，JVM、JUC、Spring，SpringCloud，计算机网络，操作系统，数据结构，Vue等

本仓库有来源自己总结、网上收集、视频笔记，如果有侵权之处，可以联系我进行删除

因个人能力有限，笔记中可能还有很多错误的地方，还请大家能够多多指出交流，也欢迎各位小伙伴能够提交pull request请求进行完善

如果您要转载本仓库中的笔记到其它地方，欢迎添加笔记的仓库地址：[LearningNotes](https://gitee.com/moxi159753/LearningNotes)

## 文档

为了更方便小伙伴的复习和查询，把本仓库做成一个在线的文档

- 在线文档：http://moxi159753.gitee.io/learningnotes

## Java

> 来源Bilibili尚硅谷周阳老师学习视频：[点我传送](https://www.bilibili.com/video/BV15J4112785)

- [equals和等等的区别](校招面试/基础面试题/1_equals和等等的区别/README.md)
- [代码块](./校招面试/基础面试题/2_代码块/README.md)
- [分布式锁](./校招面试/基础面试题/3_分布式锁/README.md)
- [MySQL的存储引擎](./校招面试/基础面试题/4_MySQL的存储引擎/README.md)
- [JDK动态代理和CGLIB动态代理](./校招面试/基础面试题/5_JDK动态代理和CGLIB动态代理/README.md)
- [Java注解和反射](./Java/Java注解和反射/README.md)
- [泛型的类型擦除](./Java/泛型的类型擦除/README.md)
- [Java使用Redis删除指定前缀Key](./Java/Java使用Redis删除指定前缀Key/README.md)
- [前端的一些跨域问题](./Java/前端的一些跨域问题/README.md)
- [使用Ip2region替代淘宝IP接口](./Java/使用Ip2region替代淘宝IP接口/README.md)
- [聊一聊-Java泛型中的通配符T，E，K，V](http://www.moguit.cn/#/info?blogUid=0aa459dc0ae9f9ad82cd22665d08a20d)
- [JVM类加载机制](./Java/JVM类加载机制/README.md)
- [VisualVM安装VisualGC插件](./Java/VisualVM安装VisualGC插件/README.md)
- [谈谈你对ThreadLocal的理解](./Java/谈谈你对ThreadLocal的理解/README.md)
- [谈谈你对AQS的理解](./Java/谈谈你对AQS的理解/README.md)
- [ArrayList扩容机制](./Java/ArrayList扩容机制/README.md)

## Java8新特性

> 来源Bilibili尚硅谷李贺飞老师学习视频：[Java8新特性](https://www.bilibili.com/video/BV1ut411g7E9)

- [HashMap变化](./校招面试/Java8新特性/1_HashMap变化/README.md)
- [Lambda表达式](./校招面试/Java8新特性/2_Lambda表达式/README.md) 
- [方法引用和构造器](./校招面试/Java8新特性/3_方法引用和构造器/README.md)
- [强大的Stream](./校招面试/Java8新特性/4_强大的Stream/README.md)
- [并行流](./校招面试/Java8新特性/5_并行流/README.md)
- [Optional容器类](./校招面试/Java8新特性/6_Optional容器类/README.md)

## NIO

- [NIO是什么](./校招面试/NIO/NIO是什么/README.md) 
- [IO到NIO的演变](./校招面试/NIO/NIO的使用案例/README.md)
- [IO和NIO的区别](http://www.moguit.cn/#/info?blogUid=28d61ec002594fc5a9c441ec8560f3ad)

## JVM

> 来源Bilibili尚硅谷宋红康老师JVM教程：[硅谷2020最新版宋红康JVM教程](https://www.bilibili.com/video/BV1PJ411n7xZ)

- [JVM与Java体系结构](JVM/1_内存与垃圾回收篇/1_JVM与Java体系结构/README.md)
- [类加载子系统](./JVM/1_内存与垃圾回收篇/2_类加载子系统/README.md)
- [运行时数据区概述及线程](./JVM/1_内存与垃圾回收篇/3_运行时数据区概述及线程/README.md)
- [程序计数器](./JVM/1_内存与垃圾回收篇/4_程序计数器/README.md)
- [虚拟机栈](./JVM/1_内存与垃圾回收篇/5_虚拟机栈/README.md)
- [本地方法接口](./JVM/1_内存与垃圾回收篇/6_本地方法接口/README.md)
- [本地方法栈](./JVM/1_内存与垃圾回收篇/7_本地方法栈/README.md)
- [堆](./JVM/1_内存与垃圾回收篇/8_堆/README.md)
- [方法区](./JVM/1_内存与垃圾回收篇/9_方法区/README.md)
- [对象实例化内存布局与访问定位](./JVM/1_内存与垃圾回收篇/10_对象实例化内存布局与访问定位/README.md)
- [直接内存](./JVM/1_内存与垃圾回收篇/11_直接内存/README.md)
- [执行引擎](./JVM/1_内存与垃圾回收篇/12_执行引擎/README.md)
- [StringTable](./JVM/1_内存与垃圾回收篇/13_StringTable/README.md)
- [垃圾回收概述](./JVM/1_内存与垃圾回收篇/14_垃圾回收概述/README.md)
- [垃圾回收相关算法](./JVM/1_内存与垃圾回收篇/15_垃圾回收相关算法/README.md)
- [垃圾回收相关概念](./JVM/1_内存与垃圾回收篇/16_垃圾回收相关概念/README.md)
- [垃圾回收器](./JVM/1_内存与垃圾回收篇/17_垃圾回收器/README.md)

## JUC

>来源Bilibili尚硅谷周阳老师学习视频：[尚硅谷Java大厂面试题第二季](https://www.bilibili.com/video/BV18b411M7xz)

- [Volatile和JMM内存模型的可见性](./校招面试/JUC/1_谈谈Volatile/1_Volatile和JMM内存模型的可见性/README.md)
- [Volatile不保证原子性](./校招面试/JUC/1_谈谈Volatile/2_Volatile不保证原子性/README.md)
- [Volatile禁止指令重排](./校招面试/JUC/1_谈谈Volatile/3_Volatile禁止指令重排/README.md)
- [Volatile的应用](./校招面试/JUC/1_谈谈Volatile/4_Volatile的应用/README.md)
- [CAS底层原理](./校招面试/JUC/2_谈谈CAS/5_CAS底层原理/README.md)
- [原子类AtomicInteger的ABA问题](./校招面试/JUC/3_谈谈原子类的ABA问题/6_原子类AtomicInteger的ABA问题/README.md)
- [ArrayList为什么是线程不安全的](./校招面试/JUC/4_ArrayList为什么线程不安全/ArrayList线程不安全的举例/README.md)
- [TransferValue是什么](./校招面试/JUC/5_TransferValue是什么/README.md)
- [Java锁之读写锁](./校招面试/JUC/6_Java的锁/Java锁之读写锁/README.md)
- [Java锁之公平锁和非公平锁](./校招面试/JUC/6_Java的锁/Java锁之公平锁和非公平锁/README.md)
- [Java锁之可重入锁和递归锁](./校招面试/JUC/6_Java的锁/Java锁之可重入锁和递归锁/README.md)
- [Java锁之自旋锁](./校招面试/JUC/6_Java的锁/Java锁之自旋锁/README.md)
- [CountDownLatch是什么](./校招面试/JUC/7_CountDownLatch_CyclicBarrier_Semaphore使用/CountDownLatch/README.md)
- [CyclicBarrier是什么](./校招面试/JUC/7_CountDownLatch_CyclicBarrier_Semaphore使用/CyclicBarrier/README.md)
- [Semaphore是什么](./校招面试/JUC/7_CountDownLatch_CyclicBarrier_Semaphore使用/Semaphore/README.md)
- [Java中的阻塞队列](./校招面试/JUC/8_阻塞队列/README.md)
- [Synchronized和Lock的区别与好处](./校招面试/JUC/Synchronized和Lock的区别与好处/README.md)
- [Java线程池详解](./校招面试/JUC/10_线程池/README.md)
- [死锁编码及快速定位](./校招面试/JUC/11_死锁编码及快速定位/README.md)
- [JVM体系结构](./校招面试/JUC/12_JVM/JVM体系结构/README.md)
- [什么是GCRoots能做什么](./校招面试/JUC/12_JVM/JVM面试题汇总/1_什么是GCRoots能做什么/README.md)
- [JVM参数调优](./校招面试/JUC/12_JVM/JVM面试题汇总/2_JVM参数调优/README.md)
- [Java中的强引用_软引用_弱引用_虚引用分别是什么](./校招面试/JUC/12_JVM/JVM面试题汇总/3_Java中的强引用_软引用_弱引用_虚引用分别是什么/README.md)
- [Java内存溢出OOM](./校招面试/JUC/12_JVM/JVM面试题汇总/4_Java内存溢出OOM/README.md)
- [垃圾回收器](./校招面试/JUC/12_JVM/JVM面试题汇总/5_垃圾回收器/README.md)
- [Linux相关命令](./校招面试/JUC/13_Linux相关命令/README.md)
- [Github学习](./校招面试/JUC/14_Github学习/README.md)
- [乐观锁和悲观锁](./校招面试/JUC/15_乐观锁和悲观锁/README.md)
- [源码](./校招面试/JUC/Code)

## 中间件

>来源Bilibili中华石杉老师学习视频：[Java工程师面试突击](https://www.bilibili.com/video/BV1UJ411X7M1)

- [消息队列的面试连环炮](./校招面试/面试扫盲学习/1_消息队列的面试连环炮/README.md)
- [分布式搜索引擎的面试连环炮](./校招面试/面试扫盲学习/2_分布式搜索引擎的面试连环炮/README.md)
- [分布式缓存](./校招面试/面试扫盲学习/3_分布式缓存/README.md)
- [Redis的面试连环炮](./校招面试/面试扫盲学习/4_Redis的面试连环炮/README.md)
- [Redis的面试连环炮2](./校招面试/面试扫盲学习/5_Redis的面试连环炮2/README.md)
- [分布式系统的面试连环炮](./校招面试/面试扫盲学习/6_分布式系统的面试连环炮/README.md)
- [分布式系统幂等性与顺序性及分布式锁](./校招面试/面试扫盲学习/7_分布式系统幂等性与顺序性及分布式锁/README.md)
- [分布式Session解决方案](./校招面试/面试扫盲学习/8_分布式Session解决方案/README.md)
- [Spring中的事务](./校招面试/面试扫盲学习/9_Spring中的事务/README.md)
- [设计一个高并发系统](./校招面试/面试扫盲学习/10_设计一个高并发系统/README.md)
- [数据库分库分表的面试连环炮](./校招面试/面试扫盲学习/11_数据库分库分表的面试连环炮/README.md)
- [MySQL读写复制及主从同步时延](./校招面试/面试扫盲学习/12_MySQL读写复制及主从同步时延/README.md)
- [常见的消息队列有哪些？](http://www.moguit.cn/#/info?blogUid=3a309d5c258c58e7b03a99cda13f650c)
- [5个方案告诉你：高并发环境下，先操作数据库还是先操作缓存？](http://www.moguit.cn/#/info?blogUid=b73aba84b0890c3c282a18c4fb0aab3d)

## SpringCloud

> 来源Bilibili尚硅谷周阳老师学习视频：[尚硅谷2020最新版SpringCloud(H版&alibaba)框架](https://www.bilibili.com/video/BV18E411x7eT)

- [SpringCloud是什么](./SpringCloud/SpringCloud2020/1_SpringCloud是什么/README.md)   
- [搭建Eureka集群](./SpringCloud/SpringCloud2020/3_搭建Eureka集群/README.md)
- [Eureka停更后的替换](./SpringCloud/SpringCloud2020/4_Eureka停更后的替换/README.md)
- [Ribbon负载均衡](./SpringCloud/SpringCloud2020/5_Ribbon负载均衡/README.md) 
- [OpenFeign实现服务调用](./SpringCloud/SpringCloud2020/6_OpenFeign实现服务调用/README.md) 
- [Hystrix中的服务降级和熔断](./SpringCloud/SpringCloud2020/7_Hystrix中的服务降级和熔断/README.md) 
- [服务网关Gateway](./SpringCloud/SpringCloud2020/8_服务网关Gateway/README.md)
- [分布式配置中心SpringCloudConfig](./SpringCloud/SpringCloud2020/9_分布式配置中心SpringCloudConfig/README.md)
- [消息总线Bus](./SpringCloud/SpringCloud2020/10_消息总线Bus/README.md)
- [消息驱动SpringCloudStream](./SpringCloud/SpringCloud2020/11_消息驱动SpringCloudStream/README.md)
- [SpringCloudSleuth分布式请求链路跟踪](./SpringCloud/SpringCloud2020/12_SpringCloudSleuth分布式请求链路跟踪/README.md)
- [使用Nacos实现服务注册发现以及服务配置等功能](./SpringCloud/SpringCloud2020/13_Nacos是什么/README.md)
- [SpringCloudAlibabaSentinel实现熔断和限流](./SpringCloud/SpringCloud2020/14_SpringCloudAlibabaSentinel实现熔断和限流/README.md)
- [SpringCloudAlibabaSeata处理分布式事务](./SpringCloud/SpringCloud2020/15_SpringCloudAlibabaSeata处理分布式事务/README.md)
- [使用Zipkin搭建蘑菇博客链路追踪](./SpringCloud/使用Zipkin搭建蘑菇博客链路追踪/README.md)
- [源码](./SpringCloud/SpringCloud2020/SpringCloud2020)

## 算法学习

> 来源牛客网剑指offer的题目：&#x2003;&#x2003;[点我传送](https://www.nowcoder.com/ta/coding-interviews?page=1)
>
> Bilibili视频学习解题思路(Python版本)：&#x2003;&#x2003;[点我传送](https://www.bilibili.com/video/BV1K4411o7KP)

- [斐波那契数列](./数据结构/1_斐波那契数列/README.md)
- [青蛙跳台阶](./数据结构/2_青蛙跳台阶/README.md)
- [找出丑数](./数据结构/3_找出丑数/README.md)
- [二维数组中的查找](./数据结构/4_二维数组中的查找/README.md)
- [替换空格](./数据结构/5_替换空格/README.md)
- [两个栈实现一个队列](./数据结构/6_两个栈实现一个队列/README.md)
- [旋转数组的最小数字](./数据结构/7_旋转数组的最小数字/README.md)
- [调整数组顺序使奇数位于偶数前面](./数据结构/8_调整数组顺序使奇数位于偶数前面/README.md)
- [包含min函数的栈](./数据结构/9_包含min函数的栈/README.md)
- [栈的压入弹出序列](./数据结构/10_栈的压入弹出序列/README.md)
- [从尾到头打印链表](./数据结构/11_从尾到头打印链表/README.md)
- [链表中倒数第K个节点](./数据结构/12_链表中倒数第K个节点/README.md)
- [反转链表](./数据结构/13_反转链表/README.md)
- [合并两个排序的链表](./数据结构/14_合并两个排序的链表/README.md)
- [复杂链表的复制](./数据结构/15_复杂链表的复制/README.md)
- [两个链表的公共结点](./数据结构/16_两个链表的公共结点/README.md)
- [孩子们的游戏(圆圈中最后剩下的数)](./数据结构/17_孩子们的游戏(圆圈中最后剩下的数/README.md))
- [链表中环的入口结点](./数据结构/18_链表中环的入口结点/README.md)
- [二进制中1的个数](./数据结构/19_二进制中1的个数/README.md)
- [不用加减乘除做加法](./数据结构/20_不用加减乘除做加法/README.md)
- [数组中出现次数超过一半的数字](./数据结构/21_数组中出现次数超过一半的数字/README.md)
- [整数中1出现的次数](./数据结构/22_整数中1出现的次数/README.md)
- [数组中只出现一次的数字](./数据结构/23_数组中只出现一次的数字/README.md)
- [树的遍历](./数据结构/24_树的遍历/README.md)
- [重建二叉树](./数据结构/25_重建二叉树/README.md)
- [树的子结构](./数据结构/26_树的子结构/README.md)
- [二叉树的镜像](./数据结构/27_二叉树的镜像/README.md)
- [从上往下打印二叉树](./数据结构/28_从上往下打印二叉树/README.md)
- [二叉搜索树的后序遍历序列](./数据结构/29_二叉搜索树的后序遍历序列/README.md)
- [二叉树中和为某一值的路径](./数据结构/30_二叉树中和为某一值的路径/README.md)
- [二叉搜索树与双向链表](./数据结构/31_二叉搜索树与双向链表/README.md)
- [最小的K个数](./数据结构/32_最小的K个数/README.md)
- [数据流中的中位数](./数据结构/33_数据流中的中位数/README.md)
- [ 二叉树的下一个节点](./数据结构/34_二叉树的下一个节点/README.md)
- [对称的二叉树](./数据结构/35_对称的二叉树/README.md)
- [按之字形顺序打印二叉树](./数据结构/36_按之字形顺序打印二叉树/README.md)
- [把二叉树打印成多行](./数据结构/37_把二叉树打印成多行/README.md)
- [二叉搜索树的第K个节点](./数据结构/38_二叉搜索树的第K个节点/README.md)
- [序列化二叉树](./数据结构/39_序列化二叉树/README.md)
- [连续子数组的最大和](./数据结构/40_连续子数组的最大和/README.md)
- [矩形覆盖](./数据结构/41_矩形覆盖/README.md)
- [排序算法-冒泡插入选择](./数据结构/42_排序算法-冒泡插入选择/README.md)
- [希尔排序](./数据结构/43_希尔排序/README.md)
- [归并排序](./数据结构/44_归并排序/README.md)
- [快速排序](./数据结构/45_快速排序/README.md)
- [动态规划算法](./数据结构/动态规划算法/README.md)
- [源码](./数据结构/NowCode)

## SpringBoot

- [Eureka管理页面配置接口返回git信息](./SpringBoot/Eureka管理页面配置接口返回git信息/README.md)
- [Java如何通过IP地址获取地区](./SpringBoot/Java如何通过IP地址获取地区/README.md)
- [SpringSecurity造成无法使用iframe的内嵌页面的解决方法](./SpringBoot/SpringSecurity造成无法使用iframe的内嵌页面的解决方法/README.md)
- [SpringBoot解决时区问题](./SpringBoot/SpringBoot解决时区问题/README.md)
- [SpringBoot项目中使用字符串占位符](./SpringBoot/SpringBoot项目中使用字符串占位符/README.md)
- [SpringBoot中使用注解的方式创建队列和交换机](./SpringBoot/SpringBoot中使用注解的方式创建队列和交换机/README.md)
- [解决升级SpringBoot2.X后无法向eureka注册服务的问题](./SpringBoot/解决升级SpringBoot2.X后无法向eureka注册服务的问题/README.md)
- [使用DevTool实现SpringBoot项目热部署](./SpringBoot/使用DevTool实现SpringBoot项目热部署/README.md)
- [使用自定义日志接口收集用户访问日志](./SpringBoot/使用自定义日志接口收集用户访问日志/README.md)
- [Bean的生命周期](./SpringBoot/Bean的生命周期/README.md)

## Vue

- [Axios中拦截器的使用](./Vue/Axios中拦截器的使用/README.md)
- [ElementUI中Upload如何批量上传](./Vue/ElementUI中Upload如何批量上传/README.md)
- [el-select因为绑定的值为整数而无法默认选择](./Vue/el-select因为绑定的值为整数而无法默认选择/README.md)
- [Vue动态计算Table表格的高度](./Vue/Vue动态计算Table表格的高度/README.md)
- [Vue对Element中的e-tag添加@click事件无效](./Vue/Vue对Element中的e-tag添加@click事件无效/README.md)
- [Vue使用Echarts制作一个文章贡献度表](./Vue/Vue使用Echarts制作一个文章贡献度表/README.md)
- [Vue中input框自动聚焦](./Vue/Vue中input框自动聚焦/README.md)
- [Vue使用vue-count-to插件对数字显示美化](./Vue/Vue使用vue-count-to插件对数字显示美化/README.md)
- [Vue项目如何关闭Eslint校验](./Vue/Vue项目如何关闭Eslint校验/README.md)
- [Vue项目使用阿里巴巴矢量图标库](./Vue/Vue项目使用阿里巴巴矢量图标库/README.md)
- [Vue项目引入CDN加速](./Vue/Vue项目引入CDN加速/README.md)
- [Vue制作一个评论模块](./Vue/Vue制作一个评论模块/README.md)
- [Vue中Html和Markdown互相转换](./Vue/Vue中Html和Markdown互相转换/README.md)
- [Vue中对数组变化监听](./Vue/Vue中对数组变化监听/README.md)
- [Vue中使用Vue-cropper进行图片裁剪](./Vue/Vue中使用Vue-cropper进行图片裁剪/README.md)
- [Vuex学习指南-实现一个计数器](./Vue/VueX/Vuex学习指南-实现一个计数器/README.md)
- [Vue中防止XSS脚本攻击](./Vue/VueX/Vue中防止XSS脚本攻击/README.md)
- [Vue如何使用G2绘制图片](./Ant/G2/Vue如何使用G2绘制图片/README.md)
- [使用Vuex进行两个页面逻辑交互](./Vue/使用Vuex进行两个页面逻辑交互/README.md)

## 杂记

- [CKEditor前端样式和编辑器的样式不一致的问题](./杂记/CKEditor前端样式和编辑器的样式不一致的问题/README.md)
- [Ckeidtor中上传图片添加token信息](./杂记/ckeidtor中上传图片添加token信息/README.md)
- [CLion搭建C语言开发环境](./杂记/CLion搭建C语言开发环境/README.md)
- [Elasticsearch介绍与安装](./杂记/Elasticsearch介绍与安装/README.md)
- [Github项目配置Actions](./杂记/Github项目配置Actions/README.md)
- [SpringBoot+Vue如何集成第三方登录登录JustAuth](./杂记/SpringBoot+Vue如何集成第三方登录登录JustAuth/README.md)
- [SpringBoot项目启动增加自定义Banner](./杂记/SpringBoot项目启动增加自定义Banner/README.md)
- [VSCode服务版搭建教程,让平板化为生产力工具](./杂记/VSCode服务版搭建教程/README.md)
- [Windows平台编写bat脚本让后台启动多个程序](./杂记/Windows平台编写bat脚本让后台启动多个程序/README.md)
- [记一次蘑菇博客差点被删库的经历](./杂记/记一次蘑菇博客差点被删库的经历/README.md)
- [解决git默认不区分大小写的问题](./杂记/解决git默认不区分大小写的问题/README.md)
- [蘑菇博客后台登录页面增加粒子特效](./杂记/蘑菇博客后台登录页面增加粒子特效/README.md)
- [蘑菇博客集成MarkDown编辑器tui-editor](./杂记/蘑菇博客集成MarkDown编辑器tui-editor/README.md)
- [蘑菇博客配置七牛云存储](./杂记/蘑菇博客配置七牛云存储/README.md)
- [蘑菇博客配置域名解析](./杂记/蘑菇博客配置域名解析/README.md)
- [蘑菇博客切换搜索模式](./杂记/蘑菇博客切换搜索模式/README.md)
- [蘑菇博客如何部署到阿里云服务器](./杂记/蘑菇博客如何部署到阿里云服务器/README.md)
- [蘑菇博客如何扩展新的功能和页面](./杂记/蘑菇博客如何扩展新的功能和页面/README.md)
- [蘑菇博客使用GithubAction完成持续集成](./杂记/蘑菇博客使用GithubAction完成持续集成/README.md)
- [蘑菇博客使用SQL语句进行搜索出的内容忽略大小写并添加高亮效果](./杂记/蘑菇博客使用SQL语句进行搜索出的内容忽略大小写并添加高亮效果/README.md)
- [蘑菇博客添加本地Markdown文件上传功能](./杂记/蘑菇博客添加本地Markdown文件上传功能/README.md)
- [如何给七牛云中的文件配置防盗链](./杂记/如何给七牛云中的文件配置防盗链/README.md)
- [如何使用docsify给蘑菇博客编写开发文档](./杂记/如何使用docsify给蘑菇博客编写开发文档/README.md)
- [如何制作github小徽章](./杂记/如何制作github小徽章/README.md)
- [使用JustAuth集成QQ登录](./杂记/使用JustAuth集成QQ登录/README.md)
- [使用开源项目申请JetBrains全家桶](./杂记/使用开源项目申请JetBrains全家桶/README.md)
- [什么是CICD](./杂记/什么是CICD/README.md)
- [罗技K380快捷键](./杂记/罗技K380快捷键/README.md)
- [将PDF转换为Kindle能识别的MOBI格式](./杂记/将PDF转换为Kindle能识别的MOBI格式/README.md)
- [OCR文字识别软件](./杂记/OCR文字识别软件/README.md)

## Linux

- [Linux下查看文件和文件夹占用空间大小](./Linux/Linux下查看文件和文件夹占用空间大小/README.md)
- [Linux下通过nginx配置https](./Linux/Linux下通过nginx配置https/README.md)
- [记一次因代码出错不断输出日志占满Docker容器硬盘的排查经历](./Linux/记一次因代码出错不断输出日志占满Docker容器硬盘的排查经历/README.md)

## Redis

- [Redis中的数据结构](./Redis/Redis中的数据结构/README.md)
- [Redis中的跳跃表](./Redis/Redis中的跳跃表/README.md)
- [Redis缓存穿透-布隆过滤器](./Redis/Redis缓存穿透-布隆过滤器/README.md)
- [大白话谈IO模型](./Redis/大白话谈IO模型/README.md)
- [IO多路复用底层原理](./Redis/IO多路复用底层原理/README.md)

## JavaScript

- [Js设置二级域名和顶级域名下共享Cookie](./JavaScript/Js设置二级域名和顶级域名下共享Cookie/README.md)
- [如何通过Js将时间转换为刚刚_几分钟前_几小时前](./JavaScript/如何通过Js将时间转换为刚刚_几分钟前_几小时前/README.md)

## 数据库

- [MyBatis常见面试题](./数据库/MyBatis常见面试题/README.md)
- [MyBatis的缓存机制](./数据库/MyBatis的缓存机制/README.md)
- [MySQL索引](./数据库/MySQL索引/README.md)

## 操作系统

- [进程和线程通信](./操作系统/1_进程和线程通信/README.md)

## 计算机网络

- [三次握手和四次挥手](./计算机网络/1_三次握手和四次挥手/README.md)
- [https和http](./计算机网络/2_https和http/README.md)
- [TCP中的拥塞控制和流量控制](./计算机网络/3_TCP中的拥塞控制和流量控制/README.md)
- [物理层](./计算机网络/4_物理层/README.md)
- [数据链路层](./计算机网络/5_数据链路层/README.md)
- [http中的状态码](./计算机网络/http中的状态码/README.md)

## 面经

- [京东面经](./校招面试/面经汇总/1_京东面经/README.md)
- [字节跳动面试总结](./校招面试/面经汇总/2_字节跳动面试总结/README.md)
- [京东零售提前批Java一面](./校招面试/面经汇总/3_京东零售提前批Java一面/README.md)
- [京东零售提前批Java二面](./校招面试/面经汇总/4_京东零售提前批Java二面/README.md)
- [滴滴出行提前批Java123面](./校招面试/面经汇总/5_滴滴出行提前批Java123面/README.md)

## Golang基础

> 来源Bilibili IT营 大地老师学习视频：[点我传送](https://www.bilibili.com/video/BV14T4y1g7h9)

- [Go语言的安装](./Golang/Golang基础/0_Go语言的安装/README.md)
- [Go语言发展简史](./Golang/Golang基础/1_Go语言发展简史/README.md)
- [Go的变量](./Golang/Golang基础/2_Go的变量/README.md)
- [Go的数据类型](./Golang/Golang基础/3_Go的数据类型/README.md)
- [Go的运算符](./Golang/Golang基础/4_Go的运算符/README.md)
- [Go的流程控制](./Golang/Golang基础/5_Go的流程控制/README.md)
- [Go的数组](./Golang/Golang基础/6_Go的数组/README.md)
- [Go的切片](./Golang/Golang基础/7_Go的切片/README.md)
- [Go的map](./Golang/Golang基础/8_Go的map/README.md)
- [Go的函数](./Golang/Golang基础/9_Go的函数/README.md)
- [Go中的日期函数](./Golang/Golang基础/10_Go中的日期函数/README.md)
- [Go中的指针](./Golang/Golang基础/11_Go中的指针/README.md)
- [Go中的结构体](./Golang/Golang基础/12_Go中的结构体/README.md)
- [Go中的包以及GoMod](./Golang/Golang基础/13_Go中的包以及GoMod/README.md)
- [Go中的接口](./Golang/Golang基础/14_Go中的接口/README.md)
- [goroutine实现并行和并发](./Golang/Golang基础/15_goroutine实现并行和并发/README.md)
- [Golang中的反射](./Golang/Golang基础/16_Golang中的反射/README.md)
- [源码](./Golang/Golang基础/Code)

## 关注&交流

刚刚创建了一个QQ群 (**加群备注**：`蘑菇博客`) <a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=88bc57d77601a3c5ae97fe6d9c0bfa25c2ae166d8f0b9f6da6f7294097be6d08"><img border="0" src="./doc/images/qq/group.png" alt="蘑菇博客交流群" title="蘑菇博客交流群"></a>，目前项目还存在很多不足之处，欢迎各位老哥进群进行技术交流，为了防止广告进入，希望加群的时候能添加备注，谢谢~

|             QQ群（加群备注：`蘑菇博客`）              |              QQ（备注：`蘑菇博客`）              |
| :---------------------------------------------------: | :----------------------------------------------: |
| <img src="./doc/images/qq/qqGroup.png" width="200" /> | <img src="./doc/images/qq/qq.png" width="200" /> |

## 赞赏

如果觉得本仓库对您有帮助的话，希望朋友能够给博主喝一杯咖啡（ps.. 小伙伴赞赏的时候可以备注一下下~）

|                       微信                       |                      支付宝                       |
| :----------------------------------------------: | :-----------------------------------------------: |
| <img src="./doc/images/qq/wx.png" width="200" /> | <img src="./doc/images/qq/zfb.png" width="200" /> |

