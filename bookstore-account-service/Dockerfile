FROM eclipse-temurin:8-jdk-jammy

COPY target/*.jar account-service.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/account-service.jar"]
