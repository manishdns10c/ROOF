FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY target/*.jar  ROOF.jar
ENTRYPOINT ["java","-jar","ROOF.jar"]