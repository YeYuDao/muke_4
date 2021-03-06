# muke_4
Spring 5实战开发及新特性精讲
Spring 5实战开发及新特性精讲
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 课程导学与学习指南 

#### 本章将对本门课程整体内容安排进行详细阐述，让大家全面了解课程设计的合理性，并在学习方法上给出合理建议，让大家在最短时间内达到高质量的学习效果。
1-1 课前必读（不读错过一个亿）

1-2 Spring5新特性-课程导学 (11:12)


### 第2章 Spring 5 课程基础概念综述

#### 本章作为全课程开篇，将介绍整个课程的章节安排，并对Spring 框架的重要概念进行梳理。
2-1 Spring 基本概念 (08:23)

2-2 Spring 5.0-5.3引入的新功能（一） (13:10)

2-3 Spring 5.0-5.3引入的新功能（二） (08:26)

2-4 实战项目介绍 (03:55)

2-5 环境安装指导


### 第3章 Spring MVC 应用实战开发

#### 本章通过一个股价查询订阅系统的Spring MVC初版实现，带领大家回顾Spring MVC框架，并重点对Spring MVC框架的实现原理和重点功能进行分析。
3-1 Spring MVC实现股价订阅系统 (13:09)

3-2 Sring MVC的工作机制和请求生命周期 (06:14)

3-3 Spring MVC的工作机制和请求生命周期

3-4 Spring MVC重要类源码分析 (19:31)

3-5 Validator使用的浅析 (14:19)

3-6 Spring MVC 程序可扩展性的设计讨论 (07:41)


### 第4章 Spring MVC应用整合Spring 5安全框架

#### 本章会基于上一章中实现的股价查询订阅系统，加入Spring安全框架的配置，来对服务进行权限管控。将会在本章节研究Spring 安全框架的设计，并对定制化开发会涉及的类进行代码展示，也将介绍目前业界颇为流行的单点登录SSO的实现。...
4-1 MVC应用整合Spring5安全框架介绍 (01:19)

4-2 股价订阅系统配置Spring 5安全框架 (15:26)

4-3 Spring 5安全框架的设计思想 (06:17)

4-4 Spring 5安全框架的源码分析 (16:36)

4-5 配置多个AuthenticationProvider (10:29)

4-6 自定义AuthenticationFilter和LoginHandler (12:15)

4-7 spring security 5中的功能更新介绍 (06:30)

4-8 Spring 5安全框架的设计思想

4-9 让你的项目集成OAuth 2.0


### 第5章 Spring MVC对异步操作的支持

#### 本章节重点介绍自Servlet 3.0以来Spring MVC对异步操作的支持；通过在实战项目的MVC框架中引入响应式流，来展示Spring 5对响应式编程的全面支持，同时会介绍Spring 安全框架以及模板引擎Thymeleaf对响应式编程的支持。
5-1 Spring MVC中的异步支持 (04:27)

5-2 实战-对MVC应用进行异步化改造 (16:57)

5-3 异步控制器的实现原理 (17:46)

5-4 Spring安全框架对异步请求的支持 (06:43)

5-5 用CompletableFuture实现服务的异步结果返回 (14:10)

5-6 对MVC应用使用响应式流进行重构 (07:57)


### 第6章 响应式编程(一) - 函数式编程 

#### 本章将对Java 8中引入的函数式编程概念进行详细介绍，重点阐述lambda表达式和Stream API的使用。通过本章的学习，学员会对后续响应式编程的理解打下良好的基础。
6-1 命令式编程和函数式编程的对比

6-2 函数式编程介绍 (01:34)

6-3 基于匿名类的lambda表达式 (06:37)

6-4 基于函数式接口的lambda表达式 (07:08)

6-5 JDK8中自带的函数式接口介绍 (19:51)

6-6 方法引用和构造器引用 (10:14)

6-7 为何不能在lambda中抛出异常 (04:59)

6-8 Currying in java (08:29)

6-9 Java Stream API 的原理 (08:48)

6-10 -1 使用stream流操作Collections (14:43)

6-11 -2 使用stream流操作Collections (09:04)

6-12 使用stream流操作nio 2.0 (05:11)

6-13 ParallelStream及其线程浅析 (08:31)


### 第7章 响应式编程(二) - 响应式流

