FROM openjdk:11
ADD ./target/microservices-0.0.1-SNAPSHOT.jar eureka.jar
EXPOSE 9092
ENTRYPOINT ["java","-jar","eureka.jar"]