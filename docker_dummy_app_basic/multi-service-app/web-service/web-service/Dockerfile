FROM openjdk:21-jdk-slim
WORKDIR /app
COPY target/web-service-0.0.1-SNAPSHOT.jar /app/web-service.jar
ENTRYPOINT ["java", "-jar", "/app/web-service.jar"]
