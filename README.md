<html>
<body>
<h4>关于boostrap的例子</h4>
<img src="OnePage.png">
<img src="two.jpg">
<img src="three.jpg">
<img src="four.jpg">
<h5>总结</h5>
<p>
<strong>第二版：</strong><br/>
关于twopage的问题：要用到栅格系统，col-md-4，在电脑占四格，col-xs-12，在手机占全部<br/>
高度要设置auto，这样浏览器才能自适应<br/>
关于position:img要用到relative,div要用到absolute，left:0,top:0;<br/>
透明度opacity:<br/>
<code>.classIcon{<br/>
    width: 100%;<br/>
    height: 100%;<br/>
    position: absolute;<br/>
    left: 0;<br/>
    top: 0;<br/>
    color: #ffffff;<br/>
    opacity: 0;<br/>
}<br/>
.classIcon:hover{<br/>
    opacity: 0.9;<br/>
    background-color: #1eb450;<br/>
    transition: opacity 0.5s;<br/>
    -webkit-transition: opacity 0.5s;<br/>
}<br/>
</code>
<strong>关于第四版</strong><br/>
轮播 幻灯片<br/>
<code>class="carousel slide" data-interval="5000"</code><br/>
那些点点点<br/>
<code>
&lt;ol class="carousel-indicators" style="margin-top: 200px" &gt;<br/>
    &lt;li data-target="#carousel-example-generic" data-slide="0" class="active"&gt;&lt;/li&gt;<br/>
    &lt;li data-target="#carousel-example-generic" data-slide="0"&gt;&lt;/li&gt;<br/>
    &lt;li data-target="#carousel-example-generic" data-slide="0"&gt;&lt;/li&gt;<br/>
&lt;/ol &gt;<br/>
</code><br/>
关于改bootstrap源代码，可以在浏览器审查元素中复制之后，到css中去改就好了<br/>
</p>
</body>
</html>
