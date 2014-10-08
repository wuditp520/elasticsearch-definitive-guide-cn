# 入门

Elasticsearch是一个实时分布式搜索和分析引擎。他让你可以以前所未有的速度处理大数据成为可能。

它用于全文搜索、结构化搜索、分析以及将这三者合并：

* 维基百科使用Elasticsearch提供全文搜索并高亮关键字，并提供**输入即时搜寻(search-as-you-type)**和**搜索纠错(did-you-mean)**等搜索建议功能。

* 英国卫报使用Elasticsearch综合用户日志和社交数据提供实时的反馈给他们的编辑，以便及时获得公众反馈。

* StackOverflow将全文搜索与地理位置和相关信息进行结合，以提供**more-like-this**功能来找到相关问题的答案。

* Github使用Elasticsearch检索1300亿行的代码。

但是Elasticsearch不仅用于大型企业，它还让像DataDog以及Klout的创业公司将最初的想法变成可扩展的解决方案。Elasticsearch可以在你的笔记本上运行，也可以在数以百计的服务器上处理PB级别的数据。

Elasticsearch每个独立部分都不是创新或者革命性的。在全文搜索中早已被实现，统计系统和分布式数据库也早已存在。它的革命之初在于整合这些独立的功能在单一的、连贯的和实时的程序中。它对新用户的门槛很低，当然它也会跟上你技能和需求增长的步伐。

你之所以拿起这本书，是因为你有数据，在用这些数据计划做些事情前并不知道怎么去使用它们。

很不幸，现在很多数据库对于提取可用只是方面非常无能。当然，它们能够通过时间戳或者精准字段值过滤，但是能够执行全文搜索，处理同义词和根据相关性给文档打分吗？它们能够生成分析和聚合相同内容数据吗？最重要的是，面对如此庞大的数据，它们能够做到实时处理吗？

这就是Elasticsearch存在的理由：Elasticsearch鼓励你浏览并利用你的数据，而不是让它烂在数据库里，应为在库里太难查询了。

Elasticsearch是你最好的朋友。
