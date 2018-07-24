---
layout: post
title:  "环境搭建-Python"
date:   2018-07-24 12:43:54
categories: 环境搭建
excerpt: 
---

* content
{:toc}

## Python安装及测试

并不建议下载最新的版本，因为可能与其他要安装的东西不兼容，会出现很多问题。可以下载3.5.x版本的Python，我们以3.5为例。

---

### 环境

我电脑是Win 10系统，64位。

---

### 下载Python安装包

登陆网址：[https://www.python.org/](https://www.python.org/)

下载python的安装包：
![python下载](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-download1.png)

请点击Downloads  > Windows   下载我们需要的版本安装包3.5.4/windows/64位。

![选择python版本](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-download2.png)


---

### 安装Python

选择customize installation，选上 Add python 3.5 to path

![python安装](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-install-0.png)

下一步。全部选上吧，我一般都会选上，毕竟菜鸟，以后万一哪里出bug自己找都找不到，全部装上，出bug机会少一点。

![python安装](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-install-1.png)

下一步。安装位置记好了，大家以后都用英文地址吧，用中文说不定什么时候就会出bug。
![python安装](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-install-2.png)

下面就是安装了。安装完成后，我们进行小测试，看看是否安装成功。

### Windows设置环境变量

1. 右键点击"计算机/此电脑"，然后点击"属性"
2. 然后点击"高级系统设置"
3. 选择"系统变量"窗口下面的"Path",双击即可！
4. 然后在"Path"行，添加python安装路径即可(我的路径是C:\Python35)。
5. 各种点确定、应用。

![python环境变量设置](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-huanjingbianliang.png)

---

### 测试是否安装成功

打开Windows命令提示符commond/cmd窗口。

在cmd窗口输入 python，按回车，会显示python的版本信息等，而且进入到python模式。

之后，可以尝试输入print('hello,world')进行测试
```print('hello,world')```

如果能正常显示hello,world就可以啦。

![python环境变量设置](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/python-install-test.png)


### 参考

https://www.cnblogs.com/weven/p/7252917.html
https://www.cnblogs.com/hongten/p/hongten_python_install.html
http://www.runoob.com/python/python-install.html

---

