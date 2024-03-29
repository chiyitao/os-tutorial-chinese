# os-tutorial-chinese

译者注：os-tutorial中文版翻译。

如何从头创建一个操作系统！

我经常向往学习如何从头创建一个操作系统。在大学里我学习了如何实现高级的
特征（分页，信号量，内存管理，等等），但是：

- 我从没有从我自己的引导分区开始

- 大学的学习是困难的因而大部分内容都我不记得了

- 许多人灌输给我这样的观点，阅读一个已经存在的即使是很小的内核是学习操
  作系统的好的想法。

来自于[这篇文章](http://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
以及[OSDev wiki](http://wiki.osdev.org/)，我会为尝试任何跟随者构建循序渐进的README和代码例子。
诚实的讲，这个教程基本上是第一个划分为一个个小部分的并且没有理论介绍的文档。

更新：更多的资料[一本关于操作系统开发的小书](https://littleosbook.github.io),
[JamesM的内核开发教程](https://web.archive.org/web/20160412174753/http://www.jamesmolloy.co.uk/tutorial_html/index.html)

特点
----

- 这个课程是一个代码教程，其目标读者是那些对于底层计算感到舒适的人。例
  如对操作系统如何运行但没有时间和意志力从顶至底的阅读Linux内核的开发者。

- 没有理论。是的，这是一个特点。Google是你的理论讲师。当你从大学毕业，
  过多的理论比没有理论更遭，因为这让事情看起来比实际上更复杂。

- 这个课程是精简的并且每篇需要5-15分钟来完成。相信我也相信自己。你可以
  办到的！

如何使用这个教程
---------------

1. 从第一个文件夹开始并依次向下进行。这些教程根据先前的代码构成，因而
如果你直接跳转到文件夹05并不知道为何存在`mov ah, 0x0e`，这是因为你错过
了课程02。在实际中按照顺序进行。你可以跳过那些你已经知道的内容。

2. 打开README文件并阅读第一行，这一行描述了你在阅读代码前应当熟悉的概
念。用Google搜索那些你还不熟悉的概念。第二行描绘了每个课程的目标。阅读
他们，因为他们解释了为何我们这样做。“为何”重要于“如何”。

3. 阅读README剩下的部分。这是**非常简洁的**。

4. （可选的）在阅读REAME之后你自己可以尝试着去写下这些代码。

5. 阅读这些代码例子。它们都做了良好的注释。

6. （可选的）对它们进行实验并且尝试打破已有的东西。让你确信你已经了解
某些事物的唯一途径是打破它们或者以不同的命令来复制它们。

TL;DR：首先阅读每个文件夹的REAMME，然后是代码文件。如果你足够勇敢，尝
试自己对它们进行编码。

策略
----

我们想利用我们的操作系统做许多事情：

