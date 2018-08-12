FROM maven:3.5.4-jdk-8-slim
EXPOSE 8100
VOLUME /root/.m2

EXPOSE 8790
WORKDIR /usr/src/currency-conversion-service

COPY . /usr/src/currency-conversion-service/

CMD ["mvn", "spring-boot:run"]
