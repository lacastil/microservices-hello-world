FROM openjdk:15-jdk-slim
VOLUME /tmp
ADD target/service-registry-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]