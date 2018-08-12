FROM maven:3.5.4-jdk-8-slim

EXPOSE 8000
VOLUME /root/.m2
EXPOSE 7686

WORKDIR /usr/src/currency-exchange-service

COPY . /usr/src/currency-exchange-service/

CMD ["mvn", "spring-boot:run"]
