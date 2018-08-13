FROM maven:3.5.4-jdk-8-slim

EXPOSE 8765
VOLUME /root/.m2
WORKDIR /usr/src/zuul-api-gateway

COPY . /usr/src/zuul-api-gateway/

CMD ["mvn", "spring-boot:run"]
