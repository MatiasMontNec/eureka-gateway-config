FROM openjdk:21
ARG JAR_FILE=target/eureka.jar
COPY ${JAR_FILE} eureka.jar
ENTRYPOINT ["java","-jar","/eureka.jar"]