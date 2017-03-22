<!DOCTYPE html>
<html>
<head>
<style>
/*定义最外层样式及字体*/
div.body
{
/*width:30em;*/
/*border:1em solid;*/
font-family: "Microsoft YaHei";
margin: 60px;
}
/*下面注释为css内容*/
/*h2{
  font-family: cursive;
}*/
/*定义左边20%的盒子样式*/
/*边界 字体样式 浮动左边 背景*/
div.box1
{
box-sizing:border-box;
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
width:20%;
border:1em solid #f9f6f6;
float:left;
height: 600px;
padding-top: 50px;
padding-bottom: 50px;
text-align: center;
background-color: #eaebe5;
font-family: cursive;
}
/*定义右边80%的盒子样式*/
/*边界 字体样式 浮动左边 背景*/
div.box2
{
box-sizing:border-box;
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
width:80%;
border:1em solid #f9f6f6;
float:left;
padding-top: 50px;
background-color: #dcd6d4;
}

/*p{
  padding-left: 50px;
  width: 400px;
}
h2{
  padding-left: 60px;
}*/
</style>
</head>
<body>
  <!-- 引入css样式 -->
<link rel="stylesheet" href="jiaman.css">
<div class="body">
<div class="box1">
  <!-- 定义第一张图片及其规格 -->
     <img src="5.jpg" alt="center"
     width="100px" height="100px">
     <!-- 无序列表且作为锚点链接到每一个对应的章节 -->
     <ul>
       <li><a href="#my" class="goDown"><h3>my</h3></a></li>
        <li><a href="#love" class="goDown"><h3>the person I love</h3></a></li>
        <li><a href="#hometown" class="goDown"><h3>my hometown</h3></a></li>
        <li><a href="#expectation" class="goDown"><h3>expectation</h3></a></li>
     </ul>
     <!-- 左边最底下的图片及其规格 -->
     <img src="7.jpg" alt=""
     width="150px" height="150px">
</div>
<div class="box2">
  <!-- 第一个章节内容以及右边图片的规格（用段落包裹图片） -->
       <div id="my">
         <p id="tupian"><img src="6.jpg" alt=""
           width="140px" height="200px" align="right"></p>
         <h2>陈嘉曼</h2>
         <p>一个来自广东汕头的女生。</p>
         <p>“嘉曼”在潮汕话的音译中是“只蚊”的意思，就是一个蚊子。
         所以我的好朋友都叫我阿蚊。</p>
         <p>我的性格比较乐观开朗，周围的人都说我没事经常傻笑~
         想到喜欢的事就会去做，貌似运气也不错，只要努力做自己的事就会有回报。</p>
       </div>
       <!-- 第二个章节的内容 -->
       <div id="love">
         <h2>我的父母</h2>
         <p>我的父母都是普通人，但是他们都很疼爱我。
         爸爸最近常说的话就是“谦虚使人进步，骄傲使人落后”，他们不会强求我去做我不喜欢的事，
         只要是我喜欢的都会支持我，也在我气馁的时候鼓励安慰我，是我心里最温暖的地方。</p>
         <h2>我的舍友</h2>
         <p>2016年9月2号，我们第一次在西六遇见了对方，带着大学的期盼和未知，我们一起前行。
         在过程中，我们有伤心有疲惫，但我们互相鼓励，像家人一样关心每一个人。小个子的yoyo，帅气的阿源，
         总是被我们抱大腿的大佬阿婷婷，正是你们才组成的我们这个小小温暖的小家庭。</p>
       </div>
       <!-- 用段落包裹右边盒子的左下角图片定义规格 -->
       <p id="tupian2"><img src="http://img.hb.aicdn.com/d0e0651f32b33330dd3ad3956a98fcf6073073fe1eb9d-iwIj4v_fw658" alt=""
         width="140px" height="340px" align="left"></p>
      <!-- 定义第三个章节内容 -->
       <div id="hometown">
         <h2>汕头</h2>
         <p>一座美丽的海滨城市，也是我成长的地方。</p>
         <p>汕头，又名鮀城，是中国大陆唯一一个中心城区拥有内海的城市。我们也有自己特色的方言：潮汕话。
         汕头也有许多美食，如汕头牛肉丸享誉全国，还有汕头的特色小食：笑枣、反沙芋等</p>
       </div>
       <!-- 定义第四个章节内容及采用了有序列表 -->
       <div id="expectation">
         <h2>我的期望</h2>
         <p>对于接下来大学四年，我充满了期待，我希望在大学期间能实现自己的期望。<p>
         <ol>
           <li>完成自己的学业，对自己最基本的作为一个学生的事情要做好</li>
           <li>坚持锻炼，身体是学习的本钱，努力成为更好的自己</li>
           <li>学习不同的知识，增长自己的见识，充实自己的精神世界</li>
         </ol>
       </div>
</div>
</div>

</body>
</html>
