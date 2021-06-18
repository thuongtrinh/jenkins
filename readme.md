## What is it?
This source code is an Spring Boot web application (mvc + thymeleaf).
 
Tested with
* Docker
* Ubuntu
* Java 8 or Java 11
* Spring Boot 2.2.4.RELEASE
* Maven

## How to run this?
```bash
$ git clone https://github.com/thuongtrinh/jenkins
$ cd docker-spring-boot
$ mvn clean package
$ java -jar target/spring-boot-web.jar

  access http://localhost:8080

//dockerize

// create a docker image
$ sudo docker build -t spring-boot:1.0 .
// run it
$ sudo docker run -d -p 8080:8080 -t spring-boot:1.0

  access http://localhost:8080
```