# You can change this base image to anything else
# But make sure to use the correct version of Jav
FROM eclipse-temurin:11-jre

# Simply the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]


