FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY target/esd_hostel_service-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 5002
ENTRYPOINT ["java", "-jar", "app.jar"]
