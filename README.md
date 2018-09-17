# jmstest
Project for testing Amazon MQ(active mq)

- after importing the project(with pom.xml), then make "application.properties"
- copy and paste below text, modify &lt;url&gt;, &lt;username&gt;, &lt;password&gt;
- add this to vm option
- -Dorg.apache.activemq.SERIALIZABLE_PACKAGES="com.kurly.jmstest"
- run testclass, then check the result.
  
```
spring.activemq.broker-url=<url>
spring.activemq.user=<username>
spring.activemq.password=<password>
```

