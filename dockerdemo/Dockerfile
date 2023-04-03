FROM openjdk:11
LABEL maintainer="dockerdemo.net"
ADD target/dockerdemo-0.0.1-SNAPSHOT.jar dockerdemo.jar
ENTRYPOINT ["java", "-jar", "dockerdemo.jar"]