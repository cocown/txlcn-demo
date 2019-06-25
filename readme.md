txlcn 5.0 demo


使用说明:

1. 本Demo基于[txlcn-最新发布](https://github.com/codingapi/tx-lcn)版本
2. 启动Demo前需先启动事务管理器TM（txlcn-demo-tm）。
3. 更多信息见官网 [https://www.txlcn.org](https://www.txlcn.org)   
4. [性能测试报告](https://txlcn.org/zh-cn/docs/test.html)

启动步骤：（consul改为了eureka）

1. 启动redis 端口6379
2. 创建数据库和表 txlcn-demo.sql
3. 启动注册中心txlcn-demo-registry
4. 启动tx-demo-tm  事务管理器TM
5. 启动服务
```$xslt
    启动txlcn-demo-spring-service-b
    启动txlcn-demo-spring-service-c
    启动txlcn-demo-spring-service-a
```
    