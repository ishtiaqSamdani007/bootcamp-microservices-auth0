FROM openjdk:11

WORKDIR /micro-service

COPY target/*.jar app.jar

CMD [ "java","-jar","/app.jar" ]

EXPOSE 9003