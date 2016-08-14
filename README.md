# CDJenkinsDocker
Continuous Delivery  (CD) Mini Setup with Spring Boot, Jenkins, Gradle and Docker

## Build & Run


(maven) gradle build && java -jar build/libs/gs-spring-boot-docker-0.1.0.jar

## Build & Run Docker Image

gradle build buildDocker

docker run -p 8082:8080 -t accelaero/gs-spring-boot-docker



