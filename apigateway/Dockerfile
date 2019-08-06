FROM openjdk:11
ADD ./target/apigateway-0.0.1-SNAPSHOT.jar apigateway.jar
EXPOSE 8092
ENTRYPOINT ["java","-jar","apigateway.jar"]