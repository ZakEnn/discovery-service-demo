# discovery-service-demo
Service Discovery enables us to dynamically adapt to new instances and distribute load among microservices.

# Application setup
Run the app using maven command:

mvn spring-boot:run -Dspring-boot.run.arguments=--spring.cloud.config.uri=http://localhost:8888, --spring.profiles.active=dev
