FROM maven:3.9.14 AS builder
WORKDIR /app
COPY src ./src
COPY pom.xml .
CMD ["java","-jar","target/shipping-1.0.jar"]