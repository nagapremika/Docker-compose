FROM openjdk:11
ADD ./target/microserviceconfig-0.0.1-SNAPSHOT.jar config.jar
EXPOSE 8891
ENTRYPOINT ["java","-jar","config.jar"]