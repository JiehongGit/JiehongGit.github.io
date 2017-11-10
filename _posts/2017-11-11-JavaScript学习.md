---
layout: post
title: JavaScript学习
date: 2017-11-11 
tags: Web前端   
---

### 介绍

* JavaScript是一款运行在客户端的网页编程语言。  

### 组成部分  
* ecamascript：js标准  
* dom：通过js操作网页元素  
* bom：通过api操作浏览器  

### 特点  
* 简单易用  
* 解释执行  
* 基于对象

### 应用
* 表单验证
* 轮播特效
* 游戏开发 

### JS书写位置
* 内嵌式  

```
<script type="text/javascript">
		alert("javascript学习");
</script>
```
推荐将JS代码写在html结束标签后面  

* 外链式

```
<script src="1.js"></script>
```
1. 先创建一个外部JS文件  
2. 通过src将外部JS调用

### 页面输出消息的方式  
* `alert("")`：在页面弹出一个对话框，早期JS调试使用  
* `confirm("")`：在页面弹出一个对话框  
* `console.log("")`：将信息显示到控制台