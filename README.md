# Folk

> [Click here to read the English documents.](https://github.com/envirs/folk/blob/master/README_en.md)

Folk是一个轻量、便携，同时又很强大且可高度定制的内容发布平台。Folk的目标是：让您可以轻松地与世界分享您的点滴。

Folk使用世界流行的javascript语言开发，因此可以同时运行于node和asp(非.net)。其中，node版本支持sqlite(推荐)和mysql两种数据库，而asp版本则同时支持access、mssql、mysql和sqlite四种数据库。这两个版本的核心代码完全相同，因此对应的主题和插件也可以做到同时兼容。

Folk的核心程序是轻量的，只提供最基础的文章和用户功能，让您能够非常快速地上手。同时，Folk也支持自定义主题，让您的网站更加个性化。而强大的插件系统，则可以让您在Folk的基础上，扩展出您所能想像的任何功能，甚至将她变成一个cms系统。

Folk默认使用markdown语法来撰写日志，但是Folk也支持通过插件来使用可视化的html编辑器，让您自由选择、随心书写！

## 快速安装手册

1. 从install/目录下载对应版本的安装文件；
2. 将解压后的install文件夹（包括install文件夹本身）上传至网站根目录；
3. 对于asp版本，访问`http://您的域名/install`，然后根据提示进行安装；
4. 对于node版本，在命令行执行`node install`，然后根据提示进行安装；
5. 安装完毕，删除install目录。
6. 对于asp版本，访问`http://您的域名/control.asp`进入管理后台
7. 对于node版本，先`node index.js`启动网站服务，然后访问`http://您的域名/control`进入管理后台

## 文档

[详细安装:](https://github.com/envirs/folk/blob/master/documents/cn/%E5%AE%89%E8%A3%85%E6%8C%87%E5%AF%BC%E6%96%87%E6%A1%A3.md)

[主题开发:](https://github.com/envirs/folk/blob/master/documents/cn/%E4%B8%BB%E9%A2%98%E5%88%B6%E4%BD%9C%E6%96%87%E6%A1%A3.md)

[插件开发:](https://github.com/envirs/folk/blob/master/documents/cn/%E6%8F%92%E4%BB%B6%E5%88%B6%E4%BD%9C%E6%96%87%E6%A1%A3.md)

## 开发计划

### 云平台

云平台是一个将广大博主形成联盟生态圈的线上系统，可以让用户在写作之余，方便地认识更多朋友、向更多志同道合的人展示自己的网站。

同时，您还可以在云平台上分享或者出售您的主题、插件等，也可以在平台上广招英雄，来帮助您实现所需要的功能！

### APP

在今天这个移动互联网时代，随时随地使用手机分享自己此刻的想法或者拍下的照片，当然是必不可少的。所以，我们会在后续推出方便好用的配套APP，让这一切更加美好。

## 关于PJBlog与Folk

PJBlog是一个历史悠久(源于2004年)的ASP博客程序，在国内有着广泛的用户基础。在经过十来年的发展之后，显然她已经有些跟不上时代的发展了。于是我们于2014年开始研发全新理念的PJBlog5, 并在两年后推出同时兼容node和asp平台的全新版本，并以Folk作为开发代号。

## 版权与许可

PJBlog项目由陈子舜发起，Folk版本由沈赟杰和刘彬共同开发，因此版权归陈子舜、沈赟杰和刘彬共同所有。

任何组织和个人在不移除版权标识及链接的前提下，可以免费使用；但是作为大型商业盈利用途的情况除外。

任何组织和个人使用本程序发布的内容皆属于其自由意志，本程序开发团队不承担任何法律连带责任。