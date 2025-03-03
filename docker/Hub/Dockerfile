FROM openjdk:11-jre-slim
ADD https://github.com/SeleniumHQ/selenium/releases/download/selenium-4.29.0/selenium-server-4.29.0.jar selenium-server-4.29.0.jar
ENTRYPOINT exec java -jar selenium-server-4.29.0.jar hub
EXPOSE 4442
EXPOSE 4443
EXPOSE 4444
