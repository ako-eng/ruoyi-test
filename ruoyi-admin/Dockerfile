FROM openjdk:8-jdk-slim

WORKDIR /app

COPY target/ruoyi-admin.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar", "--spring.profiles.active=druid"]