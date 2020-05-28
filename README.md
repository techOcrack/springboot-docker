# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.techocrack.springboot-docker' is invalid and this project uses 'com.techocrack.springbootdocker' instead.

# Getting Started
I this i have tried to dockerize the application so i have used io fabric8 for that
i have added configuration in pom.xml file

#For Running This application

* springboot-docker> mvn install docker:build
* this will created the docker images and configuration of image is there in pom file.
* springboot-docker> docker run -p 8080:8080 -d image <name> 

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.3.0.RELEASE/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

