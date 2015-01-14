#JavaOpenSource
==============

The usefull open source projects

##时间处理
###JodaTime （整理自http://www.oschina.net/p/joda-time）
https://github.com/JodaOrg/joda-time
JodaTime 提供了一组Java类包用于处理包括ISO8601标准在内的date和time。可以利用它把JDK Date和Calendar类完全替换掉，而且仍然能够提供很好的集成。

Joda-Time主要的特点包括：

1. 易于使用:Calendar让获取"正常的"的日期变得很困难，使它没办法提供简单的方法，而Joda-Time能够 直接进行访问域并且索引值1就是代表January。
2. 易于扩展：JDK支持多日历系统是通过Calendar的子类来实现，这样就显示的非常笨重而且事实 上要实现其它日历系统是很困难的。Joda-Time支持多日历系统是通过基于Chronology类的插件体系来实现。
3. 提供一组完整的功能：它打算提供 所有关系到date-time计算的功能．Joda-Time当前支持6种日历系统，而且在将来还会继续添加。有着比JDK Calendar更好的整体性能等等。

##网络类
![](http://www.oschina.net/uploads/img/200902/16210315_WPfm.png)

Apache MINA(Multipurpose Infrastructure for Network Applications) 是 Apache 组织一个较新的项目，它为开发高性能和高可用性的网络应用程序提供了非常便利的框架。当前发行的 MINA 版本支持基于 Java NIO 技术的 TCP/UDP 应用程序开发、串口通讯程序（只在最新的预览版中提供），MINA 所支持的功能也在进一步的扩展中。

###ps:Mina user guide 有中文版文档

在线Javadoc：http://tool.oschina.net/apidocs/apidoc?api=mina

##图形类
###JFreeChar (整理自http://www.oschina.net/p/jfreechart)

JFreeChart主要用来各种各样的图表，这些图表包括：饼图、柱状图(普通柱状图以及堆栈柱状图)、线图、区域图、分布图、混合图、甘特图以及一些仪表盘等等。
http://www.jfree.org/jfreechart/index.html

![](http://www.oschina.net/uploads/img/201009/16163301_Zf9R.png)
![](http://www.oschina.net/uploads/img/201009/16163302_vtQq.png)
![](http://www.oschina.net/uploads/img/201009/16163302_LcuR.png)
![](http://www.oschina.net/uploads/img/201009/16163303_o2Rh.png)
![](http://www.oschina.net/uploads/img/201009/16163304_RqwE.png)
![](http://www.oschina.net/uploads/img/201009/16163304_41ZM.png)
![](http://www.oschina.net/uploads/img/201009/16163305_mP2E.png)
![](http://www.oschina.net/uploads/img/201009/16163305_Oyt0.png)
![](http://www.oschina.net/uploads/img/201009/16163305_gBl2.png)
![](http://www.oschina.net/uploads/img/201009/16163306_WYfH.png)
![](http://www.oschina.net/uploads/img/201009/16163306_6NbQ.png)
![](http://www.oschina.net/uploads/img/201009/16163307_YBrc.png)

##搜索类
###Lucene(整理自http://www.oschina.net/p/lucene)

Lucene 是apache软件基金会一个开放源代码的全文检索引擎工具包，是一个全文检索引擎的架构，提供了完整的查询引擎和索引引擎，部分文本分析引擎。Lucene的目的是为软件开发人员提供一个简单易用的工具包，以方便的在目标系统中实现全文检索的功能，或者是以此为基础建立起完整的全文检索引擎。

Lucene最初是由Doug Cutting所撰写的，是一位资深全文索引/检索专家，曾经是V-Twin搜索引擎的主要开发者，后来在Excite担任高级系统架构设计师，目前从事 于一些INTERNET底层架构的研究。他贡献出Lucene的目标是为各种中小型应用程式加入全文检索功能。

OSChina 使用 Lucene 实现全文搜索。

在线Javadoc：http://tool.oschina.net/apidocs/apidoc?api=lucene-3.6.0

##工具集合
###jodd （整理自http://www.oschina.net/p/jodd）

https://github.com/oblac/jodd

odd 被分成众多模块，按需选择，其中

	  工具类模块有：
	  jodd-core        一些工具类，包括Printf、JDateTime、StringUtil、Fast buffers等等
	  jodd-bean        BeanUtil以及类型检查转换工具
	  jodd-props       更强大的Java Properties替代
	  jodd-email       更简单易用的e-mail收发
	  jodd-upload      处理HTTP上传
	  jodd-servlets    一些Servlet相关的工具类, 附带一套漂亮的JSP标签库
	  jodd-http        轻巧的HTTP客户端
	  小型框架模块有：
	  jodd-madvoc      一个MVC框架
	  jodd-petite      一个依赖注入容器
	  jodd-lagarto     HTML/XML解析器，包含Jerry和CSSelly，让你像jQuery一样筛选HTML节点
	  jodd-lagarto-web Lagarto的Web扩展，包含Decora、HtmlStapler等等
	  jodd-proxetta    帮你实现动态代理，获取函数参数名
	  jodd-dboom       数据库访问的轻量级封装，可看作一个简单的ORM
	  jodd-json        JSON解析、序列化
	  jodd-vtor        一个基于注解的字段验证框架

##开源项目类

###版本控制：GitLab

官方网站 https://about.gitlab.com/ (IBM，)

开源中国代码托管平台 git.oschina.net 就是基于 GitLab 项目搭建。

GitLab是一个利用 Ruby on Rails 开发的开源应用程序，实现一个自托管的Git项目仓库，可通过Web界面进行访问公开的或者私人项目。

它拥有与Github类似的功能，能够浏览源代码，管理缺陷和注释。可以管理团队对仓库的访问，它非常易于浏览提交过的版本并提供一个文件历史库。团队成员可以利用内置的简单聊天程序(Wall)进行交流。它还提供一个代码片段收集功能可以轻松实现代码复用，便于日后有需要的时候进行查找。

GitLab 5.0以前版本要求服务器端采用 Gitolite 搭建，5.0版本以后不再使用 Gitolite ，采用自己开发的 gitlab-shell 来实现。如果你觉得安装麻烦可以使用 GitLab Installers 一键安装程序。

系统要求：

Ubuntu/Debian
ruby 1.9.3+
mysql or postgresql
git
gitlab-shell
redis
Sidekiq

![](./img/gitlab_demo.png)

Gitlab 的集群解决方案
![](./img/gitlab_framework.png)
![](./img/gitlab_users.png)

#开源IDEA插件

https://github.com/pbreault/adb-idea

IntelliJ plugin / Android Layout ID Converter
https://github.com/funnything/OffingHarbor
