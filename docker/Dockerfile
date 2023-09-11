FROM openjdk:8u151-jdk-alpine3.7

EXPOSE 8070

ENV APP_HOME=/usr/src/app

COPY target/demo-3.1.3.jar ${APP_HOME}/app.jar

WORKDIR $APP_HOME

ENTRYPOINT exec java -jar app.jar