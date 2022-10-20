### Spring Boot Rest API

This version does not contains *beans*, *exception handlers* or *tests*, to view a more complete version [click here](https://github.com/victorgomez09/backendDevTest).

Application runs on port **5000**

Mocks url is located in `application.properties`
```
mocks.url=http://localhost:3001
```

To run you have 2 options:
- Run with `Spring Boot Dashboard`, a plugin that comes in most IDEs.
- Package and run .jar file:
    1. Run `mvn packge` inside **rest-api** project folder
    2. Go to target folder and run `java -jar rest-api-0.0.1-SNAPSHOT.jar`
