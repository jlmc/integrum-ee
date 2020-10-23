# Integrum EE

Currently integrum EE is a proof of concept of a Java EE project with support for Kotlin and Java as languages

As 2020-10-23 it has been tested with the following enterprise APIs

- JPA
- EJB
- CDI
- JAX-RS
- MicroProfile Config

All of this over Payara and Payara Micro

## Notes for development
To run this project locally you should create your own database configuration, the easiest way is to create your own `glassfish-resources.xml` file, for reference a shadow `.dsxml` copy has been included to use it as basis

Currently this project supports

- Java EE 8
- MicroProfile 3.1
- Arquillian & Junit 4
- Java 8
- Kotlin 1.3.x
- Flyway 5 

## Build with docker
mvn clean package && docker build -t com.nabenik/integrum-ee .

## RUN with docker compose

docker compose up 
