# 一个老鸟发的公司内部整理的 Android 学习路线图 Markdown 版本

[jixiaohua](http://www.diycode.cc/jixiaohua)发了一篇`一个老鸟也发了一份他给公司内部小伙伴整理的路线图`。[另一份 Android 开发学习路线图](http://www.diycode.cc/topics/117)。可惜不是MarkDown格式的，所以[jixiaohua](http://www.diycode.cc/jixiaohua)直接上传的截图，在[jixiaohua](http://www.diycode.cc/jixiaohua)的呼吁下，我花了些时间，把这篇大牛的推荐清单编辑成了Markdown格式，方便大家浏览，学习。

有一些链接可能还不是特别准确，因为我只能根据图片上的书或者资源的名字去Google可能的书籍，所以链接上有什么不对的，欢迎大家评论指出，我会及时更正。请参考原文：[另一份 Android 开发学习路线图](http://www.diycode.cc/topics/117) 帮助修改。谢谢。

1. 基础工具部分： 中文手册，我猜c测是Maven中文手册，可是我并没有找到这样的资源，欢迎知道的朋友告诉我；
2. Android部分有 『第三方库集合』，我没能找到资源地址；
3. 书籍我大多是给的豆瓣链接，如果觉得不合适可以替换一下；

#### 关于Markdown表格

本来我一开始整理了一份表格版本的, 用 Mou 写的，表格内的换行用<br/>标签处理的，但是在DiyCode上来发的时候，发现Markdown表格内部不支持<br/>标签换行，所以就只能整理成平铺的文档格式。~~Markdown对于表格的支持不是很强大。~~

## 程序设计

### 一、java

#### （a）基本语法(如继承、异常、引用、泛型等)

- [Java核心技术 卷I](https://u.jd.com/361zpk)（适合入门）
- 进阶
  - [Effective Java中文版](https://u.jd.com/iuxtyh)（如何写好的Java代码）
  - [Java解惑](https://u.jd.com/gfwlQk) （介绍烂Java代码是什么样的）

#### （b）多线程、并发

- [Java并发编程实战](https://u.jd.com/rCX0Yi) （系统全面的介绍了Java的并发，如何设计支持并发的数据结构）

#### （c）Java 7

- [Java程序员修炼之道](https://u.jd.com/vRQ8Y6) （详细的介绍Java 7 的新特性）

#### （d）Java 8

- [写给大忙人看的Java SE 8](https://u.jd.com/ELd49g)
- [函数式编程思维](https://u.jd.com/KoeXa5)

#### （e）Java虚拟机

- [深入理解Java虚拟机](https://u.jd.com/II0ivh) （并不是那么难，Java程序员都该看看）

#### （f）性能优化

- [Java性能优化权威指南](https://u.jd.com/U5DoWA) （后面的章节好像用处不大，前面有些部分还是值得看）

------

### 二、算法与数据结构

> - 算法时间复杂度、空间复杂度的基本认知
> - 熟悉常用数据结构：链表、队列、散列表、树等；
> - 递归、分支等基本思想；
> - 常用算法应用：排序、查找、比较等

- [数据结构与算法分析](https://u.jd.com/Fgeuef) （涵盖面比较全、示例是Java语言）
- [算法设计与分析基础](https://u.jd.com/rWLIDo) （实用主义的典型、偏算法设计）
- [编程珠玑](https://u.jd.com/BcGRcv) （实践型算法数据）

### 三、操作系统

> - 对Linux/OS的基本认知
> - Linux的常用命令

- [鸟哥的Linux私房菜](https://u.jd.com/is95Uw)
- [Linux内核设计与实现(原书第3版)](https://u.jd.com/XfTgAr) （很精炼的语言描述清楚了内核算法）

### 四、网络

> - Http/Https
> - TCP/IP

- [图解HTTP](https://u.jd.com/vlmF68)
- [图解TCP/IP](https://u.jd.com/kx7WPM)
- 进阶
  - [TCP/IP详解](https://u.jd.com/RKgXHB)

### 五、Android

> - 四大组件（服务、广播、ContentProvider、页面容器）
> - 基础UI组件（ListView、ViewPager）
> - 异步任务机制（AsyncTask、Handler、线程池）
> - 布局优化（层级、绘制、碎片化处理）
> - 图片加载（Bitmap、缓冲区）

- [UniversalMusicePlayer](https://github.com/googlesamples/android-UniversalMusicPlayer) (通过学习一个音乐播放器的代码能很快了解四大组件)
- [Android Training官方课程](http://hukai.me/android-training-course-in-chinese/index.html)
- [Android一些重要知识点解析整理](https://github.com/FX-Max/Point-of-Android)
- [Android UI/UX库](https://github.com/wasabeef/awesome-android-ui)（各类常用组件及扩展组件的集合）
- [Picasso](http://square.github.io/picasso/) 、 [Glide](https://github.com/bumptech/glide) （两个图片加载库）
- [The Google I/O 2015 Android App](https://github.com/google/iosched) (Google大会官方的App，适合学习各类实现)
- [Android开发技术前线](http://www.devtf.cn/) （定期翻译、发布国内外Android优质的技术、开源库、软件架构设计、测试等文章）
- 进阶
  - [第三方库集合](https://github.com/wasabeef/awesome-android-libraries) （列举了常见的各方向第三方库）

------

## 软件工程

### 一、基础工具

> IDE、Git、Maven

- [AndroidStudio](https://developer.android.com/studio/index.html)
- [Git权威指南中文手册](http://iissnan.com/progit/html/zh/ch1_0.html)

### 二、软件质量

> - 代码整洁
> - 码质量
> - 码重构

- [编写可读代码的艺术](https://u.jd.com/XlcqcO) （来自Google工程师，专注于代码可读性）
- [代码整洁之道](https://u.jd.com/PN5CGO)（使用面向对象+敏捷开发原则编写清晰可维护的代码）
- [重构-改善既有代码的设计](https://u.jd.com/4pI6bC) （学习改善已有代码）
- [重构手册](https://u.jd.com/mPMf5r) （改善代码的实际操作）

### 三、设计模式

> 23种常见设计模式

- [大话设计模式](https://u.jd.com/afZFEm)
- [Head First设计模式](https://u.jd.com/TkjkaD)(两本入门级的设计模式书籍)
- 进阶
  - [设计模式-可复用面向对象软件的基础](https://u.jd.com/3cnsOs)（设计模式在实际中的应用）

### 四、敏捷开发

- [解析极限编程](https://u.jd.com/laW1gZ)
- [敏捷开发的艺术](https://u.jd.com/J64uky)
- 进阶
  - [敏捷软件开发-原则、模式与实践](https://u.jd.com/yfVrI3)

### 五、专业开发

> - 序员职业素养
> - 更高效、更实效

- [程序员的是职业素养](https://book.douban.com/subject/11614538/)
- [程序员修炼之道-从小工到专家](https://u.jd.com/d4iPvH)

### 六、思考人生

- [黑客与画家](https://u.jd.com/lzQ5qQ) (硅谷创业之父Paul Craham 的文集，主要介绍黑客及优秀程序员的爱好和动机)