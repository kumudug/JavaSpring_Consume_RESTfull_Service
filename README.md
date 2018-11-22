# JavaSpring_Consume_RESTfull_Service

* Project generated using spring initalizer
* https://start.spring.io/
 * ![Spring Initializer](https://github.com/kumudug/JavaSpring_Consume_RESTfull_Service/blob/master/SpringInitializr.jpg)

## Build an executable JAR

* You can run the application from the command line with Gradle or Maven. 
* Or you can build a single executable JAR file that contains all the necessary dependencies, classes, and resources, and run that. 
* This makes it easy to ship, version, and deploy the service as an application throughout the development lifecycle, across different environments, and so forth.

### If you are using Gradle,

* You can run the application using
   `./gradlew bootRun`

* You can build and run the JAR file using
 1. Build
    `./gradlew build`
 2. Run
    `java -jar build/libs/gs-rest-service-0.1.0.jar`

## Test the service

* Now that the service is up, visit 
 1. _http://localhost:8888/greeting_