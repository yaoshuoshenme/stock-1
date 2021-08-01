FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/stock-service-0.0.2.jar stock.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /stock.jar