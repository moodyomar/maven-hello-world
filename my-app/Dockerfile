FROM openjdk:8-jre-alpine3.9
COPY my-app/target/*.jar /app.jar
RUN sudo useradd -m myapp
USER myapp
CMD ["java", "-jar", "/app.jar"]