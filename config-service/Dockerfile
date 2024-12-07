FROM openjdk:21
ARG JAR_FILE=target/config.jar
COPY ${JAR_FILE} config.jar
ENTRYPOINT ["java","-jar","/config.jar"]