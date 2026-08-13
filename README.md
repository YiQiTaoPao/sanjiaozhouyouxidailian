
# 电竞护航下单系统 | UniApp + ThinkPHP6

2026年最火的游戏模式，三角洲等游戏的护航陪玩模式，面向游戏工作室、代练工作室、电竞护航工作室打造的订单管理交易系统，一套完整前后端开源方案，快速搭建电竞护航、游戏代练线上下单平台。

## 🛠️ 技术栈

-   前端：UniApp，支持编译 H5、微信小程序、App 多端
-   后端：ThinkPHP6 RESTful API
-   数据库：MySQL，支持 Redis 缓存拓展

## ✨ 核心功能

### 后台管理端

-   游戏分类管理，自定义游戏列表
-   护航商品发布，支持多规格价格、多属性配置、多图片上传
-   订单统一管理，接单操作，录入打手信息，订单完结处理
-   用户管理、资金配置、支付渠道配置、退款审核

### 用户客户端

-   用户注册登录，个人中心
-   浏览护航商品，在线下单
-   支付方式：微信支付、账户余额支付
-   完整订单流程：待接单、进行中、已完成、退款申请
-   订单详情查询，提交退款申请
-   余额明细、消费记录查看

## 🎯 项目优势

1.  专为电竞护航、游戏代练工作室业务场景定制，贴合行业流程
2.  UniApp 多端适配，小程序 / H5/App 任选上线
3.  商品支持多规格多价位，满足不同段位、时长护航套餐需求
4.  订单闭环完整：下单→支付→后台接单→登记打手→完成 / 退款
5.  双支付模式，余额体系便于工作室老客户复购结算
6.  代码分层清晰，易于二次开发、自定义功能迭代

## 📌 适用主体

电竞护航工作室、游戏代练工作室、游戏陪玩工作室、线上游戏服务交易团队

## 🚀 部署简述

1.  后端部署 PHP 环境，导入数据库，配置数据库与支付参数
2.  HBuilderX 打开 UniApp 前端项目，修改后端接口地址
3.  编译打包对应端（小程序 / H5/App）即可投入使用

## 💡 说明

欢迎 Star 收藏，有功能优化需求可提交 Issue。支持二次定制开发，商用使用请遵守相关法律法规。


 ![输入图片说明](http://www.51duoke.cn/quanzi/dailian/naotu.png)


 ![输入图片说明](https://www.51duoke.cn/quanzi/dailian/qun.png)



前后端+后端下载地址：https://gitee.com/zhangshangshidai/dailianhuhang

演示地址:https://dailian.demo.51duoke.cn/h5

后端体验：https://dailian.demo.51duoke.cn/admin

账号admin  密码123456

后端程序目录
===============

**系统需求**

- PHP 7.3
- MySQL 5.6
- Redis

## uniapp安装

将前端UNI目录导入到你的HBuilder里

修改siteinfo.js 里的域名为你的域名即可



## 后端安装
将后端php代码放到你的网站根目录

====运行WEB目录====
public

====数据库====
导入目录下的  数据库.sql 文件
修改目录下的  .env 数据库配置

配置文件路径/.env
~~~
APP_DEBUG = true

[APP]
DEFAULT_TIMEZONE = Asia/Shanghai

[DATABASE]
TYPE = mysql
HOSTNAME = 127.0.0.1 #数据库连接地址
DATABASE = test #数据库名称
USERNAME = username #数据库登录账号
PASSWORD = password #数据库登录密码
HOSTPORT = 3306 #数据库端口
CHARSET = utf8
DEBUG = true


~~~
3.修改目录权限（linux系统）777
/public


====后台登陆====
http://域名/admin
默认账号：admin 密码：123456

 ### 前端页面展示


![输入图片说明](https://www.51duoke.cn/quanzi/dailian/1.jpg)





### 后端部分页面展示
![输入图片说明](http://www.51duoke.cn/quanzi/dailian/admin1.png)
![输入图片说明](http://www.51duoke.cn/quanzi/dailian/admin2.png)
![输入图片说明](http://www.51duoke.cn/quanzi/dailian/admin3.png)
![输入图片说明](http://www.51duoke.cn/quanzi/dailian/admin4.png)
![输入图片说明](http://www.51duoke.cn/quanzi/dailian/admin5.png)


## 文档

[TP6开发手册](https://www.kancloud.cn/manual/thinkphp6_0/content)

[uniapp开发手册](https://uniapp.dcloud.net.cn/)

 ![输入图片说明](https://www.51duoke.cn/quanzi/dailian/qun.png)



-----------------------------------------------------

###  **另外我们还提供标准版和商业版，支持更多功能。



-----------------------------------------------------







## 特别鸣谢

排名不分先后，感谢这些软件的开发者：thinkphp、小牛admin、图鸟UI、vue、mysql、redis、uniapp等！


## 开源版使用须知

1.允许用于个人学习、毕业设计、教学案例、公益事业、商业使用;

2.如果商用必须保留版权信息，请自觉遵守;

3.禁止将本项目的代码和资源进行任何形式的出售，产生的一切任何后果责任由侵权者自负。

## 版权信息

版权所有Copyright © 2016-2026 by 四川掌上时代科技有限公司旗下多客开源事业部 (http://www.51duoke.cn)

All rights reserved。

著作权所有者为四川掌上时代科技有限公司。
