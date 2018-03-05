## 深入学习Python
在[2017年](https://github.com/jasonbai/2017plan) 系统学习了数据分析相关领域的一些东西，包括R，Python，D3.js等等。总体下来各个领域都有涉猎但不深入，在今年2018年，计划从Python入手，系统性的把整体相关模块都进行梳理积累。

---
### 官方文档

* [官方网站](https://www.python.org/)  https://www.python.org/
* [Python 3.6.4 documentation 英文](https://docs.python.org/3/)
* [Python 3中文文档](http://www.runoob.com/manual/pythontutorial3/docs/html/)
* [Python 2.7.14 documentation 英文](https://docs.python.org/2/)
* [Python 2中文文档](http://www.runoob.com/manual/pythontutorial/docs/html/)



### 什么是数据分析？

* 用适当的统计分析方法对收集来的大量数据进行分析，提取有用信息和形成结论对数据加以详细研究和概况总结的过程。
* 数据分析的目的是用数据中挖掘规律、验证猜想、进行预测

### 数据科学

数据科学涉及的工作范围

1.  数据探索与准备
   * 数据操作、导入、导出
   * 数据清洗
2.  数据展示形式与转化
   * 不同格式的数据操作，表格、图像、文本等
3.  关于数据的计算
   * 通过编程语言（Python或R）计算分析数据
4.  数据建模
   * 预测、聚类等机器学习模型
5.  数据可视化与展示
   * 绘图、交互式、动画等
6.  数据科学涉及到的学科知识

### 工作环境

数据分析主要平台是Anaconda

> [Anaconda](https://www.continuum.io/why-anaconda)是一个用于科学计算的Python发行版，支持 Linux, Mac, Windows系统，提供了包管理与环境管理的功能，可以很方便地解决多版本python并存、切换以及各种第三方包安装问题。Anaconda利用工具/命令`conda`来进行package和environment的管理，并且已经包含了Python和相关的配套工具。

简单来说，Anaconda是包管理器和环境管理器，Jupyter notebook 可以将数据分析的代码、图像和文档全部组合到一个web文档中。

#### 参考文档：

* [Anaconda 入门安装教程](https://foofish.net/anaconda-install.html)
* [最省心的Python版本和第三方库管理——初探Anaconda](https://zhuanlan.zhihu.com/p/25198543)

#### IDE

* Jupyter notebook

1. Anaconda 自带
2. 记录思考过程，实时查看运行过程
3. 基于web的在线编辑器
4. .ipynb 文件分享
5. 可交互式
6. 记录及时运行结果
7. 支持Markdown，Latex

* IPython

1. Anaconda 自带
2. Python的交互式命令行 Shell

* PyCharm



### Zen of Python

```
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```