---
layout:     post
title:      "Sketch使用小技巧【三】"
subtitle:   "Sketch use tips [3]"
author:     "Caiyunsky"
header-mask: 0.3
header-img: "img/post-bg-sketch.jpg"
catalog:    true
tags:
    - sketch
---

本篇将写一些sketch不为人知的冷知识——输入参数法。
## 1、sketch参数法导出无理数比例图形？
案例：画了一个60x60px的图标，现在需要导出100x100px尺寸，无法通过具体比例直接导出。(100/60=1.666666....)
解决办法：在导出参数中填入100w或者100h（也就是width和hight的首字母），即可导出该尺寸。
![1](/img/article-img/20170320/1.png)<br/>
![2](/img/article-img/20170320/2.png)<br/>
![3](/img/article-img/20170320/3.gif)
## 2、sketch参数法按指定方向缩放？
案例：在sketch中进行缩放，按默认缩放方式。<br/>
size在解锁状态时，w的缩放是基于左边，即左边不动往右边方向缩放;h的缩放是基于顶部，即顶边不动往底部缩放。
size在锁定状态时，输入w或者h任意值，均直接按左上顶点缩放。<br/>
如果想要按照其他顶点方向缩放，如何操作呢？<br/>
类似css中的盒子模型，分为上(t/top)右(r/right)下(b/bottom)左(l/left)，其中w控制右左,h控制上下，如下图<br/>
![4](/img/article-img/20170320/4.png)
控制物件单独向一个方向缩放，需要先将size解锁,在输入对应的参数值实现指定方向缩放。见下图
![5](/img/article-img/20170320/5.gif)
有一种比较特殊，也是使用频率很高的操作，那就是居中缩放。居中缩放输入m/middle或者c/center都可以，见下图
![6](/img/article-img/20170320/6.gif)
注意：作居中操作时，size一定要在解锁状态下才可以，原因是对于w或者h来说，c&m的操作是多变缩放，中心点就不在物件中心了。

