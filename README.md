# css-trick

圣杯布局（中间自适应, negative margin)
"<h4>Header内容区</h4>
<div class="container">
  <div class="middle"><h4>中间弹性区</h4></div>
  <div class="left"><h4>左边栏</h4></div>
  <div class="right"><h4>右边栏</h4></div>
</div>
<h4>Footer内容区</h4>"

.container {width: 100%;height:200px;overflow:hidden;padding: 0 200px;}
.middle {width: 100%;height: 200px; background-color: deeppink;float:left;}
.left {width: 200px;height: 200px;background-color: blue;float:left;margin-left:-100%;position: relative; left: -200px;}
.right {width: 200px;height: 200px;background-color: darkorchid;float:left;margin-left:-200px;position: relative;right: -200px;}
