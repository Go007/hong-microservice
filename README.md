# hong-microservice
Spring Boot + Spring Cloud微服务架构

# maven多module项目的引用问题 https://blog.csdn.net/ruanjian1111ban/article/details/80890539
# Maven中<dependencies>节点和<dependencyManagement>节点的区别

https://my.oschina.net/u/2278977/blog/807958 Spring-Boot使用profile来配置不同环境的配置文件
需要先执行mvn clean package -P dev 打指定环境的jar包,
然后执行类似以下命令启动服务:
java -jar hong-spring-cloud-eureka-0.0.1-SNAPSHOT.jar  --spring.profiles.active=eureka7001
