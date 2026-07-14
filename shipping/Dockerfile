FROM maven:3.9.14 AS builder
WORKDIR /app
COPY src ./src
COPY pom.xml .
RUN mvn clean package
CMD ["java","-jar","target/shipping-1.0.jar"]
