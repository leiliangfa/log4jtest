Log4j测试
===========
1、应用服务器版本：JBoss7.x or JBoss EAP 6.x
2、日志文件配置详见项目的log4j.properties文件
3、访问如下地址日志生成到D\:\\log4jtest.log
http://localhost:8080/log4jtest/log4jTestServlet		
4、访问如下地址日志生成到D\:\\cuntest.log
http://localhost:8080/log4jtest/log4jTestServlet2
5、buffer默认8k，至少写满8k才会flush到磁盘日志文件中
6、JBoss配置RootLogger级别为ERROR不影响日志输出

参考地址：
http://wallimn.iteye.com/blog/476866
http://www.mastertheboss.com/jboss-server/jboss-log/using-log4j-with-jboss-as-7-and-wildfly