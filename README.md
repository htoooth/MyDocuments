# MPI资料库
有关MPI的资料我都会在这里汇总。其中文件夹`libraries`中是收集的一些使用mpi的库，学习它们的用法。

## 库的学习说明

### ltsmin 学习
该库在`libraries`，中有一个有关mpi的事件机制的循环，可以学习。

### [casablance](http://casablanca.codeplex.com/)
该库中有一个线程实现库叫`pplx`，跨平台实现，可以参考API的设计

### [theron](http://www.theron-library.com/index.php)
该库有设计并行的实现

### [caf](http://actor-framework.org/)
该库有设计actor的实现

### [actorlite](http://www.cnblogs.com/JeffreyZhao/archive/2009/05/11/a-simple-actor-model-implementation.html)
老赵的博客中有讲actor的设计，可以借签。

### [libprocess](https://github.com/3rdparty/libprocess)
process之间的actor风格的库

### [SObjectizer](http://sourceforge.net/projects/sobjectizer/)
he SObjectizer is a framework for agent-oriented programming in C++.

### [actor-cpp](https://code.google.com/p/actor-cpp/source/checkout)
An implementation of the actor model for C++.

### [libactor](https://code.google.com/p/libactor/)
Actor Model Library for C.

### [Channel](http://channel.sourceforge.net/)
Name Space Based C++ Framework For Asynchronous, Distributed Message Passing and Event Dispatching.

### [Go-style Channel in C++](http://st.xorian.net/blog/2012/08/go-style-channel-in-c/)

### [C++CSP2](http://www.cs.kent.ac.uk/projects/ofa/c++csp/)
Easy Concurrency for C++.

### [concurrencykit](https://github.com/concurrencykit/ck)

### [libconcurrency](https://code.google.com/p/libconcurrency/)

### [libtask](http://swtch.com/libtask/)

### [Akka](http://www.iteblog.com/archives/1156)
java akka的actor学习

### [state-threads](https://github.com/winlinvip/state-threads)
线程级的库实现

### [chan](https://github.com/tylertreat/chan)
纯c实现在channel库

### [libcoro](http://software.schmorp.de/pkg/libcoro.html)
一个并发库

### [libev](http://software.schmorp.de/pkg/libev.html)
一个事件库

### [mapreduce c++](http://craighenderson.co.uk/papers/software_scalability_mapreduce/library)

### [jansson](http://www.digip.org/jansson/)

## 消息库

### [nanomsg](https://github.com/nanomsg)

### [capnproto](http://kentonv.github.io/capnproto/cxxrpc.html)

## 日志库

### [zlog](http://hardysimpson.github.io/zlog/)

## 工具类库
* [tbox](https://github.com/waruqi/tbox)，一个工具库类包括常用东西
* [sundial](https://github.com/guiquanz/sundial)，常用数据结构
* [tap](https://github.com/zorgnax/libtap)，测试类库

## 一些c++ 文章
 
* [The Auto Macro: A Clean Approach to C++ Error Handling](http://blog.memsql.com/c-error-handling-with-auto/)
* [C++ resources](https://cpp.zeef.com/faraz.fallahi)
* [并发与并行](http://www.blogjava.net/killme2008/archive/2010/03/23/316273.html)
* [熟悉GO了解它的并发](https://www.zybuluo.com/Gestapo/note/32082)
* [编译器](http://mikespook.com/2014/05/%E7%BF%BB%E8%AF%91%E7%BC%96%E8%AF%91%E5%99%A81-%E4%BD%BF%E7%94%A8-go-%E5%BC%80%E5%8F%91%E7%BC%96%E8%AF%91%E5%99%A8%E7%9A%84%E4%BB%8B%E7%BB%8D/)
* [c hard way](http://c.learncodethehardway.org/book/)
* [ruby hard way](http://lrthw.github.io/ex01/)
* [glog使用](http://www.outsky.org/article.php?id=12)


## 自己的库想法
目前有四种想法：

1. 构建一个可靠的消息队列库
2. 利用消息队列库，实现多进程的合作

* 基于scala的actor
* 基结go的channel
* 基于react的，也就是基于事件
* geaman队列系统
* 嵌入脚本，融合lua或者newlisp。

