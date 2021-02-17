FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8060
COPY target/*.jar  ROOF.jar
ENTRYPOINT ["java","-Dspring.data.mongodb.uri=mongodb://mongo/test","-jar","ROOF.jar"]