FROM openjdk:17-alpine
ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} app.jar
CMD java -jar -Dspring.profiles.active=prod app.jar