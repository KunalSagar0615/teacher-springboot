
FROM eclipse-temurin:17jre

WORKDIR /app
COPY target/*jar app.jar

EXPOSE 8080
CMD ["java","-jar","app.jar"]
