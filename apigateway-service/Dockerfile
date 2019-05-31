FROM openjdk:11-jdk-stretch
ADD target/apigateway-service-0.0.1-SNAPSHOT.jar  /src/main/apigateway-service-0.0.1-SNAPSHOT.jar
WORKDIR /src/main
ENTRYPOINT ["java","-jar","apigateway-service-0.0.1-SNAPSHOT.jar"]