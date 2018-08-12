FROM maven:3.5.4-jdk-8-slim

EXPOSE 8888
VOLUME /root/.m2

WORKDIR /usr/src/configserver

COPY . /usr/src/configserver/

CMD ["mvn", "spring-boot:run"]
