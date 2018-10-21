# -redis实现分布式session 同步
基于Redis实现了分布式Session的管理;我们如果用nginx做一个流量分发，一部分流量请求tomcatA,一部分流量请求tomcatB，同一个用户的不同请求可能会产生在不同的tomcat上，我们知道session是由tomcat管理的，那么我们如何保证两台tomcat的session同步呢，为了解决这一问题，所以产生了分布式session。网上有很多文档的描述就不多加赘述了。

#
相关文档：
官网 ： https://docs.spring.io/spring-session/docs/current/reference/html5/guides/java-redis.html

spring-boot集成spring-session-data-redis： https://www.cnblogs.com/mengmeng89012/p/5519698.html

https://blog.csdn.net/usagoole/article/details/80639804

#-redis 配置的一相关文档
https://blog.csdn.net/weixin_39723544/article/details/80743074
https://www.cnblogs.com/zeng1994/p/03303c805731afc9aa9c60dbbd32a323.html
https://blog.csdn.net/u012943767/article/details/79360748

 
