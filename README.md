# Golang从入门到跑路
<p align="center">
<a href="https://github.com/jiujuan/go-collection" target="_blank">
	<img src="./images/go-collection-logo-345x345.png" width="250" height="250" board="0"/>
</a>
</p>

[![gostudy](https://img.shields.io/badge/golang-study-orange)](https://github.com/jiujuan/go-collection#目录)
[![GitHub stars](https://img.shields.io/github/stars/jiujuan/go-collection)](https://github.com/jiujuan/go-collection/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/jiujuan/go-collection)](https://github.com/jiujuan/go-collection/network/members)
[![GitHub issues](https://img.shields.io/github/issues/jiujuan/go-collection)](https://github.com/jiujuan/go-collection/issues)


> 收录的awesome-go项目，学习基础系列，go项目实战，go源码分析，go开发者成长路线图等等，把他们收集起来一起学习，相当于给写 Go 程序一个动手路线图。

:speaker: 觉得对您学习golang有帮助，请给我点一个 Star！ :star:


:mega: :mega: :mega:

- :pencil2: 如果有的链接失效了，可以给我发[issues](https://github.com/jiujuan/go-collection/issues)，灰常感谢！

- :memo: 如果您觉得有好的golang教程、源码分析文章、书籍等等，都可以给我发[issues](https://github.com/jiujuan/go-collection/issues)，灰常感谢！
- :star: 基础部分和项目实战部分一定要打开编辑器，**动手写代码**【**动手**】，要一个字母一个字母敲出来，这样练习才会对学习 Go 基础有一定效果！

## 目录

- [awesome-go list](#awesome-go-list)
- [awesome-go存储项目](#go存储项目)
- [go基础学习系列](#go基础学习系列)
- [go标准库](#go标准库)
- [go项目实战](#go项目实战)
- [go架构和源码分析](#go架构和源码分析)
- [微服务](#微服务)
  - [nitro(原go-micro)](#nitro)
  - [go-kit](#go-kit)
 
  - [go-zero](#go-zero)
  - [kratos](#kratos)
  - [go-chassis](#go-chassis)
  - [Jupiter](#jupiter)
  - [TarsGo](#tarsgo)
  - [Stack-Labs](#Stack-Labs)
  
  - [odin](#odin)
- [rpc](#rpc)
- [Go书籍](#Go书籍)
- [pprof](#pprof)
- [常见问题和错误](#常见问题和错误)
- [Go日报周刊](#Go日报周刊)
- [Go交流社区](#Go交流社区)
- [其他](#其他)


- [Go开发者成长路线图](./golang/golang-developer-roadmap.md)
- [go社区知识图谱](./golang/golang-knowledge-graph.md)

## awesome-go list

- [awesome-go 网站](https://awesome-go.com/)   收集很多go的项目，并进行了详细分类
- [awesome-go github地址](https://github.com/avelino/awesome-Go) awesome-go.com的github源码地址
- [awesome-go 中文翻译1](https://github.com/jobbole/awesome-go-cn)
- [awesome-go 中文翻译2](https://github.com/yinggaozhen/awesome-go-cn)
- [awesome-go 一个更精细化项目](https://github.com/hackstoic/golang-open-source-projects) awesome-go的一个精细化项目，介绍更详细。本项目作为awesome-go的一个扩展
- [gopher reading list](https://github.com/enocom/gopher-reading-list)


## go存储项目

- [awesome-go-storage](https://github.com/gostor/awesome-go-storage) 开源的Go存储项目
- [开源存储项目相关速查表](https://www.ctolib.com/cheatsheets-awesome-go-storage.html) 根据右边目标可以快速查找



## go基础学习系列

- [go语言快速入门](https://github.com/jaywcjlove/golang-tutorial)
- [go tour](https://tour.golang.org/welcome/1)
  - [go tour 中文版](https://tour.go-zh.org/welcome/1)
- [Go by Example](https://gobyexample.com/)
- [Go基础编程-by无闻](https://github.com/Unknwon/go-fundamental-programming)
- [Go语言实战笔记](https://github.com/rujews/go-in-action-notes)
- [golang bootcamp](http://www.golangbootcamp.com/book)
- [study Go programming language](https://tutorialedge.net/course/golang/) 
- [golang cheatsheet](https://github.com/a8m/golang-cheat-sheet)
- [common mistakes in golang](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) go初学者经常犯的错误
- [Learn Go with test-driven development](https://github.com/quii/learn-go-with-tests)  
  - [gitbook版](https://quii.gitbook.io/learn-go-with-tests) 
  - [中文版](https://studygolang.gitbook.io/learn-go-with-tests)
- [golang program](http://www.golangprograms.com)
- [golang 项目实战简明指南](http://litang.me/post/golang-project-guide/)
- [go语言基础学习](https://www.bookstack.cn/read/golang_development_notes/2%E8%AF%AD%E8%A8%80%E5%9F%BA%E7%A1%80.md)
- [go语言高级特性学习](https://www.bookstack.cn/read/golang_development_notes/ch9.md)
- [go web开发教程](https://github.com/bonfy/go-mega)
- [聚合多套golang教程](https://hackr.io/tutorials/learn-golang)
- [go命令教程](https://github.com/hyper0x/go_command_tutorial)
- [go exmaples](https://github.com/yakuter/go-interfaces)

- [Go 综合学习demo](https://github.com/pibigstar/go-demo) 入门到进阶，基础库使用、设计模式、工具类、对接第三方等等


## go标准库
- [golang pkg](https://golang.org/pkg/)
  - [中文版](http://cngolib.com/)
- [go标准库学习](https://books.studygolang.com/The-Golang-Standard-Library-by-Example/) 
- [go语言标准包解析](https://syaning.github.io/go-pkgs/)
  
## go项目实战

- [go小项目实战系列](https://www.jianshu.com/nb/40576814)
- [gin框架实战系列](https://youngxhui.top/categories/gin/)
  - [github代码地址](https://github.com/youngxhui/GinHello)
- [beego框架开发轻博客实战系列](https://www.jianshu.com/nb/27703855)
- [golang爬虫视频课程](https://www.bilibili.com/video/av31551627/)
- [go web开发例子](https://gowebexamples.com/)
- [使用gin和gorm框架来构建 RESTful API 微服务 en](https://medium.com/@thedevsaddam/build-restful-api-service-in-golang-using-gin-gonic-framework-85b1a6e176f3) 
  - [中文翻译版](https://learnku.com/golang/t/24598)
- [go语言高级实战](https://github.com/Shitaibin/golang_step_by_step)
- [go 语言论坛实战](https://xueyuanjun.com/post/21519)
- [beego web应用开发](https://blog.csdn.net/u010986776/category_10520963.html)
- [企业级的 Go 语言实战项目](https://github.com/marmotedu/iam)

## go架构和源码分析

- [雨痕Go语言学习笔记](https://github.com/qyuhen/book)
- [go-under-the-hood--欧长坤](https://github.com/changkun/go-under-the-hood/)
  - [网站阅读版](https://changkun.de/golang/)
- [Go 语言设计与实现 - 面向信仰编程](https://draveness.me/golang/)

- [源码分析 1-曹大&柴大](https://github.com/cch123/golang-notes) 主要是源码分析，可能也会有一些使用上的知识点
- [源码分析 2](https://github.com/xuesongbj/Go-Notes) go源码剖析
- [源码分析 3](https://zhuanlan.zhihu.com/c_1010470599088594944)  [二](https://zhuanlan.zhihu.com/golang-internal) 
- [golang数据结构内部实现](https://zhuanlan.zhihu.com/goroutine)
- [从Questions学习Go](https://github.com/qcrao/Go-Questions/wiki)
- 深度解密系列-码农桃花源： [slice](https://www.cnblogs.com/qcrao-2018/p/10631989.html)、[interface](https://www.cnblogs.com/qcrao-2018/p/10766091.html)、[reflection](https://www.cnblogs.com/qcrao-2018/p/10822655.html)、[map](https://www.cnblogs.com/qcrao-2018/p/10903807.html)、[context](https://www.cnblogs.com/qcrao-2018/p/11007503.html)、[unsafe](https://www.cnblogs.com/qcrao-2018/p/10964692.html)、[channel](https://www.cnblogs.com/qcrao-2018/p/11220651.html)、[scheduler](https://www.cnblogs.com/qcrao-2018/p/11442998.html)、[defer](https://www.cnblogs.com/qcrao-2018/p/10367346.html)、[memory](https://www.cnblogs.com/qcrao-2018/p/10520785.html)、[sync.Pool](https://www.cnblogs.com/qcrao-2018/p/12736031.html)、[sync.map](https://www.cnblogs.com/qcrao-2018/p/12833787.html)
- 深度解析GPM系列-码农桃花源：[1. GPM 是什么](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/gpm-shi-shi-mo)、[2. 什么是 go schedule](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/shi-mo-shi-go-shceduler)、[3. 什么是 M:N 模型](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/shi-mo-shi-mn-mo-xing)、[4. 什么是 workstealing](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/shi-mo-shi-workstealing)、[5. Schedule 的初始化过程](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/miao-shu-scheduler-de-chu-shi-hua-guo-cheng)、[6. Schedule 循环如何启动](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/schedule-xun-huan-ru-he-qi-dong)、[7. Schedule 循环如何运转](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/schedule-xun-huan-ru-he-yun-zhuan)、[8. goroutine 和线程的区别](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/goroutine-he-xian-cheng-de-qu-bie)、[9. main goroutine 如何创建](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/mian-gorutine-ru-he-chuang-jian)、[10. g0 栈和用户栈如何切换](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/g0-zhan-he-yong-hu-zhan-ru-he-qie-huan)、[11. goroutine 调度时机有哪些](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/goroutine-tiao-du-shi-ji-you-na-xie)、[12. M 如何找工作](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/m-ru-he-zhao-gong-zuo)、[13. sysmon 后台监控线程做了什么](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/sysmon-hou-tai-jian-kong-xian-cheng-zuo-le-shi-mo)、[14. goroutine 如何退出](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/goroutine-ru-he-tui-chu)、[15. 一个调度相关的陷阱](https://qcrao91.gitbook.io/go/goroutine-tiao-du-qi/yi-ge-tiao-du-xiang-guan-de-xian-jing)

- [go 程序是怎么跑起来的?](https://www.cnblogs.com/qcrao-2018/p/11124360.html)
  

## 微服务

## nitro
> 原 go-micro 项目变更为 asim 的个人项目，名字改为 [nitro](https://github.com/asim/nitro)。

- [nitro(原go-micro)](https://github.com/asim/nitro)
- [nitro site](https://gonitro.dev/)

- [micro](https://github.com/micro/micro)
- [Learn Micro by examples](https://github.com/micro/examples)
- [microhq](https://medium.com/microhq)

## go-kit

- [go-kit](https://github.com/go-kit/kit)
- [go-kit系列教程](https://juejin.im/post/5c861c93f265da2de7138615)
- [go-kit与grpc结合开发微服务](http://www.articlechain.cn/post/46.html)

## go-zero
- [go-zero github](https://github.com/zeromicro/go-zero)
- [go-zero doc文档](https://go-zero.dev/cn/)

## kratos
- [kratos](https://github.com/go-kratos/kratos) bilibili开源的一套微服务框架
  - [go-kratos](https://github.com/go-kratos)
- [kratos 官网](https://go-kratos.dev/)
  - [kratos doc文档](https://go-kratos.dev/docs/)

## go-chassis
- [go-chassis](https://github.com/go-chassis/go-chassis)
- [go-chassis doc](https://go-chassis.readthedocs.io/en/latest/)

## Jupiter
- [Jupiter](https://github.com/douyu/jupiter) 斗鱼开源的面向服务治理的Golang微服务框架
- [官网](http://jupiter.douyu.com/)

## TarsGo
- [TarsGo](https://github.com/TarsCloud/TarsGo) TarsGo go的微服务框架
- [TarsCloud](https://github.com/TarsCloud) 
- [tarscloud官网](https://tarscloud.org/) tarscloud 官网
- [TarsFramework](https://github.com/TarsCloud/TarsFramework)

## Stack-Labs
> 由于 go-micro 停更，中国团队基于 go-micro 1.18修改，开发了第一版 stack-rpc。该项目于 2020 年 11 月 2 日正式成立。[github](https://github.com/stack-labs/stack-rpc)

- [Stack Labs](https://github.com/stack-labs)
- [stack-rpc](https://github.com/stack-labs/stack-rpc)
- [Micro-blog](https://medium.com/microhq)

- [Stack Labs site](https://microhq.cn/index-cn)
- [stack-rpc-tutorials](https://github.com/stack-labs/stack-rpc-tutorials)
- [stack-rpc Docs](https://microhq.cn/docs/micro/introduce-cn) 

## gizmo
- [gizmo](https://github.com/nytimes/gizmo) nytimes
## odin
- [odin](https://github.com/tal-tech/odin)
- [doc](https://www.yuque.com/tal-tech/odin/readme)

## rpc
- [gRPC-go](https://github.com/grpc/grpc-go)
  - [grpc](https://github.com/grpc/)
- [rpcx](https://github.com/smallnest/rpcx)
  - [website](https://rpcx.io/)

## Go书籍
- [go books集合](https://github.com/dariubs/GoBooks)
- [the way to go 中文版](https://github.com/Unknwon/the-way-to-go_ZH_CN)
  - [看云版](https://www.kancloud.cn/kancloud/the-way-to-go/72432)
- [gopl 中文版](https://books.studygolang.com/gopl-zh/) go语言圣经
- [Mastering Go 中文版](https://github.com/hantmac/Mastering_Go_ZH_CN)
  - [gitbook版](https://wskdsgcf.gitbook.io/mastering-go-zh-cn/)
- [Go语言高级编程](https://github.com/chai2010/advanced-go-programming-book/blob/master/SUMMARY.md)
- [Go Web编程](https://github.com/astaxie/build-web-application-with-golang)
- [go实战开发](https://github.com/astaxie/go-best-practice)
- [go语言42章经](https://github.com/ffhelicopter/Go42)
- [go101](https://go101.org/article/101.html)  
  - [go101 github](https://github.com/go101/go101)
  - [中文版](https://github.com/golang101/golang101)
- [go专家编程](https://github.com/RainbowMango/GoExpertProgramming)
- [go under the hood](https://github.com/changkun/go-under-the-hood)
- [Go-Mega](https://go-mega.bonfy.im/)

## pprof
- [go-profiler-notes(DataDog)](https://github.com/DataDog/go-profiler-notes)
- [diagnostics](https://golang.org/doc/diagnostics)

## 常见问题和错误

- [Go 语言中通道死锁经典错误案例详解](https://segmentfault.com/a/1190000022820306)
- [Go 项目开发里最常犯的 10 个错误](https://learnku.com/articles/38669)
- [Go新手可能会踩的50个坑](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/)
  - [翻译版](https://segmentfault.com/a/1190000013739000)

## Go日报周刊
- [gocn每日新闻 一](https://github.com/gocn/news) 
  - [go news 二](https://github.com/Han-Ya-Jun/gocn_news_set)
- [go技术日报](https://studygolang.com/go/godaily)
- [gopherdaily](https://github.com/bigwhite/gopherdaily)
- [go语言爱好者周刊](https://github.com/polaris1119/golangweekly)
- [golang weekly](https://www.golangweekly.com/)

## Go交流社区
- [Go issues](https://github.com/golang/go/issues)
- [GoCN社区](https://gocn.vip/)
- [Go语言中文网](https://studygolang.com/)
- [Golang中国](https://www.golangtc.com/)
- [Go Forum](https://forum.golangbridge.org/)
- [stackoverflow go](https://stackoverflow.com/collectives/go)
- [Golang News](http://golangnews.com/)

## 其他

- [go官网](https://go.dev/)
- [golang doc](https://golang.org/doc/)
- [go工具链](https://www.alexedwards.net/blog/an-overview-of-go-tooling) 
- [go官方语言编码规范](https://github.com/golang/go/wiki/CodeReviewComments) 
- [无闻的go语言编码规范](https://github.com/Unknwon/go-code-convention/blob/master/zh-CN/README.md)
- [high performance go workshop-by dave](https://dave.cheney.net/high-performance-go-workshop/dotgo-paris.html)  
- [go性能优化](https://github.com/dgryski/go-perfbook)  
  - [中文版](https://github.com/dgryski/go-perfbook/blob/master/performance-zh.md)
- [编写可维护 Go 语言代码建议](https://github.com/llitfkitfk/go-best-practice)
- [go各种自学资料总结](https://github.com/overnote/golang)
- [Go夜读](https://github.com/talkgo/night)
- [Go开发关键技术指南](https://github.com/ossrs/srs/wiki/GoDevGuide)
- [go每日一库](https://github.com/darjun/go-daily-lib)
- [go-advice](https://github.com/cristaloleg/go-advice)
  
- [golang-design](https://github.com/golang-design) changkun 大大最新开源的golang相关项目
  - [golang-design site](https://golang.design/)

- [topgoer地鼠文档](https://www.topgoer.com/) 一个很全的 Go 学习系列
- [topgoer地鼠文档2](https://www.topgoer.cn/) 各种Go相关学习资料
  
- [List of Golang books](https://github.com/dariubs/GoBooks)

- [Golang 导航](https://hao.studygolang.com/)

- [Go 分布式事务框架 dtf](https://github.com/dtm-labs/dtf)

- [测试工具 k6](https://github.com/grafana/k6)

- [GoCN Translator Team 翻译的文章](https://github.com/gocn/translator)
- [GCTT](https://github.com/studygolang/gctt)

- [Go wiki](https://github.com/golang/go/wiki)
 
[返回目录](#目录)
