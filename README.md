# spring-boot-starter-spring-cacheable-distributed
spring-cacheable-distributed provides a jvm based spring cache implementation which is replicated across all
instances and eviction happens on all instances through an activemq topic.

See [Spring Caching](https://docs.spring.io/spring/docs/4.3.6.RELEASE/spring-framework-reference/html/cache.html) for usages.

The following properties need to be overridden in the `application.properties` to setup the activemq broker.

```
spring.activemq.brokerUrl=<brokerurl>
spring.activemq.user=<user>
spring.activemq.password=<password>
```

