1. [CSS介绍](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-介绍)  
   (1)  [新特征简介](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#新特征简介)  
   (2)  [查看浏览器份额](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#查看浏览器份额)  
   (3)  [伪类](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#伪类pesudo-classes)   
   (4)  [伪元素](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#伪元素)  
2. [CSS变形](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-变形)  
   (1)  [border-radius](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#1border-radius)  
   (2)  [border](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#2border)  
   (3)  [菱形和平行四边形](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#3菱形和平行四边形)    
   (4)  [五角星和六角星](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#4五角星和六角星)   
   (5)  [五边形和六边形](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#5五边形和六边形)  
   (6)  [心形和蛋边形](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#6心形和蛋边形)   
   (7)  [太极阴阳图](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#7太极阴阳图)
3. [CSS3色彩](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-色彩)
4. [CSS3过渡](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-过渡)
5. [CSS3动画](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-动画)
6. [CSS3文字排版](https://github.com/LbhFront-end/About-CSS3/blob/master/AboutCSS3.md#css3-文字排版)


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

### 伪元素

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo04.html)

CSS 伪元素用于向某些选择设置特殊效果

| 伪元素        | 作用                           |
| ------------- | :----------------------------- |
| :first-letter | 将特殊的样式添加到文本的首字母 |
| :first-line   | 将特殊的样式添加到文本的首行   |
| :before       | 在某些元素之前插入某些内容     |
| :after        | 在某些元素之后插入某些内容     |

------

## CSS3 变形

### （1）border-radius

#### 半圆+标准写法

左上角开始，顺时针

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo05.html)

![半圆](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/circle.png)



```
.demo5{
    width: 100px;
    height: 200px;
    border: 1px solid #ccc;
    background: #f66;
    margin: 50px auto;
    border-radius: 0px 100px 100px 0px;									
}
```



### （2）border

#### 三角形+对话框

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo06.html)

![三角形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/triangle.png)

```
.triangle{
    border-top:100px solid #ccc;
    border-bottom:100px solid transparent;
    border-right:100px solid transparent;
    border-left:100px solid transparent;	
    width: 0;
    height: 0;								
    margin: 50px auto;
}

```

![对话框](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/triangle-dialog.png)

```
<style>
.triangle-dialog{
    background: #6a6;
    margin: 50px auto;
    width: 300px;
    height: 25px;
    line-height: 25px;
    padding: 10px;
    border-radius: 6px;
    color:#fff;
    position: relative;			
}
.triangle-dialog::before{
    content:'';
    border-left: 0px solid #6a6;
    border-top: 10px solid transparent;	
    border-right: 10px solid #6a6;
    border-bottom: 10px solid transparent;	
    position: absolute;
    left: -10px;	
    top: 10px;			
}
</style>

html
<div class="triangle-dialog">
	你好！我是三角形对话框
</div>
```

### （3）菱形和平行四边形

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo08.html)

![菱形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/diamond.png)

```
.diamond {
    width: 200px;
    height: 200px;
    background: #6a6;
    margin: 100px auto;
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
}
```

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo08.html)

![平行四边形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/parallel.png)

```
.parallel{
    width: 200px;
    height: 200px;
    background: #6a6;
    margin: 100px auto;
    /*skew 倾斜（x, y）*/
    -webkit-transform: skew(20deg);
    -ms-transform: skew(20deg);
    -o-transform: skew(20deg);
    transform: skew(20deg);
}
```



### （4）五角星和六角星

实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo09.html)

![平行四边形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/mogen-david.png)

```

<style>
    #star{
        position: relative;
        width: 0;
        height: 0;
        border-bottom: 70px solid #f66;
        border-left: 100px solid transparent;
        border-right: 100px solid transparent;
        margin: 150px auto;
        -webkit-transform: rotate(35deg);
        -ms-transform: rotate(35deg);
        -o-transform: rotate(35deg);
        transform: rotate(35deg);
    }
    #star::before{
        position: absolute;
        top: -50px;
        left: -69px;
        content: '';
        width: 0;
        height: 0;
        border-bottom: 80px solid #f66;
        border-left: 30px solid transparent;
        border-right: 30px solid transparent;
        -webkit-transform: rotate(-35deg);
        -ms-transform: rotate(-35deg);
        -o-transform: rotate(-35deg);
        transform: rotate(-35deg);
    }
    #star::after{
        position: absolute;
        content: '';
        top: 4px;
        left: -105px;
        width: 0;
        height: 0;
        border-bottom: 70px solid #f66;
        border-left: 100px solid transparent;
        border-right: 100px solid transparent;
        -webkit-transform: rotate(-70deg);
        -ms-transform: rotate(-70deg);
        -o-transform: rotate(-70deg);
        transform: rotate(-70deg);
    }		
</style>


<div id="star"></div>

```



### （5）五边形和六边形

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo10.html)

![五边形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/pentagon.png)

```
.pentagon{
    position: relative;
    margin: 100px auto;
    width: 54px;
    height: 0;
    border-top: 50px solid #f66;
    border-left: 18px solid transparent;
    border-right: 18px solid transparent;
}
.pentagon::after{
    content: '';
    position: absolute;
    top: -85px;
    left: -17px;
    width: 0;
    height: 0;
    border-bottom: 35px solid #f66;
    border-left: 45px solid transparent;
    border-right: 45px solid transparent;
}
```

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo10.html)

![六边形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/hexagon.png)

```
.hexagon{
    position: relative;
    margin: 100px auto;
    width: 100px;
    height: 50px;
    background: #f66;
}	
.hexagon::before{
    content: '';
    top: -25px;
    position: absolute;
    width: 0;
    height: 0;
    border-bottom: 25px solid #f66;
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
}
.hexagon::after{
    content: '';
    top: 50px;
    position: absolute;
    width: 0;
    height: 0;
    border-top: 25px solid #f66;
    border-left: 50px solid transparent;
    border-right: 50px solid transparent;
}	
```



### （6）心形和蛋边形

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo10.html)

![心形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/hearts.png)

```
// 无圆心
.hearts{
    position: relative;
    margin: 50px auto;
    width: 50px;
    height: 80px;
    background: #f66;
    border-top-right-radius: 25px;
    border-top-left-radius: 25px;
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
}
.hearts:before{
    position: absolute;
    content: '';
    top: 15px;
    left: 15px;
    width: 50px;
    height: 80px;
    background: #f66;
    border-top-right-radius: 25px;
    border-top-left-radius: 25px;
    -webkit-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
}

// 有圆心
.hearts1::before{
    position: absolute;
    left: 50px;
    content: '';
    margin: 50px auto;
    width: 50px;
    height: 80px;
    background: #f66;
    border-radius: 50px 40px 0 0;
    -webkit-transform-origin:0 100% ;
    -ms-transform-origin:0 100% ;
    -o-transform-origin:0 100% ;
    transform-origin:0 100% ;
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
}	
.hearts1::after{
    position: absolute;
    content: '';
    margin: 50px auto;
    width: 50px;
    height: 80px;
    background: #f66;
    border-radius: 50px 40px 0 0;
    -webkit-transform-origin:100% 100% ;
    -ms-transform-origin:100% 100% ;
    -o-transform-origin:100% 100% ;
    transform-origin:100% 100% ;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}
```

[实例](https://github.com/LbhFront-end/About-CSS3/blob/master/code/Demo10.html)

![蛋形](https://raw.githubusercontent.com/LbhFront-end/About-CSS3/master/code/img/ogival.png)

```
.ogival{
    margin: 100px auto;
    width: 60px;
    height: 100px;
    background: #fa3;
    /*(x / y)*/
    border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
```



### （7）太极阴阳图



## CSS3 色彩

## CSS3 过渡

## CSS3 动画

## CSS3 文字排版