FROM openjdk:8-jre-alpine3.9
COPY my-app/target/*.jar /app.jar
RUN useradd -m -p 123456 dauser
USER dauser
CMD ["java", "-jar", "/app.jar"]