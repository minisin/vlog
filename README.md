#介绍
vLog 是一个轻量级的日志/博客系统,使用Markdown格式书写博文, 使用tornado和MySQL驱动,创建它的目的是因为wordpress虽然优秀,但是我喜欢自己的东西,想要加什么就加什么,我又不喜欢写php所以使用Python写了一个,现在只提供了最基本的功能,写文章....,后台其余的都没写,因为我是一个非常讨厌写Web前端了,所以现在实现了基本功能,其余的以后会慢慢加上,令也希望有喜欢前台,喜欢开源的可以加入到这个项目

#安装
##平台
* Linux
* python2.7+
* MySQL


## 依赖包
* tornado
* jinja2
* MySQLdb

## 开始安装
首先确认config.py的DEBUG是打开的,然后执行run.py,打开浏览器输入当前地址,会跳转到安装页面.按照提示安装,安装完毕后可以关闭DEBUG

#结合nginx
参阅[tornado文档](http://www.tornadoweb.cn/documentation#_14)
