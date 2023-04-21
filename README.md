# Java秒杀项目
- [在线演示](http://101.43.225.225:8080/login/toLogin)
- [接口文档](http://101.43.225.225:8080/doc.html#/home)
## 项目介绍
本项目为个人学习项目，主要是针对秒杀场景进行开发工作，其中包含用户登录、商品展示、系统压测、安全优化等模块。
完成了后台代码的编写，解决了用户登录、下单、支付、超买和超卖等问题。
## 技术架构
- 后端使用SpringBoot开发，整合MyBatis-Plus框架，数据库使用MySQL
- 登录采用MD5密码加密方法，使用Redis共享Session
- 使用Docker构建了开发环境，包括Redis、RabbitMQ，并部署了SpringBoot项目
- 采用了页面缓存和页面静态化，使用RabbitMQ处理秒杀请求
