FROM azul/zulu-openjdk-alpine:11-jre
MAINTAINER Gilbert Bett <gilbertkalo.kalo@gmail.com>

ADD target/hb-docker.jar /app.jar

CMD ["java", "-Djava.net.preferIPv4Stack=true", "-jar", "/app.jar"]