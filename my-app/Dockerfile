FROM openjdk:8-jre-alpine3.9
ARG version
COPY my-app/target/my-app-${version}.jar ./app.jar
CMD ["java", "-jar", "/app.jar"]