# flex布局

### 概述

传统布局往往基于盒状模型，依赖`display`属性 + `position`属性 + `float` 属性，但对于那些特殊布局特别不方便，例如，垂直居中就不容易实现。

而 flex 布局可以简便、完整、响应式地实现各种页面布局，而且目前它已经得到了所有浏览器的支持，这意味着现在就能很安全的使用者想功能。

### 基本概念

采用 flex 布局的元素，称为 flex 容器（flex container），简称"容器"。它的所有子元素自动成为容器成员，成为 flex 项目 (flex item), 简称“项目”。

[![](http://www.ruanyifeng.com/blogimg/asset/2015/bg2015071004.png)

容器默认存在两根轴：水平的主轴（main axis）和垂直的交叉轴（cross axis）。主轴的开始位置（与边框的交叉点）叫做`main start`，结束位置叫做`main end`；交叉轴的开始位置叫做`cross start`，结束位置叫做`cross end`。

项目默认沿主轴排列。单个项目占据的主轴空间叫做`main size`，占据的交叉轴空间叫做`cross size`。

### 容器的属性

* flex-direction:row | row-reverse | column | column-reverse;
* flex-wrap:nowrap | wrap | wrap-reverse;
* flex-flow:<flex-direction> || <flex-wrap>;
* justify-content:flex-start | flex-end | center | space-between | space-around;
* align-items:flex-start | flex-end | center | baseline | stretch;
* align-content:flex-start | flex-end | center | space-between | space-around | stretch;


### 相关链接

[阮一峰的 flex 布局教程：语法篇](https://http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
