#FROM openjdk:8-jdk-alpine
FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD microservice-1.0-SNAPSHOT.jar app.jar
EXPOSE 8001
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar","-c"]
