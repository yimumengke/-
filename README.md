# Project Introduction

给自己标星的项目写点简介(一些来自星球,CodeSheep,一些自己写的)

项目，就是你看完、学完、自己默默实现完之后，可以写进你简历的项目。强烈建议，不要做重复相似的项目、不要做不适合校招生做的项目、尽量做能体现计算机系水平的项目、你的项目不要只局限于一门语言，并非做C++路线，就一定要做C++项目，你做Go、Java项目一样很不错嘛，前提是项目要好

- 这里给出的项目，只是例子，更多好项目，别人没做过的项目，你要自己创造、或者自己去查找，如果这里列出来，可能就有很多人一样做了，所以先学会模仿项目，再学会创造项目、做更深入的项目
- 重点多说一句：并非就一定要做C++项目，你做Go、Java项目一样很不错嘛，前提是项目要好，之前流行过一阵Go的RPC框架，也很好！

  - 下面列出的，只是一部分例子，更多项目，请关注我的视频～

- 重复相似的项目

  - 商城系统、博客系统、图书管理系统、各种XX应用层系统
  - WebServer、简单的课程设计

- 实现STL

  - 基于C++实现一个迷你STL

  一个合格的 `C++` 程序员是必须要会`STL`里的，其中的容器、算法在刷各种`OJ`的时候简直是一大利器。我知道有很多同学都有想过写一个属于自己的 `STL`，我也想过，但没行动过 hhh

MyTinySTL这个项目把我想的做了，它是基于 `C++11` 的`tinySTL`，其中实现了 大部分 `STL` 中的容器与函数 ，所以你也是完全可以照着它来实现自己的 `STL` 的。

    - https://github.com/Alinshans/MyTinySTL

  - 实现标准库部分容器和算法，对标准库进行扩充

    - https://github.com/senlinzhan/mystl
- 实现WebServer

  - Linux C++ WebServer

    - https://github.com/qinguoyi/TinyWebServer

  - （不适合写进项目）非常简单的http服务器

    - https://github.com/dxscjx123/tinyserver
- 实现网络框架

  - 基于IO多路复用和线程池的C++网络库

    - https://github.com/GeniusDai/kingpin

  - 轻量级网络框架，线程池技术，C++11

    - https://github.com/ZLMediaKit/ZLToolKit

  - Linux C++高性能TCP服务框架，基于Reactor模式，支持单线程、多线程Reactor，也支持UDP服务

    - https://github.com/LeechanX/Easy-Reactor
- 协程

  - libco（建议直接阅读源码，不用写进项目）

    - https://github.com/Tencent/libco
    - 文章

      - 漫谈微信libco协程设计及实现（万字长文）

        - https://runzhiwang.github.io/2019/06/21/libco/

      - 腾讯开源的 libco 号称千万级协程支持，那个共享栈模式原理是什么?

        - https://www.zhihu.com/question/52193579
- 数据库

  - 利用c/c++ 开发基于B+树的小型关系型数据库

    - https://github.com/enpeizhao/duck_db

## =========

## C语言经典案例

从Hello world 到进销存管理系统

GitHub 地址：https://github.com/Mzzopublic/C

## =========

## C：学习数据结构和刷算法题的利器

**项目简介：** 是的，你没有看错，这个项目的名字就是单个字母**C**。C是一个宝藏项目，可以说是学习数据结构和刷算法题的利器，因为里面包含了几乎各种基础算法、数据结构、以及LeetCode算法题的C语言实现。具体包括：

- 客户端/服务器问题
- 统计方法问题
- 进制转换问题
- 各种数据结构：数组、链表、字典、二叉树、堆、栈、队列、哈希、图等等
- 搜索/查找问题
- 排序问题
- LeetCode习题
- 其他杂项问题

注意，下图中只是截取了一部分数据结构和算法题的具体实现：

