# Reservation-System-hadoop-hdfs-mapreduce-
订餐系统+大数据的统计功能

网上订餐系统+大数据

开发环境：Windows7操作系统,Linux操作系统（CentOS虚拟机）

开发工具：Eclipse ,Tomcat8.0, MySql数据库,JDK-1.8,HBuilder,Vmware

项目描述：

该项目是专业实训时所做的一个java web项目，其中结合了大数据的相关知识并设计开发了大数据的功能模块
网上订餐系统是为了满足用户进行线上订餐的需求来设计与实现的项目，分为前台展示与后台管理两个部分，基本符合用户订餐的需求。
系统具有基本订餐系统的功能同时，加入了菜品热度的统计功能，此功能结合了大数据分布式计算，统计出各省份热度最高的菜品进行展示。

技术描述：

本项目中主要用到HTML+CSS+JS+JSP+JSTL等前端页面技术；
数据库使用MySql数据库；
后台用到Servlet等技术；
主要采用的是MVC的设计模式进行开发，数据交互层dao、业务逻辑层service、表示层jsp、实体层entity；
大数据的环境采用虚拟机搭建集群的方式，将菜品数据存放在hdfs上，使用MapReduce进行计算，采用echarts插件进行展示。

1>	项目前端显示采用JSTL技术显示商品，商品信息从后台输入进数据库然后获取出来，前端页面采用CSS进行样式设计，实现多种显示风格。 

2>	用户注册时采用与数据库匹配判断用户名是否存在，并使用JS验证用户注册信息并提示相应错误输入提示。

3>	用户通过购物车提交的订单数与销售排行进行了同步设置，并可以通过提交的订单进行后台记录查询。

4>	大数据模块前台进行的是菜品热度的展示，通过echarts插件把计算后的结果显示在地图上，后台开辟了一个hdfs文件管理的模块，可以连接到hdfs进行文件的查看删除以及下载等功能。 

5>	项目中还包含公告管理，菜品类别管理，订单管理等其他功能。
