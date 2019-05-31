FROM openjdk:11-jdk-stretch
ADD target/musix-service-0.0.1-SNAPSHOT.jar  /src/main/musix-service-0.0.1-SNAPSHOT.jar
WORKDIR /src/main
ENTRYPOINT ["java","-jar","musix-service-0.0.1-SNAPSHOT.jar"]

