# JDBC-Framework-Vs-JDBC-Template-
Difference between JDBC Framework  Vs JDBC Template  in Spring.

## JDBC Framework
```java
<beanid="dataSource"
class="org.springframework.jdbc.datasource.DriverManagerDataSource">
<propertyname="driverClassName"value="com.mysql.jdbc.Driver"/>
<propertyname="url"value="jdbc:mysql://localhost:3306/TEST"/>
<propertyname="username"value="root"/>
<propertyname="password"value="password"/>
</bean>
```
## JDBC Template 
```java
# Database properties
spring.datasource.url=jdbc:mysql://localhost:3306/TEST
spring.datasource.username=username
spring.datasource.password=password
spring.datasource.driver-class-name=com.mysql.jdbc.Driver
```

```java
// few more example
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.properties.hibernate.format_sql=true
```
