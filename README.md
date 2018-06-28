# 微信小程序
小程序笔记和项目

## 什么是小程序？ 
  小程序是一种不需要下载安装即可使用的应用，它实现了应用“抽手可及”的梦想
  用户扫一扫或者搜一搜即可打开应用，也体现了“用完即走”的理念
  用户不用关心是否安装太多应用的问题。应用将无处不在，随时可用，但又无需安装卸载。
  
  
## 小程序 VS app应用 

  无需安装  不占内存   易传播 
  
  
## 小程序催生的产业链？ 

  游戏 （小游戏、游戏开发商）
  第三方服务 
  创业者  （出行、内容、交通）
  运营者   （社群、电商、生活）
  传统行业  （餐饮、出行）
  应用商店 
  金融
  门店
  互联网公司 
  投资机构
  媒体
  分析工具
  
 ## 小程序开发准备工作 
 
  注册小程序账号 ------ 激活邮箱 ---------信息登记  -------登陆小程序管理后台 ----- 完善小程序信息 -------绑定开发者 
  
 ## 小程序 代码结构与基本配置 
  
   app.js 
   app.json
   app.wxss
   project.config.json
   pages
   utils
   
   window:
   navigationBarBackgroundColor
   navigationBarTextStyle
   navigationBarTitleText
   backgroundColor
   backgroundTextStyle
   onReachBottomDistance
   enablePullDownRefresh 
   
   app: Pages  tabBar newworkTimeout  debug navigationStyle  
   page: disableScroll
   
 ## 微信小程序开发框架 
  ### WXML 是框架设计的一套标签语言，结合组件、wxs和事件系统，可以构建出页面的结构 
    1.数据绑定
    2.列表渲染
    3.条件渲染
    4.模版引用   import include 
  
    属性 ：
      id        组件的唯一标示
      class     组件的样式类
      style     组件的内联样式
      hidden    组件是否显示 默认显示
      data- *     自定义属性
      bind*/catch*  组件的事件
  
  
  ### WXSS 是一套样式语言，用于描述WXML的组件样式 
      尺寸单位 rpx
      样式导入  @import
      内联样式
      选择器 
      
      优先级 ： 
      !important   ∞
      style     1000
      #element  100
      .element  10
      element   1
      
  ### JavaScript
      javascript 是一种轻量的、解释型的、面向对象的头等函数语言，是一种动态的基于原型和多范式脚本语言，支持面向对象、命令式和函数是的编程风格。
      
      推荐两本书： JavaScript 高级程序设计  JavaScript权威指南 
      
       iOS                   Android               IDE
  
       JavaScript            X5 内核               nwjs 
 
  ### wxs 
  
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
   
   
   
