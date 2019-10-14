# 171--Spring boot + Zipkin + brave

zipkin-springboot-brave 或SpringBoot.Zipkin.brave

Zipkin+brave示例项目

启动步骤：
（1）Zipkin-server ；（2）webmvc4-boot-Frontend；（3）webmvc4-boot-backend；。

This case is based on Spring boot to implement the micro-service call chain, which uses Zipkin framework.The Zipkin framework is invoked through brave components.

本案例基于Spring boot来实现微服务调用链，微服务调用链采用Zipkin框架。对于Zipkin框架通过brave组件来调用。

zipkin-server的下载地址：https://dl.bintray.com/openzipkin/maven/io/zipkin/java/zipkin-server/

zipkin-server的管理Web
http://127.0.0.1:9411/

通过调用其中一个服务webmvc4-boot-Frontend，达到服务之间的调用。该服务会调用webmvc4-boot-backend。
http://127.0.0.1:8081

