FROM openjdk:15-jdk-slim
COPY "./target/spring-boot-docker-department-service-0.0.1.jar" "app.jar"
EXPOSE 9001
ENTRYPOINT ["java","-jar","app.jar"]