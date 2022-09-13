FROM openjdk:11-slim as build

MAINTAINER bank.com

COPY build/libs/configServer-0.0.1-SNAPSHOT.jar configServer-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/configServer-0.0.1-SNAPSHOT.jar"]

#EXPOSE 5000
EXPOSE 8071
