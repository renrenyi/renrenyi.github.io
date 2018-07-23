---
layout: post
title:  "机器学习介绍"
date:   2018-07-23 20:43:54
categories: 机器学习
excerpt: 
---

* content
{:toc}


## 序

这是一个不太正经的帖子，因为我不喜欢写介绍性的东西。

我是个比较懒的人。
从我个人角度而言，对于学习，主要是三个阶段。

一是，知道机器学习某个模型可以干什么（什么应用场景，是分类、聚类、预测？？），经过简单的修改能够把网上的代码应用到自己的项目中。知道如何输入数据，如何取得结果。

二是，能够对模型的内部数学算法有个大致的了解，了解模型如何进行改进、怎么改进。我现在想要达到的就是这个水平，这样就可以大致吃饱饭啦。

三是，从数学角度对模型的理解，完全理解其数学模型的内涵。其实，我觉得这样的人，都是大牛牛，完全有能力改进模型后创建自己的模型。

我没有太大的理想，而且我说过我比较懒，所以想找着快速学会的想法，进行我自己的学习。

---

## 机器学习是什么？

额，就是，我们想学的东西。

我给大家几个网址，有兴趣可以看一看，不过我这个人对于定义性东西没太多兴趣，所以就不想写了。

https://baike.baidu.com/item/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/217599?fr=aladdin

https://baijiahao.baidu.com/s?id=1591709318502145890&wfr=spider&for=pc

http://36kr.com/p/5093721.html

---

## 杂说

我喜欢吃栗子，所以我觉得学习最好从例子开始，“举个栗子”。从例子中可以更方便地明白各种定义的含义，比单纯地定义或者理论有趣多了。

因为我之前也看过一些有关的知识，所以我想把自己现阶段所了解的讲一下。

用python，我也是第一次用python。安装python的教程自己网上百度吧。我个人建议安装3.5.x版本，因为后面需要用到TensorFlow，当前最新的3.6.x貌似支持得不好，不要给自己挖坑。

http://www.runoob.com/python/python-install.html

以后要学习Numpy、Pandas和Matplotlib（没关系，现在可以不管这些是什么），如果你用过MATLAB，恭喜你，这一部分几乎可以省略了，稍微看看代码格式，简单看1-2个小时视频应该就没问题了，遇到问题就谷歌百度嘛。按照我的理解，会R的应该对这些也会觉得很简单。下面是几个相关视频，可以看看，看完了应该就会了。

https://morvanzhou.github.io/tutorials/python-basic/basic/

https://morvanzhou.github.io/tutorials/data-manipulation/np-pd/

https://morvanzhou.github.io/tutorials/data-manipulation/plt/

学习之前可以把环境搭好，什么python安装好，Numpy、Pandas和Matplotlib装上去，然后再装上scikit-learn（这个稍微麻烦一点），还有装Anaconda3和PyCharm，再有就是TensorFlow。运气好一天可以搞好，运气不好，到处都是坑，挺烦的。具体问题涉及到具体再提。



---

