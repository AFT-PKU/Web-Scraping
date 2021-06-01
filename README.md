# Web-Scraping学习笔记

## 前言

&emsp;&emsp;这个项目记录了北京大学AFT协会对Web-Scraping的学习笔记，同时也特别感谢 @路飞学城IT 录制的[学习视频](https://www.bilibili.com/video/BV1i54y1h75W?p=1)

&emsp;&emsp;除了学习视频之外，我们也推荐其他一些学习资料：[《Python爬虫开发与项目实战》](Python网络数据采集.pdf)，[requests文档](https://docs.python-requests.org/zh_CN/latest/)，[《Python3网络爬虫开发实战》](https://pan.baidu.com/s/1QDsG1jupCmXWS_J5O45-9g)，[《Python爬虫开发与项目实战》](https://pan.baidu.com/s/1xiMej4cuhlrw9Sxv_hhFSw)


## 目录

1. [绪论——搭建SQL的学习环境](绪论——搭建SQL的学习环境)
    1. PostgreSQL的安装和连接设置
    1. 通过PostgreSQL执行SQL语句
1. [数据库和SQL](数据库和SQL)
    1. 数据库是什么
    1. 数据库的结构
    1. SQL概要
    1. 表的创建
    1. 表的删除和更新
1. [查询基础](查询基础)
    1. SELECT语句基础
    1. 算术运算符和比较运算符
    1. 逻辑运算符
1. [聚合排序](聚合与排序)
    1. 对表进行聚合查询
    1. 对表进行分组
    1. 为聚合结果指定条件
    1. 对查询结果进行排序
1. [数据更新](数据更新)
    1. 数据的插入（INSERT语句的使用方法）
    1. 数据的删除（DELETE语句的使用方法）
    1. 数据的更新（UPDATE语句的使用方法）
    1. [事务]()
1. [复杂查询](复杂查询)
    1. 视图
    1. 子查询
    1. 关联子查询
1. [函数、谓词、CASE表达式](函数、谓词、CASE表达式)
    1. 各种各样的函数
    1. 谓词
    1. CASE表达式
1. [集合运算](集合运算)
    1. 表的加减法
    1. 联结（以列为单位对表进行联结）
1. [SQL高级处理](SQL高级处理)
    1. 窗口函数
    1. GROUPING运算符
1. [通过应用程序连接数据库](通过应用程序连接数据)
    1. 据库世界和应用程序世界的连接
    1. Java基础知识
    1. 通过Java连接PostgreSQL

>持续更新中，欢迎贡献便于理解的优秀代码示例，推荐使用Python代码和Jupyter Notebook提交，并附上说明。

致谢
--------------------
我们分为两个类别的贡献者。
 - 负责人也就是对应的该章节案例维护者。
 - 贡献者对应于主要的案例开发者。

| 学习时间 | 原书章节 | 对应案例  | 小组 | 贡献者 |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| 03.23 | 第零章 绪论——搭建SQL的学习环境 | [绪论——搭建SQL的学习环境](绪论——搭建SQL的学习环境/绪论——搭建SQL的学习环境.md) |  | @CharlieSCC |
| 04.01 | 第一章 数据库和SQL | [数据库和SQL](数据库和SQL/查询基础.md) | | @jiangxunmu |
| 04.02-04.12 | 第二章 查询基础 | [查询基础](查询基础/查询基础.md) | 1  | 宁 磊，张 婷， 商陈诚 |
| 04.02-04.12 | 第三章 聚合排序 | [聚合排序](聚合与排序/聚合与排序.md) | 1  | 宁 磊，张 婷， 商陈诚 |
| 04.13-04.19 | 第四章 数据更新 | [数据更新](数据更新/数据更新.md) | 2 | 李琳雄， 胡扬帆 |
| 04.20-04.26 | 第五章 复杂查询 | [复杂查询](复杂查询/复杂查询.md) |  3| 杨子峻， 刘安诺 |
| 04.27-05.03 | 第六章 函数、谓词、CASE表达式 | [函数、谓词、CASE表达式](函数、谓词、CASE表达式/读书笔记.md) | 4 | 徐  航，张  榕  |
| 05.04-05.10 | 第七章 集合运算 | [集合运算](集合运算/集合运算.md) | 5 | 胡潇尹， 张曼娴 |
| 05.11-05.18 | 第八章 SQL高级处理 | [SQL高级处理](SQL高级处理/SQL高级处理.md) | 6 | 封宇泽， 王梦婕 |
| 05.18-05.24 | 第九章 通过应用程序连接数据 | 哈佛CS50课 | 7 | 叶梦婕， 蔡紫宴， 曾涛涛 |


还有很多同学提出了不少建议，我们都列在此处。

@CharlieSCC  @jiangxunmu ...

如有遗漏，请务必通知我们，可以发邮件至`pkuscc@stu.pku.edu.cn`。
这是我们必须要感谢的，所以不要不好意思。
