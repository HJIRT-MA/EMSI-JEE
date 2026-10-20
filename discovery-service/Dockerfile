FROM eclipse-temurin:21-jdk-alpine
VOLUME /tmp
COPY target/*-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]