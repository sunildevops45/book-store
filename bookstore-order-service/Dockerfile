FROM eclipse-temurin:8-jdk-jammy

VOLUME /tmp

ARG JAR_FILE

COPY target/*.jar order-service.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-Dspring.profiles.active=local","-jar","/order-service.jar"]
