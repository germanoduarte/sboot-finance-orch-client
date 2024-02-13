FROM eclipse-temurin:17-jdk-alpine
EXPOSE 8080
ENV JAVA_OPTS="-Xms64m -Xmx128m -XX:MaxPermSize=128m"
COPY *.jar /deployment/application.jar

ENTRYPOINT java -jar $JAVA_OPTS /deployment/application.jar