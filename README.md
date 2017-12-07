Repository for Spring Boot 2.0.0.M7 - Health details always shown when using custom management.server.port

Issue : https://github.com/spring-projects/spring-boot/issues/11285

See src/main/resources/application.properties for properties

Tested with : 

```bash
./gradlew clean build && java -jar build/libs/demo-0.0.1-SNAPSHOT.jar

curl -i -X GET http://localhost:8088/actuator/health
```
