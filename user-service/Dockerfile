FROM openjdk:11-jdk-stretch
ADD target/user-service-0.0.1-SNAPSHOT.jar  /src/main/user-service-0.0.1-SNAPSHOT.jar
WORKDIR /src/main
ENTRYPOINT ["java","-jar","user-service-0.0.1-SNAPSHOT.jar"]