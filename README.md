lemur-generation
----------------------
新一代代码生成器 秒数开发
----------------------
	
	Gen是我构思了挺久的一个代码生成项目,之前零零散散也写了不少代码生成,
	但是很多都不太理想不能够满足通用性和特殊定制性的需求,
	每次生成出来还要改一部分的代码,很难做到0修改,而这个就是为了做到让大家0修改上线的一个小系统,
	帮减少大家的开发时间,专注于业务开发.而不是写这些单纯的CURD.功能强大的代码生成器,
	点一下就可以完成我们想要的,定制容易,二次开发简单,可远程可以本地
	一个通用版本的代码生成器,不单单局限于自己用,可以分享,可以浏览别人的代码
	好的代码是可以共享,好的代码也是促进开发的

**QQ群**

	官网： http://www.afterturn.cn/
	邮箱： qrb.jueyue@gmail.com
	QQ群:  364192721
	

**使用指南**

**[http://lemur-gen.mydoc.io/](http://lemur-gen.mydoc.io/)**

**线上环境,支持直接使用,不需本地安装,注册即可使用**

**[gen.afterturn.cn](gen.afterturn.cn)**


功能
---------
|功能|子功能|进度|开始时间|版本支持|
|----|----|----|----|----|
|数据库管理| |80%|2017-9-01|1.0|
| | CURD|100%|2017-9-01|1.0|
| | 密码加密| | | |
|表管理| |0%| | |
| |CURD| | | |
| |数据库生成表| | | |
| |SQL生成表| | | |
| |JSON生成表| | | |
| |XML生成表| | | |
|模板管理| |80%|2017-9-01|1.0|
| | CURD|100%|2017-9-01|1.0|
| |语法高亮|100%|2017-9-01|1.0|
| |分享| | | |
|模板组管理| |100%|2017-9-01|1.0|
| | CURD|100%|2017-9-01|1.0|
|参数管理| |100%|2017-9-01|1.0|
| | CURD|100%|2017-9-01|1.0|
|代码生成| |30%|2017-9-01|1.0|
| | Mysql|100%|2017-9-01|1.0|
| | Oracle| | | |
| | SqlServer| | | |
| | PostgreSQL| | | |




启动方法
-----------
    1. 下载代码
    2. 导入gen.sql的SQL
    3.运行 GenApplication
    4.访问 localhost
    5.登录 admin/111111

***使用方法***

    1.在数据库管理,新建数据库连接
    2.模板分组建立自己的模板分组
    3.参数管理建立自己的参数
    4.建立自己的模板
    5.代码生成,选择想要生成的表

界面演示
----------------------------------------------------------------------------------

![代码生成界面](https://git.oschina.net/uploads/images/2017/0913/214120_a097692e_69288.png "gencode.png")

![组](https://git.oschina.net/uploads/images/2017/0913/215434_b40e7468_69288.png "group.png")

![db](https://git.oschina.net/uploads/images/2017/0913/215453_fb373cfc_69288.png "db.png")

![tt](https://git.oschina.net/uploads/images/2017/0913/215501_81a29e95_69288.png "params.png")


![ttt](https://git.oschina.net/uploads/images/2017/0913/215537_c0e2a3b6_69288.png "template.png")