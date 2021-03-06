---
Learn enough tech to be dangerous
---

# 学习一下

持续维护一个学习列表，希望能够收集到各个领域最好的教材和课程，尽可能推荐自己读过的，或者了解到非常好的书和课程。

- P.S 其实各个方向的书，在知乎上搜一搜都会有比较好的推荐。

## 一、计算机本科学习

### 1.计算机组成原理

* 《计算机组成与设计: 软硬件接口》相对清晰简单，主要基于Mips
* [《深入理解计算机系统（第2版）》](https://www.amazon.cn/gp/product/B004BJ18KM/ref=as_li_ss_tl?ie=UTF8&camp=536&tag=lucida-23&creativeASIN=B004BJ18KM&linkCode=as2&creative=3132) 又称作 CSAPP 
* **《编码：隐匿在计算机软硬件背后的语言》**

### 2.操作系统

* 《操作系统之哲学原理》
* [《Operating Systems: Three Easy Pieces》](http://pages.cs.wisc.edu/~remzi/OSTEP/), 必读, 神书
* [清华大学操作系统实验课ucore](https://github.com/chyyuu/ucorebook_code)
* **《程序员的自我修养》链接、装载与库**

### 3.面向对象程序设计

#### 设计模式

* 《大话设计模式》很通俗易懂，入门用
* 《设计模式：可复用面向对象软件的基础》
* 《编程珠玑》
* 《复杂软件设计之道》

### 4.编译原理

* 《龙书（Compilers: Principles,Techniques,and Tools）》
* 《虎书（Modern Compiler Implementation in C）》
* 《鲸书（Advanced Compiler Design and Implementation）》
* [llvm](https://github.com/llvm/llvm-project)  现代编译器，拥有非常好的IR--指令中间表示
* [90min-scheme2c](http://community.schemewiki.org/?c=s&key=[[90min-scheme2c]]) 经典教程
* 自己实现一个简单的编译器后，就能够比较好认识到代码具体在进行什么样的行为，其实所谓的语言，只是编译器和解释器的具体定义罢了。后续高级教程更多涉及编译优化，在编译器层面，自动化地去提升代码的性能。
* 《The Little Schemer》
* 《The Reasoned Schemer》
* 《The Little Prover》
* 《Compiling with Continuations》

### 5.计算机网络

* 教材 《计算机网络 谢希仁》，写的一般，只是够用，做了计算机网络实验才能明白书上在说啥。
* 《计算机网络：自顶向下》听说比教材好一些。

### 6.数理基础

#### 高等代数

* 《线性代数就应该这样学》
* 《线性代数及其应用》
*  《[Analysis I : Third Edition](https://link.zhihu.com/?target=https%3A//book.douban.com/subject/26866914/)》

#### 微积分

* 《托马斯微积分》从高中基础开始
* 《普林斯顿微积分读本》
* 菲赫金哥尔茨的微积分教程
* 卓里奇的数学分析
* rudin的数学分析原理

#### 离散数学

* 《离散数学及其应用》
* 《具体数学》这本公式多，有很多在计算机领域的实际应用，比较难啃，需要深入读和做题。

#### 概率统计

* 《概率论与数理统计》陈希孺
* 《初等概率论》钟开莱

#### 最优化

* [数值最优化(Numerical Optimization)](https://link.zhihu.com/?target=http%3A//book.douban.com/subject/2870337/) 
* [数值最优化笔记](https://zhuanlan.zhihu.com/p/53882647)
* 《[Convex Optimization](https://link.zhihu.com/?target=https%3A//book.douban.com/subject/1888111/)》

#### 其他

* 《数学悖论与三次数学危机》讲数学史，围绕数学史上促使数学发展的悖论，讲述为什么我们现在的数学体系是现在这个样子，很推荐作为数学科普读物。
* 《数学女孩》结城浩，有很多有趣的题目，轻松的数学读物，展现数学的美。
* 实分析/实变函数论？

### 7.数据结构

* [清华大学MOOC 邓俊辉老师 《数据结构》](http://www.xuetangx.com/courses/course-v1:TsinghuaX+30240184+sp/about), 很清晰。

### 8.ACM算法竞赛

* 《算法竞赛入门经典 刘汝佳》入门比较适合，不过ACM的代码基本都不工程化，学习到思想就好。
* ACM顶级选手的好玩的事情：https://zhuanlan.zhihu.com/p/139522195 **练习、练习、不断地练习！**
* 题库:
  * Leetcode
  * 洛谷
  * codeforce

### 9.信息安全

> 江湖上仍然流传着他们的传说

可以看一看一些公众号文章入门，https://zhuanlan.zhihu.com/p/39508502， 感受一下技术的美感

* CTF竞赛, 靶场 
  * see https://www.zhihu.com/question/406929241/answer/1364968559
  * [CTF time](https://ctftime.org/) 全球CTF战队排名
* 密码学
* [吾爱破解论坛](https://www.52pojie.cn/)
* 反汇编 ida pro
* [how to become a hacker](http://www.catb.org/~esr/faqs/hacker-howto.html)
* 最佳工具 [kali-linux](https://www.kali.org/downloads/)
* 暗网可以去碰，可以去看，但是绝对不可以在上面买东西留下自己的痕迹
* 电影《黑客军团》，配乐挺好听的

## 10. 编程语言学习

#### C language

* 黑C: 《C程序设计语言》
* P.S 不要读谭浩强，不适合专业人员

#### python

* 推荐先看**廖雪峰的教程**,**菜鸟教程**快速上手。
* 《Python Cookbook（第 3 版）中文版》
* Alex Martelli 的《Python 技术手册（第 2 版）》
* David Beazley 的《Python 参考手册（第 4 版）》
* 《python学习手册》有点庞杂，用来做工具书备查比较合适
* 精通Python设计模式
* 《流畅的python》推荐在有一定python基础和实践后阅读，比较多和解释器直接交互的部分，和Java的反射机制有点类似。

#### Java

* 《Java核心技术 卷I》

#### C++

* 《C++ Primer》强烈推荐
* 《Linxu高性能服务端编程》
* 《**Effective C++**》
* 《**STL源码剖析**》
* 《深入探索C++对象模型》
* 《C++ Primer Plus》读完半本，觉得一般，比较繁琐。

#### ruby 小众

* [ruby on rails tutorial](https://flapybooks.com/products/railstutorial6th)， 读完整本书，实现所有书上的功能，就能基本理解web的整套流程。
* [ruby china 官方网站](https://ruby-china.org/) 
* 《ruby元编程》对于理解动态语言很有帮助
* The Art of the Metaobject Protocal （AMOP）

### 11.数据库

* 没学到啥，求大家推荐

## 二、方向分流

这部分不好划分，会比较混乱， 为每个方向，单独开一个列表，就像Andrid方向。点击链接跳转到对应的文件

### 开发

* [Android 方向 ](./Android.md) 
* Web后端
* [前端&UI](./FrontEnd.md)
* [运维](./Operation-and-maintenance.md)

### 人工智能

* 西瓜书 《机器学习 周志华》

* 花书 《深度学习》

* 《统计机器学习 李航》

* 《信号与系统》作为计算机视觉的先导课，重点是傅里叶变换

* 课程，[吴恩达 深度学习](https://www.coursera.org/specializations/deep-learning), bilibili上有中文字幕, 零基础教学

* 课程, [李飞飞 CS231n](http://cs231n.stanford.edu/) 计算机视觉

* 深度学习框架： 首选 pytorch, 其次 tensorflow, 然后MXNET，未来可能oneflow

* 论文列表：

  在GitHub上，一般，收集好的项目的代码仓库，都会冠以awesome的前缀, like:

  * [awesome object detection](https://github.com/amusi/awesome-object-detection)
  
* 动手教程：

  * [pytorch 官方教程](https://pytorch.org/tutorials/)
  * [动手学深度学习](https://github.com/ShusenTang/Dive-into-DL-PyTorch)
  
* [《可解释的机器学习》](https://github.com/MingchaoZhu/InterpretableMLBook)

### 人文社科

see [人文社科](./Social-science.md)

## 三、好用的工具

1. Typora 最好看舒服的markdown书写工具，写文档必备
2. Tmux 非常方便的终端复用工具，在远程主机维持一个服务，可断线重连
3. win上方便的终端模拟工具：
   * git bash
   * Windows Terminal 还不成熟，但是好看，win7 不支持
   * Cmder
   * Zsh 比 Bash 好用一些
   * 算了，还是用ubuntu或者Mac吧
4. Vim 懂的都懂，有时间配置的话，不输任何IDE
5. git 因为太重要，所以放在这里, [Git权威指南中文手册](http://iissnan.com/progit/html/zh/ch1_0.html)
6. [《github漫游指南》](https://github.com/phodal/github) 学习github的一般使用



## Them

* [陈立杰](https://zhuanlan.zhihu.com/p/87460515)
* 韩衍隽
* 范浩强
* 乔明达
* 戴文渊
* 唐文斌
* [friedman](http://www.yinwang.org/blog-cn/2012/07/04/dan-friedman)

## 职场相关

1. [提问的智慧(中文版)](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)
2. [字节跳动成长方法卡](./ByteDance.md)



## 开源书单

* https://github.com/CyC2018/CS-Notes 109k star
* https://github.com/iamshuaidi/CS-Book pdfs  4.3k star
* https://github.com/woai3c/recommended-books pdfs 直接下载  1.5k star
* https://github.com/justjavac/free-programming-books-zh_CN 69k star
* https://github.com/TonnnnnnyLiu/Books pdfs 直接下载 124 star

## 集合书单

1. http://paulgraham.com/books.html



## Log

* 2020-08-30: 添加前端UI\好用的工具
* 2020-08-22: 添加职场相关
* 2020-08-01: 添加人文社科，补充部分链接
* 2020-07-25: 创建列表