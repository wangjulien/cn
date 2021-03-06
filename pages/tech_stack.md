---
layout: default
title: 技术栈
permalink: /tech-stack/
redirect_from:
  - /tech_stack.html
sitemap:
    priority: 0.8
    lastmod: 2014-05-16T00:00:00-00:00
---

# <i class="fa fa-stack-overflow"></i> 技术栈

## 客户端技术栈

单网页应用程序：

*   [Angular](https://angular.io/) or [React](https://reactjs.org/)
*   Responsive Web Design with [Twitter Bootstrap](http://getbootstrap.com/)
*   [HTML5 Boilerplate](http://html5boilerplate.com/)
*   Compatible with modern browsers (Chrome, FireFox, Microsoft Edge...)
*   Full internationalization support
*   Optional [Sass](https://www.npmjs.com/package/node-sass) support for CSS design
*   Optional WebSocket support with Spring Websocket

开发工作流程：

*   Easy installation of new JavaScript libraries with [NPM](https://www.npmjs.com/get-npm)
*   Build, optimization and live reload with [Webpack](https://webpack.js.org/)
*   Testing with [Jest](https://facebook.github.io/jest/) and [Protractor](http://www.protractortest.org)

如果一个网页应用程序不足以满足您的需求呢？

*   支持 [Thymeleaf](http://www.thymeleaf.org/) 模板引擎，在服务器端生成网页

## 服务器端技术栈

A complete [Spring application](http://spring.io/):

*   [Spring Boot](http://projects.spring.io/spring-boot/) for easy application configuration
*   [Maven](http://maven.apache.org/) or [Gradle](http://www.gradle.org/) configuration for building, testing and running the application
*   ["development" and "production" profiles]({{ site.url }}/profiles/) (both for Maven and Gradle)
*   [Spring Security](http://docs.spring.io/spring-security/site/index.html)
*   [Spring MVC REST](http://spring.io/guides/gs/rest-service/) + [Jackson](https://github.com/FasterXML/jackson)
*   Optional WebSocket support with Spring Websocket
*   [Spring Data JPA](http://projects.spring.io/spring-data-jpa/) + Bean Validation
*   Database updates with [Liquibase](http://www.liquibase.org/)
*   [Elasticsearch](https://github.com/elastic/elasticsearch) support if you want to have search capabilities on top of your database
*   [MongoDB](http://www.mongodb.org) and [Couchbase](https://www.couchbase.com) support if you'd rather use a document-oriented NoSQL database instead of JPA
*   [Cassandra](http://cassandra.apache.org/) support if you'd rather use a column-oriented NoSQL database instead of JPA
*   [Kafka](http://kafka.apache.org/) support if you want to use a publish-subscribe messaging system

## 微服务技术栈

Microservices are optional, and fully supported:

* HTTP routing using [Netflix Zuul](https://github.com/Netflix/zuul) or [Traefik](https://traefik.io/)
* Service discovery using [Netflix Eureka](https://github.com/Netflix/eureka) or [HashiCorp Consul](https://www.consul.io/)

## 准备投入生产：

*   Monitoring with [Metrics](http://metrics.dropwizard.io/) and [the ELK Stack](https://www.elastic.co/products)
*   Caching with [ehcache](http://ehcache.org/) (local cache), [hazelcast](http://www.hazelcast.com/) or [Infinispan](http://infinispan.org/)
*   Optimized static resources (gzip filter, HTTP cache headers)
*   Log management with [Logback](http://logback.qos.ch/), configurable at runtime
*   Connection pooling with [HikariCP](https://github.com/brettwooldridge/HikariCP) for optimum performance
*   Builds a standard WAR file or an executable JAR file
*   Full Docker and Docker Compose support
*   Support for all major cloud providers: AWS, Cloud Foundry, Heroku, Kubernetes, OpenShift, Azure, Docker...
