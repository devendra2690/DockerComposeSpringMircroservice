FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} inventorymanagement.jar
ENTRYPOINT ["java","-jar","/inventorymanagement.jar"]
