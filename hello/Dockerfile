FROM openjdk:11-jre-alpine
ARG jar_file=build/libs/*.jar
# ARG jar_file=target/*.jar

COPY ${jar_file} app.jar
# COPY target/*.jar app.jar
CMD ["java","-jar","/app.jar"]
