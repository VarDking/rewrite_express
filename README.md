**渐进式Express源码学习| 小白也能懂源码**

这个系列教程的目的是用一种**渐进式**的方式，**帮助Node/Javascript工程师更快更容易得理解Express工作机制**。 所谓的渐进式，就是从最简单的web服务器，一步一步添枝加叶，最后形成一个完整Express的过程。

### 缘起

接触Express已有两年多时间，也面试了很多Node工程师。我发现很多工程师会用Express，但是不知道Express如何工作，稍微深入一点的面试问题就答不上来，例如：

- 严格路由和不严格路由有什么区别
- 如何设置路由不敏感或严格路由
- 什么是lazy router以及为什么要lazy router
- trust proxy什么用
- Etag weak 和strong有什么区别
- app.all和app.use的区别及性能差异
- 如何捕捉next(err)传递的错误
- 路由function内部的错误是在哪个环节捕捉的

说到底，是知其然，不知其所以然。而读源码，是解决这个问题的最好方法。
但是大家普遍面临一个源码阅读时间成本高的问题。**而我想做的，是通过一种创新的方式，讲解Express工作原理和实现。**

### 如何讲解
我会从最基础的http模块开始，一步一步得实现一个Express。这样做的好处
1. 从最简单的出发，基础小白也能看懂
2. 循序渐进，不会迷失在复杂的代码中
3. 非常清晰得知道每一段代码添加的缘由

### 文章组织
会分成系列文章讲解，每个文章都基于上一个文章实现一个加强版的Web框架。每个文章会给出框架源码、框架说明，框架使用样例。话不多少，开始第一个Web框架的实现吧！

**文章目录**

1. [1_express](https://github.com/WenNingZhang/rewrite_express/tree/master/1_express)
1. [2_express](https://github.com/WenNingZhang/rewrite_express/tree/master/2_express)
1. [3_express](https://github.com/WenNingZhang/rewrite_express/tree/master/3_express)

