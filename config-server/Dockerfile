FROM openjdk:11-jdk-stretch
ADD target/config-server-0.0.1-SNAPSHOT.jar  /src/main/config-server-0.0.1-SNAPSHOT.jar
WORKDIR /src/main
ENTRYPOINT ["java","-jar","config-server-0.0.1-SNAPSHOT.jar"]