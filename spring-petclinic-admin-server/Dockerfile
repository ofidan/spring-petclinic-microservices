FROM amazoncorretto:17
COPY ./target/*.jar /app.jar
ENV SPRING_PROFILES_ACTIVE docker,mysql
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "/app.jar"]