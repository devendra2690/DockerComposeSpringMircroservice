FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} inventorygateway.jar
ENTRYPOINT ["java","-jar","/inventorygateway.jar"]
