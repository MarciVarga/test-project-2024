# Docker Compose Spring Boot and MySQL example

localhost:6868

## Run the System
We can easily run the whole with only a single command:
```bash
docker compose up
```

Docker will pull the MySQL and Spring Boot images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker compose down --rmi all
```

For more detail, please visit:
> [Docker Compose Spring Boot and MySQL example](https://www.bezkoder.com/docker-compose-spring-boot-mysql/)

Related Posts:
> [Spring Boot JPA + MySQL - Building Rest CRUD API example](https://www.bezkoder.com/spring-boot-jpa-crud-rest-api/)

> [Spring Boot R2DBC + MySQL example](https://www.bezkoder.com/spring-r2dbc-mysql/)

> [Spring Boot + GraphQL + MySQL example](https://www.bezkoder.com/spring-boot-graphql-mysql-jpa/)

> [Spring Boot Rest XML example – Web service with XML Response](https://www.bezkoder.com/spring-boot-rest-xml/)

> [Spring Boot: Upload CSV file data into MySQL Database](https://www.bezkoder.com/spring-boot-upload-csv-file/)

> [Spring Boot: Upload Excel file data into MySQL Database](https://www.bezkoder.com/spring-boot-upload-excel-file-database/)

> [Spring Boot Validate Request Body](https://www.bezkoder.com/spring-boot-validate-request-body/)

> [Spring Boot and Swagger 3 example](https://www.bezkoder.com/spring-boot-swagger-3/)

> [Spring Boot Redis Cache example](https://www.bezkoder.com/spring-boot-redis-cache-example/)

> [Spring Boot File upload example](https://www.bezkoder.com/spring-boot-file-upload/)

> [Exception handling: @RestControllerAdvice example in Spring Boot](https://www.bezkoder.com/spring-boot-restcontrolleradvice/)

> [Spring Boot Repository Unit Test with @DataJpaTest](https://www.bezkoder.com/spring-boot-unit-test-jpa-repo-datajpatest/)

> [Spring Boot Rest Controller Unit Test with @WebMvcTest](https://www.bezkoder.com/spring-boot-webmvctest/)

> [Deploy Spring Boot App on AWS – Elastic Beanstalk](https://www.bezkoder.com/deploy-spring-boot-aws-eb/)

Security:
> [Spring Boot + Spring Security JWT Authentication & Authorization](https://www.bezkoder.com/spring-boot-jwt-authentication/)
