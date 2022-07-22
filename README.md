# 项目名称

[含论文+源码等]SSH超市进销存管理系统

# 系统介绍
开发本超市进销存管理系统的主要目标是方便企业对商品、客户和员工信息的实时掌控，提高企业的工作效率。本系统是采用J2EE开发的一个基于B/S架构的Web项目，运用SSH开源框架进行逻辑功能的整合，MySQL作为数据库存储载体，编程思想采用MVC设计模式，使系统模块合理结构清晰。本系统的主要功能包括供应商管理、客户管理、商品管理、统计报表，其中商品管理分为商品信息管理、进货管理、销售管理、库存管理，报表统计可以按日查询和按月查询资金的出纳情况，整个系统逻辑清晰合理，开发完成后系统实用性能良好。

# 环境需要

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。\
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;\
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可\
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS； \
5.数据库：MySql 5.7版本；\
6.是否Maven项目：否；

# 技术栈

1. 后端：Spring+SpringMVC+Mybatis\
2. 前端：JSP+CSS+JavaScript+jQuery

# 使用说明

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；\
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;\
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；\
3. 将项目中springmvc-servlet.xml配置文件中的数据库配置改为自己的配置;\
4. 运行项目，在浏览器中输入http://localhost:8080/ 登录

# 高清视频演示

https://www.bilibili.com/video/BV1TT411E7vq/


​