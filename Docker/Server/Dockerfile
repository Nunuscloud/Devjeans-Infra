FROM openjdk:11-jre-slim

WORKDIR /app

ARG JAR_FILE=./build/libs/oauth-0.0.1-SNAPSHOT.jar

COPY ${JAR_FILE} /app/application.jar

CMD java -jar /app/application.jar
