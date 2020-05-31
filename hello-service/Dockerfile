FROM openjdk:8u131-jdk-alpine
MAINTAINER "Ashu"
EXPOSE 7070
WORKDIR  /usr/local/bin/
COPY ./target/hello.jar  hello.jar
CMD ["java","-jar","Hello.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
