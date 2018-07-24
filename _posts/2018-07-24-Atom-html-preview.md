---
layout: post
title:  "Atom实现html预览"
date:   2018-07-24 15:17:00
categories: 小tips
excerpt: 
---

* content
{:toc}


### Why?

之前修改静态网页都用Dreamweaver，而且喜欢实时预览。但是前段时间把Dreamweaver删了，又不想安装这么大的软件仅仅为了编辑html网页。百度了一下，发现atom+插件可以实现html网页的实时预览。

看了下atom的大小是140M，感觉还行。

下面是效果图，引用于https://blog.csdn.net/sinat_16791487/article/details/78252930。
![效果图](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/atom-html-preview.png)

--

### atom下载与安装

去官网下载：[https://atom.io/](https://atom.io/)

安装过程很简单。

---

### atom-html-preview插件的安装

1. 获取atom-html-preview插件

点击 File->Settings->Install，在输入框中输入atom-html-preview，之后下面会出现atom-html-preview插件，点击install按钮即可。
![效果图](https://raw.githubusercontent.com/renrenyi/renrenyi.github.io/master/css/pics/atom-html-preview-search.png)

---

### 插件的使用

打开html文件，右键，选择  Preview HTML，即可。

atom-html-preview初始快捷键为ctrl+p，与atom已有快捷键冲突，我看到大家一般都建议修改为ctrl+F12，操作如下

点击File->Settings->KeyBindings->your keymap file超链接->在末尾添加

```
'atom-text-editor':
   'ctrl-F12':'atom-html-preview:toggle'
```

---

### 参考

https://blog.csdn.net/sinat_16791487/article/details/78252930

https://blog.csdn.net/crper/article/details/46333295

---

