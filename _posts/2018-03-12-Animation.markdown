---
layout:     post
title:      "7个实用技巧，让你的动效变得更优秀！"
subtitle:   "Good to great UI animation tips"
#date:       2018-03-12 09:38:00
author:     "Caiyunsky"
header-mask: 0.3
header-img: "img/article-img/20180312/post-bg-banner.png"
catalog:    true
tags:
    - 设计译文
    
---

> 文章简介：随着移动应用设计的不断发展，动画在如今应用中的地位变得越来越重要，那么如何把好的动画做到更加精致，你可以从这篇文章中找到一些非常实用并且可迅速执行的小技巧！

译文：

#### 提高UI微交互的实用建议

让我们一起看看UI动画从优秀到卓越的一些例子。通过一点小小的调整，你就可以大大提升你的UI动效品质。

本文所列出的案例显示出了状态之间的连续性，以及公共元素之间的关系，并且将用户的注意力引向他们应该注意和采取行动的事情上。

为了创建这些动画， 我遵循了 [Material Motion](https://material.io/guidelines/motion/material-motion.html), [IBM’s Animation Principles](https://www.ibm.com/design/language/experience/animation), 和[The UX in Motion Manifesto.](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc)的一些原则。

所有这些动画的设计都是用了 [InVision Studio](https://www.invisionapp.com/studio)早期的版本， 你可以在这里[下载源文件](https://www.dropbox.com/sh/qfwficfun4vagv6/AAADpQyoZ5y_o8KnCnxOSqiUa?dl=0)。

------

#### 1、内容标签的滑动动效

![img](/img/article-img/20180312/image2.gif)

左边的内容是淡入淡出的，右边的是内容会随着标签一起滑动。

- 一个好的动画会把内容从一种状态淡出到另一种状态。
- 一个优秀的动画则是使内容在不同状态之间转换保持连续性。

当你设计一个类似标签或弹出菜单的交互时，尝试将内容的位置与打开它的动作相关联。这样做不仅可以提升内容的可见性，同时也可以使该内容的位置动画化。当你在设计这个动画的时候，记得要加上内容切换的滑动手势操作。

------

#### 2、连接卡片的共用元素。

![img](/img/article-img/20180312/image3.gif)

左边的内容是向上打开一个新的界面，右边则是将卡片展开并填充整个屏幕。

- 一个好的动画是使用像向左或者向上滑动来展示内容细节。
- 一个优秀的动画是通过公共元素的动画来建立两个状态之间的联系。

在不同状态之间动画时，查看它们之间是否有任何公共元素并将它们联系起来。在InVision Studio中，当你创建一个转场动画时，会自动连接两个屏幕之间的重复组件。这使得原型动画的设计变得轻而易举。

查看 [Motion Manifesto](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc) ，看看你能够应用的动画类型。上面的例子使用了遮罩，转换，子父级关系，缓动等原则。

------

#### 3、在内容中使用级联效果

![img](/img/article-img/20180312/image4.gif)

左边的卡片在动画中有滑动和淡入，右边是相同的动画，但是每张卡片都有一个很短的延时。

- 一个好的动画会改变元素在进入界面时的位置和透明度。
- 一个优秀的动画是能够快速的将界面元素错落有序的出现。

要实现瀑布流效果，尝试将延迟应用到每一块或者每一组内容上。保持相同的缓动和持续时间，这样会给人感觉是一致的。 不要将每个小元素都去做瀑布流效果，而是将这些元素组合起来，保持动画的流畅和快速。谷歌推荐每个元素开始运动不超过20ms的间隔。 查看 [Material Motion ](https://material.io/guidelines/motion/choreography.html#choreography-creation)中的编排原则并看看更多的例子。

------

#### 4、让内容把界面中的元素撑开至界面以外

![img](/img/article-img/20180312/image5.gif)

左边的动画是盖在其他内容之上，右边的动画则是随着内容的展开将内容推出来。

- 一个好的动画是在上下文中移动并显示元素。
- 一个优秀的动画则是当元素发生改变时会影响周围环境。

让内容中的元素了解周围的环境。这意味着内容在发生改变时会吸引或者排斥周围的元素。有关更多示例，请查看 [Material Design.](https://material.io/guidelines/motion/material-motion.html#material-motion-how-does-material-move)中的意识运动原理。

------

#### 5、让菜单显示在上下文中。

![img](/img/article-img/20180312/image6.gif)

左边的菜单从下面飞进来，右边的菜单则从创建它的动作展开。

- 好的动画菜单是从打开它们的按钮方向显示出现的内容。
- 优秀的动画是从创建它们的动作中浮现出来，是从触摸点展开而来。

------

#### 6、使用按钮显示不同的状态。

![img](/img/article-img/20180312/image7.gif)

左边的按钮显示指示状态的文本，右边的按钮则使用变化的容器显示不同的事件。

- 好的交互方案是在按钮附近显示事件。
- 优秀的交互方案是使用按钮本身来显示不同的状态。

尝试使用按钮的容器来提供状态的视觉反馈。例如，你可以使用一个变形或者加载动画来替换纯文本；也可以在显示进度的背景中添加一个动画。解决方案取决于你，想法是利用用户已经与之交互的空间。如果使用按钮颜色和样式来确认成功状态，则额外加分。

------

#### 7、使注意力集中在重要的事情上

![img](/img/article-img/20180312/image8.gif)

左边的例子是用颜色和位置来突出元素，右边则是使用一个微动画来引起用户的注意。

- 好的设计会使用颜色，大小和位置来突出用户需要注意或采取的重要操作。
- 优秀的设计会使用动画来引起用户对重要操作的关注，并且不会对用户造成干扰。

当用户需要做一些重要的事情时，尝试用动画来吸引他们的注意力。从一个微动画开始，根据操作的重要程度增加强度（改变大小，颜色和速度）。这种动画只能用于关键操作——使用的次数越多，效果反而越差，并且用户会受到的骚扰也会越多。

------

#### 总结

我希望这些例子可以帮助你在做交互动画时做出更好的决策。有了像 InVision’s Studio一样新的动画原型工具，我预计我们很快就会看到互动创意的爆发。我们只需要负责在这个新的王国里任意发挥。

让我们应用动画来解释状态的变化，注意必要的操作，确定元素之间的关系并为我们的产品添加一点乐趣和个性。遵循这些元素，我们就可以将我们的动画从好的变成优秀的。



> 原文：https://uxdesign.cc/good-to-great-ui-animation-tips-7850805c12e5
>
> 作者： [Pablo Stanley](https://uxdesign.cc/@pablostanley?source=post_header_lockup)
>
> 译者：彩云Sky
>
> 本文翻译已获得作者的正式授权
>
> ![shouquan](/img/article-img/20180312/shouquan.jpg)