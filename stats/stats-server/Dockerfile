FROM amazoncorretto:21-alpine3.20-jdk
COPY target/*.jar stats-server.jar
ENTRYPOINT ["java","-jar","/stats-server.jar"]