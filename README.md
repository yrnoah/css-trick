# 库

粒子效果 http://blog.topspeedsnail.com/archives/9289 https://github.com/VincentGarreau/particles.js/

# css-trick

圣杯布局（中间自适应, negative margin)<br/>
h4 Header内容区 /h4<br/>
div class="container"<br/>
  div class="middle" h4 中间弹性区 /h4 /div<br/>
  div class="left" h4 左边栏 /h4 /div<br/>
  div class="right" h4 右边栏 /h4 /div<br/>
/div<br/>
h4 Footer内容区 /h4<br/>
<br/>
.container {width: 100%;height:200px;overflow:hidden;padding: 0 200px;}<br/>
.middle {width: 100%;height: 200px; background-color: deeppink;float:left;}<br/>
.left {width: 200px;height: 200px;background-color: blue;float:left;margin-left:-100%;position: relative; left: -200px;}<br/>
.right {width: 200px;height: 200px;background-color: darkorchid;float:left;margin-left:-200px;position: relative;right: -200px;}<br/>
