---
layout:     post
title:      手浪前端技术博客成立啦!
date:       2015-07-09 12:31:19
img:        /wiki/images/cover.jpg
summary:    手机新浪网前端开发团队Blog，在github pages安家了！
categories: technology
---

![](/wiki/images/cover.jpg)

手机新浪网前端开发团队Blog，在github pages安家了！

为了积攒在移动端的开发经验，分享我们每天开发的乐趣和经验，特别在github上开启了团队的wiki和blog。

下面分享一下如何利用github来搭建一个免费开源又很geek的Blog.

首先本blog基于jekyll和github pages，jekyll是一套使用ruby开发的开源静态博客工具，并且有github原生天然的支持特性，可以很方便利用开发属于自己的Blog站点。

在mac os下使用gem安装jekyll十分方便：

{% highlight bash %}
$ gem install jekyll
$ jekyll new myblog
$ cd myblog
$ jekyll serve
{% endhighlight %}

只需要四部命令，本地就启动了一个静态blog，并且默认使用markdown语法书写，十分方便快捷。

如果是windows的小伙伴，不方便安装ruby环境，那么也有对应的nodejs替代程序。

{% highlight bash %}
$ npm install darko -g
$ cd myblog
$ darko serve
{% endhighlight %}

同样可以实现本地预览。

在`_post`目录书写完blog文章之后，只需要使用git客户端commit+push 就可以完成blog的更新了。

当然在此之前需要在对应的repo中建立gh-pages分支，把jekyll建立的目录提交，才可以，一般github pages需要15-20分钟的生效时间。

第一次建立完毕之后，更新就是实时的了。

我们这次采用的模板是<a href="https://github.com/ee0703/pixyll-zh-cn">pixyll</a>的汉化版本，十分感谢作者提供如此简洁和优雅的Theme!

OK，有更多使用的问题可以在本文之下留言，对应已经增加了多说模块，以后有技术文章会多多PO到本BLOG中。
