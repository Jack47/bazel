# [Bazel](http://bazel.io) ([Alpha](http://bazel.io/docs/roadmap.html#alpha))

*{Fast, Correct} - Choose two*


Bazel是一个快速可靠构建代码的构建工具。Google的大部分软件都是Bazel构建的，设计Bazel就是用来解决目前Google开发环境中的构建问题的，问题包括：

* **巨大的，共享代码的源，所有软件都是从源码构建的** Bazel的设计目标就是快速，我们使用缓存和并行来达到这个目的。Bazel对于Google随着公司的发展壮大而持续规模化公司的软件开发实践，具有重要意义。

* **强调自动化构建和发布** Bazel是正确的，可重现[reproducibility]的，意味者在持续构建的机器上或者发布管道里面产生的构建结果和开发人员机器上的构建结果在二进制级别上是一模一样的。

* **支持多种语言和平台** Bazel's architecture is general enough to
support many different programming languages within Google, and can be
used to build both client and server software targeting multiple
architectures from the same underlying codebase.

Find more background about Bazel in our [FAQ](docs/FAQ.md)

Bazel的架构足够通用，可以支持Google内部使用的多种语言，可以在相同的代码库里构建出多个平台的客户端和服务器端的程序。

在[经常被问到的问题](docs/FAQ_zh_cn.md)里可以找到关于Bazel的更多背景知识
## Getting Started

  * How to [install Bazel](http://bazel.io/docs/install.html)
  * How to [get started using Bazel](http://bazel.io/docs/getting-started.html)
  * The Bazel command line is documented in the  [user manual](http://bazel.io/docs/bazel-user-manual.html)
  * The rule reference documentation is in the [build encyclopedia](http://bazel.io/docs/build-encyclopedia.html)
  * How to [use the query command](http://bazel.io/docs/query.html)
  * How to [extend Bazel](http://bazel.io/docs/skylark/index.html)
  * The test environment is described in the [test encyclopedia](http://bazel.io/docs/test-encyclopedia.html)

* About the Bazel project:

  * How to [contribute to Bazel](http://bazel.io/docs/contributing.html)
  * Our [governance plan](http://bazel.io/docs/governance.html)
  * Future plans are in the [roadmap](http://bazel.io/docs/roadmap.html)
  * For each feature, which level of [support](http://bazel.io/docs/support.html) to expect.

## 开始使用

  * 如何 [安装 Bazel](http://bazel.io/docs/install.html)
  * 如何 [开始使用 Bazel](docs/getting-started-zh-cn.html)
  * 在[用户手册](docs/bazel-user-manual-zh-cn.html)中记录了Bazel命令行的使用方法
  * The rule reference documentation is in the [build encyclopedia](http://bazel.io/docs/build-encyclopedia.html)
  * 规则[rule]引用的文档在[构建百科全书](docs/build-encyclopedia-zh-cn.html)  
  * 如何 [使用查询命令](docs/query-zh-cn.html)
  * 如何 [扩展 Bazel](docs/skylark/index-zh-cn.html)
  * 测试环境的介绍在[测试百科全书](docs/test-encyclopedia-zh-cn.html)

* 关于Bazel 项目:

  * 如何[给Bazel做贡献](docs/contributing-zh-cn.html)
  * 我们的[治理计划](docs/governance-zh-cn.html)
  * [路线图]中的未来计划(docs/roadmap-zh-cn.html)
  * For each feature, which level of [support](http://bazel.io/docs/support.html) to expect.
