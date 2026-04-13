FROM eclipse-temurin:17-jre

WORKDIR /app

COPY target/ruoyi-admin.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar", "--spring.profiles.active=druid"]
