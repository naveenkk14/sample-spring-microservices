FROM openjdk:8-jdk-alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
MAINTAINER Ramazan Sakin <ramazansakin63@gmail.com>
ADD customer-service/target/customer-service.jar customer-service.jar
EXPOSE 3333
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
