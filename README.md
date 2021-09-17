# spring-maven-docker

1. Build
```
./mvnw spring-boot:build-image
```
2. Create the image
```
docker build -t spring-maven-docker .
```
3. Execute
```
docker run -d -p 8080:8080 --name spring-maven-docker spring-maven-docker
```
4. To stop
```
docker stop spring-maven-docker
```
