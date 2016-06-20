title: nodeppt demo
speaker: etc1208
url: https://github.com/etc1208/nodePPT-Demo.git
transition: newspaper
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: moon
usemathjax: yes

[slide style="background-image:url('/img/bg1.png')"]
# 我叫杨赫
## 来自北京邮电大学计算机学院

[slide style="background-image:url('/img/bg3.jpg')"]
## 关于我
----
* 热爱前端
* 喜欢健身和画画
* 喜欢分享

[slide style="background-image:url('/img/bg4.jpg')"]

> 掌握SSH、SpringMVC、MySql
> 熟悉html,css,js
> 熟悉node,express
> 了解React,Less/Sass,Jade/Freemarker
> ......

[slide]

## 我的博客
----

地址：https://etc1208.github.io


[slide]
## 文字墙
-----

<span class="text-danger">.text-danger</span> <span class="text-success">.text-sucess</span><span class="text-primary">.text-primary</span>

<span class="text-warning">.text-warning</span><span class="text-info">.text-info</span><span class="text-white">.text-white</span><span class="text-dark">.text-dark</span>


<span class="blue">.blue</span><span class="blue2">.blue2</span><span class="blue3">.blue3</span><span class="gray">.gray</span><span class="gray2">.gray2</span><span class="gray3">.gray3</span>

<span class="red">.red</span><span class="red2">.red2</span><span class="red3">.red3</span>

<span class="yellow">.yellow</span><span class="yellow2">.yellow2</span><span class="yellow3">.yellow3</span><span class="green">.green</span><span class="green2">.green2</span><span class="green3">.green3</span>

[slide]
## label and link
<span class="label label-primary">.label.label-primary</span><span class="label label-warning">.label.label-warning</span><span class="label label-danger">.label.label-danger</span><span class="label label-default">.label.label-default</span><span class="label label-success">.label.label-success</span><span class="label label-info">.label.label-info</span>

<a href="#">link style</a> <mark>mark</mark>

[slide]
## buttons
----

<button class="btn btn-default">.btn .btn-default</button>  <button class="btn btn-primary">.btn.btn-lg.btn-primary</button> <button class="btn btn-warning">.btn.btn-waring</button> <button class="btn btn-success">.btn.btn-success</button> <button class="btn btn-danger">.btn.btn-danger</button>

<button class="btn btn-lg btn-default">.btn.btn-lg.btn-default</button> <button class="btn btn-xs btn-success">.btn.btn-xs.btn-success</button> <button class="btn btn-sm btn-primary">.btn.btn-sm.btn-primary</button> <button class="btn btn-rounded btn-warning">.btn.btn-rounded.btn-waring</button>  <button class="btn btn-danger" disabled="disabled">disabled.btn.btn-danger</button>

<button class="btn btn-success"><i class="fa fa-share mr5"></i></button>

[slide]
## icons: Font Awesome
------

<i class="fa fa-apple"></i>
<i class="fa fa-android"></i>
<i class="fa fa-github"></i>
<i class="fa fa-google"></i>
<i class="fa fa-linux"></i>
<i class="fa fa-css3"></i>
<i class="fa fa-html5"></i>
<i class="fa fa-usd"></i>
<i class="fa fa-pie-chart"></i>
<i class="fa fa-file-video-o"></i>
<i class="fa fa-cog"></i>


[slide]

## 代码格式化
### 使用 `highlightjs` 进行语法高亮
----
<div class="columns-2">
    <pre><code class="javascript">(function(window, document){
    var a = 1;
    var test = function(){
        var b = 1;
        alert(b);
    };
    //泛数组转换为数组
    function toArray(arrayLike) {
        return [].slice.call(arrayLike);
    }
}(window, document));
    </code></pre>
    <pre><code class="javascript">(function(window, document){
    var a = 1;
    var test = function(){
        var b = 1;
        alert(b);
    };
    //泛数组转换为数组
    function toArray(arrayLike) {
        return [].slice.call(arrayLike);
    }
}(window, document));
    </code></pre>
</div>


[slide]
## iframe效果
----
<iframe data-src="http://www.baidu.com" src="about:blank;"></iframe>


[slide]
## 支持多种皮肤
----

<div class="columns6">
    <a href="?theme=color" class="label-danger">color</a>
    <a href="?theme=blue" class="label-primary">blue</a>
    <a href="?theme=dark" class="label-info">dark</a>
    <a href="?theme=green" class="label-success">green</a>
    <a href="?theme=light" class="label-warning">light</a>
</div>


[slide]
## 动效：fadeIn
----
* 列表支持渐显动效哦 {:&.fadeIn}
    * 使用方法
    * markdown列表第一条加上：{:&.动效类型}
* 动效类型
    * fadeIn
    * rollIn
    * bounceIn
    * moveIn
    * zoomIn

[slide]
## 动效：zoomIn
----
* 列表支持渐显动效哦 {:&.zoomIn}
* 动效类型
    * fadeIn
    * rollIn
    * bounceIn
    * moveIn
    * zoomIn


[slide data-transition="glue"]

## 这是一个glue的动效
----
使用方法（全局设置） 1：

> transition: glue

[slide]

# nodePPT快捷键介绍
## 快速翻页
----
1. 输入页码，然后enter
2. 使用O键，开启纵览模式，然后翻页

[slide]
## 支持zoom.js
----

增加了zoom.js的支持，在演示过程中使用`alt`+鼠标点击，则点击的地方就开始放大，再次`alt+click`则回复原状

[slide]

## 图片，点击全屏
----

![小萝莉](/girl.jpg "小萝莉")


[slide]

## 使用画笔
### 使用画笔做标记哦~你也可以随便作画啊！
---
按下键盘【P】键：按下鼠标左键，在此处乱花下看看效果。

按下键盘【B/Y/R/G/M】：更换颜色，按下【1~4】：更换粗细

按下键盘【C】键：清空画板


[slide]
## 使用overview模式
---
按下键盘【O】键。看下效果。

在overview模式下，方向键下一页，【enter】键进入选中页

或者按下键盘【O】键，退出overview模式

