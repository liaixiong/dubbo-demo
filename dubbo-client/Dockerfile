FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY target/dubbo-client-1.0.0-SNAPSHOT.jar /app.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "java", "-jar", "/app.jar" ]
