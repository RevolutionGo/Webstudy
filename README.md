# 前端开发
## 项目：[田野打架网-战地玩家的俱乐部](https://revolutiongo.github.io/Webstudy/Web/)
### 一、项目简介
>本站作为“战地”系列游戏资讯网，旨在为“战地”玩家提供一个集游戏资讯、新闻、评论、视频等内容的专门平台，集中提供Battlefield系列游戏资讯，相比于传统游戏资讯网的内容冗杂、界面杂乱、广告众多，本网站以简洁明快的界面设计和合理的内容分区向玩家提供零广告的资讯服务。
### 二、项目内容
#### 1.目录
  * 首页 index.html
  * 资讯页 review.html
  * 新闻评论页 single.html
  * 图集页 gallery.html
  * 反馈页 contact.html 
  * 登录页 sign-in.html
  * 注册页 sign-.html
  * 忘记密码 forgot.html
  * 资源包 assets
#### 2.内容简介
  * 首页主要利用轮播图向访客展示游戏宣传图，在首页还嵌入了游戏视频区，方便访客在首页直接播放视频。
  * 资讯页一改传统游戏门户网站各种冗杂列表的资讯标题展示方式，使用缩略图展示各资讯入口。
  * 新闻评论页主要显示详细文章内容和访客评论
  * 图集页用于向访客展示精彩游戏图片
  * 反馈页提供访客联系站长的入口及联系地址的百度地图
#### 3.开发技术
主要研究了浏览器兼容性与响应式设计方面的问题，本站兼容IE7，采用了响应式设计，可以较好地兼容移动端
##### html
  * 利用iframe嵌入视频网站和百度地图
  * viewport元标签
##### css
  * 利用bootstrap 栅格系统进行页面布局
  * 鼠标悬停图片变灰
  * 使用伪类、伪元素
  * 媒体查询@media 指令
  * 使用了一个有趣，酷炫的，跨浏览器的CSS3动画库[animate.css](https://www.cnblogs.com/xiaohuochai/p/7372665.html)
##### js  
  * 使用了[responsiveslides.js](https://www.w3cways.com/1653.html)实现轮播图
  * 使用[lightbox.js](http://code.ciaoca.com/jquery/lightbox2/)实现灯箱效果
  * 使用[flexisel.js](http://www.511yj.com/wordpress-flexisel-js.html)响应适应屏幕宽度旋转木马插件
  * 使用[Waypoints.js](http://www.bcty365.com/content-47-2583-1.html)实现滚动监听
  * 使用[jquery.placeholder.min.js](https://www.cnblogs.com/chiangyibo/p/6938250.html)让IE6+支持placeholder。
  * 使用[modernizr.js](http://caibaojian.com/modernizr-js.html)检测浏览器的css3和HTML5的属性，从而通过CSS来解决兼容性问题。
  * 使用[Respond.js](https://www.cnblogs.com/xcsn/p/5586859.html)让IE6-8支持CSS3 Media Query，兼容响应式布局。

  
