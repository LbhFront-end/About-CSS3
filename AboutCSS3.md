## CSS3 介绍

[开始实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo01.html)

### 新特征简介

1.  强大的CSS选择器
2.  抛弃图片的视觉效果
3.  盒模型变化（多列布局和弹性盒模型）
4.  阴影效果
5.  Web字体和web Font 图标
6.  CSS33过渡与动画交互效果
7.  媒体查询

------

### 查看浏览器份额

[点我查看](http://tongji.baidu.com/data/browser)

------

### 伪类（Pesudo Classes）

#### （1）动态伪类选择器

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo02.html)

:link 设置a对象在未被访问前的样式表属性 

:visited 设置a对象在其链接地址已被访问过时的样式表属性 

:hover 设置对象在其鼠标悬停时的样式表属性 

:active 设置对象在被用户激活（在鼠标点击与释放之间发生的事件）时的样式表属性 

定义CSS时候的顺序不同，也会直接导致链接显示的效果不同。原因可能在于浏览器解释CSS时遵循的“就近原则”。正确的顺序：a:link、a:visited、a:hover、a:active

解释：

- link:连接平常的状态 
- visited:连接被访问过之后 
- hover:鼠标放到连接上的时候
- active:连接被按下的时候 

#### （2）结构伪类选择器

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo03.html)

:first-child 选择某个元素第一个子元素

:last-child 选择某个元素最后一个子元素

:nth-child() 选择某个元素的一个或者多个特定的子元素

:nth-last-child 选择某个元素的一个或者多个特定的子元素，从这个元素的最后一个子元素开始算

:nth-of--type() 选择指定的元素

:nth-last-of--type() 选择指定的元素，从元素的最后一个开始计算

:first-of-type 选择一个上级元素下的第一个同类子元素

:last-of-type  选择一个上级元素下的最后一个同类子元素

:only-of-type 选择的是它父元素唯一一个子元素

:empty 选择的元素里面没有内容

------



