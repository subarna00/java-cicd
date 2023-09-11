FROM openjdk:8u151-jdk-alpine3.7

EXPOSE 9070

ENV APP_HOME=/opt/apache-tomcat-9.0.65/webapps

copy target/demo.jar ${APP_HOME}/app.jar

WORKDIR APP_HOME

ENTRYPOINT exec java -jar app.jar