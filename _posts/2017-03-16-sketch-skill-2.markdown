---
layout:     post
title:      "Sketch使用小技巧【二】"
subtitle:   "Sketch use tips [2]"
author:     "Caiyunsky"
header-mask: 0.3
header-img: "img/post-bg-sketch.jpg"
catalog:    true
tags:
    - sketch
---

接上一篇<a href="http://caiyunsky.me/2017/03/15/sketch-skill-1/">http://caiyunsky.me/2017/03/15/sketch-skill-1/</a> 中提到的2个小技巧，一个是如何修改sketch的默认值，另一个是如何用sketch绘制特殊形状。有不清楚的各位看官可以回头再翻翻，这篇我将继续来说说sketch的一些使用小技巧。
## 3、如何进行快捷的图层选择操作？
Tab/shift+Tab对图层进行上下切换选择
![sketch6](/img/article-img/2/sketch6.gif) 
## 4、symbol属性太多，只需要改动其中某些属性，其他属性不予显示，怎么解决？
问题重现：见图![sketch1](/img/article-img/2/sketch1.png) symbol可以自定义的属性太多，而很多时候只需要变动其中的几个，其他属性在团队合作中并不想要其他人改动，怎么办？
解决办法：进到symbol，锁定不需要改动的属性图层，如图![sketch2](/img/article-img/2/sketch2.png) 进行锁定。锁定后，不需要改动的属性就不会出现在overrides里了，如图 ![sketch3](/img/article-img/2/sketch3.png) 
## 5、在sketch中选择某个层后移动会误操作到别的层，如何解决？
这个问题，在开始使用sketch的时候特别不适应。因为在ps中是有移动工具的，选中了某个图层后使用移动工具移动并不会误操作到其他图层。但是在sketch中简直很痛苦，当你艰难的选择到了某个图层（在sketch操作图层感觉没有ps那么顺利）后，想要移动下这个图层，结果发现移动的根本不是你想要的图形，因为你已经离开了选中的焦点，并按了左键试图移动，却点中了其他图层或者图层组，结果导致布局错乱。更严重的情况是，有时候轻微的移动还很难被发现，等回过头来发现移动错误后，不得不从头开始。。。
![sketch4](/img/article-img/2/sketch4.gif)
解决办法：移动图层时配合option+command组合键就可以搞定这个问题（这个功能好像是在最新41.1版本中才有的功能）。
![sketch5](/img/article-img/2/sketch5.gif)

本篇就先说到这里吧。
