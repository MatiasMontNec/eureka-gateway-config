FROM openjdk:21
ARG JAR_FILE=target/gateway.jar
COPY ${JAR_FILE} gateway.jar
ENTRYPOINT ["java","-jar","/gateway.jar"]