---
layout:     post
title:      "Sketch使用小技巧【一】"
subtitle:   "Sketch use tips [1]"
#date:       2017-03-13 15:00:00
author:     "Caiyunsky"
header-mask: 0.3
header-img: "img/post-bg-sketch.jpg"
catalog:    true
tags:
    - sketch
---

在刚开始使用sketch这个工具时，遇到过一些坑。总结记录一些解决办法和经验技巧吧。

## 1、如何修改sketch的默认值，比如默认画矩形不要边框？

问题重现：打开sketch随意画一个矩形或者其他图形，会有一个样式默认值。

![anli-1](/img/article-img/1/anli-1.jpg)

带来的问题：有时候，我们并不想每次都自带样式属性，比如每次都自带描边。有默认样式的情况下，每次都需要去调整样式，比较麻烦。

如何解决：先画一个不带描边属性的矩形，然后进到Edit——Set Style as Default。将不带描边属性的矩形样式定义为默认样式，这样下次再绘制图形时，就不会有描边。

![anli-2](/img/article-img/1/anli-2.jpg)

小结：经过测试，对于图形的默认样式，仅包括填充和描边，圆角和大小是不会成为默认属性。而对与文字来说，Edit——Set Style as Default是置灰的，因为文字会自动保持与上一次文本样式的设置。

软件必须有一个初始样式，sketch的初始样式就是保持上一次的样式设置。

## 2、如何用sketch绘制特殊形状

![anli-3](/img/article-img/1/anli-3.jpg)

方法一：绘制2个圆，设置描边属性为center，然后利用修剪工具![anli-4](/img/article-img/1/anli-4.png)修剪掉不需要的路径即可（不可以是直接删除锚点哦）。

方法二：直接设置描边属性。

![anli-5](/img/article-img/1/anli-5.png)其中，Dash控制显示长度，Gap控制缺口的大小，所以要出那种效果，gap的长度一定要大于圆的周长，也就是3.14*2R，这个方法可以设置更加精确的圆弧。

采用方法二，还可以制作更多不同的示数效果。

例如![anli-6](/img/article-img/1/anli-6.png)对应参数为![anli-7](/img/article-img/1/anli-7.png) ![anli-8](/img/article-img/1/anli-8.png) 或者![anli-9](/img/article-img/1/anli-9.png) 对应参数为![anli-10](/img/article-img/1/anli-10.png) ![anli-11](/img/article-img/1/anli-11.png) 其中：Dash是线段的宽度，Gap是间隔的宽度，Thickness是线段的长度。

只是举了2个实用的小案例，更多的效果需要等你们去发掘了！