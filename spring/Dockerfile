# Build the jar for the service
FROM maven:3.8-openjdk-8-slim 

COPY ./src ./src
COPY pom.xml .

CMD mvn spring-boot:run
