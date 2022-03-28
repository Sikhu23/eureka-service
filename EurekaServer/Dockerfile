FROM openjdk:17
ADD target/dockerEurekaServer.jar dockerEurekaServer.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","dockerEurekaServer.jar"]