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

