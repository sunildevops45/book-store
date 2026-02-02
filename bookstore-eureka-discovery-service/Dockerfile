FROM eclipse-temurin:8-jdk-jammy

ARG JAR_FILE

COPY target/*.jar eureka-app.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/eureka-app.jar"]
