FROM eclipse-temurin:8-jdk-jammy

VOLUME /tmp

ARG JAR_FILE

COPY target/*.jar payment-server.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-Dspring.profiles.active=local","-jar","/payment-server.jar"]