#### 本章将对响应式编程和响应式流进行细致的介绍，通过大量的代码实操案例，带大家了解响应式流的常用写法（基于Project Reactor），作为扩展阅读，同时会介绍另外一个流行的Java响应式开发框架RxJava。
7-1 响应式编程基本概念和规范介绍 (08:57)

7-2 Project Reactor开发文档

7-3 响应式编程接口分析 (06:58)

7-4 响应式编程接口分析

7-5 Reactor框架简介 (04:03)

7-6 流的构建 (13:18)

7-7 流的操作 (20:21)

7-8 Scheduler的使用 (05:43)

7-9 publishOn和subscribeOn的区别 (07:00)

7-10 Flux的并发执行 (04:40)

7-11 处理实时流 (12:06)

7-12 编写响应式流的测试用例 (16:44)

7-13 RxJava, Observable, RxJS (09:01)

7-14 ReactiveX文档


### 第8章 完全异步非阻塞的WebFlux

#### 本章节详细解析Spring WebFlux框架，由实战项目股价订阅查询系统从MVC向WebFlux的改造展开，一步步展示阻塞式代码向响应式代码的改造。同时介绍之前章节代码中用到的安全框架和模板引擎向WebFlux的兼容，让大家对响应式开发框架有更深了解。最后会介绍介绍函数式框架WebFlux.fn。...
8-1 实战项目--Spring WebFlux实现股价订阅系统 (14:50)

8-2 阻塞式代码改造的常见误区 (08:33)

8-3 响应式Repository的使用和源码分析 (19:50)

8-4 进阶--浅析Spring安全框架对WebFlux的支持 (10:48)

8-5 进阶--浅析模板引擎对WebFlux的支持 (06:58)

8-6 函数式Web框架WebFlux.fn (15:14)


### 第9章 Spring 5中Web服务客户端和测试用例的编写

#### 本章围绕Spring MVC和WebFlux的测试和客户端调用展开，详细介绍Spring 5中两种不同Web框架的测试和调用方法上的区别。对于Spring 5新引进的WebClient，会着重对其源码进行分析。
9-1 MVC测试用例的编写 (14:26)

9-2 WebFlux测试用例的编写 (12:00)

9-3 使用RestTemplate完成同步调用 (08:01)

9-4 使用AsyncRestTemplate完成异步调用 (04:56)

9-5 使用WebClient完成响应式异步调用 (12:17)

9-6 WebClient的高级配置 (06:16)

9-7 WebClient源码分析 (08:01)


### 第10章 Spring WebFlux深入源码剖析 

#### 本章深入讲解Spring WebFlux，从源码层面分析WebFlux的实现。
10-1 浅析响应式框架的线程模型(加片头) (08:15)

10-2 源码分析 - Spring WebFlux启动过程 (09:50)

10-3 源码分析 - WebFlux如何实现异步请求处理 (13:33)

10-4 嵌入式服务器的选择 - Netty和Tomcat (09:42)


### 第11章 Spring 5的新增/改动功能（一）

#### 本章着重于介绍响应式编程之外的Spring 5新特性，结合代码演示对新特性进行展示。
11-1 JUnit 5的新功能和使用 (10:59)

11-2 JUnit 4迁移指北 (10:15)

11-3 不同的响应式Repository的介绍 (09:54)

11-4 JDK8的反射增强 (07:33)

11-5 新增对服务器推送技术的支持 (13:22)

11-6 日志框架的改动 (05:11)

11-7 新增和不再支持的框架 (04:57)


### 第12章 Spring 5的新增/改动功能（二）

#### 本章着重于介绍Spring5中除WebFlux以外响应式编程相关的新特性。 包括服务端消息推送和数据库访问。
12-1 实战-使用Reactive WebSocket完成数据实时推送 (21:56)

12-2 使用RSocket完成服务间通讯 (14:56)

12-3 RSocket协议简介

12-4 数据库访问 - 使用R2DBC (24:09)

12-5 解析R2DBC中的事务管理 (14:37)


### 第13章 如何拥抱Spring 5的未来

#### 本章着重于介绍Spring 框架在云原生发展趋势下的开发方向，囊括Spring5中对Spring Native和及对JDK LTS版本的支持。
13-1 云原生发展趋势下的Spring框架 (19:38)


### 第14章 课程总结
#### 本章将带大家回顾之前章节所学内容，并对java/spring的未来发展方向进行分析，让学员有的放矢的进行学习。

[下载地址](https://51xueit.vip "下载地址")
