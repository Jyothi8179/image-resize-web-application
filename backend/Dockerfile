# Dockerfile for backend service
FROM openjdk:17-jdk-slim
WORKDIR /resize
COPY ./target/backend-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
