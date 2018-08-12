FROM maven:3.5.4-jdk-8-slim

EXPOSE 8761

VOLUME /root/.m2

WORKDIR /usr/src/netflix-eureka-naming-server

COPY . /usr/src/netflix-eureka-naming-server/

CMD ["mvn", "spring-boot:run"]
