FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ./target/JavaSE-1.8.jar app.jar
ENTRYPOINT ["java","-jar",'/app.jar"]