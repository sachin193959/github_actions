FROM openjdk:11-jre-slim
ADD https://github.com/SeleniumHQ/selenium/releases/download/selenium-4.29.0/selenium-server-4.29.0.jar selenium-server-4.29.0.jar
ENTRYPOINT exec java -jar selenium-server-4.29.0.jar node
EXPOSE 5555
