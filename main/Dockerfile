FROM amazoncorretto:21-alpine3.20-jdk
COPY target/*.jar main.jar
ENTRYPOINT ["java","-jar","/main.jar"]