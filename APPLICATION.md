```
spring.datasource.url=jdbc:postgresql://localhost:5432/db
spring.datasource.username=minesk
spring.datasource.password=admin
spring.jpa.hibernate.ddl-auto=create-drop

spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
spring.jpa.properties.hibernate.format_sql=true
spring.jackson.serialization.fail-on-empty-beans=false

server.error.include-message=always

spring.servlet.multipart.max-file-size=100MB
spring.servlet.multipart.max-request-size=100MB

# Redis Config
spring.cache.type=redis
spring.redis.host=localhost
spring.redis.port=6379
```