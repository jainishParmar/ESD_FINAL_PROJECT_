FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY target/Task_Server-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8070
ENTRYPOINT ["java", "-jar", "app.jar"]
