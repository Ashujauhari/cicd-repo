FROM openjdk:8u131-jdk-alpine
MAINTAINER "Ashu"
EXPOSE 8010
WORKDIR  /usr/local/bin/
COPY ./target/eureka.jar   eureka.jar
CMD ["java","-jar","eureka.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