![图片](https://mmbiz.qpic.cn/mmbiz_png/vdXWcmzIVZHLHAMfKL4cOY9b60vaeckmia72ibmoFd9AJE8WBOyOMkkMPofFzYFe7jvnECZtn9MCFia5gbGibwVhTQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**对于我们的作用：** 可以帮助我们更好的学习**数据结构**、以及**刷算法题**

**项目源码地址：** `https://github.com/TheAlgorithms/C`

## =========

##  CPlusPlusThings：C++适合初学者的从入门到进阶的仓库

**项目简介：** CPlusPlusThings是一个适合初学者的从入门到进阶的仓库，里面包含了大量 C++语言的基础和进阶教程、源码剖析、工具推荐、实战练习等等，解决了初学者从入门到深入 C++的学习问题。

![图片](https://mmbiz.qpic.cn/mmbiz_png/vdXWcmzIVZHLHAMfKL4cOY9b60vaeckmcA9oEl79MbbgsZETrDXBhb6dLQoJrlXasU1zS5IIF6wqjj4RiaKKVJQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**对于我们的作用：** 可以帮助我们系统地学习 **C++** 相关知识

**项目源码地址：** `https://github.com/Light-City/CPlusPlusThings`

## =========

## 手把手教你从零开始实现一个 JSON 解析器

JSON 格式大家应该了解吧，带你从 0 到 1 实现一个 JSON 解析器，腾讯大佬写的，该项目我觉得最大的优点就是，手把手教你写，教你设计，可以学到很多编程的知识，而且也比较简单，不需要太多的前置知识

GitHub 地址：https://github.com/miloyip/json-tutorial

知乎地址:https://zhuanlan.zhihu.com/p/22460835

前置知识：学习过基本 C/C++ 编程的同学

## =========

## design-patterns-cpp：C++语言版的设计模式实现

**项目简介：** 从项目名称就能够猜出来，这是一个C++语言版的设计模式实现，里面包含了常见设计模式的C++ 语言实现。

![图片](https://mmbiz.qpic.cn/mmbiz_png/vdXWcmzIVZHLHAMfKL4cOY9b60vaeckmQuH40m7EcBljb8QQ8ibia4HwxQzM0iaqXZgH2EAEYfzjxdazIUd25wtrg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**对于我们的作用：** 帮助我们理解和实践**设计模式**相关知识

**项目源码地址：** `https://github.com/JakubVojvoda/design-patterns-cpp`

## =========

## Tinyhttpd：超轻量型 Http Server

**项目简介：**Tinyhttpd 是J. David Blackstone在1999年写的一个不到 500 行的超轻量型 Http Server ，用来学习非常不错，可以帮助我们真正理解服务器程序的本质。建议源码阅读顺序为：`main->startup->accept_request->execute_cgi`, 通晓主要工作流程后再仔细把每个函数的源码看一看。这500行代码吃透了，C语言的功底就会大幅提升。

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRhtIm9wok3zC6QpNWU9HlC0GxemS6yxM0ia90vNHu6yiaGdrEZmic6V3mw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

【注：图片来源于：www.cnblogs.com/nengm1988/p/7816618.html】

**项目源码：**https://github.com/EZLippi/Tinyhttpd



## MyTinySTL：小型的STL库

**项目简介：** 很多人表示学完C++不知道用来干什么，我觉得学完C++的第一个练手的好机会那就是自己试着实现一个小型的STL库。MyTinySTL的作者它就用 C++11 重新复写了一个小型 STL（容器库＋算法库）。代码结构清晰规范、包含中文文档与注释，并且自带一个简单的测试框架，非常适合新手学习与参考！

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRl0ogZiacBZxkbSDMicAiaab5V4fArePQatLj3WJVRFbzFpH8LrKsny6XQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**项目源码：**https://github.com/Alinshans/MyTinySTL

## =========

## Linux下C++轻量级Web服务器

这个是前几天咱门星球的小伙伴 @仰望 推荐给帅友的项目，我看了下，还不错，而且有教程。虽然说用 C++ 实现服务器有点烂大街，但我们的目标是学习，而且越简单的项目，我们可以做的改进就越多，比如加入代理功能、添加支持CGI功能或者加入日志记录等，到时候可以和面试官聊这些，证明你研究过。

GitHub 地址：https://github.com/qinguoyi/TinyWebServer
前置知识：看《liunx高性能服务器编程》之后看看《unix网络编程》和《unix环境高级编程》（大头书，挑重点)，然后可以在看看《linux多线程服务器编程》就可以做了

## =========

## oatpp： C++ 实现的 Web 框架

**项目简介：** 我们知道Java领域的Web框架非常繁荣，最知名的当属Spring全家桶，而C语言和C++阵营则几乎没有。那oatpp则是一个轻量、跨平台、高性能、完全零依赖，用纯 C++ 实现的 Web 框架，实在是难得，小伙伴们可以学习学习。

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRn9WbSyzYj41cKbdfLwibRyJnFj6BuVlkgtTz60YNiaib8TgcAUbHVibAbA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**项目源码：**https://github.com/oatpp/oatpp

## =========

## 基于跳表实现的轻量级键值数据库

这是我一个朋友几年前做的一个 C++ 项目，主要就是基于跳表来实现一个 K- V 小型存储数据库，不过没有详细的讲解教程，你们可以根据文档把项目运行起来，之后去研究怎么实现。

**Title** : Skiplist-CPP

**Description** : A tiny KV storage based on skiplist written in C++ language

一个使用 C++ 编程实现的基于跳表的轻量级键值型数据库。

提供的功能接口主要有

- insertElement
- deleteElement
- searchElement
- displayList
- dumpFile
- loadFile
- size

1、主要是 WebServer 烂大街了，我感觉是个 C++党的简历上必有 WebServer 服务器，太千篇一律了。

2、该项目是与 Redis 中的跳表联系在一起，如果在面试中面试官谈起你的项目，很容易就会把话题扯到跳表上，进而跟 Redis 搭上线，而 Redis 数据库可以说是 后端开发必问的一个知识点了。

所以，做这个项目相当于是提前给面试官挖了一个坑，就等着他跳进去。他要是借由跳表问起 Redis，你就可以侃侃而谈了~

不过也需要注意，不要自己给自己挖坑，做这个项目的前提就是对于 Redis的常见知识点有所掌握，比如`五种数据结构`、`底层模型`、`缓存击穿`、`缓存雪崩`之类。

千万不要自己对 Redis 一窍不通，还在简历上写了这个项目，那可真是自己给自己挖坑，小丑竟是我自己了。

前置知识：学过 C++，对象，模版，了解跳表原理
GitHub 地址：https://github.com/youngyangyang04/Skiplist-CPP

## =========

## libhv：跨平台的具有非阻塞I/O和计时器的异步事件驱动库

**项目简介：**`libhv`类似于`libevent`、`libev`和`libuv`，是一个跨平台的具有非阻塞I/O和计时器的异步事件驱动库，但`libhv`提供了更加简单易用的API接口并支持更加丰富的网络协议，基于它可以快速驱动HTTP服务端和客户端，从而提供高性能的`http`服务。

**主要技术点或特性：** 跨平台、事件循环、非阻塞I/O、支持IPv6、使用OpenSSL、支持多种网络协议

**对于我们的作用：** 可以帮助我们理解和实践**操作系统**的相关知识

**项目源码地址：**`https://github.com/ithewei/libhv`

## =========

## 实现一个多线程网络服务器

这是某个大四的学生学习网络编程所写的，直接搬运 readme 的介绍吧

本项目为C++11编写的基于epoll的多线程网络服务器框架，应用层实现了简单的HTTP服务器HttpServer和一个回显服务器EchoServer，其中HTTP服务器实现了HTTP的解析和Get方法请求，目前支持静态资源访问，支持HTTP长连接；该框架不限于这两类服务器，用户可根据需要编写应用层服务。

通过该项目你可以了解到部分 `C++11` 的语法和编码规范、学习巩固网络编程、网络 `IO` 模型、多线程、`git` 使用、`Linux`命令、性能分析、`TCP/IP、HTTP`协议等知识

地址：https://github.com/chenshuaihao/NetServer

## =========

## 烂大街的HTTP服务器

这个项目似乎成了Linux C/C++技术栈人手一个的项目了？

虽然这个项目烂大街了，看着也挺简单的，不过能玩的花样还是不少的。比如加入代理功能、添加支持 `CGI` 功能或者加入日志记录等。它越简单，你可以做的改进就越多，在面试的时候，你就可以跟面试官聊你的改进和你添加的功能，面试官是很愿意看到你的自己在做一个项目时的思考和改进的。偷偷跟你说，这种改进很加面试分的。

这里我推荐牛客大佬健康成长天线宝宝啊的 HTTP服务器，这位大佬现在在阿里云做平台开发。他在牛客上写的 `C++` 求职/基础架构路线文章非常不错，想要走 `C++` 路线的同学推荐你们去牛客看看他的帖子。

> 健康成长天线宝宝啊个人主页：https://www.nowcoder.com/ profile /2765647?noredirect=true
>
> 健康成长天线宝宝啊服务器项目`github`链接：https://github.com/linyacool/WebServer

## =========

##  CppNet：封装在 TCP 协议上的 Proactor 模式 multi-thread 网络库

**项目简介：** CppNet一个封装在 TCP 协议上的 Proactor 模式 multi-thread 网络库。包含 OS 接口调用、回调处理、定时器、缓存管理等，这里有从操作系统到应用层的所有网络细节，便于初学者学习和实践。

- 简单：只导出了最少量的接口，其声明都类似系统 socket API。对客户端而言，只新增了一个 buffer 类型
- 快速：采用性能最优的 epoll 和 IOCP 做事件驱动。每个连接都独享一个内存池，从内存池中申请的内存都由智能指针管理
- 清晰：结构上分为事件驱动，会话管理，接口三层，通过回调向上通知。模块之间职责分工明确，最大的类不超过 500 行代码

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRHlcW4ZBVic3u8CBpAOp0xgtdNe1d7ibUvt2j8g2C7sFiaFRpyJe5s8tng/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**项目源码：**https://github.com/caozhiyi/CppNet

## =========

##  muduo：基于Boost库实现的现代C++高并发网络库

**项目简介：** muduo是一个基于Boost库实现的现代C++高并发网络库，由陈硕大神编写。它一个高质量的事件驱动型的网络库，其核心代码不超过4500行，使用 `non-blocking IO(IO multiplexing)` + `one loop per thread`模型，适合开发 Linux 下的多线程服务端应用程序，通过阅读源码还可学习到 C++ 语言、Linux 网络编程等后端知识。

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRJAyhLZ3EPg76qefSgUnG2aXSZdn5712ZLBBODL095zSQxtQtkP6MjA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**项目源码：**https://github.com/chenshuo/muduo

## =========

## RocksDB：用于闪存和RAM存储的持久键值存储

RocksDB由Facebook数据库工程团队开发和维护。 它建立在Sanjay Ghemawat（sanjay@google.com）在LevelDB上的早期工作之上。 和杰夫·迪恩（jeff@google.com)

此代码是一个库，它构成了快速的核心构建块 键值服务器，特别适合在闪存驱动器上存储数据。 它具有日志结构合并数据库 （LSM） 设计，具有灵活的权衡 在写入放大因子 （WAF）、读取放大因子 （RAF） 之间 和空间放大因子（SAF）。它具有多线程压缩， 使其特别适合在 单一数据库。

从此处的示例用法开始：https://github.com/facebook/rocksdb/tree/main/examples

请参阅 github wiki 了解更多解释。

公共接口位于 中。呼叫者不应包含或 依赖此包中任何其他头文件的详细信息。那些 内部 API 可能会更改，恕不另行警告。include/

欢迎在 RocksDB Developers Public Facebook 群组和 Google Groups 上的电子邮件列表中提出问题和讨论。

地址：https://github.com/facebook/rocksdb

## =========

## 牛客网:Linux高并发服务器开发

今天这个 C++ 项目是视频版的，之前是付费的，价格好几百，但是最近牛客网开放成免费了，而且前置知识也讲的很详细，总时长 40 个小时，非常适合新手，项目是带大家写一个 Linux 高并发服务器，帅友们可以白嫖学一波。

百度云版本的我一直找不到，大家直接在网页这里学吧：C  高薪面试项目_牛客网

总结：这个项目在于学基础知识以及运用，适合新手，不适合进阶。

大家直接在网页白嫖学就行，如果牛客网的小姐姐向你推荐其他付费的课程，你们可以不理，毕竟开放成免费的，肯定有目的，大概率就是为了引流勒。

地址：https://www.nowcoder.com/courses/cover/live/504
![image](https://user-images.githubusercontent.com/92212984/230613942-3d919e21-6b7f-48a1-92cf-afdf1dd9efee.png)

## =========

## WinMerge：一个免费开源的文件对比神器(C++)

WinMerge 是一款 Windows 系统下的免费开源的文件比较/合并工具，它可以比较两个文件夹和文件，以一种易于理解和处理的可视文本格式呈现差异。



地址：https://github.com/WinMerge/winmerge

## =========

## tmux：终端复用软件

**项目简介：** tmux一个炫酷的终端复用软件，它提供了一个非常易于使用的命令行界面，可横向和纵向分割窗口，窗格可以自由移动和调整大小，而且还可以通过交互式菜单来选择窗口、会话及客户端。类似的终端复用器还有 GNU Screen。Tmux 与它功能相似，但是更易用，也更强大。大名鼎鼎的阮一峰老师还写过tmux的使用教程，大家也可以看一看。

它的命令行界面非常炫酷易用，支持自由分割窗口，并且可以自由移动和调整，灵活且强大。一个非常强大的使用场景是：当远程连接到服务器使用时，只需要启动`tmux`，利用它就可以方便地进行后续操作，而无需打开多个ssh控制台窗口。

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRwM4ujOia7IIzpK1paChO0Npwhmel5wDAAicBptNvjRh1r77w4G1XZ52w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**对于我们的作用：** 既是一个高效的工具，研究源码也可以帮助我们学习和理解Linux环境实战编程。

**项目源码：**https://github.com/tmux/tmux

## =========

## netdata：系统监控工具

**项目简介：** netdata是一款开源免费的炫酷Linux系统实时性能和运行状况的系统监控工具。netdata通过使用可交互的仪表盘形式，来提供灵活易用的系统监控。除了支持常见系统平台的安装之外，它还可以非常方便地安装于Docker容器和集群之中并提供监控服务。

![图片](https://mmbiz.qpic.cn/mmbiz_png/vdXWcmzIVZHLHAMfKL4cOY9b60vaeckmjagicIHRLwq6NYiaV7aNzykAXjHAoG7rnzKibVUDniaeCAjDiaZaw8UWPkg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**对于我们的作用：** 既是一个高效的工具，研究其源码也可以帮助我们学习和理解Linux环境实战编程。

**项目源码地址：** `https://github.com/netdata/netdata`

## =========

## musikcube：音乐播放器

**项目简介：** musikcube是一个使用C ++编写的跨平台，运行于终端上的音乐播放器。musikcube可以在Windows，macos和linux上轻松编译和运行。它也可以在带有raspbian的树莓派上很好地运行，并且可以设置为流音频服务器。炫酷得一腿。

![图片](https://mmbiz.qpic.cn/mmbiz_png/xq9PqibkVAzotWUYMzMur1y8X3kPrJxyRAN7tN0Wbb0EL5XG6Ric63ABdCIicibGl9cvZ47o5fEAP5Mpb3cemSzd3w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**项目源码：**https://github.com/clangen/musikcube

## =========

## C++并行计算和异步网络引擎

作为搜狗C++服务器引擎，搜狗C++工作流几乎支持搜狗所有的后端C++在线服务，包括所有搜索服务、云输入法、在线广告等，每天处理超过10亿次请求。这是一个企业级编程引擎，设计轻巧优雅，可以满足大多数C++后端开发需求。

地址：https://github.com/sogou/workflow

## =========

## SRPC:企业级RPC系统(C++)

SRPC是全搜狗业务线上使用的企业级RPC系统，目前每天承载上百亿的请求量，涵盖搜广推及其他类型业务。

SRPC学习系列2 ：一次RPC请求过程 - 1412的文章 - 知乎
https://zhuanlan.zhihu.com/p/619721187

配套:srpc小工具

一个帮你快速生成Workflow和SRPC项目的脚手架小工具。

地址：https://github.com/sogou/srpc

## =========

## OpenCV: Open Source Computer Vision Library(开源计算机视觉库C++)

-- 首页： https://opencv.org
--- 课程： https://opencv.org/courses

- 文档：https://docs.opencv.org/4.x/
- 问答论坛：https://forum.opencv.org
  -- 上一届论坛（只读）： http://answers.opencv.org
- 问题跟踪：https://github.com/opencv/opencv/issues
- 其他 OpenCV 功能：https://github.com/opencv/opencv_contrib

地址：https://github.com/opencv/opencv

## =========

## tinyrenderer:一个简短的计算机图形/渲染课程(C++)

从零开始构建光栅器
Tiny Renderer 或 OpenGL 的工作原理：500 行代码中的软件渲染

- 知乎学习笔记:从零构建光栅器，tinyrenderer笔记（上） - Shawoxo的文章 - 知乎
  https://zhuanlan.zhihu.com/p/399056546
- [「十天自制软渲染器」](https://supercodepower.com/docs/toy-renderer/index)

地址：https://github.com/opencv/opencv

前置知识:推荐看完GAMES101有一定基础再跟着做一遍，有更好的理解~
图形学入门课程我只推荐一个，闫令琪大神的[《GAMES101-现代计算机图形学入门》](https://www.bilibili.com/video/BV1X7411F744?from=search&seid=13888633704437789145)。

## =========

## 从0开始手把手教你做的服务器框架

说实话，这个算是比较难的`C++`项目了，是我在`B`站发现的，我看了底下的评论，相当不错。是一个C++ 高性能分布式服务器框架 的项目，我确认过了，是新手不要尝试的那种难度。

该项目主要有 13 大模块组成，分别是日志模块、配置模块、线程模块、协程模块、协程调度模块、`IO` 协程调度模块、`Hook` 模块、`Socket` 模块、`ByteArray` 序列化模块、`TcpServer`模块、`Stream` 模块、`HTTP` 模块、`Servlet` 模块。

> B站视频教程：https://www.bilibili.com/ video /av53602631?from= search &seid=9029288577396826503
>
> 服务器框架`github`链接：https://github.com/sylar-yin/sylar

## =========

## 做个操作系统内核

《深入理解计算机系统》这本书大家应该都听说过吧，这本书被誉为“跟金子一样珍贵的计算机基础书籍”，如果你还没看过，赶快去买一本补补功课。

其中这本书中的一些`lab` 很是不错，你完全可以实现其中的一个小 `lab` 来作为自己的 C++』 项目的。而且这本书也是美国麻省理工学院的推荐的计算机书籍之一，课后的一些`lab` 也会布置给上课的学生。

想一下，面试官问你的项目背景是什么的时候，你直接告诉他“这是美国麻省理工学院的计算机专业学生的结课大作业”，**没有分量吗？不能装逼吗？**

建议先看一下 `B` 站 MIT 6.828 视频，再去实践。

> 《深入理解计算机系统》课后`lab`作业`github`链接链接： https://github.com/woai3c/MIT6.828

## =========

## 几点说明

GitHub 上其实有很多项目，大家也可以自己去找哦，不过很多项目都是没有详细教程的，就是只有源码和教你如何运行，所以我给星球的帅友们找了两个至少有一些教程说明的（第一和第二个），没有做过项目的新手可以先跟着教程说，导入源码运行。

之后呢，就得学会适应没有教程的项目，你可以导入代码，运行，通过代码来研究，改造，其实你以后去工作，也是这样的，导入代码运行起来，然后自己通过业务去熟悉代码。

![c9bcc156a3ff75a63c3f9f6d01061f20](https://user-images.githubusercontent.com/92212984/230620293-0cc5e4f0-8308-449d-bac9-8d7afb745736.jpg)
