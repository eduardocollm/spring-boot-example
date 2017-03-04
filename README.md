# spring-boot-example
Spring Boot Example

Build:
```
gradle clean build
```

Build w/ docker image:
```
gradle clean build buildDocker
```

Run:
```
docker run -p 8080:8080 -t collesoft/collesoft-spring-boot
```

Test:
```
http://localhost:8080
```

Stop:
```
docker ps
docker stop <process id>
```
