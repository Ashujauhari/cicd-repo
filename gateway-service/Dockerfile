FROM openjdk:8u131-jdk-alpine
MAINTAINER "Ashu"
EXPOSE 8011
#WORKDIR  /usr/local/bin/
COPY ./target/gateway.jar   gateway.jar
CMD ["java","-jar","gateway.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
