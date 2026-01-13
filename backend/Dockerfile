FROM eclipse-temurin:21-jre-alpine
VOLUME /tmp
COPY target/backend*.jar app.jar
EXPOSE 8074
ENTRYPOINT ["java", "-jar", "app.jar"]