# text5
第五次测试
Github 高级搜索功能

GitHub 提供高级搜索方式。

一、明确搜索仓库标题、仓库描述、README

1.只想查找仓库名称包含XX的仓库。语法：

　　 in:name 关键词

2.查找描述的内容

　　in:descripton 关键词

3.查README文件包含特定关键词

　　in:readme 关键词

二、明确搜索 star、fork 数大于多少的

1. star 数大于 1000 的XX 仓库

　　stars: > 数字 关键字

2.star 数在某个区间 的XX 仓库

　　stars: 10..20 关键词

 三、明确搜索仓库大小的

搜索限定size的仓库

　　size:>=5000 关键词

注意：这个数字代表K, 5000代表着5M

四、明确仓库是否还在更新维护

　　指定时间之前或之后创建或更新的仓库

 　　pushed:>2019-01-03 关键字    //在xx时间后还有更新

　　 created:>2019-01-03 关键字   //在xx时间后创建

五、明确搜索仓库的 LICENSE

　　寻找协议为 Apache License 2 的代码

　　license:apache-2.0 关键词

六、明确搜索仓库的语言

　　language:java 关键词

七、明确搜索某个人或组织的仓库

       user:userName

      user:userName language:java

      org:spring-cloud
