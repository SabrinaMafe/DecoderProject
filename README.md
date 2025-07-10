# DecoderProject - API Gateway

API Gateway for the DecoderProject system, using Spring Cloud Gateway and Eureka for service registration and discovery.

## Technologies

- Java
- Spring Boot
- Spring Cloud Gateway
- Eureka
- Maven

## How to run

1. Make sure the Eureka Server is running at `localhost:8761`.
2. Configure Eureka credentials in `application.yaml` if needed.
3. Run the following command:

   ```shell
   mvn spring-boot:run

## Configured routes

- `/ead-authuser/**` → EAD-AUTHUSER-SERVICE
- `/ead-course/**` → EAD-COURSE-SERVICE
- `/ead-notification/**` → EAD-NOTIFICATION-SERVICE

## Configuration

Main configurations are in `api-gateway/src/main/resources/application.yaml`.

## Author

- [SabrinaMafe](https://github.com/SabrinaMafe)