##node替换淘宝npm镜像
国外npm由于在国外，网速太慢，有时还会出现无法链接的现象。淘宝给出了一个解决办法就是[国内镜像](https://npm.taobao.org/)，npm.taobao.org。
并且官方团队给出了安装方法
然而：
我并没有安装成功（大写的尴尬）
最后找到一个方法，更改了npm镜像源地址为淘宝源，安装速度提升了不少，但是还是不能使用cnpm命令
方法如下：
1. 在nodejs文件夹下nodejs/node_modules/npm/npmrc文件
2. 打开编辑
添加语句：

        registry = http://registry.npm.taobao.org

这样npm下载安装软件时就会从指定的镜像中下载了。

        本地版本:
        nodeV4.4.4
        npm v 2.15.1

小码农博客，一个入门码农的学习记录平台，分享wordpress、joomla、laravel、web前端等资料和教程。


小码农博客,小码农,小码农在线,萧逸雨,夏秋波,PHP学习,wordpress学习,larave学习l,web前端学习,交流学习


http://www.weibo.com/xiaqiubo
https://twitter.com/xiaqiubo123
https://cn.linkedin.com/in/xiaqiubo
https://github.com/xiaqiubo