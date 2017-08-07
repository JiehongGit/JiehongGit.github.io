---
layout: post
title: Jekyll+Github搭建个人博客
date: 2017-08-07 
tags: 博客   
---

### 介绍  

&#160; &#160; &#160; &#160;Jekyll是一个简单的免费的Blog生成工具，能够生成静态网页并且可以配合第三方服务，例如Disqus。最关键的是jekyll可以免费部署在Github上，而且可以绑定自己的域名。  
&#160; &#160; &#160; &#160;关于绑定自己的域名，有兴趣的小伙伴可以去了解了解。

### Github博客仓库

1、Start a project
<div ><img src="/images/posts/2017-08-07/StartAProject.png" align="center"/></div>

2、输入基本信息（注意：仓库名与账号对应）
<div ><img src="/images/posts/2017-08-07/Create.png" align="center"/></div>

3、在Settings当中选择主题theme
<div ><img src="/images/posts/2017-08-07/Settings.png" align="center"/></div>
<div ><img src="/images/posts/2017-08-07/Theme.png" align="center"/></div>
这样就完成了博客的基本搭建了！！

4、将Project从Github中git clone到本地
<div ><img src="/images/posts/2017-08-07/Git.png" align="center"/></div>

5、搭建目录结构

```
.
├── index.html
├── _config.yml
├── assets
│   ├── blog-images
│   ├── css
│   ├── fonts
│   ├── images├── _includes
│   └── javascripts
├── _includes 
├── _layouts
├── _plugins
├── _posts
└── _site

```
·index.html：网站的首页，访问http://username.github.io时，会指向http://username.github.io/index.html。

·_config.html：这是针对Jekyll的配置文件，决定了 Jekyll 如何解析网站的源代码。

·_includes：存放着一些模块文件。

·_layouts：存放着一些网页模板文件，为网站所有网页提供一个基本模板。

·_plugins：存放这一些Ruby插件。

·_posts：存放我们所有的博客文章。
具体的应用可以参考官方文档：[Enter](http://jekyll.com.cn/docs/structure/)

·_site：Jekyll 解析整个网站源代码后，会将最终的静态网站源代码放在这里。

### 环境配置

1、[Git环境](https://git-for-windows.github.io/)（用于部署到远端）  

2、[Ruby环境](https://rubyinstaller.org/downloads/)（Jekyll是基于Ruby开发的）

3、安装jekyll

```     
$ gem install jekyll     
```    

4、进入博客目录下（Git bash）

5、安装bundler命令
```
$ gem install bundler
```

6、执行下一条命令
```
$ bundle install
```

7、启动服务
```
$ bundle exec jekyll serve
```
这样就基本搭建完成了，可以进行博客的编写了。

### Write
开始你的表演吧！